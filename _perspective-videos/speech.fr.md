---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after "#".
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:"

title: "La synthèse vocale"
nav_title: "La synthèse vocale"
lang: fr
last_updated: 2020-12-31
order: 4

translators: 
- name: "Sofia Ahmed"
contributors:
- name: "Sandra Velarde Gonzalez (ETNIC)"

permalink: /perspective-videos/speech/fr    # Add the language shortcode to the end, with no slash at the end. For example /path/to/file/fr
ref: /perspective-videos/speech/    # Do not change this
acknowledgements: /perspective-videos/acknowledgements/ # Do not change this

description: Courte vidéo à propos de la synthèse vocale pour l'accessibilité Web - de quoi s'agit-il, qui en bénéficie, et comment mettre cela en pratique.
image: /perspective-videos/img/speech.jpg

vtt: speech # Do not change this

# In the footer below:
# Do not change the dates
# Do not translate or change ACKNOWLEDGEMENTS
# Translate the other words below.
# Translate the Working Group name. Leave the Working Group acronym in English.
footer: >
  <p><strong>Statut :</strong> Mise à jour : 23 janvier 2019. <br><strong>Rédacteur et chef du projet :</strong> <a href="https://www.w3.org/People/shadi">Shadi Abou-Zahra</a>. Développé par le <a href="https://www.w3.org/WAI/EO/">Groupe de travail Éducation et Promotion</a> avec le soutien du projet <a href="https://www.w3.org/WAI/DEV/">WAI-DEV</a> financé par la Commission européenne (CE) ACKNOWLEDGEMENTS.</p>
---

{::nomarkdown}
{% include vtt.html module="wai-perspective-videos" name=page.vtt l=page.lang langfolder=true %}
{:/}

L'accessibilité Web est essentielle pour les personnes en situation de handicap et utile à tous. Découvrez les effets de l'accessibilité et les avantages pour tous dans diverses situations.

