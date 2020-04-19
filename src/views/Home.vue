<template>
  <b-container>
    <b-row align-v="center">
      <job-card></job-card>
      <job-card></job-card>
      <job-card></job-card>
      <!-- <b-col md="3">
        <b-card
        bg-variant="dark"
        body-text-variant="white"
        title="1 Agriculture, Forestry, Fishing and Hunting"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="NAICS Code 11 Agriculture, Forestry, and Hunting"
        img-top
        tag="article"
        style="max-width:20rem"
        class="mb-2"
        >
          <b-card-text
            >LoremIpsum dolor sit amet</b-card-text
          >
          <b-button variant="primary">Quote</b-button>  
        </b-card>
      </b-col>
      <b-col md="3">
        <b-card
        bg-variant="dark"
        body-text-variant="white"
        title="2 Agriculture, Forestry, Fishing and Hunting"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="NAICS Code 11 Agriculture, Forestry, and Hunting"
        img-top
        tag="article"
        style="max-width:20rem"
        class="mb-2"
        >
          <b-card-text
            >LoremIpsum dolor sit amet</b-card-text
          >
          <b-button variant="primary">Quote</b-button>  
        </b-card>
      </b-col>
      <b-col md="3">
        <b-card
        bg-variant="dark"
        body-text-variant="white"
        title="3 Agriculture, Forestry, Fishing and Hunting"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="NAICS Code 11 Agriculture, Forestry, and Hunting"
        img-top
        tag="article"
        style="max-width:20rem"
        class="mb-2"
        >
          <b-card-text
            >LoremIpsum dolor sit amet</b-card-text
          >
          <b-button variant="primary">Quote</b-button>  
        </b-card>
      </b-col>
            <b-col md="3">
        <b-card
        bg-variant="dark"
        body-text-variant="white"
        title="4 Agriculture, Forestry, Fishing and Hunting"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="NAICS Code 11 Agriculture, Forestry, and Hunting"
        img-top
        tag="article"
        style="max-width:20rem"
        class="mb-2"
        >
          <b-card-text
            >LoremIpsum dolor sit amet</b-card-text
          >
          <b-button variant="primary">Quote</b-button>  
        </b-card>
      </b-col>
      
      <b-col>3 of 3</b-col>
      -->
    </b-row>
  </b-container>
  <!-- <div class="home"> -->
  <!-- 
      <img alt="Vue logo" src="../assets/logo.png" />
      <HelloWorld msg="Welcome to Your Vue.js App" />
    -->
  <!-- </div> -->
</template>

<script>
// @ is an alias to /src

// import HelloWorld from "@/components/HelloWorld.vue";
import JobCard from '@/components/JobCard.vue';

export default {
  name: "Home",
  components: {
    "job-card":JobCard
    // HelloWorld
  }
};
</script>
