﻿---
title: Json'u DOCX dosyasına aktar via Android
description: Aspose.Cells Cloud REST API, Excel dosyasının ve dahili nesnelerin dosya biçimi türlerine dışa aktarılmasını destekler. SDK, geliştirme dili türlerini destekler. Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby ve Swift'i içerir.
url: /tr/android/export/json-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="JSON\'u Bulutta DOCX dosyasına aktarın" h2="Excel & Android için açık kaynaklı Cloud SDK ile OpenOffice e-tablo dışa aktarımı" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=" Android için Cloud SDK\'da JSON\'u DOCX dosyasına aktarın" %}}
1.  adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları
1. ```CellsApi```'i İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlat
1. Ortaya çıkan DOCX akışını almak için ```cellsWorkbookPutConvertWorkbook``` yöntemini çağırın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Başlayın Excel REST API" %}}
 Excel Cloud SDK for .NET kaynak kodunu şu adresten alın:[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) SDK'yı kendiniz derlemek veya[Salıverme](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/releases) alternatif indirme seçenekleri için.

 Ayrıca Swagger tabanlı bir göz atın[API Referans]() hakkında daha fazla bilgi edinmek için[Excel DİNLENME API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="JSON\'dan DOCX\'e Dönüşüm için Android Kodu" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xlsx";
            String format = "docx";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.docx";
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

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}