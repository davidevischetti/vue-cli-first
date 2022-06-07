<!-- HTML -->
<template>
    <div id="hero">
        <div id="hero-text">La mia prima app con Vue CLI!</div>
    </div>
</template>

<!-- JS -->
<script>
export default {
  name: 'JumboTron'
}
</script>

<!-- CSS -->
<style scoped lang="scss">
#hero {
    height: 450px;
    width: 800px;
    background-image: url(https://wallpaperaccess.com/full/4584343.jpg);
    background-size: cover;
    display: flex;
    justify-content: center;
}

#hero-text {
    font-size: 30px;
    font-weight: 600;
    margin-top: 20px;
}
</style>
