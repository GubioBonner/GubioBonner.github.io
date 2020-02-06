<!DOCTYPE html>
<html>
<body>

<script>
   if (typeof(stockdio_events) == "undefined") {
      stockdio_events = true;
      var stockdio_eventMethod = window.addEventListener ? "addEventListener" : "attachEvent";
      var stockdio_eventer = window[stockdio_eventMethod];
      var stockdio_messageEvent = stockdio_eventMethod == "attachEvent" ? "onmessage" : "message";
      stockdio_eventer(stockdio_messageEvent, function (e) {
         if (typeof(e.data) != "undefined" && typeof(e.data.method) != "undefined") {
            eval(e.data.method);
         }
      },false);
   }
</script>
<iframe id='st_cfe56f5970ba4cbdb3c7c9410e777ab3' frameBorder='0' scrolling='no' width='800' height='100%' src='https://api.stockdio.com/visualization/financial/charts/v1/historicalpricesboard?app-key=&indicators=SimpleMovingAverage(30);&stockExchange=Bovespa&symbols=PETR4;PETR3&dividends=true&splits=true&culture=Portuguese-Brasil&palette=Aurora&title=Watch%20List&onload=st_cfe56f5970ba4cbdb3c7c9410e777ab3'></iframe>
<br>
<a class="weatherwidget-io" href="https://forecast7.com/pt/n5d78n35d20/natal/" data-label_1="NATAL" data-label_2="previsão" data-font="Roboto" data-icons="Climacons Animated" data-theme="original" >NATAL previsão</a>
<script>
!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src='https://weatherwidget.io/js/widget.min.js';fjs.parentNode.insertBefore(js,fjs);}}(document,'script','weatherwidget-io-js');
</script>
TRA lA lA
   
</body>
</html>
