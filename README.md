*** IN CASE BE NECESSARY, REQUEST ACCESS TO FULL SOFTWARE DOCUMENT ***

1. INTRODUCTION
   THIS IS A FICTIONARY PROJECT USED AS PORTFOLIO

   In a market more and more competitive and in constant evolution, the operative eficience is fundamental for any enterprise.
   This software solution approaches the problem of any dedicated package delivery enterprise can face,
   from logistic processes optimization problems which impede to satisfy customers expectations and keep a reliable market position,
   to reduction of incomes and quality uneficience of delivery services.
   This software brings an integral tool to optimize all stages of package delivery process, from reception of request
   to final delivery.

   This document offers a general outlook of softwre development process, its key characteristics and
   supossed benefits for the enterprise.

   2. BUSINESS DESCRIPTION AND REQUIREMENTS
  
      Was devised a solution for an enterprise who has this structure:
      . distributes 3 types or packages (fragile, commom and bulk) using as transport automovile, motorbike and / or truck.
      . System´s users are: Employee (Driver, Administrative) and Customers.
      For authentication are required usar and access password.
      After logged in, will access to DB with an SQL User asociated to that logged user.

      ROLE OF EACH USER INTO THE SYSTEM
      2.1. Primary actors
      As following are detailed the actors and tasks assigned to each one into de System.

      Driver: 
      ● Package state change
      ● Login

      Administrative:
      
      ● Administrative´s CRUD
      
      ● Driver´s CRUD
      
      ● Enterprise´s CRUD
      
      ● Package´s CRUD
      
      ● Vehicle´s CRUD
      
      ● Request´s CRUD
      
      ● Driver´s sanctions and suspentions
      
      ● Penalty fee´s registration (asociated to a vehicle and driver)

      3. TECHNOLOGIES
         
         3.1 BACK END AND SERVICE
         
         3.1.1 SQL SERVER 2014
         
         Pros of using this technology
         1 - Scalability: SQL SERVER is well knowed for being capable by handle big data          quantity and vertical and horizontal scalability. It can grow up depending on            application´s needings.

         2 - Security:
         Offers data cyfer, integrated authentication and access control. Is fundamental          to protect sensitive data confidenciality.
         
         3 - Integration with other Microsoft´s tools:
         SQL SERVER integrates well with other Microsoft's tools, like .NET Framework,            Visual Studio development and Azure. All this allows to develop and to                   implement complete solutions.

         4 . Database administration:
         Offers a huge diversity of administrative tools tasking backup, as security              copies, recovering against disasters, database maintenance and queries         optmimization.

         Contras of using this technology:

         1 - Cost:

         Can be costous, specially for small enterprises and startups. Also powerfull hardware could be required.

         2 - Specific platform:

         Can be excuted on Windows and Linux, but is specific of Windows. This can limitate flexibility.

         3 - Learning curve:

         For new users, learning curve can be high.

         4 - Hardware requirements

         Can require a significative amount of hardware and software resources, becoming a challenge to small enterprises.

         Why SQL SERVER ??

         This technology became efective at development stage and set on function the database. The learning curve was almost nule due the previous experience and was not powerfull hardware needed to execute it. This technology offered great value to the project.

   3.1.2 IIS SERVER HOSTED LOCALLY

   1 - Integers very well with Windows and is the option by default to hosting of Web applications on Windows environment.

   2 - Performance

   Has a solid performance and is capable to handle heavy duty tasks. Is optimized to work with Microsoft technologies.

   3 - Security

   Offers many security options, like integrated authentication, roles based authentication, SSL/TLS encryption, protection against atacks.

   4 - Administration tools

   Offers strong admnistrative tools, like IIS administrator.

   - Learning curve
  
     As previous experience, learning for this project was not necessary.

     This technology was choosen because currently applications are developed as Microsoft native applications, and this server is ideal.

URL's server: https://ansuz.ddns.net


3.3. FRONT END

3.3.1. Xamarin

1 - Multiplatform development:

