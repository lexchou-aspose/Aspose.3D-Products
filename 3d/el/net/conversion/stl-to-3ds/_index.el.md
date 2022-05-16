﻿---
title: Μετατροπή STL σε 3DS μέσω C# 
weight: 280
url: /el/net/conversion/stl-to-3ds/ 
description: Δείγμα κώδικα για μετατροπή STL σε 3DS C#. Χρησιμοποιήστε API παράδειγμα κώδικα για ομαδικά αρχεία STL σε 3DS μετατροπή εντός VB.NET, Asp.NET ή οποιασδήποτε εφαρμογής που βασίζεται σε .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή STL σε 3DS μέσω C#" h2="Αποδώστε το STL ως 3DS χωρίς κανένα λογισμικό μοντελοποίησης και απόδοσης 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="3DS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="STL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το STL σε 3DS χρησιμοποιώντας το C#" %}}

 Για να μετατρέψουμε το STL σε 3DS, θα χρησιμοποιήσουμε
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API που είναι μια πλατφόρμα πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση χειρισμό και μετατροπή εγγράφων API για C#. Ανοιξε
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 διαχειριστής πακέτων, αναζητήστε
 Aspose.3D 
 και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή κονσόλας διαχείρισης πακέτων" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή STL σε 3DS μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές .NET μπορούν εύκολα να φορτώσουν και να μετατρέψουν αρχεία STL σε 3DS σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου STL μέσω του κατασκευαστή της κλάσης Scene1. Δημιουργήστε μια παρουσία του 3dsSaveOptions1. Ορίστε 3DS συγκεκριμένες ιδιότητες για σύνθετη μετατροπή1. Καλέστε τη μέθοδο Scene.Save1. Περάστε τη διαδρομή εξόδου με την επέκταση αρχείου 3DS και το αντικείμενο του 3dsSaveOptions1. Ελέγξτε το προκύπτον αρχείο 3DS στην καθορισμένη διαδρομή
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε τον κωδικό μετατροπής .NET, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με .NET Framework, .NET Core, Mono.- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.- Aspose.3D for .NET DLL που αναφέρεται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή STL σε 3DS C#" offSpacer="" %}}

```cs
// φορτώστε το STL σε ένα αντικείμενο της σκηνής 
var document = new Aspose.ThreeD.Scene("template.stl");
// δημιουργήστε μια παρουσία του 3dsSaveOptions 
var options = new Aspose.ThreeD.Formats.Discreet3dsSaveOptions();
// αποθήκευση STL ως 3DS 
document.Save("output.3ds", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Δωρεάν εφαρμογή για μετατροπή STL σε 3DS" sectionDescription="Ελέγξτε τις ζωντανές επιδείξεις μας για [μετατροπή STL σε 3DS](https://products.aspose.app/3d/conversion/stl-to-3ds) με τα ακόλουθα οφέλη." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς μεταφορτώστε το αρχείο σας STL και πατήστε το κουμπί \"Μετατροπή\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε αμέσως τον σύνδεσμο λήψης για το αρχείο 3DS που προκύπτει." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Μια 3D Βιβλιοθήκη Επεξεργασίας Αρχείων για χειρισμό αρχείων 3D χωρίς λογισμικό μοντελοποίησης και απόδοσης. Το 3D API υποστηρίζει Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco μορφές αρχείων και άλλα. Οι προγραμματιστές μπορούν να δημιουργήσουν, να διαβάσουν, να μετατρέψουν, να τροποποιήσουν και να ελέγξουν την ουσία των 3D μορφών εγγράφων εύκολα.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
Το STL, συντομογραφία για τη στερεολιθρογραφία, είναι μια εναλλάξιμη μορφή αρχείου που αντιπροσωπεύει τρισδιάστατη γεωμετρία επιφάνειας. Η μορφή αρχείου βρίσκει τη χρήση της σε πολλά πεδία, όπως η ταχεία δημιουργία πρωτοτύπων, η 3D εκτύπωση και η κατασκευή με τη βοήθεια υπολογιστή. Αντιπροσωπεύει μια επιφάνεια ως μια σειρά από μικρά τρίγωνα, γνωστά ως όψεις, όπου κάθε όψη περιγράφεται με μια κάθετη κατεύθυνση και τρία σημεία που αντιπροσωπεύουν τις κορυφές του τριγώνου. Τα δεδομένα που προκύπτουν χρησιμοποιούνται από εφαρμογές για τον προσδιορισμό της διατομής του σχήματος 3D που θα κατασκευαστεί από το fabber. Δεν υπάρχουν διαθέσιμες πληροφορίες στη μορφή αρχείου STL για την αναπαράσταση του χρώματος, της υφής ή άλλων κοινών χαρακτηριστικών μοντέλου CAD.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3ds" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
Ένα αρχείο με επέκταση 3DS αντιπροσωπεύει τη μορφή αρχείου πλέγματος 3D Studio (DOS) που χρησιμοποιείται από το Autodesk 3D Studio. Το Autodesk 3D Studio βρίσκεται στην αγορά μορφής αρχείων 3D από τη δεκαετία του 1990 και τώρα έχει εξελιχθεί σε 3D Studio MAX για εργασία με μοντελοποίηση, κινούμενα σχέδια και απόδοση 3D. Ένα αρχείο 3DS περιέχει δεδομένα για 3D αναπαράσταση σκηνών και εικόνων και είναι μία από τις δημοφιλείς μορφές αρχείων για εισαγωγή και εξαγωγή δεδομένων 3D. Λαμβάνει υπόψη πληροφορίες όπως τοποθεσίες κάμερας, δεδομένα Mesh, πληροφορίες φωτισμού, διαμορφώσεις θυρών προβολής, εξομάλυνση δεδομένων ομάδας, αναφορές bitmap και χαρακτηριστικά για τη δημιουργία κορυφών και πολυγώνων για την απόδοση μιας σκηνής.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το STL σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-amf/" name="STL ΠΡΟΣ AMF" description="Μορφή κατασκευής πρόσθετων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-dae/" name="STL ΠΡΟΣ DAE" description="Ανταλλαγή ψηφιακών περιουσιακών στοιχείων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-fbx/" name="STL ΠΡΟΣ FBX" description="3D Μορφή" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-html/" name="STL ΠΡΟΣ HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-obj/" name="STL ΠΡΟΣ OBJ" description="3D Μορφή αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-pdf/" name="STL ΠΡΟΣ PDF" description="Μορφή φορητού εγγράφου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-ply/" name="STL ΠΡΟΣ PLY" description="Μορφή αρχείου Polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-rvm/" name="STL ΠΡΟΣ RVM" description="Μοντέλο σχεδίασης φυτών AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-u3d/" name="STL ΠΡΟΣ U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}