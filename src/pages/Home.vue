<template>
    <div class="home">
        <Header></Header>
        <Hero></Hero>
        <Stack></Stack>
        <Pricing></Pricing>
        <Spesification></Spesification>
        <Feature></Feature>
        <Laravel></Laravel>
        <Module></Module>
        <Hosting></Hosting>
        <SocialMedia></SocialMedia>
        <Chat></Chat>
        <Footer></Footer>



        


    </div>
</template>

<script>
import Header from '../components/Header'
import Hero from '../components/Hero'
import Stack from '../components/Stack'
import Pricing from '../components/Pricing'
import Spesification from '../components/Spesification'
import Feature from '../components/Feature'
import Laravel from '../components/Laravel'
import Module from '../components/Module'
import Hosting from '../components/Hosting'
import Chat from '../components/Chat'
import SocialMedia from '../components/SocialMedia'

import Footer from '../components/Footer'







export default {
    name:'home',
    components:{
        Header,
        Hero,
        Stack,
        Pricing,
        Spesification,
        Feature,
        Laravel,
        Module,
        Hosting,
        Chat,
        SocialMedia,
        Footer,



    }
}
</script>