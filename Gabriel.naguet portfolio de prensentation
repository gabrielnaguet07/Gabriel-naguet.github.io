<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Portfolio de Gabriel Naguet</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="selection-langue">
        <img src="francais.png" alt="Français" class="drapeau" id="bouton-fr">
        <img src="anglais.png" alt="English" class="drapeau" id="bouton-en">
    </div>

    <div class="conteneur">
        
        <div class="boite entete">
            <h1>Gabriel Naguet</h1>
            <img src="moi.jpg" alt="Photo de Gabriel" class="photo-profil">
            <p class="fr">Étudiant en Réseaux & Télécommunications à l'IUT de Béziers</p>
            <p class="en">Networks & Telecommunications student at the IUT of Béziers</p>
        </div>

        <div class="boite">
            <h2 class="fr">À Propos de Moi</h2>
            <h2 class="en">About Me</h2>
            <p class="fr">Passionné par les mathématiques et l'informatique, j'ai développé une forte expertise en programmation, qui me permet de résoudre des problèmes complexes de manière créative. Mon intérêt pour ces disciplines me pousse à approfondir mes connaissances et à explorer les dernières innovations technologiques, afin de créer des solutions efficaces et performantes</p>
            <p class="en">Passionate about mathematics and computer science, I have developed strong expertise in programming, which allows me to solve complex problems creatively. My interest in these disciplines drives me to deepen my knowledge and explore the latest technological innovations in order to create efficient and effective solutions.</p>
        </div>

        <div class="boite">
            <h2 class="fr">Compétences</h2>
            <h2 class="en">Skills</h2>
			
            <p class="fr"><strong>administration Système : </strong>linux</p>
			<p class="fr"><strong>Développement d'outils Web : </strong>HTML, CSS et javaScript</p>
			<p class="fr"><strong>Programmation et Scripts : </strong>python</p>
			<p class="fr"><strong>Architecture Réseaux : </strong>Adressage IP et Cisco / Packet Tracer</p>
			
			<p class="en"><strong>System Administration: </strong> Linux</p>
			<p class="en"><strong>Web Development Tools: </strong> HTML, CSS and JavaScript</p>
			<p class="en"><strong>Programming and Scripts: </strong> Python</p>
			<p class="en"><strong>Network Architecture: </strong> IP Addressing and Cisco / Packet Tracer</p>
           
        </div>

        <div class="boite">
            <h2 class="fr">Pour me contact :</h2>
            <h2 class="en">To contact me:</h2>
            <p>Email : <a href="mailto:gabrielnaguet07@gmail.com">gabrielnaguet07@gmail.com</a></p>
            <p>LinkedIn : <a href="https://linkedin.com/in/gabriel-naguet-a4b05538b" target="_blank">Mon profil</a></p>
        </div>

    </div>

    <script>
        const btnFr = document.getElementById('bouton-fr');
        const btnEn = document.getElementById('bouton-en');
        const textesFr = document.querySelectorAll('.fr');
        const textesEn = document.querySelectorAll('.en');

        textesEn.forEach(t => t.style.display = 'none');

        btnFr.addEventListener('click', () => {
            textesFr.forEach(t => t.style.display = 'block');
            textesEn.forEach(t => t.style.display = 'none');
        });

        btnEn.addEventListener('click', () => {
            textesEn.forEach(t => t.style.display = 'block');
            textesFr.forEach(t => t.style.display = 'none');
        });
    </script>

</body>
</html>
