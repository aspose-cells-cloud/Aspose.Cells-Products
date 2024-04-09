---
title:  Convierta MHTML a PDF usando Java
description:  Utilizando el Aspose.Cells Cloud SDK for Java para convertir un archivo de formato MHTML a un archivo de formato PDF.
kwords: Excel, Convert MHTML to PDF, REST, Java
howto: How to convert MHTML to PDF using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir MHTML a PDF" h2="Biblioteca Java para convertir MHTML a PDF" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Java proyectos. Esta es una solución profesional para convertir MHTML a PDF y otros formatos de documentos en línea usando Java." urlsection="conversion/mhtml-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta MHTML a PDF usando Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de MHTML a PDF puede ser una tarea compleja. Nuestro SDK Java maneja todas las conversiones de formato MHTML a PDF y al mismo tiempo conserva el contenido estructural y lógico principal de la hoja de cálculo MHTML de origen. Nuestra biblioteca Java proporciona una solución profesional para convertir archivos MHTML a PDF en línea. Este SDK de nube brinda a los desarrolladores de Java una potente funcionalidad y garantiza resultados de PDF de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Ejemplo de código para convertir MHTML a PDF usando Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.mhtml";
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
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir MHTML a PDF usando la biblioteca Cells Cloud Java." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Java y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Java.</li>
<li>Utilice el método `putConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Maven 2.2.0 o más reciente</li>
<li>Java(TM) SE entorno de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
