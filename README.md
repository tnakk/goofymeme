<html>
<body>
<h2><center> Goofy Meme! </center></h2>
<style>
* {
  padding: 0;
  margin: 0;
}
.fit {
  max-width: 100%;
  max-height: 100%;
}
.center {
  display: block;
  margin: auto;
}
</style>
<script src="http://code.jquery.com/jquery-latest.js"></script>
<script type="text/javascript" language="JavaScript">
function set_body_height()
{
    var wh = $(window).height();
    $('body').attr('style', 'height:' + wh + 'px;');
}
$(document).ready(function() {
    set_body_height();
    $(window).bind('resize', function() { set_body_height(); });
});
</script>
</head>
<body>
<img id="Goofy_Meme" class="center fit" src="EBjQFBM.jpg" >   
</body>
</html>
