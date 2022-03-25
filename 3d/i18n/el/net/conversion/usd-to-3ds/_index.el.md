---
title: Μετατροπή USD σε 3DS μέσω C# 
description: Μετατροπή USD & άλλων αρχείων 3D χρησιμοποιώντας .NET API
url: /el/net/conversion/usd-to-3ds/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: 3DS
otherformats: OBJ STL HTML FBX RVM JT DAE DXF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Μετατροπή USD σε 3DS μέσω C#" h2="Εξαγωγή USD & άλλων αρχείων 3D χρησιμοποιώντας .NET Πλαίσιο, .NET πυρήνα και Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Εξαγωγή USD σκηνής ως 3DS με C#" %}}
1. Φόρτωση αρχείου USD χρησιμοποιώντας έναν κατασκευαστή του κατασκευαστή [Σκηνή](https://apireference.aspose.com/3d/net/aspose.threed/scene) Κλάσης2. Κλήση [Σκηνή.](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Μέθοδος
3. Πέρασε το όνομα του αρχείου εξόδου με .3ds επέκταση ως πρώτη παράμετρος
4. Καθορισμός τιμής πεδίου 'Discreet3DS' [Μορφή αρχείου](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Κλάσης
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Μορφή μετατροπής API for .NET" %}}
Εγκαταστήστε από τη γραμμή εντολών ως ''nuget install Aspose.3d''' ή μέσω κονσόλας διαχειριστή πακέτων του Visual Studio με ''' Εγκατάσταση-Πακέτο Aspose.3D'''.

Εναλλακτικά, πάρτε το εκτός σύνδεσης MSI εγκαταστάτης ή DLLs σε ένα αρχείο ZIP [Λήψεις](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Κωδικός για USD σε 3DS Μετατροπή" gistPath="" %}}
```cs
// Φόρτωση του USD σε ένα αντικείμενο σκηνής 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Αποθήκευση USD ως 3DS 
scene.Save("output.3ds", Aspose.ThreeD.FileFormat.Discreet3DS);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}