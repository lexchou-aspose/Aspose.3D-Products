---
title: Java 3D API | 3D Files Manipulation and Conversion 
weight: 1820
url: /java/ 
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/upper-banner h1="Java 3D File Processing API" h2="Create, Manipulate & Save 3D files to multiple formats without requiring any external modeling & rendering software." logoImageSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/3d/header/aspose_3d-for-java.png" pfName="Aspose.3D" subTitlepfName="for Java" downloadUrl="https://downloads.aspose.com/3d/java" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D" subTitlepfName="for Java" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" liveDemosLink="https://products.aspose.app/3d/family" PricingLink="https://purchase.aspose.com/pricing/3d/java" buyLink="https://purchase.aspose.com" docsLink="https://docs.aspose.com/3d/java/" instalationsDocsLink="https://docs.aspose.com/3d/java/installation/" nugetLink="" nugetPackageName="Autodesk:" >}}

{{< blocks/products/pf/tab-content >}}
{{< /blocks/products/pf/tab-content >}}

<!--Diagrams Start-->
{{< blocks/products/pf/carousel >}}

{{< blocks/products/pf/carousel-item h3="" description="" >}}
{{< /blocks/products/pf/carousel-item >}}

{{< /blocks/products/pf/carousel >}}
<!--Diagrams End-->

<!--Feature-section Start-->
<div class="container-fluid features-section bg-gray singleproduct">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
    Advanced Java 3D API Features
   </h2>
   <p>
   </p>
   <div class="col-lg-4">
    <em class="fa fa-square-o ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Generate scene and save in supported formats
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-file ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Load, save and render 3D document to a stream
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-rocket ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Work with geometry and scene hierarchy
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-table ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Share mesh geometry data within multiple nodes
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-spinner ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Add animation property to the scene file
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-tasks ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Triangulate a Mesh with custom memory layout of the vertex
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-video-camera ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Add a target camera as well as animate objects in a 3D scene
    </p>
   </div>
   <!--<div class="col-lg-4"><em class="fa fa-sliders ico-blue fa-2x col-lg-2"> </em>

<p class="col-lg-10">Animate objects in a 3D scene</p>

</div>-->
   <div class="col-lg-4">
    <em class="fa fa-object-ungroup ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Split meshes by material
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-edit ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Change plane's orientation by specifying an up normal
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-code ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Create geometry by extruding shapes
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-arrows-h ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Enhance the creation of cylinder
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-folder ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Archive-based file format-detection
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-print ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     support of AMF format
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-bolt ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Import and export glTF documents using Draco compression
    </p>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">
     Inter-convert Scene Files
    </h2>
    <p>
     API provides the support of 3D file format conversion in a simple way. Developers can load the source document in a Scene instance, and use its Save function with the FileFormat parameter. That's it!
    </p>
    <div class="codeblock" id="code">
     <h3>
      Save 3D scene in different formats - Java
     </h3>
     <pre><code class="java">// load the file to be converted

Scene scnObj = new Scene(dir + "srctemplate.fbx");

// save in different formats

scnObj.save(dir + "trgoutput.stl", FileFormat.STLASCII);

scnObj.save(dir + "trgoutput.obj", FileFormat.WAVEFRONTOBJ);</code></pre>
    </div>
   </div>
   <!--<div class="col-lg-12">

<h2 class="h2title">Build Mesh of Various 3D Geometric Shapes</h2>

<p>Aspose.3D for Java API help the developers in building mesh of various 3D geometric shapes, define control points and polygons in the simplest way to create 3D meshes. The API also allows to point a mesh to multiple instances of a shape type or place 3D shapes anywhere on a 3D scene.</p>

</div>

<div class="col-lg-12">

<h2 class="h2title">Managing Normal and UV on Geometric Shapes</h2>

<p>Aspose.3D for Java API offers to manage Normal (geometry) and UV on the geometric shapes. A mesh stores the key properties for every vertex at its position in space and its normal - a vector perpendicular to the original surface. The normal is major to shading counts. Most of the mesh formats also support some form of UV coordinates which are a separate 2D representation of the mesh "unfolded" to show what portion of a 2-dimensional texture map to apply to different polygons of the mesh.</p>

