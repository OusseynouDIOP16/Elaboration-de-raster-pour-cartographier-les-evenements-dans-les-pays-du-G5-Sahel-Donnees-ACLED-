Ce projet propose une représentation cartographique des incidents survenus dans les pays du G5-Sahel, en mettant particulièrement l'accent sur la Mauritanie. Les données utilisées proviennent d'ACLED (Armed Conflict Location & Event Data Project - Nom :( ACLED Western Africa)). Par ailleurs, les contours des pays sont délimités à l'aide des fichiers de GADM (shp, shx, dbf, cpg).

Les principales étapes de ce travail comprennent :
1) Le calcul du nombre d'événements par pays.
2) Le calcul du nombre d'événements par région au sein d'un pays.
3) La création d'une grille raster d'une résolution de 10 km * 10 km, permettant de comptabiliser le nombre d'événements.
4) La génération d'une autre grille raster qui catégorise le nombre d'événements selon les intervalles : [0,5[:1 ; [5,10[:2 ; et [10,inf[ : 3.
