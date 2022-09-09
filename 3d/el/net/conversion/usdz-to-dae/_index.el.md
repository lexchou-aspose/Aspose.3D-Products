---
title: Μετατροπή USDZ σε DAE μέσω C# 
description: Μετατροπή USDZ και άλλων 3D αρχείων χρησιμοποιώντας .NET API
url: /el/net/conversion/usdz-to-dae/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: DAE
otherformats: DRC HTML DAE ASE STL PLY 3MF OBJ 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Μετατροπή USDZ σε DAE μέσω C#" h2="Εξαγωγή USDZ και άλλων 3D αρχείων χρησιμοποιώντας .NET Framework, .NET Core και Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Εξαγωγή σκηνής USDZ ως DAE με C#" %}}
1. Φόρτωση αρχείου USDZ χρησιμοποιώντας έναν κατασκευαστή του [Σκηνή](https://apireference.aspose.com/3d/net/aspose.threed/scene) τάξη2. Καλέστε [Σκηνή.Αποθήκευση](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) μέθοδος
3. Περάστε το όνομα αρχείου εξόδου με την επέκταση .dae ως πρώτη παράμετρο
4. Καθορίστε την τιμή του πεδίου "Collada" από [Μορφή αρχείου](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) τάξη
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Μετατροπή μορφής API for .NET" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.3d``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.3D```.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από [λήψεις](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Κωδικός για μετατροπή USDZ σε DAE" gistPath="" %}}
```cs
// φορτώστε το USDZ σε ένα αντικείμενο της σκηνής 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// αποθήκευση USDZ ως DAE 
scene.Save("output.dae", Aspose.ThreeD.FileFormat.Collada);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}