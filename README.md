# What is SASE?
--------------
SASE stands for Secure Access Service Edge, which is essentially a modern approach to networking and security. It combines network connectivity with security features, all delivered as a cloud-based service




# SASE with Zscaler
--------------
For the Zscalar, The using **"Zscaler App Connector/Zscaler Client Connector"** to connect to **Edge service node of Zscaler** to using service such as Internet Access and private resource on premise.

Zscaler have 3 modules for provide SASE service.
### 1. ZIA:Zscaler Internet Access™

The ZIA module enables clients to access the internet through Zscaler's edge nodes, enforcing policies such as URL filtering, threat prevention, DNS security, and more.

### 2. ZDX:Zscaler Digital Experience™
The ZDX module provides insights and analytics into network performance, application usage, and user experience, allowing organizations to identify and resolve issues quickly. By monitoring and analyzing data from various sources, including the Zscaler cloud and user devices, ZDX helps businesses improve the performance and reliability of their digital services, ultimately enhancing productivity and satisfaction for end-users

### 3. ZPA:Zscaler Private Access™

The ZPA module enables the connection of private on-premises services with the Zscaler cloud. It utilizes the 'App Connector' to allow clients to access on-premises services securely when connected to the SASE environment.



# How to access management of Zscaler
--------------
To access the management of Zscaler, as it is a SASE service platform, you can configure or check your tenant by following the link and logging in.

- ZIA Login URL: https://admin.zscalerthree.net

<div style="display: flex; justify-content: space-between;">
      <div style="flex: 50%; padding: 5px;">
        <img src="https://private-user-images.githubusercontent.com/48705342/323123880-280fcc70-5c65-4a34-b803-5a1a728181e5.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzMzk1NDYsIm5iZiI6MTcxMzMzOTI0NiwicGF0aCI6Ii80ODcwNTM0Mi8zMjMxMjM4ODAtMjgwZmNjNzAtNWM2NS00YTM0LWI4MDMtNWExYTcyODE4MWU1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE3VDA3MzQwNlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTZmYzg1NjkxMTYyNzZjYTYwNTlmNGY4ZTQyMzNiODE5ZDRlZjJjY2M2M2MzODJhZGUxY2E3NTAzNTQ2MWJlMzcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.aodTLaPLNbNhHvInhSqJPu2FyqFVdO2knbdHBKFbCAk" alt="loginpage" style="width: 50%;">
        </div>
      <div style="flex: 50%; padding: 5px;">
        <img src="https://private-user-images.githubusercontent.com/48705342/323123515-4d939298-4f12-494f-9b49-27061f81a4ce.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzMzk1NDYsIm5iZiI6MTcxMzMzOTI0NiwicGF0aCI6Ii80ODcwNTM0Mi8zMjMxMjM1MTUtNGQ5MzkyOTgtNGYxMi00OTRmLTliNDktMjcwNjFmODFhNGNlLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE3VDA3MzQwNlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWRkZTlmMzcyNzkxZWUxOWE5MjdhZjkwM2Q0ZTY2OTVjYTkwYWEwNGU0MTQ3OGEzYjQwNzQxYTQ2N2UxOGMzNjQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.OfqBBwZruYt1Js0aEvTMrO8tZvx3CZXXcUPOlEICgt0" alt="Dashboard" style="width: 50%;">
        </div>
</div>


- ZDX Login URL: https://admin.zdxcloud.net

