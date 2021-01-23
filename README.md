# IframeSourceJquery
you don't need iframe now !

```
<body onload="docs()">
<div id="docs"></div>
<script>
     function docs() {
     $.get('SITE_LINK', function(data) {
          $('#div').html(data);
document.getElementById("docs").innerHTML = data

        });
     }
</script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</body>

```
