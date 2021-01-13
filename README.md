# 20487D_MOD05_LAK_EX1_BlueYonder.Flights.Service

JOSE VICENTE TEJERO - 06/01/2021

RESUMEN
**Module 5: Hosting Services On-Premises and in Azure**

**Lab: Host an ASP.NET Core service in a Windows Service**

 

**### Exercise 1: Creating an ASP.NET Core Application**

 

**#### Task 1: Create an ASP.NET Core application Project**

 

**![img](clip_image002.png)**

#### Task 2: Install the Microsoft.AspNetCore.Hosting.WindowsServices NuGet package

![img](clip_image004.png)

![img](clip_image006.png)



 

Task 3: Modify the Main method to use Kestrel RunAsService hosting

![img](clip_image008.png)

 

 

\### Exercise 2: Registering the Windows Service

\#### Task 1: Register the Windows Service

![img](clip_image010.png)

 

![img](clip_image012.png)

 

#### Task 2: Start the Windows Service and test it

 

![img](clip_image014.png)

![img](clip_image016.png)

![img](clip_image018.png)

 



 

 

# Lab: Host an ASP.NET Core Web API in an Azure Web App

### Exercise 1: Creating a Web App in the Azure Portal

#### Task 1: Run a setup script to upload a database to Azure

 

![img](clip_image020.png)

 

![img](clip_image021.png)

![img](clip_image022.png)

OutputsString      :

 

Server=tcp:blueyonder05-jvtc.database.windows.net,1433;Initial Catalog=BlueYonder.Flights.Lab05;Persist Security Info=False;User ID=BlueYonderAdmin;Password=Pa$$w0rd;MultipleActiveResultSets=False;Encrypt=True;TrustServerCertificate=False;Connection Timeout=180;

 

![img](clip_image024.png)

![img](clip_image025.png)

 



 

 

#### Task 2: Create a free website

 

![img](clip_image027.png)

![img](clip_image029.png)

#### Task 3: Configure an environment variable and the database connection string

 

![img](clip_image031.png)

#### Task 4: Configure IIS logs 

 

![img](clip_image033.png)

![img](clip_image035.png)

 

ftp://waws-prod-par-007.ftp.azurewebsites.windows.net/site/wwwroot

 

 

 

 

 

 



 

### Exercise 2: Deploying an ASP.NET Core Web API to the Web App

#### Task 1: Deploy an ASP.NET Core project to the web app

 

blueyonder-flights-jvtc 

**MyFlightAppService** 

![img](clip_image037.png)

 

 

![img](clip_image039.png)

 

![img](clip_image041.png)

![img](clip_image043.png)

#### Task 2: Test and verify the web app uses the database and environment variable

 

 

![img](clip_image045.png)

 

 

 

 

#### Task 3: Use the FTP Deployment server to view the web app and its log files

 

![img](clip_image046.png)

 

![img](clip_image047.png)

 

 

 

 

 

\# Lab: Host an ASP.NET Core service in Azure Container Instances 

\### Exercise 1: Publishing the service to a Docker container

![img](clip_image049.png)

![img](clip_image051.png)

Resultado:

![img](clip_image053.png)

#### Task 3: Push the container to a public container registry

 

Task 3: Push the container to a public container registry

![img](clip_image055.png)

 

![img](clip_image057.png)

 

 

![img](clip_image059.png)

 

 

![img](clip_image061.png)

 

 

 

 

 

### Exercise 2: Hosting the service in Azure Container Instances

#### Task 1: Create a Resource Group for Azure Container Instances

 

![img](clip_image063.png)

 

![img](clip_image065.png)

 

#### Task 2: Create an Azure Container Instance from the container image

 

![img](clip_image067.png)

 

![img](clip_image069.png)

 

![img](clip_image071.png)

"ipAddress": {

   "dnsNameLabel": "blueyonder-hotels-service-jvtc",

   "fqdn": "blueyonder-hotels-service-jvtc.eastus.azurecontainer.io",

 

![img](clip_image072.png)

   "ip": "20.75.216.169",

   "ports": [

​    {

​     "port": 80,

​     "protocol": "TCP"

​    }

   ],

   "type": "Public"

"ip": "20.75.216.169"

 

 

 

 

 

![img](clip_image074.png)

 

En Azure:

 

![img](clip_image076.png)

![img](clip_image077.png)



 

 

# Lab: Implement an Azure Function 

### Exercise 1: Developing the Service Locally

 

Task 1: Create a new Function App project in Visual Studio

![img](clip_image079.png)



 

![img](clip_image081.png)

 

![img](clip_image083.png)

 

#### Task 2: Implement an HTTP trigger that invokes the flights booking Web App

 

![img](clip_image085.png)

 

#### Task 3: Test the Function App locally in a browser

 

![img](clip_image087.png)

 

 

![img](clip_image089.png)

 

![img](clip_image091.png)

 



 

### Exercise 2: Deploying the Service to Azure Functions

#### Task 1: Deploy the service to Azure Functions from Visual Studio

 

![img](clip_image093.png)

 

![img](clip_image095.png)

 

![img](clip_image096.png)

 

Publicando:

![img](clip_image098.png)

 

#### Task 2: Test the Function App on Azure in a browser 

 

 

 

![img](clip_image100.png)

 

 

 

 
 

PROBLEMAS
No

