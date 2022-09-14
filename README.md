# webysitey.github.io

## Grabanakki

<center>
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.6.0/jquery.min.js"></script>
<script type="text/javascript">
$(function(){
    $('#button').click(function(){ 
        if(!$('#iframe').length) {
                $('#iframeHolder').html('<iframe frameborder="0" allowfullscreen="true" scrolling="no" src="https://v6p9d9t4.ssl.hwcdn.net/html/4768274/index.html" width="800" height="600" allowtransparency="true"></iframe>');
        }
    });   
});
</script>
 
<button id="button">Load Game "Grabanakki"</button>
<div id="iframeHolder"></div>
</center>

## Test 2

<p><button onclick="myFunction()">Show/Hide Game</button></p>

<div id="myDIV">
<iframe frameborder="0" allowfullscreen="true" scrolling="no" src="https://v6p9d9t4.ssl.hwcdn.net/html/4768274/index.html" width="800" height="600" allowtransparency="true"></iframe>
</div>
<script>
function myFunction() {
  var x = document.getElementById("myDIV");
  if (x.style.display === "none") {
    x.style.display = "block";
  } else {
    x.style.display = "none";
  }
}
</script>
