﻿---
title: Δημιουργία Cloud Point σε μορφές αρχείων ASE μέσω .NET 
weight: 830
url: /el/net/point-cloud/ase/ 
description: C# πηγαίος κώδικας για φόρτωση, αποτύπωση και προσθήκη δημιουργίας σύννεφου σημείου σε αρχεία ASE σε .NET Πλαίσιο, .NET Πυρήνα, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Δημιουργία Cloud Point σε ASE μέσω C#" h2="Κατασκευάστε τις δικές σας εφαρμογές .NET για να δημιουργήσετε το σημείο cloud σε αρχεία ASE χρησιμοποιώντας API από το εξυπηρετητή." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ASE" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να δημιουργηθεί το Point Cloud στο ASE αρχείο χρήσης C#" %}}

 Προκειμένου να δημιουργήσουμε σύννεφο σημείο στο αρχείο ASE, θα χρησιμοποιήσουμε το σημείο
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API που είναι πλούσιο σε χαρακτηριστικά, ισχυρό και εύκολο στη χρήση API για την πλατφόρμα C# που θα χρησιμοποιηθεί με την παράγει σημείο σύννεφο. Άνοιγμα:
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Διαχειριστής πακέτου, αναζήτηση για την αναζήτηση.
 **Aspose.3D** 
 Και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την κονσόλα διαχειριστή πακέτων.

{{% blocks/products/pf/agp/code-block title="Εντολή κονσόλων διαχειριστή πακέτων" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη δημιουργία νέφου σημείου στο ASE μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

 Το Aspose.3D καθιστά εύκολο για τους προγραμματιστές να δημιουργήσουν σύννεφο σημείου στο αρχείο ASE με λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

- Φόρτωση αρχείου ASE μέσω του κατασκευαστή της κλάσης σκηνής- Λήψη αντικειμένου Pointcloud του Aspose.3D- Δημιουργήστε ένα αντικείμενο μετασχηματισμού μέσω της μέθοδος EvaluateGlobalTransform:- Δημιουργία νέφου σημείου χρησιμοποιώντας τη μέθοδο συγχώνευσης- Καλέστε τη σκηνή.Save μέθοδος με αντικείμενο
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Το Aspose.3D for .NET υποστηρίζεται σε όλα τα μεγάλα λειτουργικά συστήματα. Απλά βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή ένα συμβατό OS με .NET Πλαίσιο, .NET Πυρήνα, Mono- Περιβάλλον ανάπτυξης όπως Microsoft Visual Studio στο Microsoft Visual- Aspose.3D for .NET αναφέρεται στο έργο σας
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# κωδικός για τη δημιουργία Cloud Point σε ASE" offSpacer="" %}}

```cs

//Το αρχείο πηγαίου που πρέπει να δημιουργήσει το σύννεφο σημείου
string file = "template.ase";

// Δημιουργία μιας σκηνής
Scene scene = new Scene(file);

//Λήψη αντικειμένου Pointcloud του Aspose.3D και δημιουργήστε ένα σύννεφο σημείου
var pc = new PointCloud();
scene.RootNode.Accept((Node n) =>
{
    if (n.Entities.Count > 0)
    {
        var transform = n.EvaluateGlobalTransform(true);
        foreach (var entity in n.Entities)
        {
            if (entity is Geometry g)
            {
                Merge(pc, g, transform);
            }
            else if (entity is IMeshConvertible mc)
            {
                var mesh = mc.ToMesh();
                Merge(pc, mesh, transform);
            }

        }
    }
    return true;
});

//Μέθοδος συγχώνευσης για τη δημιουργία νέφων σημείου
private void Merge(PointCloud pc, Geometry g, Matrix4 transform)
{
    var tmp = PointCloud.FromGeometry(g, 10);
    for (int i = 0; i < tmp.ControlPoints.Count; i++)
    {
        var pt = transform * tmp.ControlPoints[i];
        pc.ControlPoints.Add(pt);
    }
}

// Δημιουργία μιας ένδειξης νέουScene
var newScene = new Scene(pc);

//Κατά την αποθήκευση, πρέπει να δημιουργήσετε ένα αντικείμενο SaveOptions της μορφής αποθήκευσης
string output=System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".ply";
PlySaveOptions ply = new PlySaveOptions();
ply.PointCloud = true;
newScene.Save(output,ply);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με το Aspose.3D for .NET API" %}}

 Το Aspose.3D είναι ένα CAD και το λογισμικό API για τη φόρτωση, την τροποποίηση και τη μετατροπή αρχείων 3D. Το API είναι αυτόνομο και δεν απαιτεί κανένα λογισμικό μοντελοποίησης ή αποτύπωσης 3D. Μπορεί κανείς να χρησιμοποιήσει το API για Discreet3DS, WavefrontOBJ, STL (ASCII, δυαδικό), Universal3D, FBX (ASCII, δυαδικό), Collada, glTF, PLY, GLB, DirectX και περισσότερες μορφές. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ελεύθερη εφαρμογή για τη δημιουργία νέφου σημείου στο ASE" sectionDescription="Ελέγξτε τα ζωντανά μας ντέμους [Σύννεφο σημείο 3DS](https://products.aspose.app/3d/point-cloud/ase) Με τα ακόλουθα οφέλη." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δε χρειάζεται να γράψετε ή να μεταγράψετε τον κώδικα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλά ανεβάστε ASE αρχείο και πατήστε το κουμπί \"Generate\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Λήψη αρχείου ASE από το σύνδεσμο, αν απαιτείται" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}
Ένα αρχείο ASE είναι ένα 2D animation ή γραφικά που περιέχει στρώματα, πλαίσια, παλέτες, ετικέτες και ρυθμίσεις.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλη υποστηριζόμενη εφαρμογή για να δημιουργήσει σημείο Cloud σε μορφές" subTitle="Χρησιμοποιώντας C#, Μπορεί κανείς επίσης να δημιουργήσει σημείο cloud σε πολλές άλλες μορφές αρχείων συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/3mf/" name="3MF" description="3D Μορφή παραγωγής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/amf/" name="AMF" description="Πρόσθετη μορφή παραγωγής παραγωγής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/3ds/" name="3DS" description="3D Μορφή αρχείων μετόχων στούντιο" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/dae/" name="DAE" description="Ανταλλαγή ψηφιακών περιουσιακών στοιχείων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/dxf/" name="DXF" description="Μορφή ανταλλαγής σχεδίασης" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/fbx/" name="FBX" description="Μορφή 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/glb/" name="GLB" description="3D Δυαδική αναπαραγωγή αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/gltf/" name="GLTF" description="Μορφή μετάδοσης GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/jt/" name="JT" description="Αρχείο Tessellation JupiterName" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/obj/" name="OBJ" description="Μορφή αρχείου 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/ply/" name="PLY" description="Μορφή αρχείων Πολυγόνου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/rvm/" name="RVM" description="Σχεδιασμός φυτών AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/stl/" name="STL" description="Εναλλάξιμο 3D Γεωμετρία επιφάνειας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/vrml/" name="VRML" description="Εικονική Πραγματικότητα Μοντελοποίηση Γλώσσα" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/x/" name="Υ" description="DirectX μοντέλο εικόνας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/usd/" name="USD" description="Περιγραφή καθολικής σκηνής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/usdz/" name="USDZ" description="Καθολική Σκηνή Περιγραφή Zip Archive Zip" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}