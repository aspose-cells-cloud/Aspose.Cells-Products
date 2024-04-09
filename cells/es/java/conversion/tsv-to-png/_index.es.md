---
title:  Convierta TSV a PNG usando Java
description:  Utilizando el Aspose.Cells Cloud SDK for Java para convertir un archivo de formato TSV a un archivo de formato PNG.
kwords: Excel, Convert TSV to PNG, REST, Java
howto: How to convert TSV to PNG using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir TSV a PNG" h2="Biblioteca Java para convertir TSV a PNG" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Java proyectos. Esta es una solución profesional para convertir TSV a PNG y otros formatos de documentos en línea usando Java." urlsection="conversion/tsv-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta TSV a PNG usando Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de TSV a PNG puede ser una tarea compleja. Nuestro SDK Java maneja todas las conversiones de formato TSV a PNG y al mismo tiempo conserva el contenido estructural y lógico principal de la hoja de cálculo TSV de origen. Nuestra biblioteca Java proporciona una solución profesional para convertir archivos TSV a PNG en línea. Este SDK de nube brinda a los desarrolladores de Java una potente funcionalidad y garantiza resultados de PNG de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Ejemplo de código para convertir TSV a PNG usando Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.tsv";
            String format = "png";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.png";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir TSV a PNG usando la biblioteca Cells Cloud Java." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Java y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Java.</li>
<li>Utilice el método `putConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Maven 2.2.0 o más reciente</li>
<li>Java(TM) SE entorno de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
