<template>
    <HeaderSection />
    <SliderSection />
    <ImageSection skill="section" />
    <ImgTextSection skill="section" />
</template>


<script>
import HeaderSection from "./components/HeaderSection";
import SliderSection from "./components/SliderSection";
import ImageSection from "./components/ImageSection";
import ImgTextSection from "./components/ImgTextSection";

export default {
    name: 'App',
    components: {
        HeaderSection,
        SliderSection,
        ImageSection,
        ImgTextSection,
    }
}


</script>


<style>
@import "./App.css";
</style>