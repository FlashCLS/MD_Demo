1.  Log in to the AWS Management Console with your AWS account credentials.
    
2.  Navigate to the IAM service by searching for "IAM" in the search bar or by selecting "IAM" from the list of services.
    
3.  In the IAM dashboard, select "Users" from the sidebar menu and then click "Add user".
    
4.  Enter a name for the IAM user and select "Programmatic access" as the access type.
    
5.  On the next page, select the permissions that you want to grant to the IAM user. You can either select an existing policy or create a custom policy to grant specific permissions to the user.
    
6.  Review the user details and permissions on the next page and then create the user.
    
7.  On the final page, you will see the IAM user's access key ID and secret access key. These are the credentials that you will need to configure the AWS provider in your Terraform configuration file.
    

Note: Make sure to securely store the IAM user's access key ID and secret access key, as they are sensitive credentials that provide full access to your AWS resources. It is best practice to store these credentials in a secure location such as a password manager or a secrets management system.

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
