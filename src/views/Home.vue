<template>
    <div>
        <FirstComponent/>
        <SecondComponent/>
        <ThirdComponent/>
        <FourthComponent/>
        <FifthComponent/>
    </div>
</template>


<script>
import FirstComponent from '../components/FirstComponent.vue';
import SecondComponent from '../components/SecondComponent.vue';
import ThirdComponent from '../components/ThirdComponent.vue';
import FourthComponent from '../components/FourthComponent.vue';
import FifthComponent from '../components/FifthComponent.vue';

export default {
    name: 'Home',
    components: {
       FirstComponent,
       SecondComponent,
       ThirdComponent,
       FourthComponent,
       FifthComponent
    }
}
</script>

<style scoped>

</style>