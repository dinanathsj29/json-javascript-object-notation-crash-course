<p align="center">
 <img src="_images-json-javascript-object-notation/json-logo-1.png" alt="JSON - JavaScript Object Notation" title="JSON - JavaScript Object Notation" width="200" />
</p>

<p align="center">
 <img src="_images-json-javascript-object-notation/json-logo-2.png" alt="JSON - JavaScript Object Notation" title="JSON - JavaScript Object Notation" width="400" />
</p>

JSON JavaScript Object Notation
=====================

Welcome
---------------------

About the Course/Tutorial
---------------------
Hi All, I'm **`Dinanath Jayaswal, Senior UI/Web Developer and Adobe Certified Expert Professional`**, I wanna welcome you to `JSON (JavaScript Object Notation) Crash Course for Beginners`. This course/tutorial will give you a complete understanding of JSON syntax, data types, and formatting.

This course will share the under the hood basic understanding of JSON using the practical implementation in your web development project. Here we will start from scratch/basics & go to a higher level very quickly.


Who is this for? 
---------------------
This course is for anyone interested in quickly learning JSON & it's power to utilize it in Web Development. 

This Course/Tutorial is ideal for:
- Anyone who wants to learn JSON from scratch
- Anyone interested in learning JSON & JSON Schema
- Programmers and Developers at any level
- Web developers
- Application developers
- Anyone who wants to interchange data between clients and servers
- Anyone who wants to choose JSON as the data interchange format in their REST API design

This course/Tutorial is for anyone and everyone, Almost everyone!

Why learn JSON
---------------------
JSON stands for JavaScript Object Notation is text-based and human-readable. JSON has become a widely accepted and popular format for data due to its platform-neutral nature, lightweight format, and it’s the ability to convert directly to native JavaScript Objects. JSON is being used everywhere from Web APIs to NoSQL databases, to server-side language libraries and client-side frameworks.

JSON has significantly improved server-to-browser communications, especially when it comes to AJAX. JSON is better than XML and more popular! Easily exchange data between client and server applications. JSON is easy to use and built for storing and exchanging data.


Course/Tutorial achievement
---------------------

Course/Tutorial Goal
---------------------
After completing/attending this JSON Course/Tutorial, participants should be able to: 
- Understand what and why JSON
- Use JSON format confidently
- Exchange Data with JSON format and use JSON in Web development/project

Prerequisites for current course / What you need to know
---------------------
- Basic knowledge and understandings of HTML, CSS, JavaScript and ASP/PHP
- Knowledge of using any text editor and a web browser
- Basics of Browser and Internet
- A basic understanding of Client Side vs Server Side

