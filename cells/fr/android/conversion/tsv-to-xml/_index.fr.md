---
title:  Convertir TSV en XML avec Android
description:  Utilisation du SDK Cloud Aspose.Cells pour Android pour convertir un fichier au format TSV en fichier au format XML.
kwords: Excel, Convert TSV to XML, REST, Android
howto: How to convert TSV to XML using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir TSV en XML" h2="Bibliothèque Android pour convertir TSV en XML" p="Utilisez la conversion API de Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans des projets Android. Il s\'agit d\'une solution professionnelle pour convertir TSV en XML et d\'autres formats de documents en ligne à l\'aide d\'Android." urlsection="conversion/tsv-to-xml/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez TSV en XML à l\'aide du SDK Cloud Cells pour Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers TSV en XML peut être une tâche complexe. Notre SDK Android gère toutes les conversions du format TSV vers XML tout en préservant le contenu structurel et logique principal de la feuille de calcul TSV source. Notre bibliothèque Android fournit une solution professionnelle pour convertir des fichiers TSV en XML en ligne. Ce SDK Cloud offre aux développeurs Android des fonctionnalités puissantes et garantit une sortie XML de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code Android pour convertir TSV en XML à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.tsv";
                String format = "xml";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.xml";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Android pour convertir les fichiers Excel vers d\'autres formats" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `putConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Android 7 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
