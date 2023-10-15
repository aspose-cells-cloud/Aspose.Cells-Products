---
title:  Convierta ODS a WMF usando Java
description: Utilizando el Aspose.Cells Cloud SDK for Java para convertir un archivo en formato ODS a un archivo en formato WMF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir ODS a WMF" h2="Biblioteca Java para convertir ODS a WMF" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Java proyectos. Esta es una solución profesional para convertir ODS a WMF y otros formatos de documentos en línea usando Java." urlsection="conversion/ods-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta ODS a WMF usando Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de ODS a WMF puede ser una tarea compleja. Nuestro SDK Java maneja todas las conversiones de formato ODS a WMF al tiempo que conserva el contenido estructural y lógico principal de la hoja de cálculo ODS de origen. Nuestra biblioteca Java proporciona una solución profesional para convertir archivos ODS a WMF en línea. Este SDK de nube brinda a los desarrolladores Java una potente funcionalidad y garantiza resultados WMF de alta calidad.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Ejemplo de código para convertir ODS a WMF usando Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.ods";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK for Java para convertir archivos Excel a otros formatos ODS a WMF" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `putConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Maven 2.2.0 o más reciente</li>
<li>Java(TM) SE entorno de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
