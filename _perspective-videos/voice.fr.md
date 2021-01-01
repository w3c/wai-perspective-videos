---
lang: fr
permalink: /perspective-videos/voice/fr
translators: 
- name: "Sofia Ahmed"
contributors:
- name: "Sandra Velarde Gonzalez (ETNIC)"
ref: /perspective-videos/voice/
title: La reconnaissance vocale
order: 8
description: Courte vidéo à propos de la reconnaissance vocale pour l'accessibilité Web - de quoi s'agit-il, qui en bénéficie, et comment mettre cela en pratique.
image: /perspective-videos/img/voice.jpg
footer: >
  <p><strong>Statut :</strong> Mise à jour : 23 janvier 2019. <br><strong>Rédacteur et chef du projet :</strong> <a href="https://www.w3.org/People/shadi">Shadi Abou-Zahra</a>. Développé par le <a href="https://www.w3.org/WAI/EO/">Groupe de travail Éducation et Promotion</a> avec le soutien du projet <a href="https://www.w3.org/WAI/DEV/">WAI-DEV</a> financé par la Commission européenne (CE)<a href="./acknowledgements/">Remerciements</a>.</p>
---

L'accessibilité Web est essentielle pour les personnes en situation de handicap et utile à tous. Découvrez les effets de l'accessibilité et les avantages pour tous dans diverses situations.


