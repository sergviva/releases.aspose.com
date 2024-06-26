---

title: "PDF Import with Table Detection in Aspose.Slides Node.js 24.1"
description: "Utilize Aspose.Slides Node.js Java 24.1 in your Node.js apps for improved PDF import with automatic table detection. Download & convert PDF tables to slides!"
keywords: ""
page_type: single_release_page
folder_link: "/slides/nodejs-java/new-releases/aspose.slides-for-node.js-via-java-24.1/"
folder_name: "Aspose.Slides for Node.js via Java 24.1"
download_link: "/slides/nodejs-java/new-releases/aspose.slides-for-node.js-via-java-24.1/c1876154f8a81a1293ab399a2abaaebd-6-10219"
download_text: "Download"
intro_text: "It contains Aspose.Slides for Node.js via Java 24.1 release."
image_link: "/resources/img/zip-icon.png"
download_count: " 26/1/2024 Downloads: 1  Views: 1 "
file_size: "File Size: 26.8MB"
parent_path: "slides/nodejs-java"
section_parent_path: "slides/nodejs-java"

tags: ""
release_notes_url: "https://releases.aspose.com/slides/nodejs-java/release-notes/2024/aspose-slides-for-nodejs-via-java-24-1-release-notes/"
weight: 6

---

{{< Releases/ReleasesWapper >}}
  {{< Releases/ReleasesHeading H2txt="Aspose.Slides for Node.js via Java 24.1" imagelink="/resources/img/zip-icon.png">}}
  {{< Releases/ReleasesButtons >}}
    {{< Releases/ReleasesSingleButtons text="Download" link="/slides/nodejs-java/new-releases/aspose.slides-for-node.js-via-java-24.1/c1876154f8a81a1293ab399a2abaaebd-6-10219" >}}
    {{< Releases/ReleasesSingleButtons text="Support Forum" link="https://forum.aspose.com/c/slides" >}}
  {{< Releases/ReleasesButtons >}}
  {{< Releases/ReleasesFileArea >}}
    {{< Releases/ReleasesHeading h4txt="File Details">}}
    {{< Releases/ReleasesDetailsUl >}}
      {{< Common/li >}} Downloads: {{< /Common/li >}}
      {{< Common/li class="downloadcount" id="dwn-update-c1876154f8a81a1293ab399a2abaaebd-6-10219" >}} 1 {{< /Common/li >}}
      {{< Common/li >}} File Size: {{< /Common/li >}}
      {{< Common/li id="size-update-c1876154f8a81a1293ab399a2abaaebd-6-10219" >}} 26.8MB {{< /Common/li >}}

      {{< Common/li >}} Date Added: {{< /Common/li >}}
      {{< Common/li id="added-update-c1876154f8a81a1293ab399a2abaaebd-6-10219" >}}26/1/2024 {{< /Common/li >}}
    {{< /Releases/ReleasesDetailsUl >}}

  {{< Releases/ReleasesFileFeatures >}}
      <h4>Release Notes</h4><div><a href='https://releases.aspose.com/slides/nodejs-java/release-notes/2024/aspose-slides-for-nodejs-via-java-24-1-release-notes/'>https://releases.aspose.com/slides/nodejs-java/release-notes/2024/aspose-slides-for-nodejs-via-java-24-1-release-notes/</a></div>
  {{< /Releases/ReleasesFileFeatures >}}
  {{< Releases/ReleasesFileFeatures >}}
      <h4>Description</h4><div class="HTMLDescription">It contains Aspose.Slides for Node.js via Java 24.1 release.</div>
  {{< /Releases/ReleasesFileFeatures >}}

{{< Releases/ReleasesHeading h4txt="Notable Features">}}
{{< Common/wrapper class="HTMLDescription">}}
{{% Releases/ReleasesFileFeatures %}}

### Optimized PDF Import

In version 24.1 of Aspose.Slides for Node.js via Java, the `PdfImportOptions` class now includes the `setDetectTables` method. With this option enabled, you can automatically recognize and convert tables within imported PDFs into slide tables.

This coding example shows how to import PDF with table detection enabled.

```java
var pres = new aspose.slides.Presentation();
try {
    var pdfImportOptions = new aspose.slides.PdfImportOptions();
    pdfImportOptions.setDetectTables(true);

    var stream = java.newInstanceSync("java.io.FileInputStream", "document.pdf");
    pres.getSlides().addFromPdf(stream, pdfImportOptions);

    pres.save("output.pptx", aspose.slides.SaveFormat.Pptx);
} finally {
    if (pres != null) pres.dispose();
}

```
*[Source\*](https://releases.aspose.com/slides/nodejs-java/release-notes/2024/aspose-slides-for-nodejs-via-java-24-1-release-notes/)*

### Bug Fixes and Enhancements

We have resolved the issue causing installation failures with ```npm install aspose.slides.via.java``` and also streamlined the Node.js API's presentation development with Aspose.Slides for Java 24.1 version's enhanced PowerPoint processing capabilities.


> You can view the list of all new features, enhancements, and bug fixes introduced in this release by visiting [Aspose.Slides for Node.js via Java 24.1 Release Notes](https://releases.aspose.com/slides/nodejs-java/release-notes/2024/aspose-slides-for-nodejs-via-java-24-1-release-notes/).


{{% /Releases/ReleasesFileFeatures %}}

{{< /Common/wrapper >}}
{{< /Releases/ReleasesFileFeatures >}}

 {{< /Releases/ReleasesFileArea >}}
{{< /Releases/ReleasesWapper >}}


