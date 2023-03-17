<p align="center">
  <img style="width:100%" src="./img/ASP.NETMVCANDBootstrap2.png">
</p>

<h3 align="center">:weight_lifting: ASP.Net MVC and Bootstrap Frameworks for Developing Web Applications</h3>

<p align="center">
  Welcome to the ASP.Net MVC and Bootstrap seminar/training.
</p>

## :wrench: Requirements
- [x] 1. Visual Studio Community 2022
  - [Download Link](https://visualstudio.microsoft.com/vs/community/)
- [x] 2. SQL Server Management Studio (SSMS)
  - [Donwload Link](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16)
- [x] 3. SQL Server Management Studio Express
  - [GUIDE](https://www.sqlshack.com/how-to-install-sql-server-express-edition/)
  - [Download Link](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- [x] 4. [Somee](https://somee.com/doka) account
- [ ] 5. GitHub Account (Not Required but good to have)

# :clock10: First Session

<p align="center">
  <img height="100" src="https://devmaster.edu.vn/uploads/images/2020/08/0408/devmaster-asp-net-mvc.jpg">
  <img height="100" src="https://www.drupal.org/files/project-images/bootstrap-stack.png">
</p>

<h3 align="center">1st Session - ASP.NET MVC and Bootstrap/Bootswatch</h3>

<p align="center">
  We'll spend our first session learning about the visual studio, ASP.NET MVC and how to implement bootstrap
  <br>
</p>

## :bulb: Scope
- [x] I. Installing Visual Studio
  - Selecting the right packages and plugins
- [x] II. Creating your first ASP.NET MVC solution
  - Exploring ASP.NET MVC solution
- [x] III. Creating your first custom page
- [x] IV. Implementing [Bootstrap/Bootswatch](https://bootswatch.com/)

## :wrench: I. Installing Visual Studio
- [ ] Download [Visual Studio Community 2022](https://visualstudio.microsoft.com/vs/community/)
- [ ] After installing, open Visual Studio Installer 

  ![Visual Studio Installer](./img/1.1.png)

- [ ] Modify your Visual Studio Comunity 2022

  ![Modify Visual Studio](./img//1.2.png)

- [ ] Check ASP.NET web development, Data storage processing

  ![ASP.NET Web Development](./img/1.3.png)
  ![Data Storage Processing](./img/1.4.png)

- [ ] Go to Individual Components and check ".NET Framework 4.7.2 SDK" and ".NET Framework 4.7.2 targeting pack" then click modify 

  ![Go to Individual Components and check ".NET Framework 4.7.2 SDK" and ".NET Framework 4.7.2 targeting pack"](./img/1.5.png)


## :test_tube: II. Creating your first ASP.NET MVC solution
> For this example, we'll be creating a web site application for this seminar. We'll be adding our seminar poster into our application and use bootstrap to design it.

- [ ] Open Visual Studio and click on "Create a new project"

  ![Open Visual Studio Community 2022](./img/2.1.png)
  ![Click "Create a new project"](./img/2.2.png)

- [ ] Select ASP.NET Web Application (.Net Framework) and click next

  ![Select ASP.NET Web Application (.Net Framework)](./img/2.3.png)

- [ ] Create a name for your solution and click create
  > :warning: Note: Framework should be ".NET Framework 4.7.2"

  ![Create a name for your solution and click create](./img/2.4.png)

- [ ] Select MVC and hit Create

  ![Select MVC and hit Create](./img/2.5.png)

- [ ] Wait for the creation of your new solution to open before pressing F5 or selecting the IIS Express option at the window's top to run your solution.

  ![Hit F5 or click IIS Express button](./img//2.6.png)

- [ ] After Executing your solution, your web application will be automatically open in your selected browser.

  ![Running Website](./img/2.7.png)

### :bus: MVC TOUR
> The MVC architectural pattern has existed for a long time in software engineering. All most all the languages use MVC with slight variation, but conceptually it remains the same.

>MVC stands for Model, View, and Controller. MVC separates an application into three components - Model, View, and Controller.

<p align="center">
  <img style="width:50%" src="./img/MVCDiagram.png">
</p>

- **Model:** Model represents the shape of the data. A class in C# is used to describe a model. Model objects store data retrieved from the database. **Model represents the data.**

- **View:** View in MVC is a user interface. View display model data to the user and also enables them to modify them. View in ASP.NET MVC is HTML, CSS, and some special syntax (Razor syntax) that makes it easy to communicate with the model and the controller. **View is the User Interface.**

- **Controller:** The controller handles the user request. Typically, the user uses the view and raises an HTTP request, which will be handled by the controller. The controller processes the request and returns the appropriate view as a response. **Controller is the request handler.**

# :clock2: Second Session

<p align="center">
  <img height="100" src="https://i.morioh.com/210611/b50f500b.webp">
</p>

<h3 align="center">2nd Session - ASP.NET MVC and Bootstrap/Bootswatch</h3>

<p align="center">
  For the second session, Databases (tables, stored procedures, etc) and deploying the visual studio solution and database to somee.com.
</p>

## :bulb: Scope

