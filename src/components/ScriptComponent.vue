<!-- <script src="../assets/js/plugins.js"></script>
<script src="../assets/js/jquery.countdown.min.js"></script>
<script src="../assets/js/main.js"></script>
<script src="../assets/js/jquery.js"></script> -->
<script>
export default {
  mounted() {
    const script = document.createElement('script')
    script.src = '../assets/js/main.js'
    document.body.appendChild(script)
  },
}
</script>
