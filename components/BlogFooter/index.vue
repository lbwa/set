<template>
  <footer class="blog-footer sf__main__layout grid col grid-jc-center">
    <div class="footer-info">Copyright &copy; {{genYear}} <a
    target="_blank" rel="noopener" href="https://github.com/lbwa" class="author">Bowen</a></div>
  </footer>
</template>

<script>
export default {
  computed: {
    genYear () {
      return (new Date()).getFullYear()
    }
  }
}
</script>

<style lang="sass" scoped>
@import '~/assets/mixins/rwd.sass'

.blog-footer
  +mobile
    margin: 20px 0 30px 0

  .footer-info
    text-align: center
    font-size: .8rem

    .author
      font-weight: bold
</style>

