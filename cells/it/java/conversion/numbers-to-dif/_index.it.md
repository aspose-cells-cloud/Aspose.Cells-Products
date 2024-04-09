---
title:  Converti i NUMERI in DIF utilizzando Java
description: Utilizzando Aspose.Cells Cloud SDK for Java per convertire un file in formato NUMERI in un file in formato DIF.
kwords: Excel, Convert NUMBERS to DIF, REST, Java
howto: How to convert NUMBERS to DIF using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti NUMERI in DIF" h2="Libreria Java per convertire i NUMERI in DIF" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Java. Questa è una soluzione professionale per convertire online NUMERI in DIF e altri formati di documenti utilizzando Java." urlsection="conversion/numbers-to-dif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti NUMERI in DIF utilizzando Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da NUMBERS a DIF può essere un compito complesso. Il nostro SDK Java gestisce tutte le conversioni dal formato NUMBERS al formato DIF preservando il contenuto strutturale e logico principale del foglio di calcolo NUMBERS di origine. La nostra libreria Java fornisce una soluzione professionale per convertire online NUMBERS in file DIF. Questo Cloud SDK offre agli sviluppatori Java potenti funzionalità e garantisce un output DIF di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Esempio di codice per convertire NUMERI in DIF utilizzando Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.numbers";
            String format = "dif";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.dif";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Scopri come convertire i NUMERI in DIF utilizzando la libreria Cells Cloud Java." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Java e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in Java.</li>
<li>Utilizza il metodo `putConvertWorkbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Maven 2.2.0 o successiva</li>
<li>Java(TM) Ambiente runtime SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
