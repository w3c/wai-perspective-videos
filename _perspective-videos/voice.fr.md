---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after "#".
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:"

title: "La reconnaissance vocale"
nav_title: "Reconnaissance vocale"
lang: fr
last_updated: 2023-10-16    # Put the date of this translation YYYY-MM-DD (with month in the middle)
order: 8

translators:
- name: "Sofia Ahmed"
- name: "Rémi Bétin"
contributors:
- name: "Sandra Velarde Gonzalez (ETNIC)"

permalink: /perspective-videos/voice/fr # Add the language shortcode to the end, with no slash at the end. For example /path/to/file/fr
ref: /perspective-videos/voice/ # Do not change this
changelog: /perspective-videos/changelog/ # Do not change this
acknowledgements: /perspective-videos/acknowledgements/ # Do not change this

description: Courte vidéo à propos de la reconnaissance vocale pour l'accessibilité Web - de quoi s'agit-il, qui en bénéficie, et comment mettre cela en pratique.
image: /perspective-videos/img/voice.jpg

# In the footer below:
# Do not change the dates
# Do not translate or change ACKNOWLEDGEMENTS
# Translate the other words below.
# Translate the Working Group name. Leave the Working Group acronym in English.
footer: >
  <p><strong>Statut :</strong> Mise à jour : 26 février 2021. Première publication en mai 2016. CHANGELOG.<br>
    <strong>Rédacteur et chef de projet :</strong> <a href="https://www.w3.org/People/shadi">Shadi Abou-Zahra</a>. Développé par le <a href="https://www.w3.org/WAI/EO/">Groupe de travail Éducation et Promotion</a> avec le soutien du projet <a href="https://www.w3.org/WAI/DEV/">WAI-DEV</a>, co-financé par la Commission européenne (CE). Mis à jour avec le soutien de la Fondation Ford. ACKNOWLEDGEMENTS.</p>

# Read Translations Notes for this resource at https://github.com/w3c/wai-perspective-videos#readme
---

L'accessibilité Web est essentielle pour les personnes en situation de handicap et utile à tous. Découvrez les effets de l'accessibilité et les bénéfices pour tous dans diverses situations.

La «&nbsp; reconnaissance vocale&nbsp;» (ou «&nbsp; reconnaissance automatique de la parole&nbsp;») concerne la reconnaissance des mots pour la transcription de la parole en texte, les assistants virtuels et les autres interfaces de commande vocale. La «&nbsp;reconnaissance des voix&nbsp;» ou «&nbsp; reconnaissance des locuteurs&nbsp;» est une technologie qui identifie qui est le locuteur, et non les mots qu'il prononce.