## Vidéo sur la synthèse vocale
{:#film.no-display}

{% include video-player.html
    yt-id="8Rn5pXCdZWU"
    yt-id-ad="F3A1VffiOH4"
    path="/perspective-videos/cc/"
    captions=captions
    captions-ad=captions-ad
    subtitles=subtitles
    subtitles-ad=subtitles-ad
    descriptions=descriptions
    descriptions-ad=descriptions-ad
%}

Les informations relatives à cette vidéo sont disponibles sous forme de [Transcription avec description visuelle](#transcript) en bas de la page.

Qu'est-ce que la "synthèse vocale" ? {#what}
-------------------------

De nombreux ordinateurs et appareils mobiles possèdent un logiciel de synthèse vocale intégré. Certaines personnes atteintes de handicaps, y compris les personnes aveugles, utilisent des logiciels spécialisés appelés lecteurs d'écran. Les lecteurs d'écran fournissent des fonctionnalités importantes telles que la navigation au sein des rubriques, des alternatives vocales pour les images, et l'identification des liens internes et externes. Ils peuvent également mettre le texte en subrillance au fur et à mesure de la lecture vocale pour les personnes qui souhaitent voir et entendre le contenu en même temps. Le contenu doit être codé correctement pour que toutes les fonctionnalités du logiciel de synthèse vocale puissent fonctionner avec le contenu en question.

Qui en bénéficie ? {#who}
----------------------------

-   Les personnes aveugles et qui ne peuvent pas voir l'écran.
-   Les personnes malvoyantes (souvent légalement aveugles) et qui ne peuvent pas voir certains types de contenus.
-   Les personnes souffrant de dyslexie et d'autres troubles cognitifs et d'apprentissage qui ont besoin d'entendre et de voir le texte pour mieux le comprendre.

Quels sont les autres avantages ? {#others}
---------------------------------

-   Le contenu peut être lu à voix haute pour les personnes qui ne peuvent pas voir le langage écrit.
-   Le contenu peut être lu à voix haute pour les personnes qui préfèrent écouter, par exemple, en faisant autre chose.

Comment mettre cela en pratique ? {#action}
--------------------------------------

Utilisez le balisage HTML sémantique pour les structures telles que les headings, les paragraphes, les listes, les formulaires, et les tableaux. Fournissez des alternatives textuelles pour les images, les icônes, et d'autres contenus non textuels. Assurez-vous de la [Compatibilité du clavier](/perspective-videos/keyboard/), et assurez-vous que l'information du texte est compréhensible sans le contexte visuel.

Plus d'informations {#resources}
----------

-   **Principes d'accessibilité :**
    -   [Équivalents textuels pour les contenus non textuels](/fundamentals/accessibility-principles/#alternatives)
    -   [Le contenu apparaît et fonctionne de façon prévisible](/fundamentals/accessibility-principles/#adaptable)
-   **Pour démarrer :**
    -   [Ecrire des équivalents textuels significatifs pour les images](/tips/writing/#write-meaningful-text-alternatives-for-images) 
    -   [Utiliser des en-têtes pour donner du sens et structurer](/tips/writing/#use-headings-to-convey-meaning-and-structure) 
    -   [Identifier la langue des pages et les changements de langue](/tips/developing/#identify-page-language-and-language-changes) 
-   **Vérification facile :**
    -   [Équivalents textuels pour les images ("alt
        text")](/test-evaluate/preliminary/#images) 
    -   [Vérification de la structure de base](/test-evaluate/preliminary/#structure) 
-   **Témoignages d'utilisateurs :**
    -   [Ilya, cadre supérieure, aveugle](/people-use-web/user-stories/#accountant)
    -   [Kasseem, adolescente sourde et aveugle](/people-use-web/user-stories/#teenager)
    -   [Preety, collégienne atteinte d'un trouble du déficit de l'attention avec hyepractivité et dyslexie](/people-use-web/user-stories/#classroomstudent)
-   **Règles d'accessibilité Web pour les contenus Web ([Vue d'ensemble des WCAG](/standards-guidelines/wcag/)):**
    -   [Critères de réussite liés aux "images" et à la "structure"](https://www.w3.org/WAI/WCAG21/quickref/?tags=images%2Cstructure)
-   **Règles pour appareils mobiles :**
    -   [Objets non textuels (images, son, vidéo) sans équivalents textuels](/standards-guidelines/shared-experiences/#non-text) 
    -   [Information transmise en utilisant seulement du CSS (formatage visuel)](/standards-guidelines/shared-experiences/#visual-formatting) 
    -   [Étiquette de lien non descriptive](/standards-guidelines/shared-experiences/#link-label) 
-   **Tutoriel:**
    -   [Tutoriels sur l'accessibilité](https://www.w3.org/WAI/tutorials/) 
        (plusieurs sujets relatifs)

## Transcription avec description visuelle {#transcript}

<table>
  <thead>
    <tr>
      <th width="65%">Audio</th>
      <th>Visuel</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>L'accessibilité Web illustrée : la synthèse vocale</td>
      <td>L'accessibilité Web illustrée :<br>
        La synthèse vocale</td>
    </tr>
    <tr>
      <td>(L'ordinateur) &quot;Certaines personnes ne peuvent pas voir le texte sur cet écran.&quot;<br>
(L'ordinateur)                     &quot;Heureusement, les ordinateurs peuvent convertir le texte en écrit en langage oral.&quot;</td>
      <td>Un homme utilise un ordinateur portable dont l'écran montre un texte mis en surbrillance à mesure qu'il est dicté.</td>
    </tr>
    <tr>
      <td>C'est une technologie dont dépendent de nombreuses personnes aveugles depuis des années.</td>
      <td>Un chien-guide est couché aux pieds de l'homme. Il pourrait s'agir d'une personne aveugle.</td>
    </tr>
    <tr>
      <td>Mais c'est également important pour de nombreuses personnes souffrant de dyslexie.</td>
      <td>Une jeune femme lit quelque chose sur une tablette et écoute avec un casque.</td>
    </tr>
    <tr>
      <td>Et cela est très utile pour des personnes éprouvant des difficultés à lire un texte.</td>
      <td>Un homme enlève ses lunettes et écoute un article d'actualité sur sa tablette.</td>
    </tr>
    <tr>
      <td>Tout comme pour les personnes qui aiment faire autre chose en même temps.</td>
      <td>Un homme écoute un article de revue en faisant la vaisselle.</td>
    </tr>
    <tr>
      <td>Mais pour que cela fonctionne, les sites et les applications Web doivent être codés correctement.</td>
      <td>Le site Web ne fonctionne pas correctement pour la jeune femme avec le casque. Elle est frustrée.</td>
    </tr>
    <tr>
      <td>Ce qui a pour avantage supplémentaire d'aider à mieux indexer les contenus de sites Web dans les moteurs de recherche.</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>L'accessibilité Web : essentielle pour certains, utile à tous.</td>
      <td>L'homme avec le chien-guide utilise son appareil mobile dehors avec un casque à conduction osseuse. La vidéo montre les différentes personnes intervenues plus tôt utiliser la synthèse vocale.</td>
    </tr>
    <tr>
      <td>Allez sur w3.org/WAI/perspectives pour plus d'informations sur la synthèse vocale.</td>
      <td>Allez sur<br>
        w3.org/WAI/perspectives<br>
        pour plus d'informations sur<br>
        La synthèse vocale. <br>
        Logo de l'Initiative pour l'accessibilité du Web du W3C</td>
    </tr>
  </tbody>
</table>
