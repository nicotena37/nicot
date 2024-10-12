# nicot
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sambadobrasil</title>
    <script>
        function reindirizza() {
            if (localStorage.getItem("visitato")) {
                window.location.href = "https://www.youtube.com/watch?v=TsMKfLaBwhw";
            } else {
                localStorage.setItem("visitato", "true");
                setTimeout(function() {
                    window.location.href = "https://www.youtube.com/watch?v=TsMKfLaBwhw";
                }, 10000);
            }
        }
    </script>
</head>
<body onload="reindirizza()">
    <h1 id="messaggio">sambadobrasil</h1>
</body>
</html>
