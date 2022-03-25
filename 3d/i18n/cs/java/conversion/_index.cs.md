---
title: Konverzace formátů Java 3D
url: /cs/java/conversion/
description: Convert 3D formats amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x with few lines of Java code via Java library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D konverze formátů přes Java" h2="Convert 3D file formats without any 3D modeling and rendering software installation to build cross-platform Java applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
Pro vytváření, úpravu, manipulaci a ukládání trojrozměrných grafických aplikací, **Java 3D API** poskytuje vysokou úroveň metod k provedení těchto funkcí bez instalace jakéhokoli softwaru pro modelování a vykreslování 3D. Jen málo z nich je vybudovat síť různých trojrozměrných geometrických tvarů, vytvořit 3D scénický soubor, nastavit normály nebo uv na kostce, formátovat prvky, přidat vlastnost animace a další. 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Převést soubor 3D do různých formátů" %}}
Konverzní proces je jednoduchý. Načíst zdrojový soubor 3D pomocí [Třída scény](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene)A. As scene is a top-level object having the nodes, geometries, textures, materials, animation, poses, sub-scenes etc. create the relevant the [Uložit možnosti](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) Such as amfsaveoptions, colladasaveoptions, discreet3dssaveoptions, dracosaveoptions, fbxsaveoptions, gltfsaveoptions, rvmsaveoptions, stlsaveoptions, u3dsaveoptions etc and set the properties accordingly. Konečně zavolat metodu uložení s výstupním souborem a vytvořený cíl formát uložit možnosti objektu. Kromě toho lze použít API programátory dokonce uložit 3D scénu jako HTML.


{{% blocks/products/pf/feature-page-code h3="Java kód pro převedení AMF na 3DS-= = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = =" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Převést 3D scénu na HTML prostřednictvím Java" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}