## Vidéo sur la reconnaissance vocale
{:#film.no-display}

{% include video-player-data.html
    yt-id="7RHG_XiQ0ck"
    yt-id-ad="21yWr7evHTs"
    path="/perspective-videos/cc/"
    lang-folder=true
    vtt-data-location="wai-perspective-videos"
    vtt-name="voice"
%}

Les informations de cette vidéo sont disponibles sous forme de [Transcription avec description des visuels](#transcript) en bas de la page.

Qu'est-ce que la «&nbsp;reconnaissance vocale&nbsp;» ? {#what}
----------------------------

La reconnaissance vocale peut être utilisée pour dicter du texte dans un champ de formulaire, mais également pour naviguer et activer des liens, des boutons, et d'autres composants d'interface. La plupart des ordinateurs et des appareils mobiles possèdent une fonctionnalité de reconnaissance vocale intégrée. Certains outils de reconnaissance vocale permettent un contrôle complet sur l'interaction avec l'ordinateur&nbsp;; les utilisateurs pouvant, de cette manière, faire défiler l'écran, copier et coller du texte, activer des menus, et utiliser d'autres fonctions.

Qui dépend de cette fonctionnalité ? {#who}
----------------------------

-   Les personnes en situation de handicap physique qui ne peuvent pas utiliser le clavier ou la souris.
-   Les personnes souffrant de maladies chroniques, telles que des troubles musculo-squelettiques (TMS), qui ont besoin de limiter ou d'éviter l'utilisation du clavier ou de la souris.
-   Les personnes avec des troubles cognitifs et d'apprentissage qui ont besoin d'utiliser la parole plutôt que taper au clavier.

Quels sont les autres bénéfices ? {#others}
---------------------------------

-   Le contenu est utilisable par les personnes en situation de handicap temporaire, telle qu'un bras cassé.
-   Le contenu est plus utilisable par les personnes qui préfèrent parler plutôt que taper au clavier&nbsp;; par exemple, en faisant autre chose.

Comment mettre cela en pratique ? {#action}
--------------------------------------

Le contenu doit être conçu et codé correctement pour pouvoir être contrôlé par la voix. La [compatibilité avec le clavier](/perspective-videos/keyboard/) est la base d'un tel codage. De plus, les étiquettes et les identifiants des composants d'interface dans le code source doivent correspondre à leur présentation visuelle, de manière à clarifier quelle instruction vocale activera un composant d'interface.

Plus d'informations {#resources}
----------

-   **Principe d'accessibilité :**
    -   [Des fonctionnalités sont accessibles au clavier](/fundamentals/accessibility-principles/#keyboard) 
    -   [Le contenu apparaît et fonctionne de façon prévisible](/fundamentals/accessibility-principles/#predictable)
-   **Pour démarrer :**
    -   [Assurez-vous que tous les éléments interactifs sont accessibles au clavier](/tips/developing/#ensure-that-all-interactive-elements-are-keyboard-accessible) 
    -   [Transmettez une signification pour les éléments interactifs non standards](/tips/developing/#provide-meaning-for-non-standard-interactive-elements) 
    -   [Incluez des équivalents aux images](/tips/designing/#include-image-and-media-alternatives-in-your-design) 
-   **Vérifications faciles :**
    -   [Accès au clavier et visibilité du focus](/test-evaluate/preliminary/#interaction) 
    -   [Formulaires, étiquettes, et erreurs](/test-evaluate/preliminary/#forms)
-   **Témoignages d'utilisateurs :**
    -   [Alex, journaliste avec un trouble musculo-squelettique](/people-use-web/user-stories/#reporter)
-   **Règles pour l'accessibilité des contenus Web ([Vue d'ensemble des WCAG](/standards-guidelines/wcag/)):**
    -   [Critères de succès liés au "clavier" et aux "commandes"](https://www.w3.org/WAI/WCAG21/quickref/?tags=keyboard%2Ccontrols) 
-   **Applicabilité aux appareils mobiles :**
    -   [La souris est requise pour l'interaction et la navigation](/standards-guidelines/shared-experiences/#mouse) 
    -   [Etiquette de lien non descriptive](/standards-guidelines/shared-experiences/#link-label)
-   **Tutoriel :**
    -   [Tutoriels sur l'accessiblité Web](/tutorials/)
        (plusieurs sujets à ce propos)

## Transcription avec description des visuels {#transcript}

<table>
  <thead>
    <tr>
      <th width="65%">Audio</th>
      <th>Visuel</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>L'accessibilité Web illustrée : la reconnaissance vocale</td>
      <td>L'accessibilité Web illustrée :<br>
        la reconnaissance vocale</td>
    </tr>
    <tr>
      <td>Imaginez si vous ne pouviez communiquer avec votre famille que par écrit.<br></td>
      <td>Une femme écrit : «&nbsp; Que veux-tu manger pour le petit-déjeuner ?&nbsp;», et donne le papier à l'homme assis à côté d'elle.<br></td>
    </tr>
    <tr>
      <td>Parfois, il est juste plus facile de parler.<br>
        Un des progrès de la technologie est la reconnaissance vocale.<br>
        Que ce soit pour effectuer une recherche sur le Web&nbsp;:</td>
      <td>Un homme utilise une tablette grâce à sa voix.</td>
    </tr>
    <tr>
      <td>(Un utilisateur de tablette) «&nbsp;Architecture du dix-neuvième siècle&nbsp;»,</td>
      <td>Des résultats de recherche apparaissent à l'écran.</td>
    </tr>
    <tr>
      <td>dicter des e-mails,</td>
      <td>Un homme âgé utilise également une tablette grâce à sa voix.</td>
    </tr>
    <tr>
      <td>ou contrôler votre application de navigation.</td>
      <td>Une femme parle à son téléphone mobile et suit les instructions de navigation sur l'écran.</td>
    </tr>
    <tr>
      <td><p>De nombreuses personnes en situation de handicap physique dépendent de la reconnaissance vocale pour utiliser un ordinateur.<br>
          (Un homme dans un fauteuil roulant) «&nbsp;Passer commande.&nbsp;»<br>
        </p></td>
      <td>Un homme en fauteuil roulant utilise un casque pour l'ordinateur.</td>
    </tr>
    <tr>
      <td>Mais pour que cela soit possible, les sites Web et les applications doivent être codés correctement.<br>
(Un homme dans un fauteuil roulant) «&nbsp;Annuler&nbsp;?&nbsp;»</td>
      <td>Rien ne se passe sur l'ordinateur.</td>
    </tr>
    <tr>
      <td> La reconnaissance vocale peut également aider de nombreuses autres personnes en situation de handicap temporaire, telle qu'un bras cassé.<br>
(Une jeune femme) «&nbsp;Passer commande.&nbsp;»</td>
      <td>Une femme avec un bras dans une écharpe utilise la reconnaissance vocale avec succès.</td>
    </tr>
    <tr>
      <td>Cela peut aussi prévenir l'aggravation d'un trouble, tel les troubles musculo-squelettiques (TMS).</td>
      <td>Un homme est dehors avec son chien et dicte des notes sur son téléphone mobile.</td>
    </tr>
    <tr>
      <td>Ou simplement être utile aux personnes qui préfèrent utiliser la voix.<br>
        (Un homme dans un fauteuil roulant) «&nbsp;Passer commande.&nbsp;»</td>
      <td>L'homme dans le fauteuil roulant utilise désormais un site Web qui fonctionne.</td>
    </tr>
    <tr>
      <td>L'accessiblité Web : essentielle pour certains, utile à tous.</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Visitez w3.org/WAI/perspectives pour plus d'information sur <em>La reconnaissance vocale.</em></td>
      <td>Visitez<br>
        w3.org/WAI/perspectives<br>
        pour plus d'informations sur<br>
        <em>La reconnaissance vocale.</em> <br>
        Logo de l'Initiative pour l'accessibilié du Web du W3C</td>
    </tr>
  </tbody>
</table>
