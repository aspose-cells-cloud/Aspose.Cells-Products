﻿---
title:  Convertir PNG en CSV en utilisant Android
description: Utilisation du SDK Cloud Aspose.Cells pour Android pour convertir un fichier au format PNG en fichier au format CSV.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir PNG en CSV" h2="Bibliothèque Android pour convertir PNG en CSV" p="Utilisez la conversion API de Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans des projets Android. Il s\'agit d\'une solution professionnelle pour convertir PNG en CSV et autres formats de documents en ligne à l\'aide d\'Android." urlsection="conversion/png-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez PNG en CSV à l\'aide du SDK Cloud Cells pour Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de PNG en CSV peut être une tâche complexe. Notre SDK Android gère toutes les conversions au format PNG au format CSV tout en préservant le contenu structurel et logique principal de la feuille de calcul source PNG. Notre bibliothèque Android fournit une solution professionnelle pour convertir PNG en fichiers CSV en ligne. Ce SDK Cloud offre aux développeurs Android des fonctionnalités puissantes et garantit une sortie CSV de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code Android pour convertir PNG en CSV à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.png";
                String format = "csv";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.csv";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Android pour convertir des fichiers Excel vers d\'autres formats PNG en CSV" >}}
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
