<template>
  <Background>
    <div class="about">
      <div>
        <h1 class="flex justify-center text-4xl text-salmon-darkest uppercase mt-10">
          About this web
        </h1>
        <br />
        <div class="flex justify-center text-justify ">
          <div class="p-3 bg-white rounded-xl max-w-screen-lg hover:shadow">
            {{ about }}
            <a
              class="hover:underline"
              href="https://apod.nasa.gov/apod/astropix.html"
              >( https://apod.nasa.gov/apod/astropix.html )</a
            >
            In this website, You can see photo and detail of the picture from
            APOD and you can save detail and edit explanation for you will doing
            a research or write report etc.
          </div>
        </div>
        <br />
        <h1 class="flex justify-center text-4xl text- text-salmon-darkest uppercase">
          About this Developer
        </h1>
        <br />
        <div class="flex justify-center text-justify">
          <div class="p-3 bg-white rounded-xl max-w-screen-lg hover:shadow">
            {{ aboutDev }}
          </div>
        </div>
      </div>
    </div>
  </Background>
</template>

<script>
import Background from "../components/Background.vue";

export default {
  components: {
    Background,
  },
  data() {
    return {
      about:
        "This webside is have information about our universe or our earth such as Nabula, Galaxy,Physics particle, And that infomation updated each a day from APOD( Astronomy Picture of the Day ), And the APOD information from NASA API,",
      aboutDev:
        "Hello guys, I'm Diz or Pattarapol Sangsunee (62130500072), I'm who is love Physic and Astronomy so much and i saw normal people who don't care about Physic and Astronomy because maybe it not important in thier life , Therefore i create this website for want for thier know, Physic and Astronomy is important more than thier knew",
    };
  },
};
</script>

