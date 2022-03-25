﻿---
title: Μετατροπή DRC σε OBJ μέσω C# 
url: /el/net/conversion/drc-to-obj/ 
description: Κωδικός δείγματος για τη μετατροπή DRC σε OBJ C#. Χρησιμοποιήστε τον κωδικό API παράδειγμα για τα αρχεία DRC παρτίδας σε OBJ μετατροπή εντός VB.NET, Asp.NET ή οποιαδήποτε .NET εφαρμογή.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή DRC σε OBJ μέσω C#" h2="Ανάκτηση DRC ως OBJ χωρίς λογισμικό μοντελοποίησης και αποτύπωσης 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε DRC σε OBJ χρησιμοποιώντας C#" %}}

 Προκειμένου να μετατρέψουμε το DRC σε OBJ, θα χρησιμοποιήσουμε τα ακόλουθα:
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API που είναι μια πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση χειρισμού και μετατροπής εγγράφου API για την πλατφόρμα C#. Άνοιγμα:
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Διαχειριστής πακέτου, αναζήτηση για την αναζήτηση.
 Aspose.3D 
 Και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την κονσόλα διαχειριστή πακέτων.

{{% blocks/products/pf/agp/code-block title="Εντολή κονσόλων διαχειριστή πακέτων" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή DRC σε OBJ μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές .NET μπορούν εύκολα να φορτώσουν και να μετατρέψουν DRC αρχεία σε OBJ σε λίγες μόνο γραμμές του κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου DRC μέσω του κατασκευαστή της κλάσης σκηνής1. Δημιουργία μιας διάταξης AmfSaveOptionsName1. Ορισμός συγκεκριμένων ιδιοτήτων OBJ για προηγμένη μετατροπή1. Καλέστε τη σκηνή.1. Πέρασε τη διαδρομή εξόδου με επέκταση αρχείου OBJ & αντικείμενο του ObjSaveOptions1. Ελέγξτε το προκύπτον αρχείο OBJ σε καθορισμένη διαδρομή
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Πριν εκτελέσετε τον κώδικα μετατροπής .NET, βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή ένα συμβατό OS με .NET Πλαίσιο, .NET Πυρήνα, Mono.- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.- Aspose.3D for .NET DLL αναφέρονται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτός ο κωδικός δείγματος εμφανίζει DRC σε OBJ C#" offSpacer="" %}}

```cs
// Φόρτωση του DRC σε ένα αντικείμενο σκηνής 
var document = new Aspose.ThreeD.Scene("template.drc");
// Δημιουργία μιας ένδειξης του ObjSaveOptions 
var options = new Aspose.ThreeD.Formats.ObjSaveOptions();
// Αποθήκευση DRC ως OBJ 
document.Save("output.obj", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ελεύθερη εφαρμογή για τη μετατροπή DRC σε OBJ" sectionDescription="Ελέγξτε τα ζωντανά μας ντέμου [DRC σε OBJ μετατροπή](https://products.aspose.app/3d/conversion/drc-to-obj) Με τα ακόλουθα οφέλη." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράφεις κανένα κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλά ανεβάστε το DRC αρχείο σας και πατήστε το κουμπί \"Convert\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα πάρετε αμέσως το σύνδεσμο λήψης για το αρχείο OBJ." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Μια 3D Βιβλιοθήκη επεξεργασίας αρχείων για να χειριστεί τα αρχεία 3D χωρίς λογισμικό μοντελοποίησης και αποτύπωσης. Το 3D API υποστηρίζει Discreet3DS, WavefrontOBJ, FBX (ASCII, δυαδικό), STL (ASCII, Δυαδικό), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco μορφές αρχείων και πολλά άλλα. Οι προγραμματιστές μπορούν να δημιουργήσουν, να διαβάσουν, να μετατρέψουν, να τροποποιήσουν και να ελέγχουν την ουσία του 3D μορφές εγγράφου εύκολα.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
Ένα αρχείο με. Η επέκταση drc είναι μια συμπιεσμένη μορφή αρχείου 3D που δημιουργήθηκε με τη βιβλιοθήκη Google Draco. Το Google προσφέρει Draco ως βιβλιοθήκη ανοικτού κώδικα για συμπίεση και αποσυμπίεση 3D γεωμετρικών ματιών και σύννεφα σημείου, και βελτιώνει την αποθήκευση και τη μετάδοση των 3D γραφικών. Κωδικοποιεί τα δεδομένα εισόδου και τα αποθηκεύει ως . Φάκελο. Στο τέλος παραλαβής, το API αναφέρεται . Αρχεία drc και μπορούν να τα βγάλουν ως αρχεία PLY ή OBJ. Το συμπιεσμένο αρχείο εξόδου επιτρέπει στους χρήστες να κατεβάζουν ταχύτερα εφαρμογές και να παρέχουν γρήγορη φόρτωση των 3D γραφικών στα προγράμματα περιήγησης.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="obj" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
Τα αρχεία OBJ χρησιμοποιούνται από την εφαρμογή Advanced Visualizer του Wavefront για τον ορισμό και την αποθήκευση των γεωμετρικών αντικειμένων. Η πίσω και προς τα εμπρός μετάδοση των γεωμετρικών δεδομένων είναι δυνατή μέσω των αρχείων OBJ. Τόσο πολυγωνική γεωμετρία όμοια σημεία, γραμμές, κορυφές υφής, πρόσωπα και γεωμετρία ελεύθερων μορφών (καμπέλες και επιφάνειες) υποστηρίζονται από τη μορφή OBJ. Αυτή η μορφή δεν υποστηρίζει animation ή πληροφορίες σχετικά με το φως και τη θέση των σκηνών. Ένα αρχείο OBJ είναι συνήθως ένα τελικό προϊόν της διαδικασίας μοντελοποίησης 3D που δημιουργείται από ένα CAD (Computer Aided Design). Η προεπιλεγμένη σειρά για την αποθήκευση κορυφής είναι αντίθετα δεξιόστροφα αποφεύγοντας την ρητή δήλωση των κανονικών προσώπου. Αν και τα αρχεία OBJ δηλώνουν πληροφορίες κλίμακας σε μια γραμμή σχολίων, αλλά δεν έχουν δηλωθεί μονάδες για τις συντεταγμένες OBJ.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}