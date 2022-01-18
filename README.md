# exercice_risque_et_securite_faille1
MODULE
Risques et sécurité 

CSRF, XSS et Injection sql

Exercice 1 : 
 Qu’est ce qu’une Injection XSS :

Exercice 2 :
Rendez vous sur le site :

http://altoromutual.com
Que pouvez-vous dire de ce site ?

Quelles sont les failles exploitables ?

Exercice 3 :
Exécuter ses script :

<script>
   alert(Hello World);
</script>

<script>
   document.getElementById('header').style.display='none';
</script>

<script>
   var parent = document.getElementsByClassName('fl')[0];
   var a = document.createElement('a');
   var linkText = document.createTextNode('Lien sécurisé');
   a.appendChild(linkText);
   a.title = 'Lien sécurisé';
   a.href = 'https://google.com';
   parent.appendChild(a);
</script>

<script>
   document.getElementById('HyperLink1').href="https://google.com";
</script>

<script>
   var script = document.createElement('script');
   script.src = 'https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js';
   document.head.appendChild(script);
</script>

<script>
   alert(document.cookie);
</script>

Exercice 4 :
Un peu de pratique !

 Exercice 5 :
A quoi peut servir XSS ?

Exercice 6:
Quelles sont les moyens de prévenir ce genre de faille ? 


Exercice 7 :
Trouver la définition de ces 3 fonctions PHP
htmlspecialchars, htmlentities, trim
—--------------------------------------------------------------------------------------------
This work is licensed under the Creative Commons Attribution - Pas d'Utilisation Commerciale - Pas de Modification 4.0 International License. To view a copy of this license, visit
http://creativecommons.org/licenses/by-nc-nd/4.0/.
 













