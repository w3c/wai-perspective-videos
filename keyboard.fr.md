---
lang: fr
permalink: /perspective-videos/keyboard/fr
translator: Sofia Ahmed
ref: /perspective-videos/keyboard/
title: La compatibilité du clavier
order: 1
description: Courte vidéo à propos de la compatibilité du clavier pour l'accessibilité Web - de quoi s'agit-il, qui en bénéficie, et comment mettre cela en pratique.

teaser_text: All functionality must be usable with the keyboard. That is, users can access links, buttons, forms, and other controls using the Tab key and other keystrokes. Websites should not require a mouse. Keyboard accessibility is essential for people with disabilities and benefits everyone in a variety of situations.
image: /perspective-videos/img/keyboard.jpg
footer: >
  <p><strong>Statut :</strong> Mise à jour 23 janvier 2019. <br><strong>Auteur et direction du projet :</strong> <a href="https://www.w3.org/People/shadi">Shadi Abou-Zahra</a>. Développé par l' <a href="https://www.w3.org/WAI/EO/">Education and Outreach Working Group (EOWG)</a> avec le soutien du projet <a href="https://www.w3.org/WAI/DEV/">WAI-DEV project</a> fondé par la Commission européenne (CE).<a href="./acknowledgements/">Remerciements (anglais)</a>.</p>
---

L'accessibilité Web est essentielle pour les personnes en situation de handicap et utile à tous. Découvrez les effets de l'accessibilité et les avantages pour tous dans diverses situations.

## Vidéo sur la compatibilité du clavier
{:#film.no-display}

{% include video-player.html
    yt-id="93UgG72os8M"
    yt-id-ad="1rBwxGMT9ZM"
    captions="/perspective-videos/cc/keyboard-en.vtt|en|Captions"
    captions-ad="/perspective-videos/cc/keyboard_ad-en.vtt|en|Captions"
    descriptions=""
    descriptions-ad="/perspective-videos/cc/keyboard_ad_desc-en.vtt|en|Descriptions"
%}

Les informations relatives à cette vidéo sont disponibles sous forme de [Transcription avec description visuelle](#transcript) en bas de la page.

## Qu'est-ce que la "compatibilité du clavier" ?
{:#what}

Toutes les fonctionnalités doivent être utilisables au clavier. L'utilisateur doit donc pouvoir accéder et naviguer entre les liens, les boutons, les formulaires, et les autres commandes en utilisant la touche de tabulation et les autres touches. Les sites Web ne devraient pas nécessiter de souris ; par exemple, les calendriers devraient aussi permettre aux utilisateurs d'entrer une date.  

## Qui en bénéficie ?
{:#who}

-   Les personnes atteintes de handicaps physiques qui ne peuvent pas utiliser la souris.
-   Les personnes aveugles, et qui ne peuvent pas voir le curseur sur l'écran.
-   Les personnes souffrant de maladies chroniques, telles que les traumatismes liés au stress répétitif (RSI), qui devraient limiter ou éviter l'utilisation d'une souris.

## Quels sont les autres avantages ?
{:#others}

-   Le contenu est utile aux les personnes faisant face à des limitations temporaires, telles qu'un bras cassé ou une souris cassée.

## Comment mettre cela en pratique ?
{:#action}

Les commandes HTML natives, comme les liens, les boutons, et les éléments de formulaire, fonctionnent par défaut avec le clavier et devraient être utilisées quand c'est possible. Les commandes personnalisées, les styles CSS, et les scripts qui contrôlent l'interaction pourraient nécessiter du codage supplémentaire pour la compatibilité du clavier. Assurez-vous que l'ordre de tabulation est logique pour permettre la navigation avec le clavier au sein du contenu et des commandes. Prévoyez un moyen pour que les utilisateurs puissent passer des blocs de contenu aux commandes. Les problèmes de clavier arrivent surtout dans les formulaires, les menus, et les applications contenant de nombreuses commandes.

## Plus d'informations
{:#resources}

-   **Principe d'accessibilité :**
    -   [Des fonctionnalités disponibles au clavier](/fundamentals/accessibility-principles/#keyboard) 
-   **Pour démarrer :**
    -   [S'assurer que tous les éléments interactifs sont accessibles au clavier](/tips/developing/#ensure-that-all-interactive-elements-are-keyboard-accessible) 
-   **Vérification simple :**
    -   [Accès depuis le clavier et attention apportée au visuel](/test-evaluate/preliminary/#interaction) 
-   **Témoignages d'utilisateurs :**
    -   [Alex, journaliste atteint d'un trouble musculosquelettique](/people-use-web/user-stories/#reporter)
    -   [Ilya, cadre supérieure, aveugle](/people-use-web/user-stories/#accountant)
    -   [Kasseem, adolescente sourde et aveugle](/people-use-web/user-stories/#teenager)
-   **Règles pour l'accessibilité des contenus Web([Vue d'ensemble des WCAG](/standards-guidelines/wcag/)) :** 
    -   [Critères de réussite liés au "clavier"](https://www.w3.org/WAI/WCAG21/quickref/?tags=keyboard) 
-   **Applicabilité au mobile :**
    -   [Souris requise pour l'interaction et la navigation](/standards-guidelines/shared-experiences/#mouse) 
-   **Tutoriel :**
    -   [Tutoriels sur l'accessibilité Web](https://www.w3.org/WAI/tutorials/)
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
      <td>Perspectives d'accessibilité Web : la compatibilité du clavier</td>
      <td>Perspectives d'accessibilité Web :<br>
        La compatibilité du clavier</td>
    </tr>
    <tr>
      <td>Il est frustrant de ne pas être capable d'utiliser votre ordinateur parce que votre souris ne fonctionne pas.</td>
      <td>Un homme fait tomber sa souris de son bureau. La souris ne fonctionne plus.</td>
    </tr>
    <tr>
      <td>De nombreuses personnes n'utilisent le clavier que pour naviguer sur des sites Web &mdash; soit par préférence, soit en fonction des circonstances.<br></td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Qu'il s'agisse d'une mobilité temporairement limitée,</td>
      <td>Une dame dont le bras est en écharpe tape sur un clavier &mdash; mais le site Web nécessite l'utilisation d'une souris pour sélectionner la date.</td>
    </tr>
    <tr>
      <td>d'un handicap physique permanent,</td>
      <td>Un homme en fauteuil roulante utilise un bâton bucal pour taper.</td>
    </tr>
    <tr>
      <td>ou simplement d'une souris cassée,<br>
        le résultat est le même :</td>
      <td>L'homme en fauteuil roulante ne peut pas non plus naviguer sur le site.</td>
    </tr>
    <tr>
      <td>Les sites et les applications Web doivent pouvoir fonctionner au clavier.</td>
      <td>Il se rend sur un autre site qui permet d'entrer la date.</td>
    </tr>
    <tr>
      <td>L'accessibilité Web : essentielle pour certains, utile à tous.</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Visitez w3.org/WAI/perspectives pour plus d'informations sur la compatibilité du clavier</td>
      <td>Visitez<br>
        w3.org/WAI/perspectives<br>
        pour plus d'informations sur<br>
        La compatibilité du clavier.<br>
        Logo du Web Accessibility Initiative du W3C</td>
    </tr>
  </tbody>
</table>
