<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Pratique HTML</title>
</head>
<body>
<p>Bonjour. Vous souhaitez visiter <a href="https://openclassrooms.com">OpenClassrooms</a> ?<br />
C'est un bon site ;o)</p> 

<p>Bonjour. Souhaitez-vous consulter <a href="TEST.html">la page 2</a> ?</p>


<h1>Ma grande page</h1>

<p>
    Aller directement à la partie traitant de :<br />
    <a href="#cuisine">La cuisine</a><br />
    <a href="#rollers">Les rollers</a><br />
    <a href="#arc">Le tir à l'arc</a><br />
</p>
<h2 id="cuisine">La cuisine</h2>

<p>... (beaucoup de texte) ...</p>

<h2 id="rollers">Les rollers</h2>

<p>... (beaucoup de texte) ...</p>

<h2 id="arc">Le tir à l'arc</h2>

<p>... (beaucoup de texte) ...</p>


<h1>Le Mégamix</h1>
<p>
    Rendez-vous quelque part sur une autre page :<br />
    <a href="ancres.html#cuisine">La cuisine</a><br />
    <a href="ancres.html#rollers">Les rollers</a><br />
    <a href="ancres.html#arc">Le tir à l'arc</a><br />
</p>


<p>Bonjour. Souhaitez-vous visiter <a href="https://openclassrooms.com" title="Vous ne le regretterez pas !">OpenClassrooms</a> ?</p>

<p>Bonjour. Souhaitez-vous visiter <a href="https://openclassrooms.com" title="Vous ne le regretterez pas !" target="_blank">OpenClassrooms</a> ?</p>


<p><a href="mailto:votrenom@bidule.com">Envoyez-moi un e-mail !</a></p>

<p><a href="telecharger/Chat-master.zip">Télécharger le fichier</a></p>

<p>
    Voici une photo que j'ai prise lors de mes dernières vacances à la montagne :<br />
    <img src="img/montagne.jpg" alt="Photo de montagne" />

    <p>
    Voici une photo que j'ai prise lors de mes dernières vacances à la montagne :<br />
    <img src="img/montagne.jpg" alt="Photo de montagne" title="C'est beau les Alpes quand même !" />

    <p>
    Vous souhaitez voir l'image dans sa taille d'origine ? Cliquez dessus !<br />
    <a href="img/montagne.jpg"><img src="img/montagne_mini.jpg" alt="Photo de montagne" title="Cliquez pour agrandir" /></a>
</p>
</p>


<figure>
    <img src="img//blocnotes.png" alt="Bloc-Notes" />
</figure>

<figure>
    <img src="img/blocnotes.png" alt="Bloc-Notes" />
    <figcaption>Le logiciel Bloc-Notes</figcaption>
</figure>

<p>Connaissez-vous le logiciel Bloc-Notes ? On peut faire des sites web avec !</p>

<figure>
    <img src="img/blocnotes.png" alt="Bloc-Notes" />
    <figcaption>Le logiciel Bloc-Notes</figcaption>
</figure>

<figure>
    <img src="img/internetexplorer.png" alt="Logo Internet Explorer" />
    <img src="img/firefox.png" alt="Logo Mozilla Firefox" />
    <img src="img/chrome.png" alt="Logo Google Chrome" />
    <figcaption>Logos des différents navigateurs</figcaption>
</figure>

</body>
</html>
