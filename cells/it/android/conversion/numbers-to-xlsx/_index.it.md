---
title:  Converti NUMERI in XLSX utilizzando Android
description: Utilizzando Aspose.Cells Cloud SDK per Android per convertire un file in formato NUMBERS in un file in formato XLSX.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Converti i NUMERI in XLSX" h2="Libreria Android per convertire NUMBERS in XLSX" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Android. Questa è una soluzione professionale per convertire NUMBERS in XLSX e altri formati di documenti online utilizzando Android." urlsection="conversion/numbers-to-xlsx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti NUMERI in XLSX utilizzando Cells Cloud SDK per Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da NUMBERS a XLSX può essere un compito complesso. Il nostro SDK Android gestisce tutte le conversioni dal formato NUMBERS al formato XLSX preservando il contenuto strutturale e logico principale del foglio di calcolo NUMBERS di origine. La nostra libreria Android fornisce una soluzione professionale per convertire online file NUMBERS in XLSX. Questo Cloud SDK offre agli sviluppatori Android funzionalità potenti e garantisce output XLSX di alta qualità.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice Android per convertire NUMBERS in XLSX utilizzando Cells Cloud SDK" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.numbers";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Android per convertire i file Excel in altri formati da NUMERI a XLSX" >}}
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
