<template lang="pug">
    li
        h2: a(href="artist.url" target="_blank") {{ artist.name }}
        img(:src="artist.image[2]['#text']", alt="")


</template>

<script>
export default {
    name: 'artist',
    props: ['artist']
}

</script>

<style lang="stylus" scoped>

li
    display block
    margin 10px 0

a
    font-size 1.5rem

</style>
