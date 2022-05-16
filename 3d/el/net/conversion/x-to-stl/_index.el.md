﻿---
title: Μετατροπή X σε STL μέσω C# 
weight: 2120
url: /el/net/conversion/x-to-stl/ 
description: Δείγμα κώδικα για μετατροπή X σε STL C#. Χρησιμοποιήστε API παράδειγμα κώδικα για ομαδικά αρχεία X σε STL μετατροπή εντός VB.NET, Asp.NET ή οποιασδήποτε εφαρμογής που βασίζεται σε .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή X σε STL μέσω C#" h2="Αποδώστε το X ως STL χωρίς κανένα λογισμικό μοντελοποίησης και απόδοσης 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="X" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το X σε STL χρησιμοποιώντας το C#" %}}

 Για να μετατρέψουμε το X σε STL, θα χρησιμοποιήσουμε
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή X σε STL μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές του .NET μπορούν εύκολα να φορτώσουν και να μετατρέψουν αρχεία X σε STL σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου X μέσω του κατασκευαστή της κλάσης Scene1. Δημιουργήστε μια παρουσία του StlSaveOptions1. Ορίστε STL συγκεκριμένες ιδιότητες για σύνθετη μετατροπή1. Καλέστε τη μέθοδο Scene.Save1. Περάστε τη διαδρομή εξόδου με την επέκταση αρχείου STL και το αντικείμενο του StlSaveOptions1. Ελέγξτε το προκύπτον αρχείο STL στην καθορισμένη διαδρομή
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε τον κωδικό μετατροπής .NET, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με .NET Framework, .NET Core, Mono.- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.- Aspose.3D for .NET DLL που αναφέρεται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή X σε STL C#" offSpacer="" %}}

```cs
// φορτώστε το X σε ένα αντικείμενο της σκηνής 
var document = new Aspose.ThreeD.Scene("template.x");
// δημιουργήστε μια παρουσία του StlSaveOptions 
var options = new Aspose.ThreeD.Formats.StlSaveOptions();
// αποθήκευση X ως STL 
document.Save("output.stl", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Δωρεάν εφαρμογή για μετατροπή X σε STL" sectionDescription="Ελέγξτε τις ζωντανές επιδείξεις μας για [μετατροπή X σε STL](https://products.aspose.app/3d/conversion/x-to-stl) με τα ακόλουθα οφέλη." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το X αρχείο σας και πατήστε το κουμπί \"Μετατροπή\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε αμέσως τον σύνδεσμο λήψης για το αρχείο STL που προκύπτει." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Μια 3D Βιβλιοθήκη Επεξεργασίας Αρχείων για χειρισμό αρχείων 3D χωρίς λογισμικό μοντελοποίησης και απόδοσης. Το 3D API υποστηρίζει Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco μορφές αρχείων και άλλα. Οι προγραμματιστές μπορούν να δημιουργήσουν, να διαβάσουν, να μετατρέψουν, να τροποποιήσουν και να ελέγξουν την ουσία των 3D μορφών εγγράφων εύκολα.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="X" readMoreLink="https://docs.fileformat.com/3d/x/" >}}
Το X είναι ένα αρχείο εικόνας μοντέλου DirectX που χρησιμοποιείται από την τεχνολογία DirectX και προορίζεται για απόδοση γραφικών 3D σε παιχνίδια. Η μορφή αρχείου καθορίζει 3D δομές αντικειμένων για πλέγματα, υφές, κινούμενα σχέδια και αντικείμενα.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="stl" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
Το STL, συντομογραφία για τη στερεολιθρογραφία, είναι μια εναλλάξιμη μορφή αρχείου που αντιπροσωπεύει τρισδιάστατη γεωμετρία επιφάνειας. Η μορφή αρχείου βρίσκει τη χρήση της σε πολλά πεδία, όπως η ταχεία δημιουργία πρωτοτύπων, η 3D εκτύπωση και η κατασκευή με τη βοήθεια υπολογιστή. Αντιπροσωπεύει μια επιφάνεια ως μια σειρά από μικρά τρίγωνα, γνωστά ως όψεις, όπου κάθε όψη περιγράφεται με μια κάθετη κατεύθυνση και τρία σημεία που αντιπροσωπεύουν τις κορυφές του τριγώνου. Τα δεδομένα που προκύπτουν χρησιμοποιούνται από εφαρμογές για τον προσδιορισμό της διατομής του σχήματος 3D που θα κατασκευαστεί από το fabber. Δεν υπάρχουν διαθέσιμες πληροφορίες στη μορφή αρχείου STL για την αναπαράσταση του χρώματος, της υφής ή άλλων κοινών χαρακτηριστικών μοντέλου CAD.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το X σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-3ds/" name="X ΠΡΟΣ 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-amf/" name="X ΠΡΟΣ AMF" description="Μορφή κατασκευής πρόσθετων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-dae/" name="X ΠΡΟΣ DAE" description="Ανταλλαγή ψηφιακών περιουσιακών στοιχείων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-fbx/" name="X ΠΡΟΣ FBX" description="3D Μορφή" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-html/" name="X ΠΡΟΣ HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-obj/" name="X ΠΡΟΣ OBJ" description="3D Μορφή αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-pdf/" name="X ΠΡΟΣ PDF" description="Μορφή φορητού εγγράφου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-ply/" name="X ΠΡΟΣ PLY" description="Μορφή αρχείου Polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-rvm/" name="X ΠΡΟΣ RVM" description="Μοντέλο σχεδίασης φυτών AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-u3d/" name="X ΠΡΟΣ U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}