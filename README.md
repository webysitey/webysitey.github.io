# webysitey.github.io

## Test One

Game Links:
 - 1
 - 2
 - 3
 - 4
 - 5

## Image

![title](https://images.unsplash.com/photo-1453728013993-6d66e9c9123a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8bGVuc3xlbnwwfHwwfHw%3D&w=1000&q=80)

## Game Test 1
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

## Game Test 2

<button onclick="myFunction()">Show/Hide Game</button>

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
