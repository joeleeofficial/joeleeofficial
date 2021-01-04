<svg width="100%" height="100%" xmlns="http://www.w3.org/2000/svg">
<script type="text/javascript">var countDownDate = new Date("Jan 1, 2022").getTime();
var x = setInterval(function() {
var now = new Date().getTime();
var distance = countDownDate - now;
var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
  document.getElementById("countdown").innerHTML = "🎉 "+ days + "d " + hours + "h "
  + minutes + "m " + seconds + "s "  + " 🎉";
    document.title = "🎉 "+ days + "d " + hours + "h "
  + minutes + "m " + seconds + "s "  + " 🎉";

    
}, 1000);</script>
<foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
            <h1 class="countdown" id="countdown" style=" text-align: center; font-size: 20pt;min-height: 10em;display: table-cell; font-family: 'Montserrat', sans-serif; text-align: center; vertical-align: middle;"></h1>
    </div>
</foreignObject>

</svg>
