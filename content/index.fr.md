---
# translation notes are after "#" in this section

title: "Comment la WAI élabore les standards d'accessibilité selon le processus du W3C : étapes importantes et opportunités pour contribuer"
title_html: "Comment la WAI élabore les standards d'accessibilité selon le processus du W3C :<br> étapes importantes et opportunités pour contribuer"
nav_title: Processus du W3C pour élaborer les standards

ref: /standards-guidelines/w3c-process/    # Translators, do not change this

github:
  repository: w3c/wai-about-w3c-process
  path: content/index.fr.md    # Add the language shortcode to the middle of the filename, for example: index.fr.md
permalink: /standards-guidelines/w3c-process/fr   # Add the language shortcode to the end, with no slash at end, for example: /standards-guidelines/w3c-process/fr

lang: fr   # Change "en" to the translated language shortcode
last_updated: 2021-08-12   # Put the date of this translation YYYY-MM-DD (with month in the middle)
translators:   # remove from the beginning of the line: "# " and add your name(s)
- name: "Sofia Ahmed"
contributors:
- name: "Victoria Menezes Miller"
- name: "Sandra Velarde Gonzalez (ETNIC)"

layout: default
feedbackmail: wai@w3.org
footer: >
  <p><strong>Date :</strong> Mise à jour : 2 novembre 2020. Première publication : septembre 2006.</p>
  <p><strong>Rédactrice :</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Développé avec les données du Groupe de travail Éducation et Promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>).</p>

---


{::nomarkdown}
{% include box.html type="start" h="2" title="Introduction" class="full" %}
{:/}

L'Initiative pour l'accessibilité du Web (WAI) élabore les règles en matière d'accessibilité Web, les spécifications techniques et les ressources pédagogiques dans le but de rendre le Web accessible pour les personnes en situation de handicap. Ce document introduit comment la WAI travaille selon un processus conçu pour :

