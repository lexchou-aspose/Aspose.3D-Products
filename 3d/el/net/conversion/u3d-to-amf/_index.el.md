﻿---
title: Μετατροπή U3D σε AMF μέσω C# 
weight: 1130
url: /el/net/conversion/u3d-to-amf/ 
description: Δείγμα κώδικα για μετατροπή U3D σε AMF C#. Χρησιμοποιήστε API παράδειγμα κώδικα για ομαδικά αρχεία U3D σε AMF μετατροπή εντός VB.NET, Asp.NET ή οποιασδήποτε εφαρμογής που βασίζεται σε .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή U3D σε AMF μέσω C#" h2="Αποδώστε το U3D ως AMF χωρίς κανένα λογισμικό μοντελοποίησης και απόδοσης 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="AMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="U3D" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το U3D σε AMF χρησιμοποιώντας το C#" %}}

 Για να μετατρέψουμε το U3D σε AMF, θα χρησιμοποιήσουμε
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή U3D σε AMF μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές .NET μπορούν εύκολα να φορτώσουν και να μετατρέψουν αρχεία U3D σε AMF σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου U3D μέσω του κατασκευαστή της κλάσης Scene1. Δημιουργήστε μια παρουσία του AmfSaveOptions1. Ορίστε AMF συγκεκριμένες ιδιότητες για σύνθετη μετατροπή1. Καλέστε τη μέθοδο Scene.Save1. Περάστε τη διαδρομή εξόδου με την επέκταση αρχείου AMF και το αντικείμενο του AmfSaveOptions1. Ελέγξτε το προκύπτον αρχείο AMF στην καθορισμένη διαδρομή
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε τον κωδικό μετατροπής .NET, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με .NET Framework, .NET Core, Mono.- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.- Aspose.3D for .NET DLL που αναφέρεται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει τη μετατροπή U3D σε AMF C#" offSpacer="" %}}

```cs
// φορτώστε το U3D σε ένα αντικείμενο της σκηνής 
var document = new Aspose.ThreeD.Scene("template.u3d");
// δημιουργήστε μια παρουσία του AmfSaveOptions 
var options = new Aspose.ThreeD.Formats.AmfSaveOptions();
// αποθήκευση U3D ως AMF 
document.Save("output.amf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Δωρεάν εφαρμογή για μετατροπή U3D σε AMF" sectionDescription="Ελέγξτε τις ζωντανές επιδείξεις μας για [μετατροπή U3D σε AMF](https://products.aspose.app/3d/conversion/u3d-to-amf) με τα ακόλουθα οφέλη." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς μεταφορτώστε το αρχείο σας U3D και πατήστε το κουμπί \"Μετατροπή\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε αμέσως τον σύνδεσμο λήψης για το αρχείο AMF που προκύπτει." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Μια 3D Βιβλιοθήκη Επεξεργασίας Αρχείων για χειρισμό αρχείων 3D χωρίς λογισμικό μοντελοποίησης και απόδοσης. Το 3D API υποστηρίζει Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco μορφές αρχείων και άλλα. Οι προγραμματιστές μπορούν να δημιουργήσουν, να διαβάσουν, να μετατρέψουν, να τροποποιήσουν και να ελέγξουν την ουσία των 3D μορφών εγγράφων εύκολα.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}
Το U3D (Universal 3D) είναι μια συμπιεσμένη μορφή αρχείου και δομή δεδομένων για 3D γραφικά υπολογιστή. Περιέχει πληροφορίες μοντέλου 3D όπως τρίγωνα πλέγματα, φωτισμός, σκίαση, δεδομένα κίνησης, γραμμές και σημεία με χρώμα και δομή. Η μορφή έγινε αποδεκτή ως πρότυπο ECMA-363 τον Αύγουστο του 2005. Τα έγγραφα 3D PDF υποστηρίζουν U3D ενσωμάτωση αντικειμένων και μπορούν να προβληθούν στο Adobe Reader (έκδοση 7 και μετά). Η μορφή U3D αναπτύχθηκε λαμβάνοντας υπόψη τον στόχο να καθιερωθεί ένα καθολικό πρότυπο για την τρισδιάστατη αποθήκευση και ανταλλαγή δεδομένων. Ωστόσο, η μορφή βρίσκει την κύρια χρήση της στην κωδικοποίηση για το 3D PDF αντί να χρησιμοποιείται ως μορφή ανταλλαγής. Το Acrobat 3D μετατρέπει έναν υποστηριζόμενο τύπο αρχείου 3D είτε σε U3D είτε σε ΛΔΚ κατά τη μετατροπή σε PDF.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="amf" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}
Η μορφή αρχείου Additive Manufacturing (AMF) ορίζει ανοιχτά πρότυπα για την περιγραφή αντικειμένων, προκειμένου να χρησιμοποιηθούν από διαδικασίες πρόσθετης κατασκευής, όπως η εκτύπωση 3D. Τα προγράμματα CAD χρησιμοποιούν τη μορφή αρχείου AMF χρησιμοποιώντας πληροφορίες όπως γεωμετρία, χρώμα και υλικό των αντικειμένων. Η μορφή AMF είναι διαφορετική από τη μορφή STL καθώς η πλευρική δεν υποστηρίζει χρώμα, υλικά, πλέγματα και αστερισμούς.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το U3D σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-3ds/" name="U3D ΠΡΟΣ 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-dae/" name="U3D ΠΡΟΣ DAE" description="Ανταλλαγή ψηφιακών περιουσιακών στοιχείων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-fbx/" name="U3D ΠΡΟΣ FBX" description="3D Μορφή" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-html/" name="U3D ΠΡΟΣ HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-obj/" name="U3D ΠΡΟΣ OBJ" description="3D Μορφή αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-pdf/" name="U3D ΠΡΟΣ PDF" description="Μορφή φορητού εγγράφου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-ply/" name="U3D ΠΡΟΣ PLY" description="Μορφή αρχείου Polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-rvm/" name="U3D ΠΡΟΣ RVM" description="Μοντέλο σχεδίασης φυτών AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-stl/" name="U3D ΠΡΟΣ STL" description="Εναλλάξιμη Γεωμετρία Επιφανειών 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}