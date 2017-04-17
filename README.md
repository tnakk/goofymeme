<html>
<h2><center><font size="15">Goofy Meme!</font></center></h2>
<head>
<style>
  * {
    padding: 0;
    margin: 0;
  }
  .fit { /* set relative picture size */
    max-width: 100%;
    max-height: 100%;
  }
  audio { 
   display:none;
}
  .center {
    display: block;
    margin: auto;
  }
</style>
</head>
<body>

<audio controls autoplay>
  <source src="23153880.mp3" type="audio/mp3">
</audio>
<img class="center fit" src="EBjQFBM.jpg" >    

<script src="http://code.jquery.com/jquery-latest.js"></script>
<script type="text/javascript" language="JavaScript">
  function set_body_height() { // set body height = window height
    $('body').height($(window).height());
  }
  $(document).ready(function() {
    $(window).bind('resize', set_body_height);
    set_body_height();
  });
</script>

</body>
</html>
