﻿---
title:  Converti XLS in XLSB utilizzando Android
description:  Utilizzando Aspose.Cells Cloud SDK per Android per convertire un file in formato XLS in un file in formato XLSB.
kwords: Excel, Convert XLS to XLSB, REST, Android
howto: How to convert XLS to XLSB using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti XLS in XLSB" h2="Libreria Android per convertire XLS in XLSB" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Android. Questa è una soluzione professionale per convertire XLS in XLSB e altri formati di documenti online utilizzando Android." urlsection="conversion/xls-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti XLS in XLSB utilizzando Cells Cloud SDK per Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da XLS a XLSB può essere un compito complesso. Il nostro SDK Android gestisce tutte le conversioni del formato XLS in XLSB preservando il contenuto strutturale e logico principale del foglio di calcolo XLS di origine. La nostra libreria Android fornisce una soluzione professionale per convertire file XLS in XLSB online. Questo Cloud SDK offre agli sviluppatori Android funzionalità potenti e garantisce output XLSB di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice Android per convertire XLS in XLSB utilizzando Cells Cloud SDK" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xls";
                String format = "xlsb";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.xlsb";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Android per convertire i file Excel in altri formati" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `putConvertWorkbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Android 7 o successivo</li>
<li>Java(TM) Ambiente runtime SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
