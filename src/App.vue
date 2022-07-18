<template>
    <HeaderSection />
    <SliderSection />
    <ImageSection skill="section" />
    <ImgTextSection skill="section" />
    <CardSection skill="section" />
    <BannerSection skill="section" />
    <TextSection skill="section" />
    <FooterSection skill="section" />
</template>


<script>
import HeaderSection from "./components/HeaderSection";
import SliderSection from "./components/SliderSection";
import ImageSection from "./components/ImageSection";
import ImgTextSection from "./components/ImgTextSection";
import CardSection from "./components/CardSection";
import BannerSection from "./components/BannerSection";
import TextSection from "./components/TextSection";
import FooterSection from "./components/FooterSection";

export default {
    name: 'App',
    components: {
        HeaderSection,
        SliderSection,
        ImageSection,
        ImgTextSection,
        CardSection,
        BannerSection,
        TextSection,
        FooterSection
    }
}


</script>


<style>
@import "./App.css";
</style>