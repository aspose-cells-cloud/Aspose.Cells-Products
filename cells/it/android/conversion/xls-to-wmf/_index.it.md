﻿---
title:  Conversione da XLS a WMF API per Android
description:  API cloud e SDK per Microsoft Excel e OpenOffice Calc. Converti foglio di calcolo in un altro file di formato.
url: /it/android/conversion/xls-to-wmf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API per convertire XLS in WMF" h2="Libreria Android per convertire XLS in WMF" p="Utilizza Cells Conversion REST API per creare flussi di lavoro di fogli di calcolo personalizzati in Android. Questa è una soluzione professionale per convertire XLS in WMF e altri formati di documenti online utilizzando Android." urlsection="conversion/xls-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti un file XLS in WMF in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da XLS a WMF è un'attività complessa. Tutte le transizioni dal formato XLS a WMF vengono eseguite dal nostro Android SDK mantenendo il principale contenuto strutturale e logico del foglio di calcolo XLS di origine. La nostra libreria Android è una soluzione professionale per convertire file XLS in WMF online. Questo Cloud SDK offre agli sviluppatori Android potenti funzionalità e un output WMF perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Android che utilizza REST API per convertire XLS in formato WMF" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xls";
                String format = "wmf";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.wmf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Java API per convertire XLS in WMF" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo cellsWorkbookPutConvertWorkbook per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Android 7 o più recente</li>
<li>Java(TM) SE Ambiente di runtime</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}