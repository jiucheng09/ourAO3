<span id="v0.1-alpha-dl-count"></span>
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script>
getDlCount('https://api.github.com/repos/jiucheng09/ourAO3/releases/assets/19114150', '#v0.1-alpha-dl-count');
function getDlCount(url, selector) {
    $.get(url, function (data) {
    $(selector).html = '下载次数：' + data.download_count;
  });
}
</script>
