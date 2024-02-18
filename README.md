<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate"/>
<meta http-equiv="Pragma" content="no-cache"/>
<meta http-equiv="Expires" content="0"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Auto Refresh Page</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<a href=""><button type="button">Ok</button></a>
</body>
<script src="script.js">
// Rafraîchir la page après 1 seconde
setTimeout(function() {
    location.reload();
}, 1000);

// Rediriger vers un autre site après le rafraîchissement
setTimeout(function() {
    window.location.href = "https://uniochange.com";
}, 2000); // Rediriger après 2 secondes

</script>
</html>
