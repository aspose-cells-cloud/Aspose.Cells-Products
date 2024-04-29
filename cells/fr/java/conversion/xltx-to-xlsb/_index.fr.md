---
title:  Convertissez XLTX en XLSB en utilisant Java
description:  Utilisation du SDK Cloud Aspose.Cells for Java pour convertir un fichier au format XLTX en fichier au format XLSB.
kwords: Excel, Convert XLTX to XLSB, REST, Java
howto: "{"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLTX to XLSB using the Cells Cloud Java library.","description": "How to convert XLTX to XLSB using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/conversion/xltx-to-xlsb/","step": [{ "@type": "HowToStep","name": "How to convert XLTX to XLSB using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/xltx-to-xlsb/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLTX to XLSB using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/xltx-to-xlsb/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLTX to XLSB using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/xltx-to-xlsb/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to convert XLTX to XLSB using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/xltx-to-xlsb/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}"
fqa: "{"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}"
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir XLTX en XLSB" h2="Bibliothèque Java pour convertir XLTX en XLSB" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets Java. Il s\'agit d\'une solution professionnelle pour convertir XLTX en XLSB et d\'autres formats de documents en ligne en utilisant le Java." urlsection="conversion/xltx-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez XLTX en XLSB à l’aide du SDK Cloud Cells for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers XLTX en XLSB peut être une tâche complexe. Notre SDK Java gère toutes les conversions du format XLTX vers XLSB tout en préservant le contenu structurel et logique principal de la feuille de calcul XLTX source. Notre bibliothèque Java fournit une solution professionnelle pour convertir des fichiers XLTX en XLSB en ligne. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et garantit une sortie XLSB de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Exemple de code pour convertir XLTX en XLSB à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xltx";
            String format = "xlsb";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xlsb";
            try {
                CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
                File response = cellsApi.cellsWorkbookPutConvertWorkbook(new File(name), format, password, outPath, null,null);            
                if(response.canRead())
                {
                    if(response.exists()){
                        response.renameTo(new File(destFile));
                    }                
                }
            }
            catch(Exception exception )
            {
                System.out.print(exception);
            }
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment convertir XLTX en XLSB à l\'aide de la bibliothèque Cells Cloud Java." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Java et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Java.</li>
<li>Utilisez la méthode `putConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Maven 2.2.0 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
