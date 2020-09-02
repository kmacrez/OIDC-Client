# OIDC-Client
sample oidc client using .net core 2

## Configure the Client Application

Open your web application in Visual Studio and open the file app.settings at the root of the web application. Locate the oauth/app section. 

Replace the **_authority_** with the _Oauth Endpoint_ from your tenant in CFS. (https://localhost:{port}/oauth/{tenant}).  
Replace the **_clientid_** with the _Application Key_ from CFS.  
Replace the **_clientsecret_** with the _Application Secret_ from CFS.  