## Vidéo sur la reconnaissance vocale
{:#film.no-display}

{% include video-player.html
    yt-id="7RHG_XiQ0ck"
    yt-id-ad="21yWr7evHTs"
    captions="/perspective-videos/cc/voice-en.vtt|en|Captions"
    captions-ad="/perspective-videos/cc/voice_ad-en.vtt|en|Captions"
    descriptions=""
    descriptions-ad="/perspective-videos/cc/voice_ad_desc-en.vtt|en|Descriptions"
%}

Les informations relatives à cette vidéo sont disponibles sous forme de [Transcription avec description visuelle](#transcript) en bas de la page.

Qu'est-ce que la "reonnaissance vocale" ? {#what}
----------------------------

La reconnaissance vocale peut être utilisée pour dicter du texte dans un champ de formulaire, mais également pour naviguer et activer des liens, des boutons, et d'autres commandes. La plupart des ordinateurs et des appareils mobiles possède une fonctionnalité de reconnaissance vocale intégrée. Certains outils de reconnaissance vocale permettent un contrôle complet sur l'interaction avec l'ordinateur, les utilisateurs pouvant, de cette manière, faire défiler l'écran, copier et coller du texte, activer des menus, et utiliser d'autres fonctions.

Qui en bénéficie ? {#who}
----------------------------

-   Les personnes handicapées qui ne peuvent pas utiliser le clavier ou la souris.
-   Les personnes souffrant de maladies chroniques, telles que les traumatismes liés au stress répétitif (RSI), qui ont besoin de limiter ou d'éviter l'utilisation d'un clavier ou d'une souris.
-   Les personnes souffrant de troubles cognitifs et d'apprentissage qui ont besoin d'utiliser la voix plutôt que le clavier.

Quels sont les autres avantages ? {#others}
---------------------------------

-   Le contenu est utile aux personnes ayant des limitations temporaires, comme un bras cassé.
-   Le contenu est plus facile à utiliser pour les personnes qui préfèrent parler plutôt que de taper, par exemple, lorsqu'elles sont occupées à autre chose.

Comment mettre cela en pratique ? {#action}
--------------------------------------

Le code et le design du contenu doivent être clairs pour pouvoir le contrôler par la voix. La [Compatibilité du clavier](/perspective-videos/keyboard/) est fondamentale pour un tel codage. De plus, les libellés (labels) et les identifiants pour les commandes dans le code source doivent correspondre à leur présentation visuelle, pour savoir clairement quelle instruction vocale va activer une commande.

Plus d'informations {#resources}
----------

-   **Principe d'accessibilité :**
    -   [Des fonctionnalités sont accessibles au clavier](/fundamentals/accessibility-principles/#keyboard) 
    -   [Le contenu apparaît et fonctionne de façon prévisible](/fundamentals/accessibility-principles/#predictable)
-   **Pour démarrer :**
    -   [S'assurer que tous les éléments interactifs sont accessibles au clavier](/tips/developing/#ensure-that-all-interactive-elements-are-keyboard-accessible) 
    -   [Fournir une explication pour les éléments intéractifs non standards](/tips/developing/#provide-meaning-for-non-standard-interactive-elements) 
    -   [Fournir une alternative textuelle pour les images](/tips/designing/#include-image-and-media-alternatives-in-your-design) 
-   **Vérification facile :**
    -   [Accès au clavier et "focus" visuel](/test-evaluate/preliminary/#interaction) 
    -   [Formulaires, libellés, et erreurs](/test-evaluate/preliminary/#forms)
-   **Témoignages d'utilisateurs :**
    -   [Alex, journaliste atteint d'un trouble musculosquelettique](/people-use-web/user-stories/#reporter)
-   **Règles d'accessibilité Web pour les contenus Web ([Vue d'ensemble des WCAG](/standards-guidelines/wcag/)):**
    -   [Critères de réussite liés au "clavier" et aux "commandes"](https://www.w3.org/WAI/WCAG21/quickref/?tags=keyboard%2Ccontrols) 
-   **Règles pour appareils mobiles :**
    -   [Utilisation requise de la souris pour les interactions et la navigation](/standards-guidelines/shared-experiences/#mouse) 
    -   [Etiquette de lien non descriptive](/standards-guidelines/shared-experiences/#link-label)
-   **Tutoriel :**
    -   [Tutoriels sur l'accessiblité Web](https://www.w3.org/WAI/tutorials/)
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
      <td>L'accessibilité Web illustrée : la reconnaissance vocale</td>
      <td>L'accessibilité Web illustrée :<br>
        la reconnaissance vocale</td>
    </tr>
    <tr>
      <td>Imaginez si vous ne pouvions communiquer avec votre famille que par écrit.<br></td>
      <td>Une jeune femme écrit :&quot;que veux-tu manger pour le petit-déjeuner ?&quot;, et donne le papier à l'homme assis à côté d'elle.<br></td>
    </tr>
    <tr>
      <td>Parfois, il est simplement plus facile de parler.<br>
        Une des avancées technologiques est la reconnaissance vocale.<br>
        Que ce soit pour effectuer une recherche sur le Web :</td>
      <td>Un homme utilise une tablette vocalement.</td>
    </tr>
    <tr>
      <td>(Utilisateur de la tablette) &quot;Architecture du dix-neuvième siècle.&quot;</td>
      <td>Des résultats de recherche apparaissent à l'écran.</td>
    </tr>
    <tr>
      <td>Dicter des e-mails.</td>
      <td>Un homme âgé utilise également une tablette vocalement.</td>
    </tr>
    <tr>
      <td>Ou contrôler votre application de navigation.</td>
      <td>Une jeune femme parle à son téléphone mobile et suit la direction sur son écran.</td>
    </tr>
    <tr>
      <td><p>De nombreuses personnes atteintes de handicaps dépendent de la reconnaissance vocale pour utiliser un ordinateur.<br>
          (Un homme dans un fauteuil roulant) &quot;Passer commande.&quot;<br>
        </p></td>
      <td>Un homme en fauteuil roulant utilise un casque pour l'ordinateur.</td>
    </tr>
    <tr>
      <td>Mais pour que cela soit possible, les sites et les applications Web doivent être codés correctement.<br>
(Un homme dans un fauteuil roulant)                     &quot;Annuler ?&quot;</td>
      <td>Rien ne se passe sur l'ordinateur.</td>
    </tr>
    <tr>
      <td> La reconnaissance vocale peut également aider de nombreuses autres personnes avec des limitations temporaires, telles qu'un bras cassé.<br>
(Une jeune femme)                     &quot;Passer commande.&quot;</td>
      <td>Une jeune femme avec un bras dans une écharpe utilise la fonctionnalité vocale avec succès.</td>
    </tr>
    <tr>
      <td>Cela peut aussi aider à prévenir l'aggravation d'un trouble, tel que les traumatisme liés au stress répétitif (RSI).</td>
      <td>Un homme est dehors avec son chien et prend des notes vocalement sur son téléphone mobile.</td>
    </tr>
    <tr>
      <td>Ou simplement pour les personnes préférant utiliser la voix.<br>
        (Un homme dans un fauteuil roulant) &quot;Passer commande.&quot;</td>
      <td>L'homme dans le fauteuil roulant navigue désormais sur un site Web qui fonctionne.</td>
    </tr>
    <tr>
      <td>L'accessiblité Web : essentielle pour certains, utile à tous.</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Visitez w3.org/WAI/perspectives pour plus d'information sur la reconnaissance vocale</td>
      <td>Visitez<br>
        w3.org/WAI/perspectives<br>
        pour plus d'informations sur<br>
        La reconnaissance vocale. <br>
        Logo de l'Initiative pour l'accessibilié du Web du W3C</td>
    </tr>
  </tbody>
</table>
