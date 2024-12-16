<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ArchiVtects Website</title>
    <link rel="stylesheet" href="Charte.css">
</head>


  
<body>
    <!-- Entête -->
    <header class="entete">
        <h1>ArchiVtectes</h1>
	<h2>Repenser les archives</h2>
    </header>

  <div class="bloc-recherche">
    <div style="margin-left: 20px">
    <form id="searchForm">
    <input type="text" id="searchText" placeholder="Écrire ici..." required>
    <button type="submit">Envoyer</button>
</form>
      
<script src="https://www.gstatic.com/firebasejs/9.6.0/firebase-app.js"></script>
<script src="https://www.gstatic.com/firebasejs/9.6.0/firebase-database.js"></script>
      
<script>
    // Configuration Firebase
    const firebaseConfig = {
        apiKey: "AIzaSyD-OHFBsv6QuKJb4wSRqPKsAXKD2LL0tH4",
        authDomain: "archivtectes.firebaseapp.com",
        databaseURL: "https://archivtectes-default-rtdb.europe-west1.firebasedatabase.app",
        projectId: "archivtectes",
        storageBucket: "archivtectes.firebasestorage.app",
        messagingSenderId: "696235944431",
        appId: "1:696235944431:web:2458cf39251043a3546e1a"
    };
    // Initialiser Firebase
    const app = firebase.initializeApp(firebaseConfig);
    const database = firebase.database();

    document.getElementById('searchForm').addEventListener('submit', (e) => {
        e.preventDefault();
        const searchText = document.getElementById('searchText').value;
        // Envoyer les données dans Firebase
        firebase.database().ref('adminTexts').push({ text: searchText });
        alert('Texte enregistré !');
        document.getElementById('searchText').value = ''; // Réinitialise le champ
    });
</script>
                                         
  </div>
                                                    
    <!-- Zone de texte -->
    <div class="bloc-texte">   
    <h2 class="titre">Titre du bloc</h2>
    <p class="contenu">
       Voici un exemple de texte justifié qui peut s’étendre sur plusieurs lignes. 
        Ce texte est utilisé pour démontrer comment le style s’applique à un contenu
        textuel dans un bloc centré, avec une mise en page soignée.
    </p>
    <div class="references">
        <a href="file:///C:/Users/BOURGESL/Documents/Site/index.html" class="lien-reference">Référence 1</a>
        <a href="#lien2" class="lien-reference">Référence 2</a>
        <a href="#lien3" class="lien-reference">Référence 3</a>
    </div>
</div>

    <div>
        <div class="bloc-texte">
    <h2 class="titre">Titre du bloc</h2>
    <p class="contenu">
        Voici un exemple de texte justifié qui peut s’étendre sur plusieurs lignes. 
        Ce texte est utilisé pour démontrer comment le style s’applique à un contenu
        textuel dans un bloc centré, avec une mise en page soignée.
    </p>
                      
    <div class="references">
        <a href="#lien1" class="lien-reference">Référence 1</a>
        <a href="#lien2" class="lien-reference">Référence 2</a>
        <a href="#lien3" class="lien-reference">Référence 3</a>
    </div>
</section>

    <!-- Zone avec des hyperliens -->
    <footer class="liens">
        <h3>Liens utiles</h3>
        <ul>
            <li><a href="https://www.google.com" target="_blank">Google</a></li>
            <li><a href="https://www.wikipedia.org" target="_blank">Wikipedia</a></li>
            <li><a href="https://www.github.com" target="_blank">GitHub</a></li>
        </ul>
    </footer>
</body>
</html>
