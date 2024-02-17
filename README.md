<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rafraîchissement automatique</title>
<script>
// Vérifier si la page a déjà été rafraîchie
if(!sessionStorage.getItem('pageRefreshed')) {
  // Rafraîchir la page dès le chargement initial
  document.addEventListener("DOMContentLoaded", function() {
    refreshPage();
  });
  
  // Enregistrer en session que la page a été rafraîchie
  sessionStorage.setItem('pageRefreshed', true);
}

function refreshPage() {
  setTimeout(function() {
    location.reload();
  }, 500); // Rafraîchir la page après 5 secondes
}
</script>
</head>
<body>
<h1>Page actualisée automatiquement après 5 secondes</h1>
</body>
</html>
