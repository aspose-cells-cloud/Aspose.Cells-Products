---
title:  Convertir CSV en XLSX API pour Android
description:  Utilisation de Aspose.Cells Cloud SDK pour Android pour convertir un fichier au format CSV en fichier au format XLSX.
url: /fr/android/conversion/csv-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API pour convertir CSV en XLSX" h2="Bibliothèque Android pour convertir CSV en XLSX" p="Utilisez Cells Conversion REST API pour créer des workflows de feuille de calcul personnalisés dans Android. Il s\'agit d\'une solution professionnelle pour convertir CSV en XLSX et d\'autres formats de documents en ligne à l\'aide d\'Android." urlsection="conversion/csv-to-xlsx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier CSV en XLSX sous Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de CSV en XLSX est une tâche complexe. Toutes les transitions de format CSV vers XLSX sont effectuées par notre SDK Android tout en conservant le contenu structurel et logique principal de la feuille de calcul CSV source. Notre bibliothèque Android est une solution professionnelle pour convertir des fichiers CSV en XLSX en ligne. Ce SDK Cloud offre aux développeurs Android des fonctionnalités puissantes et une sortie XLSX parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Android utilisant REST API pour convertir CSV au format XLSX" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.csv";
                String format = "xlsx";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.xlsx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Java API pour convertir CSV en XLSX" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode cellsWorkbookPutConvertWorkbook pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Android 7 ou plus récent</li>
<li>Java(TM) Environnement d'exécution SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
