﻿---
title:  XLS a HTML Convertir API para Android
description:  Usando Aspose.Cells Cloud SDK para Android para convertir un archivo de formato XLS a un archivo de formato HTML.
url: /es/android/conversion/xls-to-html/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API para convertir XLS a HTML" h2="Biblioteca de Android para convertir XLS a HTML" p="Use Cells Conversion REST API para crear flujos de trabajo de hojas de cálculo personalizados en Android. Esta es una solución profesional para convertir XLS a HTML y otros formatos de documentos en línea usando Android." urlsection="conversion/xls-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierte un archivo XLS a HTML en Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de XLS a HTML es una tarea compleja. Todas las transiciones de formato XLS a HTML las realiza nuestro SDK de Android mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLS de origen. Nuestra biblioteca de Android es una solución profesional para convertir archivos XLS a HTML en línea. Este SDK de la nube brinda a los desarrolladores de Android una funcionalidad poderosa y una salida HTML perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Android usando REST API para convertir XLS al formato HTML" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xls";
                String format = "html";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.html";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Java API para convertir XLS a HTML" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método cellsWorkbookPutConvertWorkbook para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Android 7 o más reciente</li>
<li>Java(TM) SE Entorno de tiempo de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}