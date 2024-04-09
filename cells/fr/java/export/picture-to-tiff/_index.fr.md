---
title:  Exportez l'IMAGE vers TIFF à partir de Excel à l'aide du SDK Cloud Cells for Java.
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exporter l\'IMAGE vers le TIFF à partir du Excel" h2="Bibliothèque Java pour exporter PICTURE vers le fichier TIFF" p="Utilisez Export API de Cells Cloud pour exporter les flux de travail d\'objets internes du fichier Excel dans Java. Il s\'agit d\'une solution professionnelle pour exporter une IMAGE au format TIFF à partir d\'une feuille de calcul en ligne à l\'aide de Java." urlsection="export/picture-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportez l\'objet PICTURE vers un fichier au format TIFF à l\'aide du SDK Cloud Cells for Java." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter un objet PICTURE vers le fichier TIFF à partir du fichier Excel est une tâche complexe. Les transitions d'exportation du format PICTURE au format TIFF sont effectuées par notre SDK Java tout en conservant le contenu structurel et logique principal de la feuille de calcul PICTURE source. Notre bibliothèque Java est une solution professionnelle pour exporter des objets IMAGE au format TIFF en ligne. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et une sortie TIFF parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code dans Java utilisant REST API pour exporter PICTURE au format TIFF à partir d\'une feuille de calcul" gistPath="" %}}
  
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
            String format = "tiff";
            String objectType = "picture";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells for Java pour exporter des objets de Excel PICTURE vers TIFF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `postExport` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Maven 2.2.0 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
