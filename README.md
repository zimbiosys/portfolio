# portfolio
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

     3.3. FRONT END

3.3.1. Xamarin

1 - Multiplatform development

Xamarin allows mobile applications development for iOS, Android 
   
         
      
      
