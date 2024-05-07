---
title:  Exportez SHAPE vers WMF à partir de Excel à l'aide du SDK Cloud Cells for Java
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
kwords: Excel, shape, wmf, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to WMF","description": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to WMF","image": {"@type": "ImageObject"},"url": "/java/export/shape-to-wmf/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to WMF step 1", "image": {"@type": "ImageObject",},"url": "/java/export/shape-to-wmf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to WMF step 1", "image": {"@type": "ImageObject",},"url": "/java/export/shape-to-wmf/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to WMF step 1", "image": {"@type": "ImageObject",},"url": "/java/export/shape-to-wmf/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exporter SHAPE vers WMF à partir de Excel" h2="Bibliothèque Java pour exporter SHAPE vers un fichier WMF" p="Utilisez Export API de Cells Cloud pour exporter les flux de travail d\'objets internes du fichier Excel dans Java. Il s\'agit d\'une solution professionnelle pour exporter SHAPE vers un fichier au format WMF à partir d\'une feuille de calcul en ligne à l\'aide de Java." urlsection="export/shape-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportez l\'objet SHAPE vers un fichier au format WMF à l\'aide du SDK Cloud Cells for Java." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter l'objet SHAPE vers le fichier WMF à partir du fichier Excel est une tâche complexe. L'exportation des transitions au format SHAPE vers WMF est effectuée par notre SDK Java tout en conservant le contenu structurel et logique principal de la feuille de calcul SHAPE source. Notre bibliothèque Java est une solution professionnelle pour exporter des objets SHAPE vers des fichiers au format WMF en ligne. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et une sortie WMF parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code dans Java utilisant REST API pour exporter SHAPE au format WMF à partir d\'une feuille de calcul" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.*;
    import java.util.HashMap;
    import java.util.List;
    import java.util.Base64;
    import com.aspose.cloud.cells.api.*;
    import com.aspose.cloud.cells.model.*;
    public class Export {
        public static void main(String[] args) {
            String format = "wmf";
            String objectType = "shape";
            HashMap<String,File> fileMap = new HashMap<String,File>();
            fileMap.put("Book1.xlsx" ,new File("C:\Book1.xlsx") );
            fileMap.put("myDocument.xlsx" ,new File("C:\myDocument.xlsx") );
            try {
                LightCellsApi cellsApi = new LightCellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"),"v3.0","https://api.aspose.cloud");
                FilesResult response = cellsApi.postExport(fileMap,objectType, format,null);            
                List<FileInfo> files = response.getFiles();
                String filename = files.get(0).getFilename();
                String fileContent = files.get(0).getFileContent();
                byte[] data = Base64.getDecoder().decode(fileContent);
                OutputStream outputStream = new FileOutputStream(filename);
                outputStream.write(data,0,data.length);
                outputStream.close();
            }catch(Exception exception )
            {
                System.out.print(exception);
            }
        }
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Cells Cloud SDK for Java pour exporter des objets de Excel SHAPE vers WMF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `postExport` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Maven 2.2.0 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
