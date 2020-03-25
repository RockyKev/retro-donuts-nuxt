<template>
  <div>
    <Header />
    <Jumbotron />

    <TextImage>
      <h3 slot="header">this is a h3</h3>
      <p slot="paragraph">This is a para</p>
      <img slot="image" class="img-fluid" src="~assets/images/classic-donuts.png" />
    </TextImage>

    <ImageText>
      <img slot="image" class="img-fluid" src="~assets/images/classic-donuts.png" />

      <h3 slot="header">this is a h3</h3>
      <p slot="paragraph">This is a para</p>
    </ImageText>

    <TextImage>
      <h3 slot="header">this is a h3</h3>
      <p slot="paragraph">This is a para</p>
      <img slot="image" class="img-fluid" src="~assets/images/classic-donuts.png" />
    </TextImage>

    <CenterFluid column="col-4">
      <h3>We’ve created a classically new experience. Come on by!</h3>
      <p>
        10925 N Newport Hwy #1
        <br />Spokane, WA 99218
        <br />
        <br />Mon: Closed
        <br />Tue - Sat: 6AM - 3PM
        <br />Sun: 7AM - 1PM
      </p>
    </CenterFluid>

    <CenterFluid column="col-8">
      <img class="img-fluid" src="~assets/images/retro-ig-grid.png" />
    </CenterFluid>

    <Footer />
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Header from '~/components/Header.vue'
import Jumbotron from '~/components/Jumbotron.vue'
import TextImage from '~/components/layouts/TextImage.vue'
import ImageText from '~/components/layouts/ImageText.vue'
import CenterFluid from '~/components/layouts/CenterFluid.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Logo,
    Header,
    Jumbotron,
    Footer,
    TextImage,
    ImageText,
    CenterFluid
  }
}

const content1 = '<h3>Is it just us?</h3>'
</script>

<style>
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
