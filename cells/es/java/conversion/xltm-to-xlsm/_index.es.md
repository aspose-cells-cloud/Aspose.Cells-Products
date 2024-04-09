---
title:  Convierta XLTM a XLSM usando Java
description:  Utilizando el Aspose.Cells Cloud SDK for Java para convertir un archivo de formato XLTM a un archivo de formato XLSM.
kwords: Excel, Convert XLTM to XLSM, REST, Java
howto: How to convert XLTM to XLSM using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir XLTM a XLSM" h2="Biblioteca Java para convertir XLTM a XLSM" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Java proyectos. Esta es una solución profesional para convertir XLTM a XLSM y otros formatos de documentos en línea usando Java." urlsection="conversion/xltm-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta XLTM a XLSM usando Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de XLTM a XLSM puede ser una tarea compleja. Nuestro SDK Java maneja todas las conversiones de formato XLTM a XLSM al tiempo que conserva el contenido estructural y lógico principal de la hoja de cálculo XLTM de origen. Nuestra biblioteca Java proporciona una solución profesional para convertir archivos XLTM a XLSM en línea. Este SDK de nube brinda a los desarrolladores Java una potente funcionalidad y garantiza una salida XLSM de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Ejemplo de código para convertir XLTM a XLSM usando Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xltm";
            String format = "xlsm";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xlsm";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir XLTM a XLSM usando la biblioteca Cells Cloud Java." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Java y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Java.</li>
<li>Utilice el método `putConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Maven 2.2.0 o más reciente</li>
<li>Java(TM) SE entorno de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
