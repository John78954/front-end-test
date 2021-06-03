<template>
    <div>
        {{info}}
    </div>
</template>

<script>
import axios from 'axios'

export default {
    name: 'FifthComponent',
    data() {
        return{
            info: null
        }
    },
    mounted () {
    axios
      .post('https://services.metricsamsi.com/v1.0/dealers/swagger/v1/swagger.json#/components/schemas/RooftopGoogleOptionListApiResponse')
      .then(response => (this.info = response.data.restore.rooftopGoogleOptionId))
  }
}
</script>

<style scoped>

</style>