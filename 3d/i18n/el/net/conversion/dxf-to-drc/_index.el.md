﻿---
title: Μετατροπή DXF σε DRC μέσω C# 
url: /el/net/conversion/dxf-to-drc/ 
description: Κωδικός δείγματος για τη μετατροπή DXF σε DRC C#. Χρησιμοποιήστε τον κωδικό API παράδειγμα για τα αρχεία DXF παρτίδας σε DRC μετατροπή εντός VB.NET, Asp.NET ή οποιαδήποτε .NET εφαρμογή.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή DXF σε DRC μέσω C#" h2="Ανάκτηση DXF ως DRC χωρίς λογισμικό μοντελοποίησης και αποτύπωσης 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DRC" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε DXF σε DRC χρησιμοποιώντας C#" %}}

 Προκειμένου να μετατρέψουμε το DXF σε DRC, θα χρησιμοποιήσουμε τα ακόλουθα:
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή DXF σε DRC μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές .NET μπορούν εύκολα να φορτώσουν και να μετατρέψουν DXF αρχεία σε DRC σε λίγες μόνο γραμμές του κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου DXF μέσω του κατασκευαστή της κλάσης σκηνής1. Δημιουργία μιας διάταξης AmfSaveOptionsName1. Ορισμός συγκεκριμένων ιδιοτήτων DRC για προηγμένη μετατροπή1. Καλέστε τη σκηνή.1. Πέρασε τη διαδρομή εξόδου με επέκταση αρχείου DRC & αντικείμενο του DrcSaveOptions1. Ελέγξτε το προκύπτον αρχείο DRC σε καθορισμένη διαδρομή
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Πριν εκτελέσετε τον κώδικα μετατροπής .NET, βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή ένα συμβατό OS με .NET Πλαίσιο, .NET Πυρήνα, Mono.- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.- Aspose.3D for .NET DLL αναφέρονται στο έργο σας.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτός ο κωδικός δείγματος εμφανίζει DXF σε DRC C#" offSpacer="" %}}

```cs
// Φόρτωση του DXF σε ένα αντικείμενο σκηνής 
var document = new Aspose.ThreeD.Scene("template.dxf");
// Δημιουργία μιας ένδειξης του DrcSaveOptions 
var options = new Aspose.ThreeD.Formats.DrcSaveOptions();
// Αποθήκευση DXF ως DRC 
document.Save("output.drc", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ελεύθερη εφαρμογή για τη μετατροπή DXF σε DRC" sectionDescription="Ελέγξτε τα ζωντανά μας ντέμου [DXF σε DRC μετατροπή](https://products.aspose.app/3d/conversion/dxf-to-drc) Με τα ακόλουθα οφέλη." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράφεις κανένα κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλά ανεβάστε το DXF αρχείο σας και πατήστε το κουμπί \"Convert\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα πάρετε αμέσως το σύνδεσμο λήψης για το αρχείο DRC." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Μια 3D Βιβλιοθήκη επεξεργασίας αρχείων για να χειριστεί τα αρχεία 3D χωρίς λογισμικό μοντελοποίησης και αποτύπωσης. Το 3D API υποστηρίζει Discreet3DS, WavefrontOBJ, FBX (ASCII, δυαδικό), STL (ASCII, Δυαδικό), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco μορφές αρχείων και πολλά άλλα. Οι προγραμματιστές μπορούν να δημιουργήσουν, να διαβάσουν, να μετατρέψουν, να τροποποιήσουν και να ελέγχουν την ουσία του 3D μορφές εγγράφου εύκολα.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}
DXF, Σχέδιο Interchange Format, ή σχεδίαση Exchange Format, είναι μια ετικέτα αναπαράσταση δεδομένων του αρχείου σχεδίασης AutoCAD. Κάθε στοιχείο του αρχείου έχει έναν αριθμό ακέραιο πρόθεμα που ονομάζεται κωδικός ομάδας. Αυτός ο κωδικός ομάδας αντιπροσωπεύει το στοιχείο που ακολουθεί και δείχνει την έννοια ενός στοιχείου δεδομένων για έναν συγκεκριμένο τύπο αντικειμένου. Η DXF καθιστά δυνατή την αντιπροσωπεία σχεδόν όλων των πληροφοριών που καθορίζονται από το χρήστη σε ένα αρχείο σχεδίασης. DXF μορφή αρχείου αναπτύχθηκε από την Autodesk ως μορφή αρχείου δεδομένων CAD για τη διαλειτουργικότητα δεδομένων μεταξύ AutoCAD και άλλων εφαρμογών. Έτσι, τα δεδομένα μπορούν να εισαχθούν από άλλες μορφές έως DXF σε AutoCAD σύμφωνα με τις προδιαγραφές διαλειτουργικότητας του μορφού αρχείου DXF.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="drc" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
Ένα αρχείο με. Η επέκταση drc είναι μια συμπιεσμένη μορφή αρχείου 3D που δημιουργήθηκε με τη βιβλιοθήκη Google Draco. Το Google προσφέρει Draco ως βιβλιοθήκη ανοικτού κώδικα για συμπίεση και αποσυμπίεση 3D γεωμετρικών ματιών και σύννεφα σημείου, και βελτιώνει την αποθήκευση και τη μετάδοση των 3D γραφικών. Κωδικοποιεί τα δεδομένα εισόδου και τα αποθηκεύει ως . Φάκελο. Στο τέλος παραλαβής, το API αναφέρεται . Αρχεία drc και μπορούν να τα βγάλουν ως αρχεία PLY ή OBJ. Το συμπιεσμένο αρχείο εξόδου επιτρέπει στους χρήστες να κατεβάζουν ταχύτερα εφαρμογές και να παρέχουν γρήγορη φόρτωση των 3D γραφικών στα προγράμματα περιήγησης.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε DXF σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων λίγα που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-3ds/" name="DXF έως 3DS" description="3D Μέσα DOS στούντιο" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-amf/" name="DXF έως AMF" description="Πρόσθετη μορφή παραγωγής παραγωγής" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-dae/" name="DXF έως DAE" description="Ανταλλαγή ψηφιακών περιουσιακών στοιχείων" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-fbx/" name="DXF έως FBX" description="Μορφή 3D" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-html/" name="DXF έως HTML" description="Γλώσσα σήμανσης Hyper κειμένου" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-obj/" name="DXF έως OBJ" description="Μορφή αρχείου 3D" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-pdf/" name="DXF έως PDF" description="Φορητή μορφή εγγράφου εγγράφου" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-ply/" name="DXF έως PLY" description="Μορφή αρχείων Πολυγόνου" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-rvm/" name="DXF έως RVM" description="Σχεδιασμός φυτών AVEVA" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-stl/" name="DXF έως STL" description="Εναλλάξιμο 3D Γεωμετρία επιφάνειας" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dxf-to-u3d/" name="DXF έως U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}