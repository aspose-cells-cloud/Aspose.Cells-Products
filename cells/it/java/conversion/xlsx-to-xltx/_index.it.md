---
title:  Converti XLSX in XLTX utilizzando Java
description: Utilizzando Aspose.Cells Cloud SDK for Java per convertire un file in formato XLSX in un file in formato XLTX.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Converti XLSX in XLTX" h2="Java libreria per la conversione da XLSX a XLTX" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Java. Questa è una soluzione professionale per convertire XLSX in XLTX e altri formati di documenti online utilizzando Java." urlsection="conversion/xlsx-to-xltx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti XLSX in XLTX utilizzando Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da XLSX a XLTX può essere un compito complesso. Il nostro SDK Java gestisce tutte le conversioni del formato XLSX in XLTX preservando il contenuto strutturale e logico principale del foglio di calcolo XLSX di origine. La nostra libreria Java fornisce una soluzione professionale per convertire online file XLSX in XLTX. Questo Cloud SDK offre agli sviluppatori Java potenti funzionalità e garantisce output XLTX di alta qualità.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Esempio di codice per convertire XLSX in XLTX utilizzando Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xlsx";
            String format = "xltx";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xltx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK for Java per convertire i file Excel in altri formati XLSX in XLTX" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `putConvertWorkbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Maven 2.2.0 o successiva</li>
<li>Java(TM) Ambiente runtime SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
