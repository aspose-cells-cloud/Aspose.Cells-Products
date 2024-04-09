---
title:  Esporta cartella di lavoro in PPTX da Excel utilizzando Cells Cloud SDK for Java
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Esporta cartella di lavoro in PPTX da Excel" h2="Java libreria per esportare WORKBOOK in file PPTX" p="Utilizza Export API of Cells Cloud per esportare i flussi di lavoro degli oggetti interni del file Excel in Java. Questa è una soluzione professionale per esportare WORKBOOK in file in formato PPTX dal foglio di calcolo online utilizzando Java." urlsection="export/workbook-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Esporta l\'oggetto WORKBOOK nel file in formato PPTX utilizzando Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto WORKBOOK nel file PPTX dal file Excel è un'attività complessa. L'esportazione delle transizioni del formato WORKBOOK in PPTX viene eseguita dal nostro SDK Java mantenendo il contenuto strutturale e logico principale del foglio di calcolo WORKBOOK di origine. La nostra libreria Java è una soluzione professionale per esportare online oggetti WORKBOOK in file in formato PPTX. Questo Cloud SDK offre agli sviluppatori Java funzionalità potenti e un output PPTX perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice in Java utilizzando REST API per esportare WORKBOOK in formato PPTX dal foglio di calcolo" gistPath="" %}}
  
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
            String format = "pptx";
            String objectType = "workbook";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK for Java per esportare oggetti da Excel WORKBOOK a PPTX" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `postExport` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Maven 2.2.0 o successiva</li>
<li>Java(TM) Ambiente runtime SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
