Nikki Shakeraneh						<br>			 April 1, 2025
# Lab 4: Azure Key Vault Exploration

## Questions

1. What are the benefits of using Azure Key Vault in application development? 
    * Utilizing Azure Key Vault is a secure way to manage sensitive data such as API keys and passwords, This reduces the risk of unintentional leaks in code. It integrates well with Azure services, and it supports automated key rotation. This is when secrets are regularly updated without any manual intervention to enhance security. It also makes credential management easier to use, because it allows access through managed identities. This improves overall security and it simplifies secret handling in development workflows.

2. What security measures does Key Vault offer? 
    * Azure Key Vault offers multiple levels of security, including data encryption, role-based access control (RBAC), and detailed access policies that restrict who can manage or access secrets. It supports soft delete and purge protection, which prevents data loss. It also allows network access restrictions for using firewalls or private endpoints. Managed identities can additionally enhance security by removing the need to store credentials in application code.

3. How can Azure Key Vault help in managing application configurations securely?
    * Azure Key Vault allows applications to securely retrieve configuration values without storing them in code or environment files. These values can either be connection strings or API tokens. By using managed identities, applications can authenticate to Key Vault securely and dynamically fetch configurations at runtime. This prevents credential leaks, and also simplifies secret rotation, which ensures consistent configuration management across environments.

## Screenshots
  * Created Key Vault
    
  ![image](https://github.com/user-attachments/assets/33e349ed-3bce-4e24-a327-5f9805523f6a)

<br>

  * Key Vault secrets
    
![image](https://github.com/user-attachments/assets/a31ad4fc-16da-40c3-8552-434589677c44)

<br>

  * Permissions confirming the Azure account access
    
    ![image](https://github.com/user-attachments/assets/34e26ce2-922b-428f-97bd-350bbde6e652)

<br>

  * Sample input, output from the application
    
    ![image](https://github.com/user-attachments/assets/82c903cf-e834-40f0-bc0a-91160affad47)

    <br>

  * Each Individual Secret
    ![image](https://github.com/user-attachments/assets/820dd35a-5d7e-4616-b8c4-77a7e53f85d4)
    ![image](https://github.com/user-attachments/assets/653e9b0a-9f93-4390-b6bc-32c3d7eeb8f1)
    ![image](https://github.com/user-attachments/assets/40482e81-d70c-42e1-9c70-25c1314a7d57)
    ![image](https://github.com/user-attachments/assets/18150e60-fd44-4557-821b-fd7b181d0c5e)
    ![image](https://github.com/user-attachments/assets/4feb2a0a-9b14-45a0-80f5-c8460c229472)
    ![image](https://github.com/user-attachments/assets/245382e7-5f4d-4217-bc60-bd226f0cca5c)
