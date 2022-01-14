# CP
Customer portal

This is Model view controller for GTV SOAP APIs

SVCUTIL generate code from static metadata (WSDL files)
typical command for WSDL is = svcutil [sourceWSDLFolder]\WSDLFile.WSDL /sc /wrapped /out:[SourceClassFolder]/WSDL_Class.cs

Model : Models\ContactViewModel.cs : returns instances from  INSITE_CP classes
View: Views\InsiteTest\gtvAccountData.cshtml
Controller: Controllers\InsiteTestController.cs

Insite_CP classes: cut down version of SOAP classes to take only whats needed from GTV SOAP classes like name, address, email, balance, etc...

WSDL files and docs

http://GTVUAT:5602/MOD/WEBSERVICES
+   MOD/WEBSERVICES/GTV:EBC.CUSTOMER?version=2&edition=5
            MOD/WEBSERVICES/GTV:EBC.INSTALL?version=2&edition=5
            MOD/WEBSERVICES/GTV:EBC.LEDGER?version=2&edition=5
	    MOD/WEBSERVICES/INSS:ACCOUNT.HELPER?version=1&edition=5
            MOD/WEBSERVICES/INSS:CONSUMER.HELPER?version=1&edition=5
            MOD/WEBSERVICES/LAM:METER?version=2&edition=5
            MOD/WEBSERVICES/INSS:METER.HELPER?version=1&edition=5
            MOD/WEBSERVICES/INSS:TRANSACTION.HELPER?version=1&edition=5
            MOD/WEBSERVICES/JBI:LEDGER?version=1&edition=5
            MOD/WEBSERVICES/CCA:CUSTOMER.BRAND?version=1&edition=5
            MOD/WEBSERVICES/CCA:ACCOUNT?version=4&edition=5
            MOD/WEBSERVICES/CCD:CUSTOMER.ROLE.TYPE?version=1&edition=5
            MOD/WEBSERVICES/CCD:CUSTOMER.ROLE?version=1&edition=5
            MOD/WEBSERVICES/IIA:INSTALL?version=2&edition=5
            MOD/WEBSERVICES/LAA:ASSET?version=1&edition=5
            MOD/WEBSERVICES/INSS:CUSTOMER.HELPER?version=1&edition=5
            MOD/WEBSERVICES/CCD:CUSTOMER?version=2&edition=5