-   assurer une large participation de la communauté et
-   encourager le développement du [consensus](https://www.w3.org/Consortium/Process/#Consensus).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include_cached toc.html type="start" title="Table des matières" class="simple" %}
{:/}

{::options toc_levels="2,3" /}

-   This text will be replaced by the TOC.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Les standards du W3C {#standards}

Le World Wide Web Consortium (W3C) élabore les standards Web tels que l'HTML, le CSS, etc. La WAI fait partie du W3C et suit le [processus du W3C](http://www.w3.org/Consortium/Process/) pour l'élaboration de ces standards Web.

Les standards du W3C sont appelés ***Recommandations du W3C***. La WAI a élaboré plusieurs recommandations, dont :

-   Les Règles pour l'accessibilité des contenus Web, voir [Vue d'ensemble des WCAG]({{ "/standards-guidelines/wcag/" | relative_url }})
-   Les Règles d'accessibilité pour les outils d'édition, voir [Vue d'ensemble des ATAG]({{ "/standards-guidelines/atag/" | relative_url }})
-   Les Règles pour l'accessibilité des agents utilisateurs, voir [Vue d'ensemble des UAAG]({{ "/standards-guidelines/uaag/" | relative_url }})
-   Les applications internet riches accessibles, voir [Vue d'ensemble de WAI-ARIA]({{ "/standards-guidelines/aria/" | relative_url }})

**\[Les Règles d'accessibilité de la WAI\] qui constituent des \[W3C Recommandations\] sont des
\[ Standards Web\]**

### Les étapes importantes {#milestones}

Les étapes importantes par lesquelles doit passer le "rapport technique" pour devenir une recommandation du W3C sont énumérées ci-dessous.
{:#stages}

**Les projets des rédacteurs** n'ont pas de statut officiel, n'impliquent pas de consensus d'un groupe de travail, et ne sont pas approuvés par le W3C.

1.  {:#wd}![draft documents:]({{ "/content-images/wai-about-w3c-process/wd.gif" | relative_url }}){:style="float:left; margin-right: 1em; clear: left;"} **Les travaux préliminaires** : les travaux préliminaires sont publiés et annoncés dans le but de demander une révision et une participation de la communauté. Souvent, un groupe de travail souhaite une contribution particulière pour certaines questions. Habituellement, plusieurs travaux préliminaires d'un rapport technique sont publiés.
2.  {:#lcwd}![complete technical report:]({{ "/content-images/wai-about-w3c-process/lcwd.gif" | relative_url }}){:style="float:left; margin-right: 1em; clear: left;"} **Révision générale des travaux préliminaires** : lorsqu'un groupe de travail pense avoir répondu à tous les commentaires et aux besoins techniques, il fournit le document complet pour que la communauté le révise et annonce que le document est prêt pour une révision générale.
3.  {:#cr}![using computer with technical report:]({{ "/content-images/wai-about-w3c-process/cr.gif" | relative_url }}){:style="float:left; margin-right: 1em; clear: left;"} **Recommandation candidate** : L'objectif premier du statut de recommandation candidate est de s'assurer que le rapport technique peut être implémenté. Le W3C encourage les développeurs à utiliser le rapport technique dans leurs projets. Le rapport technique est stable à cette étape ; toutefois, il pourrait être modifié en fonction des résultats de l'implémentation.
4.  {:#pr}![endorsing technical report:]({{ "/content-images/wai-about-w3c-process/pr.gif" | relative_url }}){:style="float:left; margin-right: 1em; clear: left;"} **Proposition de recommandation** : après l'implémentation de chaque étape du rapport technique, le W3C annonce la proposition de recommandation. À ce stade, le rapport est soumis aux membres du W3C pour être approuvé.
5.  {:#rec}![approved technical report:]({{ "/content-images/wai-about-w3c-process/rec.gif" | relative_url }}){:style="float:left; margin-right: 1em; clear: left;"} **Recommandation du W3C
    (Standard Web)** : Lorsque le rapport technique est approuvé par les membres, le directeur et le public du W3C, il est publié en tant que recommandation. Le W3C encourage le déploiement à grande échelle de ses recommandations.

Il s'agit d'une description simplifiée du processus. Pour la version définitive, consultez le [document sur le processus du W3C, section 7 : Processus de développement d'un rapport technique du W3C](http://www.w3.org/Consortium/Process/#Reports).

## Ressources complémentaires {#other}

La WAI élabore également des documents qui corroborent les recommandations et qui ne suivent pas le processus décrit ci-dessus.
{:#other_docs}

-   Les **notes des groupes de travail du W3C** sont des rapports techniques consultatifs, et non des standards.
-   Les **ressources de la WAI** et les ressources du EOWG recouvrent un large éventail de sujets en matière d'accessibilité Web, tels que les [Composants essentiels de l'accessibilité Web]({{ "/fundamentals/components/" | relative_url }}), [Les WCAG 2 en un coup d'oeil](https://www.w3.org/WAI/standards-guidelines/wcag/glance/),
    les [Vérifications simples - Une première révision de l'accessibilité Web]({{ "/test-evaluate/preliminary/" | relative_url }}), et de nombreux autres sujets listés dans les [Ressources de la WAI](https://www.w3.org/WAI/resources/).

## Accès aux actualités de la WAI en rapport avec la collaboration de la communauté {#community}

Pour obtenir les annonces de la WAI à propos des travaux préliminaires à réviser par e-mail, Twitter, ou Atom/RSS feed, **allez sur [Obtenir les actualités de la WAI](https://www.w3.org/WAI/news/subscribe/)**.

Les recommandations du W3C et de la WAI, les notes de groupe de travail et les ressources sont élaborées au sein des [groupes de travail de la WAI]({{ "/about/groups/" | relative_url }})
avec la participation de la communauté. La WAI encourage activement la participation de l'industrie, des organisations de personnes handicapées, des chercheurs en accessibilité, du gouvernement, et d'autres interessés par l'accessibilité Web.

**[Participer à la WAI]({{ "/get-involved/" | relative_url }})**
décrit les manières dont vous pouvez contribuer aux travaux axés sur l'accessibilité de la WAI, notamment en révisant et en commentant les recommandations de la WAI au fur et à mesure de leur élaboration.

**Le moment opportun pour commenter est lorsque la WAI annonce que les travaux préliminaires sont prêts à être révisés**. Veuillez envoyer vos commentaires au début du processus, lorsque le groupe de travail est en mesure de les ajouter dans le rapport technique. Les commentaires techniques envoyés après la période prévue pour la révision générale a moins d'impact, et il est probable que le groupe de travail ne puisse pas apporter de modifications significatives à la fin du processus. Le document portant sur le processus du W3C fournit plus d'informations sur les [révisions et les responsabilités liées à celles-ci](https://www.w3.org/Consortium/Process/#doc-reviews).
