1.  Log in to the Azure portal with your Azure account credentials.
    
2.  Navigate to the Azure Active Directory service by searching for "Azure Active Directory" in the search bar or by selecting "Azure Active Directory" from the list of services.
    
3.  In the Azure Active Directory dashboard, select "App registrations" from the sidebar menu and then click "New registration".
    
4.  Enter a name for the application and select "Accounts in this organizational directory only" as the supported account type.
    
5.  Enter a redirect URI for the application. This can be any valid URL that you control, such as "[https://localhost](https://localhost/)".
    
6.  After creating the application registration, note down the "Application (client) ID" and "Directory (tenant) ID" values, which you will need to configure the Azure provider in your Terraform configuration file.
    
7.  In the application registration dashboard, select "Certificates & secrets" from the sidebar menu and then click "New client secret".
    
8.  Enter a description for the client secret and select an expiration date. Note down the value of the client secret, as you will need to configure the Azure provider in your Terraform configuration file.
    
9.  Assign a role to the service principal so that it has the necessary permissions to manage resources in your Azure subscription. Go to Active directory services and select Global Administrator.
    

By following these steps, you can create an Azure service principal and configure the necessary credentials to connect to Azure from Terraform.


<style>
body {
    background-color: #f2f2f2;
    color: #333;
    font-size: 16px;
}

h1, h2, h3, h4, h5, h6 {
    color: #2f4f4f;
}

table {
    border-collapse: collapse;
    width: 100%;
}

table td, table th {
    border: 1px solid #ddd;
    padding: 8px;
}

table th {
    text-align: left;
    background-color: #f2f2f2;
}

a {
    color: #008080;
}

</style>
