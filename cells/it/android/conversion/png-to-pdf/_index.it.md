---
title:  Converti PNG in PDF utilizzando Android
description:  Utilizzando Aspose.Cells Cloud SDK per Android per convertire un file in formato PNG in un file in formato PDF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertire PNG in PDF" h2="Libreria Android per la conversione da PNG a PDF" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Android. Questa è una soluzione professionale per convertire PNG in PDF e altri formati di documenti online utilizzando Android." urlsection="conversion/png-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti PNG in PDF utilizzando Cells Cloud SDK per Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da PNG a PDF può essere un compito complesso. Il nostro SDK Android gestisce tutte le conversioni del formato da PNG a PDF preservando il contenuto strutturale e logico principale del foglio di calcolo di origine PNG. La nostra libreria Android fornisce una soluzione professionale per convertire i file PNG in PDF online. Questo Cloud SDK offre agli sviluppatori Android funzionalità potenti e garantisce un output PDF di alta qualità.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice Android per convertire PNG in PDF utilizzando Cells Cloud SDK" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.png";
                String format = "pdf";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.pdf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Android per convertire i file Excel in altri formati da PNG a PDF" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `putConvertWorkbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Android 7 o successivo</li>
<li>Java(TM) Ambiente runtime SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
