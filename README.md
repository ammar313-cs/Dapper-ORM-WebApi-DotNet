# Using Dapper with ASP.NET Core Web API
## https://code-maze.com/using-dapper-with-asp-net-core-web-api
This repo contains the source code for the "Using Dapper with ASP.NET Core Web API" article on Code Maze


<h1>Dapper ORM for Web API Development</h1>

<h2>Overview</h2>
<p>This repository showcases my work with Dapper ORM in ASP.NET Core for building Web APIs. It explores the usage of Dapper, a micro ORM, as an alternative to Entity Framework Core for data access in Web API projects.</p>

<h2>Features</h2>
<ul>
  <li><strong>Dapper ORM Integration</strong>: Utilizes Dapper ORM for efficient data access and manipulation.</li>
  <li><strong>ASP.NET Core Web API</strong>: Implements RESTful APIs using ASP.NET Core framework.</li>
  <li><strong>Database Interactions</strong>: Demonstrates CRUD operations with Dapper ORM, including querying, inserting, updating, and deleting data.</li>
  <li><strong>Performance Considerations</strong>: Discusses the performance benefits and considerations of using Dapper ORM compared to Entity Framework Core.</li>
</ul>

<h2>How it Differs from MVC Core</h2>
<ul>
  <li><strong>Data Access Approach</strong>: In MVC Core, Entity Framework Core is commonly used for data access, providing a higher level of abstraction and productivity tools. However, Dapper ORM offers a lightweight alternative, focusing on raw SQL execution and performance.</li>
  <li><strong>Control Over Queries</strong>: With Dapper, developers have more control over SQL queries, allowing fine-tuning for performance optimization and leveraging database-specific features.</li>
  <li><strong>Mapping Flexibility</strong>: While Entity Framework Core uses object-relational mapping (ORM) conventions for mapping database entities to C# objects, Dapper provides more flexibility in mapping by allowing manual control over result set mapping.</li>
</ul>

<h2>Usage</h2>
<ol>
  <li>Clone the repository: <code>git clone https://github.com/your_username/dapper-orm-web-api.git</code></li>
  <li>Navigate to the project directory: <code>cd dapper-orm-web-api</code></li>
  <li>Install dependencies: <code>dotnet restore</code></li>
  <li>Run the application: <code>dotnet run</code></li>
</ol>

<p>Feel free to explore the codebase and experiment with Dapper ORM for your Web API development needs!</p>
