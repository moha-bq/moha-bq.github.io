---
layout: default
lang: fr
title: Mes projets
about_me: Mohammed BEQQI est un programmeur passionné, qui porte un intérêt particulier pour les systèmes temps-réel. Il pratique le C/C++ depuis plus de dix ans, période durant laquelle il a exploré en profondeur le fonctionnement des ordinateurs et a développé des compétences solides en algorithmique et en structures de données.
---

<br>

<div style="text-align: center;">
<h1> Medit </h1>
<h3> Mon éditeur C/C++ personnel</h3>
</div>

Afin d'apprendre et en tant que service à moi-même, j'ai décidé de créer un éditeur de code adapté à mes besoins et à mes habitudes. Il est encore en cours de développement, mais il est déjà tout à fait utilisable.

Fonctionnalités: 
* Edition de texte basique: Copier/Coller, Annuler/Rétablir, UTF-8, Rechercher et remplacer, ...
* Coloration syntaxique
* Auto-Complétion
* Edition multi-curseur
* Indentation automatique: le programmeur ne devra plus jamais indenter le code!
* Compilation et parcours des erreurs(seul MSVC est supporté pour le moment)
* Recherche de symboles et accés à leur définition
* Rapidité (charge et analyse mackron/miniaudio.h sans retard visible)

Vous pouvez le voir en action dans cette vidéo: 

<div style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/HhTwIjqeDlQ?si=RoYPKLqw3qGtyac_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<br>

Ecrit en C++. Il utilise WIN32 pour la couche plateforme (fenêtrage, mémoire, système de fichiers, etc.), D3D11 pour dessiner des rectangles et Freetype pour la rastérisation des glyphes  et le chargement des fichiers TTF
<div style="text-align: center;">
<a href="https://github.com/moha-bq/Medit-Release/releases/tag/Medit" class="my_btn">Télécharger Medit</a>
</div>

<br>

* * * 

<br>
<br>

<div style="text-align: center;">
<h1> 3D Demo </h1>
<h3> Implémentation de différents algorithmes d'éclairage 3D, d'un système de particules et de l'animation squelettique</h3>
</div>


Fonctionnalités:

* Shading: Forward, Deferred, Tiled Forward, Tiled Deferred
* Le culling de lumières est effectué à l'aide d'un Compute Shader.
* Culling de lumières 2.5D (Comme décrit dans la publication de Takahiro Harada)
* Lumières ponctuelles, spot et directionnelles
* Modèle d'éclairage Blinn-Phong
* Normal mapping
* Modèle simple ciel/soleil (interpolation de couleurs en fonction de l'élévation de la direction de la vue)
* Effets de particules
* Animation squelettique (Skinning à l'aide du Vertex Shader)
* Editeurr UI
* 3D Gizmo personnalisé
* Profileur CPU et GPU basé sur l'instrumentation
* Format binaire de modèle 3D personnalisé


Vous pouvez la voir en action dans cette vidéo:

<div style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/TmroTbdkY5I?si=-UWbF91SeLwIYzjV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></div>
<br>

Écrit en C++. Il utilise WIN32, D3D11, Freetype, stb_image et Dear Imgui. Blender a été utilisé via son interface Python pour écrire un format binaire de modèle 3D personnalisé qui prend en charge les données de géométrie, de matériaux, de textures et d'animation.
<div style="text-align: center;">
<a href="https://github.com/moha-bq/Demo3D/releases/tag/Demo-Release" class="my_btn"> Télécharger la démo</a>
<a href="https://github.com/moha-bq/Demo3D" class="my_btn">Code source</a>
</div>

<br>
* * *


<br>
<br>

<div style="text-align: center;">
<h1> Simulateur Mémoire Virtuelle</h1>
<br>
<!-- <h3> Projet scolaire </h3> -->
</div>

Dans le cadre d'un projet scolaire, J'ai développé un alloeur de mémoire généraliste en dessus d'une couche d'allocation et de virtualisation de pages.
Le système d'exploitation (implémenté en tant que thread) prend des requêtes d'allocation/libération des mémoires prevenant des processus(implémenté en tant que thread aussi). 
Le système sert aussi des requêtes TCP en retournant des images TARGA qui visualise l'état de mémoire du système ou d'un processus.

<div style="text-align: center;">
<img src="https://github.com/moha-bq/vmem_simulator/raw/master/imgs/arch.png" />
</div>
<br>

Écrit en C++. Il utilise POSIX pour le multi-threading et les sockets.
 
 
<div style="text-align: center;">
<a href="https://github.com/moha-bq/vmem_simulator" class="my_btn">Code source</a>
</div>


<br>
* * *

<br>
<br>

<div style="text-align: center;">
<h1> Super Mario Bros. Clone</h1>
<h3> Une implémentation de Super Mario Bros version NES avec un éditeur de niveaux.</h3>
</div>

<div style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/CZezLogQr-c?si=5ywmMbd0UxXxfZVC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<br>

Écrit en C++. Il utilise HGE(Haaf's Game Engine).

<div style="text-align: center;">
<a href="https://github.com/moha-bq/Super-Mario-Bros" class="my_btn">Code source et Démo</a>
</div>

<br>

* * *

<br>
<br>

<div style="text-align: center;">
<h1> Jelly Couple</h1>
<h3> Jeu Android où on contrôle deux gelées en même temps</h3>
</div>

<div style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/B9TVaaU090k?si=75y2VLyYowQwkpl5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<br>

Écrit en C++. Il utilise Cocos2Dx.

<div style="text-align: center;">
<a href="https://github.com/moha-bq/Jelly-Couple" class="my_btn">Code source</a>
</div>

<br>

* * *

<br>
<br>

<div style="text-align: center;">
<h1> Divers</h1>
<h3> Autres projets, prototypes and travaux inachevés</h3>
</div>

La vidéo suivante montre un prototype de FPS, physique automobile et un éditeur de Tilemap:
<div style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/vC1n0iNAx38?si=wOpHFLYN1UVfyoOQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<br>

Vous pouvez retrouver mes autres projets sur mon github :

* 3D Software renderer avec perspective-correct texture mapping, traitant 4 pixels en même temps à l’aide des instructions SSE2 -- C++
* Raytracer -- C++ 
* Implémentation des cascaded shadow maps stables (learnd3d) -- C++, D3D11
* Edition et visualisation des T-Splines (NURBS avec des T-jonctions) -- C++, SDL2, OpenGL3
* Et bien d'autres...
<div style="text-align: center;">
<a href="https://github.com/moha-bq?tab=repositories" class="my_btn">Voir sur mon Github</a>
</div>