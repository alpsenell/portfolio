<template>
    <div id="introduction-section">
        <Header/>
        <div class="columns">
            <div class="column">
                <h2 class="subtitle">Frontend Developer</h2>
                <h1 class="title">Alp Senel</h1>
            </div>
            <div class="column"></div>
        </div>
        <div class="half-background"></div>
    </div>
</template>

<script>
    import Header from './Header.vue'

export default {
  name: 'Introduction',
  components: {
    Header,
  }
};
</script>

<style scoped lang="scss">
    #introduction-section {
        width: 100vw;
        height: 100vh;

        > div {
            position: relative;
            z-index: 2;

            &.half-background {
                height: 70%;
                width: 100%;
                background-color: #d8aba1;
                position: absolute;
                top: 0;
                z-index: 1;
            }
        }
    }
</style>