<div style="display: flex; justify-content: space-between;">
      <div style="flex: 50%; padding: 5px;">
        <img src="https://private-user-images.githubusercontent.com/48705342/323129608-019d511f-fcd6-4c69-aa5a-b163c03f397d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzNDA2MTUsIm5iZiI6MTcxMzM0MDMxNSwicGF0aCI6Ii80ODcwNTM0Mi8zMjMxMjk2MDgtMDE5ZDUxMWYtZmNkNi00YzY5LWFhNWEtYjE2M2MwM2YzOTdkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE3VDA3NTE1NVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWRkZDZhNTQ0Mjg3Y2EyZTAxYjI5ZGJkMmNmOWNhZDUyOWU5YTliM2RhMDYyMTI1ZjhiMDA1MDQ4ZGJjODMwN2UmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.THCGuqASKVbsnHbDRhlotIS3QaGwcwg3EeP9L2_OrVg" alt="ZDXLoginPage" style="width: 50%;>
        </div>
      <div style="flex: 50%; padding: 5px;">
        <img src="https://private-user-images.githubusercontent.com/48705342/323129595-216071f4-fe36-4455-b3cf-1882c39f0dc8.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzNDA2MTUsIm5iZiI6MTcxMzM0MDMxNSwicGF0aCI6Ii80ODcwNTM0Mi8zMjMxMjk1OTUtMjE2MDcxZjQtZmUzNi00NDU1LWIzY2YtMTg4MmMzOWYwZGM4LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE3VDA3NTE1NVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTA3M2MzMTkyZTQwYTczNmU3Njk4Y2Y3NDQ4YTE5OWU0NDY0YTdjYTE3Y2FmNGE0NjRlMTM3NWJkMDZhN2JmMmImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.1IaH7dU9fRJkkMwe3TtSEJaP0q0xmAIkDrxYbGtqTIM" alt="zdxdashboard" style="width: 50%;>
        </div>
</div>


- ZPA Login URL: https://admin.private.zscaler.com

<div style="display: flex; justify-content: space-between;">
      <div style="flex: 50%; padding: 5px;">
        <img src="https://private-user-images.githubusercontent.com/48705342/323125474-f174c047-eeda-448b-8fe9-8180fdbb3cee.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzMzk4NDksIm5iZiI6MTcxMzMzOTU0OSwicGF0aCI6Ii80ODcwNTM0Mi8zMjMxMjU0NzQtZjE3NGMwNDctZWVkYS00NDhiLThmZTktODE4MGZkYmIzY2VlLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE3VDA3MzkwOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWI3MGUwYjMyN2NkY2VmNDBjMDMxYzA1Y2JhMDE0Y2FhNjU2NTdkODkzZWM1MzJhMzk0ZTA2MGEyYzIyM2JmZTkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.cv2-We60PU41b0ZQDms1soo-wcSTsT55LMYpy78TiQw" alt="ZPA Login" style="width: 50%;>
        </div>
      <div style="flex: 50%; padding: 5px;">
        <img src="https://private-user-images.githubusercontent.com/48705342/323126047-98b96104-9445-4cf0-a6f2-a7699a04dab6.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzMzk5NTQsIm5iZiI6MTcxMzMzOTY1NCwicGF0aCI6Ii80ODcwNTM0Mi8zMjMxMjYwNDctOThiOTYxMDQtOTQ0NS00Y2YwLWE2ZjItYTc2OTlhMDRkYWI2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE3VDA3NDA1NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWFmNjc1YjhkMDI2YmQ1NTQ4NDk2MDQ0MzE4ZGZiZWEwOGQ1NTRiMTBhMGFkYWYxYjgxNjc3NWFiYzU5NTQ1ODAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.jcxYy5Bk2xaGUsolCiVNjIWMHQPGTrVXAfTIyhQ_3ic" alt="ZPA Dashboard" style="width: 50%;>
        </div>
</div>

- ***Note: GUI may change depending on the version of Zscaler Cloud Management.*** You can check the version at the bottom left corner of the cloud management page.
![Alt Text](https://private-user-images.githubusercontent.com/48705342/323123533-c6d1f108-968b-4066-8f0d-4543dfe3db75.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzMzk1NDYsIm5iZiI6MTcxMzMzOTI0NiwicGF0aCI6Ii80ODcwNTM0Mi8zMjMxMjM1MzMtYzZkMWYxMDgtOTY4Yi00MDY2LThmMGQtNDU0M2RmZTNkYjc1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE3VDA3MzQwNlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWE4MTkzNGE4MzBjNWUwMGI0ZmFkNzIyYzJlZWEzZDk4MjMxMjI1ZGI4MzIxNjUzYTMwNmEwNDY2YTQ4NjJlMmYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.KYE8SgNeJIorJRlD9pj8mZOeSHhgjSsPWWKsB1-brfI)