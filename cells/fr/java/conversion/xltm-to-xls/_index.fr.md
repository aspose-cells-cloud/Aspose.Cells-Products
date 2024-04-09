---
title:  Convertissez XLTM en XLS en utilisant Java
description:  Utilisation du SDK Cloud Aspose.Cells for Java pour convertir un fichier au format XLTM en fichier au format XLS.
kwords: Excel, Convert XLTM to XLS, REST, Java
howto: How to convert XLTM to XLS using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir XLTM en XLS" h2="Bibliothèque Java pour convertir XLTM en XLS" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets Java. Il s\'agit d\'une solution professionnelle pour convertir XLTM en XLS et d\'autres formats de documents en ligne en utilisant le Java." urlsection="conversion/xltm-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez XLTM en XLS à l\'aide du SDK Cloud Cells for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers XLTM vers XLS peut être une tâche complexe. Notre SDK Java gère toutes les conversions du format XLTM vers XLS tout en préservant le contenu structurel et logique principal de la feuille de calcul XLTM source. Notre bibliothèque Java fournit une solution professionnelle pour convertir des fichiers XLTM en XLS en ligne. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et garantit une sortie XLS de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Exemple de code pour convertir XLTM en XLS à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xltm";
            String format = "xls";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xls";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment convertir XLTM en XLS à l\'aide de la bibliothèque Cells Cloud Java." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Java et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Java.</li>
<li>Utilisez la méthode `putConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Maven 2.2.0 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
