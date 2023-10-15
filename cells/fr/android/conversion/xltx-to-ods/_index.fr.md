---
title:  Convertir XLTX en ODS en utilisant Android
description:  Utilisation du SDK Cloud Aspose.Cells pour Android pour convertir un fichier au format XLTX en fichier au format ODS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir XLTX en ODS" h2="Bibliothèque Android pour convertir XLTX en ODS" p="Utilisez la conversion API de Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans des projets Android. Il s\'agit d\'une solution professionnelle pour convertir XLTX en ODS et d\'autres formats de documents en ligne à l\'aide d\'Android." urlsection="conversion/xltx-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez XLTX en ODS à l\'aide du SDK Cloud Cells pour Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers XLTX vers ODS peut être une tâche complexe. Notre SDK Android gère toutes les conversions du format XLTX vers ODS tout en préservant le contenu structurel et logique principal de la feuille de calcul XLTX source. Notre bibliothèque Android fournit une solution professionnelle pour convertir des fichiers XLTX en fichiers ODS en ligne. Ce SDK Cloud offre aux développeurs Android des fonctionnalités puissantes et garantit une sortie ODS de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code Android pour convertir XLTX en ODS à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xltx";
                String format = "ods";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.ods";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Android pour convertir des fichiers Excel vers d\'autres formats XLTX en ODS" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `putConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Android 7 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
