<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script>
  $.get('https://api.github.com/repos/jiucheng09/ourAO3/releases/assets/19114150', function (data) {
    console.log(data);
    console.log(data.download_count);
  });
</script>
