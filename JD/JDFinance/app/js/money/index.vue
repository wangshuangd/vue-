<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Ada/>
        <Money/>
        <Adb/>
        <Finance/>
        <Adc/>
        <Footer cname="mfooter"/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from "../public/header.vue"
import Footer from "../public/footer.vue"
import Navbar from "../public/navbar.vue"
import Slider from "./mslider.vue"
import Ada from "./ada.vue"
import Money from "./money.vue"
import Adb from "./adb.vue"
import Finance from "./finance.vue"
import Adc from "./adc.vue"
export default {
    components: {
        Heador,
        Footer,
        Navbar,
        Slider,
        Ada,
        Money,
        Adb,
        Finance,
        Adc,
    },
}
</script>
<style lang="scss">
    .mfooter{
        margin-top: 0!important;
        ul{
            li:first-child{
                display: none;
            }
        }
    }
</style>
