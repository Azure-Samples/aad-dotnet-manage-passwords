---
page_type: sample
languages:
- csharp
products:
- azure
services: Graph-Rbac
platforms: dotnet
author: yaohaizh
---

# Getting started on managing passwords using C# #

          Azure Service Principal sample for managing Service Principal -
           - Create an Active Directory application
           - Create a Service Principal for the application and assign a role
           - Export the Service Principal to an authentication file
           - Use the file to list subcription virtual machines
           - Update the application 
           - Delete the application and Service Principal.


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/aad-dotnet-manage-passwords.git

    cd aad-dotnet-manage-passwords

    dotnet build

    bin\Debug\net452\ManageServicePrincipalCredentails.exe

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.