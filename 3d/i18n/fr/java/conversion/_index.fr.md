---
title: Java 3D Formats de conversion
url: /fr/java/conversion/
description: Convertir 3D formats amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x avec quelques lignes de Java code via la bibliothèque Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D Formats de conversion via Java" h2="Convertissez 3D formats de fichiers sans aucune installation de logiciel de modélisation et de rendu 3D pour créer des applications multiplateformes Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
Pour créer, éditer, manipuler et enregistrer des applications graphiques tridimensionnelles, **Java 3D API** fournit un niveau élevé de méthodes permettant de réaliser de telles fonctionnalités sans installer de logiciel de modélisation et de rendu 3D. Rares sont ceux qui construisent le maillage de différentes formes géométriques tridimensionnelles, créent un fichier de scène 3D, mettent en place des normales ou des UV sur le cube, formatent des éléments, ajoutent une propriété d'animation et plus encore. 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir 3D Fichier en différents formats" %}}
Le processus de conversion est simple. Il suffit de charger le fichier source 3D en utilisant [Classe de scène](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene). Comme scène est un objet de niveau supérieur ayant les nœuds, les géométries, les textures, les matériaux, l'animation, les poses, les sous-scènes, etc. Créez le [Enregistrer les options](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) Tels que AmfSaveOptions, ColladaSaveOptions, Discreet3dsSaveOptions, DracoSaveOptions, FbxSaveOptions, GltfSaveOptions, RvmSaveOptions, StlSaveOptions, U3dSaveOptions, etc. et définissez les propriétés en conséquence. Enfin, appelez la méthode de sauvegarde avec le fichier de sortie et l'objet de sauvegarde des options de format cible créé. En outre, l'utilisation des programmeurs API peut même enregistrer 3D scène comme HTML.


{{% blocks/products/pf/feature-page-code h3="Java Code pour la conversion de AMF à 3DS" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Convertir 3D Scène en HTML via Java" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}