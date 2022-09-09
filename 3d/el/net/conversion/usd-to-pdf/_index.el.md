---
title: Μετατροπή USD σε PDF μέσω C# 
description: Μετατροπή USD και άλλων 3D αρχείων χρησιμοποιώντας .NET API
url: /el/net/conversion/usd-to-pdf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: PDF
otherformats: RVM HTML DRC OBJ 3DS PDF FBX DAE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Μετατροπή USD σε PDF μέσω C#" h2="Εξαγωγή USD και άλλων 3D αρχείων χρησιμοποιώντας .NET Framework, .NET Core και Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Εξαγωγή σκηνής USD ως PDF με C#" %}}
1. Φόρτωση αρχείου USD χρησιμοποιώντας έναν κατασκευαστή του [Σκηνή](https://apireference.aspose.com/3d/net/aspose.threed/scene) τάξη2. Καλέστε [Σκηνή.Αποθήκευση](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) μέθοδος
3. Περάστε το όνομα αρχείου εξόδου με την επέκταση .pdf ως πρώτη παράμετρο
4. Καθορίστε την τιμή του πεδίου "PDF" από [Μορφή αρχείου](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) τάξη
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Μετατροπή μορφής API for .NET" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.3d``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.3D```.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από [λήψεις](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Κωδικός για μετατροπή USD σε PDF" gistPath="" %}}
```cs
// φορτώστε το USD σε ένα αντικείμενο της σκηνής 
var scene = new Aspose.ThreeD.Scene("template.usd");
// αποθήκευση USD ως PDF 
scene.Save("output.pdf", Aspose.ThreeD.FileFormat.PDF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}