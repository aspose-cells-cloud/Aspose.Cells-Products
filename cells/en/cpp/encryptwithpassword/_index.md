---
title: Decrypt local spreadsheets with password in Cloud 
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc unlock. Spreadsheets decrypt by the Cells Cloud API. SDK support kinds of development languages. They include Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby, and swift. 
kwords: aspose cells
url: /cpp/decrypt-with-password/
---


{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convert Excel files to other formats" indexdesc="Cpp library to decrypt local Microsoft Excel and OpenOffice Calc spreadsheet with password">}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Supported Features" featuremsg="Use Cells Decrypt REST API to decrypt local Microsoft Excel and OpenOffice Calc spreadsheet with password workflows in cpp. This professional solution decrypts local Microsoft Excel and OpenOffice Calc spreadsheet online with passwords using cpp.">}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="https://api.aspose.cloud/v4.0/cells/protection/spreadsheet"  %}}

{{% blocks/products/cells/cells-cloud-showcode request="format,password,outPath,storageName,checkExcelRestriction,streamFormat,region,pageWideFitOnPerSheet,pageTallFitOnPerSheet" requestvalue="pdf,,,,true,,,true,true" %}}

```cpp
	#include <string>
	#include "SampleSupport.h"
	#include "aspose/cells/cloud/model/WorkbookEncryptionRequest.h"
	#include "aspose/cells/cloud/request/DeleteDecryptWorkbookRequest.h"

	using namespace Aspose::Cells::Cloud;
	namespace Samples = Aspose::Cells::Cloud::Examples::Samples;

	int main() {
		return Samples::RunSample("Example_DecryptWithPassword", [] {
			auto client = Samples::MakeClient();

			const std::string remoteName = "encrypted.xlsx";
			const std::string password = "123456";

			Samples::Section("Upload encrypted file");
			const std::string remotePath =
				Samples::Upload(client, Samples::Fixture(remoteName), remoteName);
			Samples::Ok("uploaded " + remotePath);

			Samples::Section("Decrypt file with password");
			auto encryption = std::make_shared<WorkbookEncryptionRequest>();
			encryption->SetPassword(password);

			auto request = DeleteDecryptWorkbookRequest::Create(remoteName, encryption);
			request->SetFolder(Samples::RemoteFolder());

			const auto response = client->Do(*request);
			if (!response.IsSuccess()) {
				throw std::runtime_error("decrypt failed with HTTP " +
										 std::to_string(response.GetStatusCode()) + ": " +
										 response.ToString().substr(0, 200));
			}

			Samples::Ok("decrypted " + remoteName);
		});
	}
```
{{% /blocks/products/cells/cells-cloud-showcode %}}



{{< blocks/products/cells/cells-cloud-available-sdks >}}





{{< /blocks/products/pf/main-container >}}


{{< blocks/products/cells/cells-cloud-resource-links >}}
{{< /blocks/products/pf/main-wrap-class >}}
