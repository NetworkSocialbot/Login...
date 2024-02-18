<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate"/>
<meta http-equiv="Pragma" content="no-cache"/>
<meta http-equiv="Expires" content="0"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Auto Refresh and Redirect Page</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<button type="button" onclick="refreshAndRedirect()">Ok</button>
</body>
<script>
function refreshAndRedirect() {
   window.location.reload();
   setTimeout(function(){
       window.location.href = 'https://uniochange.com';
   }, 2000); // 2000 milliseconds (2 seconds) delay before redirection
}
</script>
</html>