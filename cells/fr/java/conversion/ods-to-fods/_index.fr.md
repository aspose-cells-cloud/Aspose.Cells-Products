---
title:  Convertissez ODS en FODS en utilisant Java
description:  Utilisation du SDK Cloud Aspose.Cells for Java pour convertir un fichier au format ODS en fichier au format FODS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir des ODS en FODS" h2="Bibliothèque Java pour convertir ODS en FODS" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets Java. Il s\'agit d\'une solution professionnelle pour convertir ODS en FODS et d\'autres formats de documents en ligne en utilisant le Java." urlsection="conversion/ods-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez ODS en FODS à l\'aide du SDK Cloud Cells for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers d'ODS en FODS peut être une tâche complexe. Notre SDK Java gère toutes les conversions de format ODS vers FODS tout en préservant le contenu structurel et logique principal de la feuille de calcul ODS source. Notre bibliothèque Java fournit une solution professionnelle pour convertir des fichiers ODS en FODS en ligne. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et garantit une sortie FODS de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Exemple de code pour convertir ODS en FODS à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.ods";
            String format = "fods";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.fods";
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
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Cells Cloud SDK for Java pour convertir des fichiers Excel vers d\'autres formats ODS en FODS" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `putConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Maven 2.2.0 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
