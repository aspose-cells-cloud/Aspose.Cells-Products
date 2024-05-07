---
title:  Java'i kullanarak SXC'yi WMF'ye dönüştürün
description: SXC formatındaki bir dosyayı WMF formatındaki bir dosyaya dönüştürmek için Aspose.Cells Cloud SDK for Java'i kullanma.
kwords: Excel, Convert SXC to WMF, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert SXC to WMF using the Cells Cloud Java library.","description": "How to convert SXC to WMF using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/conversion/sxc-to-wmf/","step": [{ "@type": "HowToStep","name": "How to convert SXC to WMF using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/sxc-to-wmf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert SXC to WMF using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/sxc-to-wmf/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert SXC to WMF using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/sxc-to-wmf/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to convert SXC to WMF using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/sxc-to-wmf/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="SXC\'yi WMF\'ye dönüştür" h2="SXC\'yi WMF\'ye dönüştürmek için Java kitaplığı" p="Java projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Java\'i kullanarak SXC\'yi WMF\'ye ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/sxc-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Cells Cloud SDK for Java\'i kullanarak SXC\'yi WMF\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını SXC'den WMF'ye dönüştürmek karmaşık bir iş olabilir. Java SDK'mız, kaynak SXC e-tablosunun ana yapısal ve mantıksal içeriğini korurken tüm SXC'den WMF'ye format dönüşümlerini gerçekleştirir. Java kitaplığımız, SXC'yi çevrimiçi olarak WMF dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Java geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli WMF çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Cells Cloud SDK\'yı kullanarak SXC\'yi WMF\'ye dönüştürmek için Kod Örneği" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.sxc";
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
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Java kitaplığını kullanarak SXC\'yi WMF\'ye dönüştürme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Java kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Java'de açın.</li>
<li>Ortaya çıkan akışı almak için `putConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Maven 2.2.0 veya daha yenisi</li>
<li>Java(TM) SE Çalışma Zamanı Ortamı</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