</div>-->
   <div class="col-lg-12">
    <h2 class="h2title">
     Generate 3D Scenes via API
    </h2>
    <p>
     Aspose.3D for Java lets the developers create scenes from scratch without the dependency of any modeling software. The Java API also empowers the developers to save the scenes in any of the supported formats such as (STL, FBX,  Discreet3DS, WavefrontOBJ, Collada and Universal3D).
    </p>
    <div class="codeblock" id="code">
     <h3>
      Create a scene with primitive 3D shapes - Java
     </h3>
     <pre><code class="java">// initialize a Scene object

Scene scn = new Scene();

// create a Box model

scn.getRootNode().createChildNode("box", new Box());

// create a Cylinder model

scn.getRootNode().createChildNode("cylinder", new Cylinder());

// save drawing in the FBX format

scn.save(dir + "output.fbx", FileFormat.FBX7500ASCII);</code></pre>
    </div>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">
     Build Node Hierarchy in a Simple Way
    </h2>
    <p>
     Aspose.3D for Java API provides the ability to build a Node hierarchy where a Node is the basic building block of a scene. A hierarchy of nodes defines the logical structure and provides visible content by attaching geometries, lights, and cameras to the nodes.
    </p>
   </div>
   <!--<div class="col-lg-12">

<h2 class="h2title">Mesh Geometry Data Sharing</h2>

<p>In order to reduce memory necessities, a single instance of Mesh can be bound to various instances of Node. Envision that you require a system where a large number of 3D cubes seemed indistinguishable; you could spare memory by making one Mesh object when the system starts up. At that point, each time you require another shape, you make another Node object, then point that node to one Mesh. This is how Aspose.3D for Java API manages instancing.</p>

</div>-->
   <div class="col-lg-12">
    <h2 class="h2title">
     Add Animation Property to Scene
    </h2>
    <p>
     Aspose.3D for Java API provides support for keyframe animation via CurveMapping which maps components of a property to different curves. Moreover, library offers to set up the target camera in a 3D file which is useful in animation when you need the camera to face a particular node.
    </p>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">
     Robustness, Performance &amp; Scalability
    </h2>
    <p>
     Aspose.3D for Java is designed to perform equally well on the server or client-side. It is a single Java assembly that can be deployed with any Java application by simply adding its reference. You don't have to worry about other services or modules while working with API.
    </p>
   </div>
   <!--<div class="col-lg-12">

<h2 class="h2title">Independent of External Software Installation</h2>

<p>Aspose.3D API is built using managed code that never needs any external API or software installation on the machine to work with 3D files. It is perfectly customized solution in terms of supported features, security, stability and price.</p>

</div>-->
  </div>
 </div>
</div>
<!--Feature-section End-->

{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/testimonials title="" subTitle="" >}}

{{< blocks/products/pf/testimonials-quote >}}
{{< /blocks/products/pf/testimonials-quote >}}

{{< /blocks/products/pf/testimonials >}}

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/3d/java/" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-3d/Aspose.3D-for-Java" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.com/3d/java" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/3d" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/3d/" >}}
{{< blocks/products/pf/slr-element name="Release Notes" href="https://docs.aspose.com/3d/java/release-notes/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.3D for Java" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.com/customers" >}}
{{< blocks/products/pf/slr-element name="Success Stories" href="https://company.aspose.com/customers/success-stories/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://downloads.aspose.com/3d/java" pricingInformationLink="https://purchase.aspose.com/pricing/3d/java" >}}

{{< blocks/products/pf/offers-section pfName="Aspose.3D offers individual 3D processing APIs for other popular development environments as listed below:" >}}

    {{< blocks/products/pf/offers-section-item link="/3d/net" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-net.png" sdkName="Aspose.3D for .NET" >}}

{{< /blocks/products/pf/offers-section >}}

{{< /blocks/products/pf/main-wrap-class >}}