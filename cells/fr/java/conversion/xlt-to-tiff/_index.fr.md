---
title:  Convertir XLT en TIFF en utilisant Java
description:  Utilisation du SDK Cloud Aspose.Cells for Java pour convertir un fichier au format XLT en fichier au format TIFF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir XLT en TIFF" h2="Bibliothèque Java pour convertir XLT en TIFF" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets Java. Il s\'agit d\'une solution professionnelle pour convertir XLT en TIFF et d\'autres formats de documents en ligne en utilisant Java." urlsection="conversion/xlt-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir XLT en TIFF à l\'aide du SDK Cloud Cells for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers XLT vers TIFF peut être une tâche complexe. Notre SDK Java gère toutes les conversions du format XLT vers TIFF tout en préservant le contenu structurel et logique principal de la feuille de calcul XLT source. Notre bibliothèque Java fournit une solution professionnelle pour convertir en ligne des fichiers XLT en fichiers TIFF. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et garantit une sortie TIFF de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Exemple de code pour convertir XLT en TIFF à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xlt";
            String format = "tiff";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.tiff";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Cells Cloud SDK for Java pour convertir des fichiers Excel vers d\'autres formats XLT en TIFF" >}}
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
