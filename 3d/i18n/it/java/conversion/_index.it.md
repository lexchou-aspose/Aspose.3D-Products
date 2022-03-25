---
title: Java 3D conversione formati
url: /it/java/conversion/
description: Convertire 3D formati amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x con poche righe di Java codice tramite Java libreria.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversione di 3D formati tramite Java" h2="Convertire 3D formati di file senza alcuna installazione di software di modellazione e rendering 3D per creare Java applicazioni multipiattaforma." >}}

{{% blocks/products/pf/feature-page-summary %}}
Per la creazione, la modifica, la manipolazione e il salvataggio di applicazioni grafiche tridimensionali, **Java 3D API** fornisce metodi di alto livello per eseguire tali funzionalità senza l'installazione di alcun software di modellazione e rendering 3D. Pochi costruiscono la mesh di diverse forme geometriche tridimensionali, creano un file di scena 3D, impostano normali o UV sul cubo, formattano elementi, aggiungono proprietà di animazione e altro ancora. 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertire 3D file in diversi formati" %}}
Il processo di conversione è semplice. Basta caricare il file sorgente 3D usando [Classe di scena](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene). Poiché la scena è un oggetto di livello superiore avente i nodi, le geometrie, le trame, i materiali, l'animazione, le pose, le sotto-scene ecc. Creare il relativo [Opzioni di salvataggio](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) Come AmfSaveOptions, ColladaSaveOptions, Discreet3dsSaveOptions, DracoSaveOptions, FbxSaveOptions, GltfSaveOptions, RvmSaveOptions, StlSaveOptions, U3dSaveOptions ecc. Imposta le proprietà di conseguenza. Infine chiamare il metodo di salvataggio con file di output e creato oggetto opzioni di salvataggio del formato di destinazione. Inoltre, utilizzando API programmatori può anche salvare 3D scena come HTML.


{{% blocks/products/pf/feature-page-code h3="Java codice per la conversione da AMF a 3DS" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Convertire 3D scena in HTML tramite Java" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}