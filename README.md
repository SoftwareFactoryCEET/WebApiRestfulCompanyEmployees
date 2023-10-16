<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <!-- <title>readme2</title> -->
  
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><h2 id="project-configuration">1 PROJECT CONFIGURATION</h2>
<p>1.1 Creating a New Project<br>
1.2 launchSettings.json File Configuration<br>
1.3 Program.cs Class Explanations<br>
1.4 Extension Methods and CORS Configuration<br>
1.5 IIS Configuration<br>
1.6 Additional Code in the Program Class<br>
1.7 Environment-Based Settings<br>
1.8 <a href="http://ASP.NET">ASP.NET</a> Core Middleware<br>
1.8.1 Creating a First Middleware Component<br>
1.8.2 Working with the Use Method<br>
1.8.3 Using the Map and MapWhen Methods<br>
1.8.4 Using MapWhen Method</p>
<h2 id="configuring-a-logging-service">2 CONFIGURING A LOGGING SERVICE</h2>
<p>2.1 Creating the Required Projects<br>
2.2 Creating the ILoggerManager Interface and Installing NLog<br>
2.3 Implementing the Interface and Nlog.Config File<br>
2.4 Configuring Logger Service for Logging Messages<br>
2.5 DI, IoC, and Logger Service Testing</p>
<h2 id="onion-architecture-implementation">3 ONION ARCHITECTURE IMPLEMENTATION</h2>
<p>3.1 About Onion Architecture<br>
3.1.1 Advantages of the Onion Architecture<br>
3.1.2 Flow of Dependencies<br>
3.2 Creating Models<br>
3.3 Context Class and the Database Connection<br>
3.4 Migration and Initial Data Seed<br>
3.5 Repository Pattern Logic<br>
3.6 Repository User Interfaces and Classes<br>
3.7 Creating a Repository Manager<br>
3.8 Adding a Service Layer<br>
3.9 Registering RepositoryContext at a Runtime</p>
<h2 id="handling-get-requests">4 HANDLING GET REQUESTS</h2>
<p>4.1 Controllers and Routing in WEB API<br>
4.2 Naming Our Resources<br>
4.3 Getting All Companies From the Database<br>
4.4 Testing the Result with Postman<br>
4.5 DTO Classes vs. Entity Model Classes<br>
4.6 Using AutoMapper in <a href="http://ASP.NET">ASP.NET</a> Core</p>
<h2 id="global-error-handling">5 GLOBAL ERROR HANDLING</h2>
<p>5.1 Handling Errors Globally with the Built-In Middleware<br>
5.2 Program Class Modification<br>
5.3 Testing the Result</p>
<h2 id="getting-additional-resources">6 GETTING ADDITIONAL RESOURCES</h2>
<p>6.1 Getting a Single Resource From the Database<br>
6.1.1 Handling Invalid Requests in a Service Layer<br>
6.2 Parent/Child Relationships in Web API<br>
6.3 Getting a Single Employee for Company</p>
<h2 id="content-negotiation">7 CONTENT NEGOTIATION</h2>
<p>7.1 What Do We Get Out of the Box?<br>
7.2 Changing the Default Configuration of Our Project<br>
7.3 Testing Content Negotiation<br>
7.4 Restricting Media Types<br>
7.5 More About Formatters<br>
7.6 Implementing a Custom Formatter</p>
<h2 id="method-safety-and-method-idempotency">8 METHOD SAFETY AND METHOD IDEMPOTENCY</h2>
<h2 id="creating-resources">9 CREATING RESOURCES</h2>
<p>9.1 Handling POST Requests<br>
9.2 Code Explanation<br>
9.2.1 Validation from the ApiController Attribute<br>
9.3 Creating a Child Resource<br>
9.4 Creating Children Resources Together with a Parent<br>
9.5 Creating a Collection of Resources<br>
9.6 Model Binding in API</p>
<h2 id="working-with-delete-requests">10 WORKING WITH DELETE REQUESTS</h2>
<p>10.1 Deleting a Parent Resource with its Children</p>
<h2 id="working-with-put-requests">11 WORKING WITH PUT REQUESTS</h2>
<p>11.1 Updating Employee<br>
11.1.1 About the Update Method from the RepositoryBase Class<br>
11.2 Inserting Resources while Updating One</p>
<h2 id="working-with-patch-requests">12 WORKING WITH PATCH REQUESTS</h2>
<p>12.1 Applying PATCH to the Employee Entity</p>
<h2 id="validation">13 VALIDATION</h2>
<p>13.1 ModelState, Rerun Validation, and Built-in Attributes<br>
13.1.1 Rerun Validation<br>
13.1.2 Built-in Attributes<br>
13.2 Custom Attributes and IValidatableObject<br>
13.3 Validation while Creating Resources<br>
13.3.1 Validating Int Type<br>
13.4 Validation for PUT Requests<br>
13.5 Validation for PATCH Requests</p>
<h2 id="asynchronous-code">14 ASYNCHRONOUS CODE</h2>
<p>14.1 What is Asynchronous Programming?<br>
14.2 Async, Await Keywords, and Return Types<br>
14.2.1 Return Types of the Asynchronous Methods<br>
14.2.2 The IRepositoryBase Interface and the RepositoryBase Class Explanation<br>
14.3 Modifying the ICompanyRepository Interface and the CompanyRepository Class<br>
14.4 IRepositoryManager and RepositoryManager Changes<br>
14.5 Updating the Service layer<br>
14.6 Controller Modification<br>
14.7 Continuation in Asynchronous Programming<br>
14.8 Common Pitfalls</p>
<h2 id="action-filters">15 ACTION FILTERS</h2>
<p>15.1 Action Filters Implementation<br>
15.2 The Scope of Action Filters<br>
15.3 Order of Invocation<br>
15.4 Improving the Code with Action Filters<br>
15.5 Validation with Action Filters<br>
15.6 Refactoring the Service Layer</p>
<h2 id="paging">16 PAGING</h2>
<p>16.1 What is Paging?<br>
16.2 Paging Implementation<br>
16.3 Concrete Query<br>
16.4 Improving the Solution<br>
16.4.1 Additional Advice</p>
<h2 id="filtering">17 FILTERING</h2>
<p>17.1 What is Filtering?<br>
17.2 How is Filtering Different from Searching?<br>
17.3 How to Implement Filtering in <a href="http://ASP.NET">ASP.NET</a> Core Web API<br>
17.4 Sending and Testing a Query</p>
<h2 id="searching">18 SEARCHING</h2>
<p>18.1 What is Searching?<br>
18.2 Implementing Searching in Our Application<br>
18.3 Testing Our Implementation</p>
<h2 id="sorting">19 SORTING</h2>
<p>19.1 What is Sorting?<br>
19.2 How to Implement Sorting in <a href="http://ASP.NET">ASP.NET</a> Core Web API<br>
19.3 Implementation – Step by Step<br>
19.4 Testing Our Implementation<br>
19.5 Improving the Sorting Functionality</p>
<h2 id="data-shaping">20 DATA SHAPING</h2>
<p>20.1 What is Data Shaping?<br>
20.2 How to Implement Data Shaping Implementation<br>
20.4 Resolving XML Serialization Problems</p>
<h2 id="supporting-hateoas">21 SUPPORTING HATEOAS</h2>
<p>21.1 What is HATEOAS and Why is it so Important?<br>
21.1.1 Typical Response with HATEOAS Implemented<br>
21.1.2 What is a Link?<br>
21.1.3 Pros/Cons of Implementing HATEOAS<br>
21.2 Adding Links in the Project<br>
21.3 Additional Project Changes<br>
21.4 Adding Custom Media Types<br>
21.4.1 Registering Custom Media Types<br>
21.4.2 Implementing a Media Type Validation Filter<br>
21.5 Implementing HATEOAS</p>
</div>
</body>

</html>
