﻿---
title:  Convertir MHTML en TXT API for Java
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/java/conversion/mhtml-to-txt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API pour convertir MHTML en TXT" h2="bibliothèque Java pour convertir MHTML en TXT" p="Utilisez Cells Conversion REST API pour créer des flux de travail de feuille de calcul personnalisés dans Java. Il s\'agit d\'une solution professionnelle pour convertir MHTML en TXT et d\'autres formats de documents en ligne à l\'aide de Java." urlsection="conversion/mhtml-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier MHTML en TXT en Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de MHTML en TXT est une tâche complexe. Toutes les transitions de format MHTML vers TXT sont effectuées par notre SDK Java tout en conservant le contenu structurel et logique principal de la feuille de calcul MHTML source. Notre bibliothèque Java est une solution professionnelle pour convertir en ligne des fichiers MHTML en TXT. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et une sortie TXT parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Java utilisant REST API pour convertir MHTML au format TXT" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.mhtml";
            String format = "txt";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.txt";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Java API pour convertir MHTML en TXT" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode cellsWorkbookPutConvertWorkbook pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Maven 2.2.0 ou plus récent</li>
<li>Java(TM) Environnement d'exécution SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}