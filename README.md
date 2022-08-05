# _Dr. Sillystringz's Factory_

#### By _Zachary Waggoner_



#### _Description_

## Table of Contents

[Technologies Used](#technologies-used)  
[Description](#description)  
[Setup/Installation Requirements](#setup-and-installation-requirements)  
[Known Bugs](#known-bugs)  
[License](#License)

## Technologies Used

* _C#_
* _.NET_
* _HTML_
* _CSS_
* _SQL Workbench_
* _Entity Framework_
* _MVC_

---
## Description

_This is an MVC application that was built using C#._

---
## Setup and Installation Requirements

<details>
<summary><strong>Initial Setup</strong></summary>
<ol>
<li>Copy the git repository url: https://github.com/CyndaZ42/Dr-Sillystringz-Factory.git
<li>Open a shell program and navigate to your desktop.
<li>Clone the repository for this project using the "git clone" command and including the copied URL.
<li>While still in the shell program, navigate to the root directory of the newly created file named "Factory.Solution".
<li>From the root directory, navigate to the "BestRestuarants" directory.
<li>Move onto "SQL Workbench" instructions below to re-create database necessary to run this project.
<br>
</details>

<details>
<summary><strong>SQL Workbench Configuration</strong></summary>
<ol>
<li>Create an appsetting.json file in the "Factory" directory of the project*  
   <pre>Factory.Solution
   └── Factory
    └── appsetting.json</pre>
<li> Insert the following code: <br>

<pre>{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=factory;uid=root;pwd=[YOUR-PASSWORD-HERE];"
  }
}</pre>
<small>*note: you must include your password in the code block section labeled "YOUR-PASSWORD-HERE".</small>

<li>Once "appsettings.json" file has been created, navigate back to SQL Workbench.
</details>

<details>
<summary><strong>To Run</strong></summary>
Navigate to:  
    <pre>Factory.Solution
    ├── <strong>Factory</strong>
    └── Factory.Tests</pre>

Run `$ dotnet restore` in the console.<br>
Run `$ dotnet ef database update` in the console.<br>
Run `$ dotnet run` in the console
</details>
<br>

<details>
<summary><strong>For Testing</strong></summary>
Navigate to  
    <pre>Factory.Solution
    ├── Factory
    └── <strong>Factory.Tests</strong></pre>

Run `$ dotnet test` in the console

</details>
<br>

This program was built using *`Microsoft .NET SDK 5.0.401`*, and may not be compatible with other versions. Your milage may vary.

## Known Bugs

* Any known bugs

## License

_Feel free to reach out via [Github](https:/github.com/CyndaZ42) to provide feedback on this project or to view my other projects._

[Copyright](/LICENSE) (c) _07-28-2022_ _Zachary Waggoner_
