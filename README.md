## 档案馆 created by 九澄

这是我自己业余时间开发的 APP，只有安卓版，是为了方便更多姐妹在被墙期间访问 AO3。下载安装 APP 即可访问 AO3，无需借助科学上网工具。如果有任何问题和建议，都可以邮箱联系我：archive_dag@protonmail.com

[点此下载安装](https://github.com/jiucheng09/ourAO3/releases/download/v0.1-alpha/app-release.apk) <span id="01dlcount"></span>

<script src="https://cdn.staticfile.org/jquery/3.4.1/jquery.min.js"></script>
<script>
getDlCount('https://api.github.com/repos/jiucheng09/ourAO3/releases/assets/19114150', '#01dlcount');
function getDlCount(url, selector) {
    $.get(url, function (data) {
    $(selector).html('下载次数：' + data.download_count);
  });
}
</script>
