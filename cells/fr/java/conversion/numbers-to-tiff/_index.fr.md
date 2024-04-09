---
title:  Convertissez des NOMBRES en TIFF en utilisant Java
description:  Utilisation du SDK Cloud Aspose.Cells for Java pour convertir un fichier au format NUMBERS en un fichier au format TIFF.
kwords: Excel, Convert NUMBERS to TIFF, REST, Java
howto: How to convert NUMBERS to TIFF using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir des NOMBRES en TIFF" h2="Bibliothèque Java pour convertir des NOMBRES en TIFF" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets Java. Il s\'agit d\'une solution professionnelle pour convertir des NUMÉROS en TIFF et d\'autres formats de documents en ligne en utilisant Java." urlsection="conversion/numbers-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez NUMBERS en TIFF à l\'aide du SDK Cloud Cells for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de NUMBERS en TIFF peut être une tâche complexe. Notre SDK Java gère toutes les conversions du format NUMBERS vers TIFF tout en préservant le contenu structurel et logique principal de la feuille de calcul NUMBERS source. Notre bibliothèque Java fournit une solution professionnelle pour convertir en ligne des NUMBERS en fichiers TIFF. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et garantit une sortie TIFF de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Exemple de code pour convertir NUMBERS en TIFF à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.numbers";
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
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment convertir NUMBERS en TIFF à l\'aide de la bibliothèque Cells Cloud Java." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Java et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Java.</li>
<li>Utilisez la méthode `putConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Maven 2.2.0 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