Before starting with JSON it is advisable to view and go through following course/tutorials to get knowledge of: 
- **Web Design Development Technology Fundamentals** - [Web Design Development Technology Fundamentals
](https://github.com/dinanathsj29/web-design-development-fundamentals-tutorial),
  - **HTML5** - [HTML5 Essentials Tutorial](https://github.com/dinanathsj29/html5-essentials-tutorial),
    - CSS3 - [CSS3 Fundamentals Tutorial](https://github.com/dinanathsj29/css3-fundamentals-tutorial),
      - **JavaScript** [JavaScript tutorial for Beginners](https://github.com/dinanathsj29/javascript-beginners-tutorial)

Topics included/covered
=====================

1. [Introduction to JSON](#1-introduction-to-json)
    - 1.1. [What is JSON?](#11-what-is-json)
    - 1.2. [Why use JSON?](#12-why-use-json)
    - 1.3. [What JSON is not?](#13-what-json-is-not)
    - 1.4. [Usage of JSON](#14-usage-of-json)
    - 1.5. [Characterstics of JSON](#15-characterstics-of-json)
    - 1.6. [JSON Syntax](#16-json-syntax)
    - 1.7. [JSON vs XML](#17-json-vs-xml)

<!-- 
2. [JSON Resources](#2-json-resources)
-->

1 Introduction to JSON
=====================

1.1. What is JSON?
--------------------- 

- JSON stands for `JavaScript Object Notation`
- JSON is a syntax for storing and exchanging data
- JSON is a lightweight data-interchange format
- JSON is `self-describing`, an easier to understand, easy to use and alternative format to `XML (eXtensible Markup Language)` also widely used these days
- JSON is language independent (JSON uses JavaScript syntax, with text-only format, 
Text can be read and used as a data format by any programming language)

```
- The JSON format was specified and popularized by `Douglas Crockford`
- The filename extension is `.json`
- JSON internet Media type is `application/json`
```

JSON is a pretty simple data exchange format which helps to communicate between JavaScript and server-side technologies like CGI (Common Gateway Interface), PERL, ASP (Active Server Pages), Java, JSP (Java Server Pages), PHP(HyperText PreProcessor / Personal Home Page), .NET, Cold Fusion CFML, NodeJS, Servelets, WCF (Windows Communication Foundation) and more

JSON has significantly improved server-to-browser communications, especially when it comes to AJAX. Most of today's APIs return the response in JSON format as it is much easier to load, read and process JSON compared to XML, making it very popular.

JSON uses, follows and based on Object Literal Notation syntax of JavaScript. JSON friendly Data Structures and friendly conventions play well with other different languages and platforms

> Example: Company X provides `JSON REST API { }` for the products related data, this WEB API is written with ASP.NET. User/Client Y or Z can make the call to this API by Java or jQuery or any other language to get JSON response.

1.2. Why use JSON?
---------------------

- JSON is text-based and human-readable, easily exchange data between client and server applications
- it's a lightweight data-interchange format that is quickly becoming the default format for data exchange on the internet today!
- JSON is better than XML and more popular!
- JSON is easy to use and built for storing and exchanging data
- Since the JSON format is text only, it can easily be sent to and from a server and used as a data format by any programming language

JSON has become a widely accepted and popular format for data due to its platform-neutral nature, lightweight format, and it’s the ability to convert directly to native JavaScript Objects. JSON is being used everywhere from Web APIs to NoSQL databases, to server-side language libraries and client-side frameworks.

JSON has significantly improved server-to-browser communications, especially when it comes to AJAX. JSON is better than XML and more popular! Easily exchange data between client and server applications. JSON is easy to use and built for storing and exchanging data.

JSON is extremely popular in web applications because it's lightweight, designed to be a language of independent and easy to read and write transfer data easily between server and client.

1.3. What JSON is not?
---------------------

- JSON is not a Programming/Markup language
- JSON is not dependent on JavaScript language
- Many people treat JSON as a javascript object, but it is not! JSON is just string representation inspired from JavaScript Object structure

```
JSON is programming language independent Data Interchange Format - an only text-based easy to use and understand the format used to Import and Export data between different platforms
```

1.4. Usage of JSON
---------------------

- It is used while writing JavaScript-based applications that include browser extensions and websites
- The JSON format is used for serializing and transmitting structured data over a network connection
- It is primarily used to transmit data between a server and web applications (client and server)
- Web services and APIs use JSON format to provide public data
- It can be used with different platform-independent modern programming languages 
- JSON is used in Web APIs as well as NoSQL databases

1.5. Characteristics of JSON
---------------------

- JSON is pretty easy to read, write and understand
- JSON is a lightweight text-based interchange format
- JSON is language independent
- JSON uses, follows and based on Object Literal Notation syntax of JavaScript
- JSON is widely used to exchange, send and receive data from server to client and vice versa
- JSON represent data in the pair of Curley braces and in the form of key-value pairs ie property and data e.g. ` var Employee = { "employeeName": "Dinanath", "employeeId": "101", "empId": 101} `
- Transfer data easily between Server and Client

1.6. JSON Syntax
---------------------

- JSON syntax is very simple and uses `name : value pair` or `key : value pair`

The JSON syntax is a subset of the JavaScript syntax. JSON syntax is derived from JavaScript object notation syntax:
- Data is in name/value pairs
- Data is separated by commas
- Curly braces hold objects
- Square brackets hold arrays

JSON format starts with `curley brace/bracket {` and `ends with curley brace/bracket }`. In-between curley brace we can put `"name" and value` or `"key":value` or `"property":value/data` pair, every property of the object is seperated by comma. 

JSON represents data in the `pair of curly braces and in the form of key-value pairs ie property and data`. We can separate `Property Name` with the help of `colon:` then specify `property Value` and multiple properties are separated with `comma,`.

```

- JSON, keys must be strings, written with "double quotes", JavaScript names don't.

```

To access or read data from a JSON object, we simply need to use property name with `. dot notation`, will get all IntelliSense as soon as will use any jsonObjectName.propertyName i.e. JsonObjectName.propertyName or so.

As soon as we assign JSON format/values to any JavaScript variable, it becomes a JavaScript object to which we can access via `. dot notation`.

### 1.6.1. JSON Values
In JSON, values must be one of the following data types:

- a string
- a number
- an object (JSON object)
- an array
- a boolean
- null

> **Syntax & Example**: `1.6.1-employee.json`

```
{ 
  "employeeName": "Dinanath",
  "employeeId": 100,
  "department": "IT-Development",
  "role": "Sr. UI Developer",
  "salary": 100000
}
```

<hr/>

> **Syntax & Example**: `1.6.2-technology.json`

```
{
  "technologyName": "JSON (JavaScript Object Notation)",
  "inventor": "Douglas Crockford",
  "usage": "Data storage and exchange format",
  "version": 1.0,
  "cost": 0,
  "license": "Open Source - MIT"
}
```

> **Syntax & Example**: `1.6.3-person.json`

```
{ 
  "name": "Dinanath",
  "age": 50,
  "country": "India",
  "height": 5.6,
  "color": "Black-Medium",
  "married": true
}
```


1.7. JSON vs XML
---------------------

### 1.7.1. Difference between JSON and XML

| JSON                            | XML                                   |
| --------------------------------|---------------------------------------|
| JavaScript Object Notation      | eXtensible Markup Language            |
| JSON uses `key : value` or `name : value` pair to store data (JSON doesn't use end tag) | XML uses tags **&lt; value &gt;** to store data | 
| JSON is shorter                 | XML is pretty larger/lengthy as we need to open and close tags for every `name` or `key`|
| JSON is quicker and easier to read and write | XML is little difficult to read and write as we need to write many tags |
| JSON can use arrays | XML cant use arrays, it uses tags|