Xamarin allows mobile apps, iOS, Android and Windows development using an unique C# base code, based on the adquired knowledgements along the career.

2 - Complete access to native APIs of each platform (iOS, Windows and Android) using native SDKs.

3 - Code reutilization

Xamarin uses an unique programming language (C#) and an unique base code. It can be reuse a big portion of code between platforms (Windows, iOS and Android), increasing development process speed and reducing costs. 

4 - Integration with Visual Studio:

Xamarin integers perfectly with Visual Studio, allowing access to all development tools.

1 - Learning curve

For this project the learning curve was big, due to previous unknowledgement of APIs development

2 - Compatibility and actualizations

Compatibility problems, cos depends on native platforms iOS and Android changes and actulizations. 

Why was choosen??

. Because language C# is already knowed.

. Is multiplatform, iOS and Andorid APIs can be accessed.

. Once Xamarin fundations are dominated, is a language with a big potential.

3.3.2. WEB Site

ASP.NET MVC technology was choosen due its numerous banefits and capacities.
Offers an structured and flexible focusing for Model - View - Controller web development patron.
 Allows to clearly separate responsabilities, making easy code maintenance and colaboration in development team.

 Why ASP.NET ?

 Allows to control HTML, CSS and JavaScript creation to personalize user interface. Making use of this hability to integrate libraries and frontend frameworks, was the way to fusionate Razor code with JavaScript to show up the map to register a new Package.

 3.4. SUPPORT TECHNOLOGIES

 3.4.1 SOFTWARE

 3.4.1.1. IDE

 3.4.1.2 VISUAL STUDIO 2022

 1 - Visual Studio offers a complete integrated development environment, that includes code edition tools, depuration, compilation and projects management. 

 2 - Multiplatform support:

 Visual Studio is compatible with a wide range of technologies, like: 
 C#, .NET, C++, JavaScript, Python, and a lot more. 
 Allows development to diferent platforms: Windows, web, mobiles and cloud.


3 - Wide community and support

Has a big developer's community and a wide learnig sources platform, documentation and on line support.


Wny was choosen ?

Because there was previous experience programming in C#, and to programming in Android was too much friendly. 
   

3.4.1.2.2. Windows virtualization

3.4.1.2.2.1 VMWare

1 - Virtualization is very eficient, emulating perfectly Windows OS that was used in this project.

2 - Wide compatibility

Is compatible with too much operating systems.

3 - Advanced functions:

Offers characteristics like hot migration (move a virtual machine to a new host without shutdown the virtual machine), high availability, recovering against disasters, etc. 

4 - In virtualization are efectively executed:

- IIS server
- SQL Server DB consumed by web site and Api
- Web Site that consumes DB
- API consumed by Mobile App


3.4.1.3 NO IP
This software was used to transform dinamic IP into an static IP, that is necessary to access from Internet to IIS server and its applications.

Advantages of using this technology:

1 - Easy configuration

Posible risks of using this technology:

1 - Posible reliability problems: depend on a third party service to assing a domain name to an static IP address, exists the risk of posible shutdown service.

2 - Security: to use a DNS dinamic service is necessary to set up security on devices and connected services, specially when are accesed from Internet.

Was used because is the ideal option to obtain an static IP.

3.4.1.4. Google Maps API

Google Maps API integration on projet was choosen because is an powerfull option to take advantage of mapping and geolocation services.
Offers a wide set of functionalities, from visualization of interactive maps to rutes and geoloaction. This makes easy the Driver´s task to moment to manage package pickups and deliveries. Is supported by Google´s service and infraestructure, that secure to be always available and to have and optimum performance. Is the ideal option for this project.

3.4.1.5 JMETER

The charge and stress tests are fundamental technics in software development to evaluate the performance of an application in simulated charge conditions.
JMeter is an open source tool developed by Apache and is very popular to execute this tests.
JMeter simulate the real user behaviour interacting with the System on simultaneous way increasing too much the working charge on the systems. Is useful to evaluate the performance of the System on limit conditions reaching its maximum capacity 






