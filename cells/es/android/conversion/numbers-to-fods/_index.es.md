﻿---
title:  NÚMEROS a FODS Convertir API para Android
description:  Usando Aspose.Cells Cloud SDK para Android para convertir un archivo de formato NUMBERS a un archivo de formato FODS.
url: /es/android/conversion/numbers-to-fods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API para convertir NÚMEROS a FODS" h2="Biblioteca de Android para convertir NÚMEROS a FODS" p="Use Cells Conversion REST API para crear flujos de trabajo de hojas de cálculo personalizados en Android. Esta es una solución profesional para convertir NÚMEROS a FODS y otros formatos de documentos en línea usando Android." urlsection="conversion/numbers-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta un archivo NUMBERS a FODS en Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de NUMBERS a FODS es una tarea compleja. Todas las transiciones de formato NUMBERS a FODS son realizadas por nuestro SDK de Android mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo NUMBERS de origen. Nuestra biblioteca de Android es una solución profesional para convertir archivos NUMBERS a FODS en línea. Este SDK de la nube brinda a los desarrolladores de Android una funcionalidad poderosa y una salida FODS perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Android usando REST API para convertir NÚMEROS a formato FODS" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.numbers";
                String format = "fods";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.fods";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Java API para convertir NÚMEROS a FODS" >}}
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