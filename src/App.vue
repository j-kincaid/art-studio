<template>
  <div class="studio bg-black">
    <div class="frame mx-auto flex max-w-7xl items-center justify-between p-6 lg:px-8">
      <TheHeader></TheHeader>
      <img alt="Beaded artwork" src="./assets/nature-12.jpg">
    </div>
  </div>
</template>

<script>
import TheHeader from "./components/TheHeader.vue"
// import TheDream from "./components/TheDream.vue"

// import TheAbout from "./components/TheAbout.vue"

// import TheNature from "./components/TheNature.vue"


const Artworks = [
  {
    title: '10 minutes of nothing',
    image: './assets/nature-12.jpg',
    media: 'glass beads, thread.',
    height: 4, 
    width: 6, 
    units: 'in',
    year: 2021,
  },

  {
    title: 'The Building with Hematite Windows',
    media: 'glass beads, thread.',
    image: './assets/site-2.jpg',
    height: 19, 
    width: 16, 
    units: 'in',
    year: 2006,
  },
  {
    title: 'Climbing Inside the Tower',
    media: 'glass beads, thread.',
    image: './assets/site-7.jpg',
    height: 16, 
    width: 16, 
    units: 'in',
    year: 2009,
  },
  {
    title: 'The Crystal Chandelier',
    media: 'glass beads, thread.',
    image: './assets/abstract-2.jpg',
    height: 10.5, 
    width: 10.5, 
    units: 'in',
    year: 2012,
  },
  {
    title: 'Day and Night, MoBank Artboards Public Art Commission',
    media: 'Billboards displayed above Mobank Crossroads on Southwest Blvd, Kansas City, MO.',
    image: './assets/03_jkincaid.jpg',
    height: 27, 
    width: 12.4, 
    dimensions: '27 ft x 12.4 ft high, each board',
    year: 2018,
  },
  {
    title: 'Day and Night (digital proof)',
    media: 'digital proof',
    image: './assets/artboards.jpg',
    height: 2000, 
    width: 590, 
    dimensions: '2000 x 590px',
    year: 2018,
  },


  {
    title: 'First Grade Self-Portraits',
    media: 'glass beads, thread.',
    
    image: './assets/site-4.jpg',
    height: 14, 
    width: 17, 
    units: 'in',
    year: 2009,
  },
  {
    title: 'Heaven and Earth',
    media: 'glass beads, thread.',
    image: './assets/site-1.jpg',
    height: 14, 
    width: 17, 
    units: 'in',
    year: 2006,
  },
  {
    title: 'Inner City Brigadoon',
    media: 'glass beads, thread.',
    image: './assets/site-3.jpg',
    height: 15, 
    width: 17, 
    units: 'in',
    year: 2010,
  },
  {
    title: 'order | disorder',
    media: 'digital print, glass beads, thread.',
    image: './assets/10order2disorder.jpg',
    height: 6, 
    width: 12, 
    units: 'in',
    year: 2017,
  },
  {
    title: 'Perfume Counter',
    media: 'glass beads, thread.',
    image: './assets/site-5.jpg',
    height: 14, 
    width: 17, 
    units: 'in',
    year: 2009,
  },
  {
    title: 'Overstimulation vs. The Future',
    media: 'glass beads, thread.',
    image: './assets/abstract-1.jpg',
    height: 7, 
    width: 10.5, 
    units: 'in',
    year: 2010,
  },
  {
    title: 'Retail Theater',
    media: 'glass beads, thread.',
    image: './assets/site-6.jpg',
    height: 15, 
    width: 18, 
    units: 'in',
    year: 2009,
  },
  {
    title: 'The Spirit is present while we are looking away',
    media: 'glass beads, thread.',
    image: './assets/site-8.jpg',
    height: 12, 
    width: 10.5, 
    units: 'in',
    year: 2011,
  },  
  {
    title: 'The Sound of Snow',
    media: 'glass beads, thread.',
    image: './assets/abstract-3.jpg',
    height: 21, 
    width: 22, 
    units: 'in',
    year: 2015,
  },  
  {
    title: 'yellow { 75%; }',
    media: 'gouache on bristol board.',
    image: './assets/06yellowKey.jpg',
    height: 17, 
    width: 21, 
    units: 'in',
    year: 2017,
  },  
  {
    title: 'yellow { 75%; }',
    media: 'glass beads, thread.',
    image: './assets/07yellowBeaded.jpg',
    height: 5.5, 
    width: 5.5, 
    units: 'in',
    year: 2016,
  },
]

export default {
  name: 'App',
  components: {
    TheHeader,
    // TheDream, 
    // TheNature,
    // TheAbout,
    }
  };

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
