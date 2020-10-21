# Azure Core Services

![Microsoft AZ-900 Azure Fundamentals Exam - Digital Thought Disruption](https://digitalthoughtdisruption.com/wp-content/uploads/2020/01/image.png?w=389)



## 1 Co jest w datacenter?

![Microsoft Data Centers | Motion design animation, Animation design, Motion  design](https://i.pinimg.com/originals/95/fa/54/95fa543775583cad8944f0fafa9f7d73.gif)

Podstawą będzie zrozumienie jak są budowane datacenters. Tutaj Mark Russinovich - CTO od Azura wyjaśnia. 

Wideo do obejrzenia[![Inside Azure datacenter architecture with Mark Russinovich](https://medius.studios.ms/video/asset/THUMBNAIL/B19-BRK3060?v=fd44debf50eb7819526783423d1eba3bef7235c1d6c04fc7e716cd984e4d2186)](https://azure.microsoft.com/en-us/resources/videos/build-2019-inside-azure-datacenter-architecture-with-mark-russinovich/?WT.mc_id=AZ-MVP-5003556) 



## 2 High level tour of Azure services 

- do przerobienia https://docs.microsoft.com/en-us/learn/modules/welcome-to-azure/3-tour-of-azure-services

- Azure Periodic Table https://azureperiodic.data3.com/ 

  ![The Azure Periodic Table - Data#3](https://www.data3.com/wp-content/uploads/2019/12/azure-blog-4-e1588117736708.png)

- Mając zbudowaną high level mapę serwisów, możemy zejść poziom niżej.



Bardzo dobre nagrania, wyjaśniające kluczowe koncepty cloud computingu jak i serwisy na Azure, nagrał Adam Marczak - Architect z firmy partnerskiej Microsoftu - Lingaro.  



## 3 Azure Regions and Availability Zones

![Building solutions for high availability using Availability Zones - High  Availability | Microsoft Docs](https://docs.microsoft.com/en-us/azure/architecture/high-availability/images/high-availability-001.png)

![Azure Launches Availability Zones in GA, Catching Up to Rivals | Data  Center Knowledge](https://www.datacenterknowledge.com/sites/datacenterknowledge.com/files/azure-availability-zones_0.jpg)

- Wideo do obejrzenia

  [![](http://img.youtube.com/vi/C-nNw1mGwzE/0.jpg)](http://www.youtube.com/watch?v=C-nNw1mGwzE "")

- Sprawdźcie do którego datacenter macie najbliżej - http://azurespeedtest.azurewebsites.net/ - i o czym mówi "latency"

- koniecznie do przerobienia - https://docs.microsoft.com/en-us/learn/modules/explore-azure-infrastructure/ - zrozumienie rozłożenia datacenter, regionów, availability zones, parowania regionów i SLA jest kluczowe w pracy z Azure i będzie dużo pytań o to na AZ-900. 



## 4 Azure Portal Tour 

- do przerobienia https://docs.microsoft.com/en-us/learn/modules/tour-azure-portal/

 ![An animated gif of the Azure portal. | Azure, Microsoft, Hosting services](https://i.pinimg.com/originals/70/da/dc/70dadc873c16a014ac7f0a824cdf7831.gif)



## 5 Azure Resource Groups and Resource Manager

![Create workspaces in the portal - Azure Machine Learning | Microsoft Docs](https://docs.microsoft.com/en-us/azure/machine-learning/media/how-to-manage-workspace/create-workspace.gif)



Zasoby grupujemy w Resource Groups. Zasoby tworzą architektury. Możemy eksportować definicję zasobu w postaci definicji JSON, tak by później przy zastosowaniu praktych DevOps automatyzować stawianie zasobów.

Wideo do obejrzenia: 

​	[![](http://img.youtube.com/vi/gIhf-S7BCdo/0.jpg)](http://www.youtube.com/watch?v=gIhf-S7BCdo "")

- więcej o automatyzacji https://youtu.be/Ge_Sp-1lWZ4



## 6 Azure Compute Services: VM, VM Scale set, App Service, Functions, Container Instance, Kubernetes Service

Mówi się, że podstawową jednostką na chmurze jest wirtualna maszyna - Virtual Machine. Na Azure jest sporo różnych możliwości uruchamiania aplikacji - czasem będzie potrzebna VMka, ale gdy mamy kontener dockerowy, to może Azure Container Instances albo Azure Functions będzie lepszym wyborem. 

![Azure Content Spotlight - Virtual Machine Serial Console (Preview) -  Microsoft Tech Community](https://techcommunity.microsoft.com/t5/image/serverpage/image-id/74074i8F8354A1CD037772)

Wideo do obejrzenia:

​	 [![](http://img.youtube.com/vi/inaXkN2UrFE/0.jpg)](http://www.youtube.com/watch?v=inaXkN2UrFE "")

- do przerobienia materiał na microsoft learn https://docs.microsoft.com/en-us/learn/modules/intro-to-azure-compute/





## 7 Azure Networking Services: Virtual Network (VNet), Load Balancer, VPN Gateway, Application Gateway, Content Delivery Network (CDN)

Wideo do obejrzenia: 

​	[![](http://img.youtube.com/vi/5NMcM4zJPM4/0.jpg)](http://www.youtube.com/watch?v=5NMcM4zJPM4 "")



![What Are Azure Virtual Networks | Aidan Finn, IT Pro](https://acomdpsstorage.blob.core.windows.net/dpsmedia-prod/azure.microsoft.com/en-us/documentation/articles/virtual-networks-overview/20150915062503/figure02.png)

- architektura powyżej do przejrzenia. Należy zwrócić uwagę, co jest w VNecie (Virtual Network), co rozrzuca ruch - Load balancer, i w czym są "spięte" np. bazy danych - NSG.
- do przerobienia materiał na microsoft learn https://docs.microsoft.com/en-us/learn/modules/intro-to-azure-networking/





## 8 Azure Storage Services: azure storage account, disc storage

Jeśli VMka jest podstawową "jednostką" computingu na Azure, to jaki serwis będzie podstawową usługą do przetrzymywania danych? 



![Azure Storage Types and Use Cases - Dremio - Dremio](https://www.dremio.com/img/explained/azure-storage/image_0.png)

![Azure Storage Services – Storage account – 4sysops](https://4sysops.com/wp-content/uploads/2016/04/Storage-account-architecture.png)



![Managing and implementing Azure storage – DB Cloud TECH](https://mostafaelmasry.files.wordpress.com/2020/03/azure-storage.png?w=712)

Kluczowe nagranie z perspektywy tworzenia jakichkolwiek aplikacji na Azure. Wideo do obejrzenia:

​	[![](http://img.youtube.com/vi/_Qlkvd4ZQuo/0.jpg)](http://www.youtube.com/watch?v=_Qlkvd4ZQuo "")



Wideo do obejrzenia:

​	[![](http://img.youtube.com/vi/UzTtastcBsk/0.jpg)](http://www.youtube.com/watch?v=UzTtastcBsk "")



![What's new in Azure Data Lake Storage Gen2](https://www.mssqltips.com/tipimages2/5986_whats-new-azure-data-lake-storage-generation-2.010.png)

Wideo do obejrzenia:

​	[![](http://img.youtube.com/vi/2uSkjBEwwq0/0.jpg)](http://www.youtube.com/watch?v=2uSkjBEwwq0 "")



- do przerobienia 25minutowy moduł: https://docs.microsoft.com/en-us/learn/modules/intro-to-data-in-azure/



## 9 Azure Database Services: cosmos db, sql databases, Azure database for MySQL, Azure Database for PostgreSQL

Pliki możemy trzymać na Blobie, ale czego użyć, gdy potrzebna jest baza relacyjna lub dokumentowa?

Wideo do obejrzenia:

​	[![](http://img.youtube.com/vi/RqD4nMyBazU/0.jpg)](http://www.youtube.com/watch?v=RqD4nMyBazU "")

- do przeczytania dokumentacja pomagająca zrozumieć kiedy jaki serwis użyć do przetrzymywania danych https://docs.microsoft.com/en-us/learn/modules/intro-to-data-in-azure/3-how-azure-storage-meets-your-business-storage-needs

![SQL Server 2017 e Azure SQL Managed Instance - Dirceu Resende](https://www.dirceuresende.com/wp-content/uploads/2017/04/azuremanagedinstanec.png)



## 10 Azure IoT Services

![Piramal Glass adopts Microsoft's Azure IoT to boost operational efficiency](https://assets.techcircle.in/uploads/article-image/2018/11/images/17151-16052-iot-1.gif)

![Processar dados de veículos em tempo real com a IoT - Azure Architecture  Center | Microsoft Docs](https://docs.microsoft.com/azure/architecture/example-scenario/data/media/architecture-realtime-analytics-vehicle-data1.png)

Wideo do obejrzenia:

​	[![](http://img.youtube.com/vi/RHkqFxJWhr8/0.jpg)](http://www.youtube.com/watch?v=RHkqFxJWhr8 "")



## 11 Azure Big Data and Analytics

Wideo do obejrzenia:

​	[![](http://img.youtube.com/vi/JUQXx0R0RfE/0.jpg)](http://www.youtube.com/watch?v=JUQXx0R0RfE "")





Azure Synapse to przyszłość, będziemy o nim rozmawiać. Na teraz zapoznajcie się bliżej z super użytecznym serwisem - Azure Databricks. 

Tutaj rysunek pokazujący co w nim jest możliwe:

![What is Azure Databricks? | James Serra's Blog](https://i2.wp.com/www.jamesserra.com/wp-content/uploads/2017/11/DataBricks1.png?resize=1947%2C1075&ssl=1)



Dlaczego Azure Synapse to przyszłość? 

![Simplify Data Analytics with Azure Synapse - Adatis](https://adatis.co.uk/wp-content/uploads/Synapse-Simplify-v3.gif)



## 12 Azure AI and ML 

![Installing Azure ML Estimator Dependencies from Remote GitHub Branches | by  Aaron (Ari) Bornstein | Microsoft Azure | Medium](https://miro.medium.com/max/3032/1*mrMYpVE62e5_a-Uy1I389g.png)

To wstęp do tematów, które będą poruszane po części przygotowawczej do AZ-900, czyli do AI i ML-a. Koniecznie należy zrozumieć co robi Azure Machine Learning i jak z niego korzystać. Wideo do obejrzenia:

​	[![](http://img.youtube.com/vi/8aMzR8iaB9s/0.jpg)](http://www.youtube.com/watch?v=8aMzR8iaB9s "")

![GitHub - Azure/MachineLearningNotebooks: Python notebooks with ML and deep  learning examples with Azure Machine Learning | Microsoft](https://raw.githubusercontent.com/MicrosoftDocs/azure-docs/master/articles/machine-learning/media/concept-azure-machine-learning-architecture/workflow.png)





## 13 Azure Serverless Computing

Jeśli chcemy uruchomić funkcję albo zbudować flow funkcji to nie musimy iść w toporne narzędzia uruchamiane w kontenerach lub na VMkach. Od tego jest serverless computing i kilka usług jakie daje Azure. Szczególnie polecam zapoznać się z Azure Functions i Azure Logic Apps. Wideo do obejrzenia:

​	[![](http://img.youtube.com/vi/ansa4M7iTmg/0.jpg)](http://www.youtube.com/watch?v=ansa4M7iTmg "")



Przykłady architektur:

![Serverless Microservices reference architecture - Code Samples | Microsoft  Docs](https://docs.microsoft.com/en-us/samples/azure-samples/serverless-microservices-reference-architecture/serverless-microservices-reference-architecture/media/macro-architecture.png)



![Implementing a Serverless Architecture | David Chou](https://dachou.github.io/assets/20181107-architecture-application.png)



## 14 Azure DevOps 

![Building Pipeline with Microsoft Azure DevOps - XenonStack](https://www.xenonstack.com/images/blog/2019/11/microsoft-azure-devops-pipeline-xenonstack.png)

Jeśli korzystaliście z Jenkins, Teamcity, Travis CI czy innego narzędzia pozwalającego na budowanie i deployment aplikacji na dane środowisko, to użycie Azure DevOps będzie dla Was banalne. W tej części skupiamy się właśnie na serwisie Azure DevOps i jego możliwościach, które z jednej strony pozwolą na  przetrzymywanie (repozytorium) kodu, zarządzanie pracą zespołu i ticketami (JIRA), a z drugiej na budowanie pipelines do testowania i releases aplikacji.  

Wideo do obejrzenia:

​	[![](http://img.youtube.com/vi/8M4DN9hjAeY/0.jpg)](http://www.youtube.com/watch?v=8M4DN9hjAeY "")



![Azure DevOps - manage your application life cycle in cloud](https://subhankarsarkar.com/wp-content/uploads/2018/09/Azure-DevOps-SubhankarSarkar.png)



## 15 Mapy myśli - mindmap  

- Interaktywna - https://www.mindmeister.com/1644491891/azure-az-900-fundamentals?fullscreen=1 
- bardzo dobrze rozbudowane koncepty i usługi w Azure https://www.shanebart.com/wp-content/uploads/2019/09/AZ-900.pdf
- sporo trudniejsza bo wiele pojęć może być dla niektórych nieznanych - https://techcommunity.microsoft.com/t5/image/serverpage/image-id/162827i36D7ACCB57356775?v=1.0 - mapka dla osób, chcących więcej 



AZ-900 daje solidne podstawy i otwiera drogę do  

![Exam AZ-304: Microsoft Azure Architect Design | Testprep Training](https://www.testpreptraining.com/tutorial/wp-content/uploads/2020/07/Azure_Certification_Path1.png)

