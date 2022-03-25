---
title: Μετατροπή USDZ σε RVM μέσω C# 
description: Μετατροπή USDZ & άλλων αρχείων 3D χρησιμοποιώντας .NET API
url: /el/net/conversion/usdz-to-rvm/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: RVM
otherformats: DRC ASE 3MF AMF GLTF OBJ DXF RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Μετατροπή USDZ σε RVM μέσω C#" h2="Εξαγωγή USDZ & άλλων αρχείων 3D χρησιμοποιώντας .NET Πλαίσιο, .NET πυρήνα και Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Εξαγωγή USDZ σκηνής ως RVM με C#" %}}
1. Φόρτωση αρχείου USDZ χρησιμοποιώντας έναν κατασκευαστή του κατασκευαστή [Σκηνή](https://apireference.aspose.com/3d/net/aspose.threed/scene) Κλάσης2. Κλήση [Σκηνή.](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Μέθοδος
3. Πέρασε το όνομα του αρχείου εξόδου με . Επέκταση rvm ως πρώτη παράμετρος
4. Καθορίστε τιμή πεδίου 'RvmBinary' [Μορφή αρχείου](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Κλάσης
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Μορφή μετατροπής API for .NET" %}}
Εγκαταστήστε από τη γραμμή εντολών ως ''nuget install Aspose.3d''' ή μέσω κονσόλας διαχειριστή πακέτων του Visual Studio με ''' Εγκατάσταση-Πακέτο Aspose.3D'''.

Εναλλακτικά, πάρτε το εκτός σύνδεσης MSI εγκαταστάτης ή DLLs σε ένα αρχείο ZIP [Λήψεις](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Κωδικός για USDZ σε RVM Μετατροπή" gistPath="" %}}
```cs
// Φόρτωση του USDZ σε ένα αντικείμενο σκηνής 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// Αποθήκευση USDZ ως RVM 
scene.Save("output.rvm", Aspose.ThreeD.FileFormat.RvmBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}