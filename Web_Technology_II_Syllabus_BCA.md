# Syllabus

| Department | Computer Science |
|---|---|
| **Program** | B.C.A. (Bachelor of Computer Applications) |
| **Course Code** | BCA-WT302 |
| **Course Name** | Web Technology - II |
| **L** | **T** | **P** | **C** |
| 3 | 0 | 0 | 3 |

---

## Pre-requisite:
Web Technology - I (BCA-WT301) — Knowledge of HTML5, CSS3, and Bootstrap 5.

---

## Course Objectives:
1. To introduce students to JavaScript programming for building interactive and dynamic web pages.
2. To enable students to apply advanced JavaScript concepts including DOM manipulation, events, and asynchronous programming.
3. To familiarize students with jQuery library for simplified DOM manipulation, event handling, and AJAX operations.
4. To equip students with server-side scripting skills using PHP and database connectivity with MySQL.
5. To enable students to build dynamic, data-driven web applications using AJAX integration with PHP and MySQL.

---

## Course Outcomes:
After completion of the course, the student will be able to:

1. **CO1:** Write JavaScript programs to add interactivity to web pages using variables, functions, DOM manipulation, and event handling.
2. **CO2:** Apply advanced JavaScript concepts including arrays, objects, ES6+ features, form validation, and asynchronous programming using Fetch API.
3. **CO3:** Use jQuery to simplify DOM manipulation, handle events, apply visual effects, and perform AJAX calls to fetch and display data dynamically.
4. **CO4:** Develop server-side web applications using PHP with form handling, session management, and MySQL database CRUD operations.
5. **CO5:** Build complete dynamic web applications by integrating AJAX with PHP and MySQL for real-time, page-reload-free data communication.

---

## CO-PO Mapping
*(Scale — 1: Low, 2: Medium, 3: High)*

| CO-PO Mapping | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PO12 | PSO1 | PSO2 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CO1 | 3 | 2 | 2 | 1 | 3 | 1 | 1 | - | 2 | 2 | 1 | 2 | 3 | 2 |
| CO2 | 3 | 3 | 2 | 2 | 3 | 1 | 1 | - | 2 | 2 | 1 | 2 | 3 | 3 |
| CO3 | 2 | 3 | 2 | 2 | 3 | 1 | 1 | - | 2 | 2 | 1 | 2 | 3 | 3 |
| CO4 | 3 | 3 | 3 | 2 | 3 | 2 | 1 | - | 2 | 2 | 1 | 2 | 3 | 3 |
| CO5 | 3 | 3 | 3 | 3 | 3 | 2 | 2 | - | 3 | 3 | 2 | 3 | 3 | 3 |

---

## Unit 1 — JavaScript Core Programming &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Introduction to JavaScript: History, Role of JavaScript in Web Development, Client-side vs Server-side scripting.
- Adding JavaScript to HTML: Inline, Internal (`<script>` tag), External JS file (`.js`).
- Variables and Data Types: `var`, `let`, `const`; Number, String, Boolean, Null, Undefined, Symbol.
- Operators: Arithmetic, Assignment, Comparison, Logical, Bitwise, Ternary Operator.
- Control Structures: `if`, `if-else`, `else-if`, `switch-case`, Nested conditions.
- Loops: `for`, `while`, `do-while`, `for-in`, `for-of`, `break` and `continue`.
- Functions: Function Declaration, Function Expression, Arrow Functions (`=>`), Default Parameters, Return values.
- Scope: Global Scope, Local Scope, Block Scope, Hoisting, Closures.
- DOM (Document Object Model): Introduction to DOM Tree, Selecting Elements (`getElementById`, `getElementsByClassName`, `querySelector`, `querySelectorAll`).
- DOM Manipulation: Changing content (`innerHTML`, `textContent`), Changing styles (`style`), Adding/Removing classes (`classList`), Creating and Appending elements.
- Events: `addEventListener`, Common Events (click, dblclick, mouseover, mouseout, keyup, keydown, submit, change, load), Event Object, `preventDefault()`.

**Practical Application:** Creating an interactive web page with a live character counter, dynamic background color changer, show/hide elements, and a simple quiz application using JavaScript DOM and Events.

---

## Unit 2 — Advanced JavaScript &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Arrays: Creating Arrays, Array Methods (`push`, `pop`, `shift`, `unshift`, `splice`, `slice`, `map`, `filter`, `reduce`, `find`, `forEach`, `sort`, `reverse`).
- Objects: Object Literals, Accessing Properties (dot notation, bracket notation), Object Methods, `this` keyword, Object Destructuring.
- ES6+ Features: Template Literals (`` ` `` backticks), Spread Operator (`...`), Rest Parameters, Destructuring (Array & Object), Modules (`import`/`export`).
- String Methods: `toUpperCase`, `toLowerCase`, `trim`, `split`, `replace`, `includes`, `startsWith`, `endsWith`, `indexOf`, `substring`.
- Error Handling: `try`, `catch`, `finally`, `throw`, Custom Error Messages.
- Asynchronous JavaScript: Synchronous vs Asynchronous execution, Callback Functions, Callback Hell, Promises (`.then()`, `.catch()`, `.finally()`), `async`/`await`.
- Fetch API: Making HTTP GET and POST requests, Handling JSON responses, Displaying fetched data on webpage.
- Web Storage: `localStorage` (setItem, getItem, removeItem, clear), `sessionStorage`, Cookies — Introduction and usage.
- Client-side Form Validation: Validating text, email, password (regex), number ranges, required fields using JavaScript without third-party libraries.
- Regular Expressions (Regex): Basic patterns, `test()`, `match()`, `replace()` for input validation.

**Practical Application:** Building a dynamic To-Do List application with localStorage persistence, a student registration form with full JavaScript validation, and fetching and displaying live data (weather / jokes / quotes) using Fetch API and a public REST API.

---

## Unit 3 — jQuery &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Introduction to jQuery: What is jQuery, Advantages over plain JavaScript, CDN vs Local setup, `$(document).ready()`.
- jQuery Selectors: Element, Class, ID, Attribute, `:first`, `:last`, `:even`, `:odd`, `:nth-child`, `:not` selectors.
- jQuery DOM Manipulation: `html()`, `text()`, `val()`, `attr()`, `prop()`, `css()`, `addClass()`, `removeClass()`, `toggleClass()`, `append()`, `prepend()`, `after()`, `before()`, `remove()`, `empty()`, `clone()`.
- jQuery Event Handling: `click()`, `dblclick()`, `hover()`, `focus()`, `blur()`, `change()`, `submit()`, `keyup()`, `keydown()`, `on()`, `off()`, Event Delegation.
- jQuery Effects and Animations: `show()`, `hide()`, `toggle()`, `fadeIn()`, `fadeOut()`, `fadeToggle()`, `slideUp()`, `slideDown()`, `slideToggle()`, `animate()`, `stop()`, `delay()`.
- jQuery Traversal: `parent()`, `parents()`, `children()`, `siblings()`, `next()`, `prev()`, `find()`, `closest()`, `filter()`.
- jQuery AJAX: `$.ajax()` — type, url, data, success, error, complete; `$.get()`, `$.post()`, `$.getJSON()`, `$.load()`, Handling JSON responses.
- jQuery Form Handling: Serializing form data (`serialize()`, `serializeArray()`), Dynamic form validation with jQuery.
- jQuery Plugins: Introduction to jQuery Plugins, Using popular plugins — **DataTables** (sortable, searchable tables), **Slick Slider** (image carousel), **Select2** (enhanced dropdowns).
- jQuery UI: Introduction to jQuery UI — Draggable, Droppable, Sortable, Datepicker, Dialog widgets.

**Practical Application:** Creating an interactive product filter page using jQuery selectors and DOM manipulation, an animated image gallery with jQuery effects, a live search filter using jQuery, and an AJAX-based data fetching demo using `$.get()` and `$.ajax()`.

---

## Unit 4 — PHP — Server Side Scripting &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Introduction to PHP: What is PHP, Features of PHP, Client-side vs Server-side scripting, Setting up environment (XAMPP / WAMP / LAMP).
- PHP Syntax: PHP tags (`<?php ?>`), Echo and Print, Comments, Variables (`$`), Constants (`define()`), Data Types (Integer, Float, String, Boolean, Array, NULL).
- Operators: Arithmetic, Assignment, Comparison, Logical, String Concatenation (`.`).
- Control Structures: `if`, `if-else`, `elseif`, `switch`, Ternary Operator.
- Loops: `for`, `while`, `do-while`, `foreach` (for arrays), `break`, `continue`.
- Functions: User-defined functions, Function arguments, Default parameter values, Return values, Variable scope (global, local), `global` keyword.
- Arrays: Indexed Arrays, Associative Arrays, Multidimensional Arrays; Array functions (`array_push`, `array_pop`, `array_merge`, `sort`, `count`, `array_search`, `in_array`, `array_keys`, `array_values`).
- String Functions: `strlen`, `strtoupper`, `strtolower`, `str_replace`, `substr`, `strpos`, `trim`, `explode`, `implode`, `sprintf`.
- Form Handling: `$_GET`, `$_POST`, `$_REQUEST`, `$_SERVER`; Form validation and sanitization (`filter_var`, `htmlspecialchars`, `trim`).
- File Handling: `fopen()`, `fread()`, `fwrite()`, `fclose()`, `file_get_contents()`, `file_put_contents()`, File Upload handling (`$_FILES`).
- Sessions and Cookies: `session_start()`, `$_SESSION`, `session_destroy()`; `setcookie()`, `$_COOKIE`, Cookie expiry.
- PHP with MySQL: Introduction to MySQLi and PDO, Connecting to MySQL database, Performing CRUD operations (Create, Read, Update, Delete), Prepared Statements (SQL Injection prevention), Fetching results (`fetch_assoc()`, `fetch_all()`).

**Practical Application:** Building a complete PHP + MySQL Student Management System — Registration form (INSERT), Display all students (SELECT), Update student details (UPDATE), Delete a student (DELETE), with session-based Login & Logout.

---

## Unit 5 — AJAX with PHP & MySQL Integration &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Introduction to AJAX: What is AJAX, Synchronous vs Asynchronous communication, How AJAX works (Browser → XMLHttpRequest → Server → Response → DOM Update).
- XMLHttpRequest (XHR): Creating XHR object, `open()`, `send()`, `onreadystatechange`, `readyState` values, `status` codes, Handling response (`responseText`, `responseXML`).
- AJAX with Vanilla JavaScript (Fetch API): GET and POST requests to PHP scripts, Sending and receiving JSON data, Updating DOM without page reload.
- AJAX with jQuery: `$.ajax()`, `$.get()`, `$.post()` — sending data to PHP, receiving JSON response, Handling success and error callbacks.
- PHP as AJAX Backend: Writing PHP scripts to handle AJAX requests, Returning JSON responses (`json_encode()`), Receiving POST data (`$_POST`), Connecting to MySQL and returning query results as JSON.
- Real-World AJAX Applications:
  - **Live Search:** Searching database records as user types (keyup event + AJAX + PHP + MySQL).
  - **Dynamic Dropdown:** Populating dependent dropdowns (State → City) using AJAX.
  - **Like / Dislike Counter:** Updating counts in database without page refresh.
  - **Real-time Form Validation:** Checking username/email availability in database using AJAX.
  - **Dynamic Data Table:** Loading, filtering, and paginating database records using AJAX.
- JSON in AJAX: `JSON.stringify()`, `JSON.parse()`, `json_encode()` in PHP, `json_decode()` in PHP, Sending complex data objects via AJAX.
- File Upload using AJAX: Uploading files asynchronously using FormData object, Displaying upload progress.
- Security in AJAX Applications: Validating and sanitizing AJAX inputs on server side, CSRF token basics, Preventing direct PHP script access.
- Mini Project — Complete Dynamic Web Application:
  - Frontend: HTML5 + CSS3 + Bootstrap 5 + JavaScript + jQuery
  - Backend: PHP + MySQL
  - Features: User Login/Registration (Session), CRUD operations via AJAX, Live Search, Responsive UI

**Practical Application:** Building a complete **Dynamic Student Portal** — User login/registration with sessions, Add/Edit/Delete student records using AJAX (no page reload), Live search students by name/roll number, Display records in a Bootstrap DataTable, File upload for student profile photo — all integrated with PHP + MySQL backend.

---

## Total Lecture Hours: 40 Hours

---

## Textbooks:
1. Robin Nixon, *Learning PHP, MySQL & JavaScript*, O'Reilly Media.
2. Ivan Bayross, *Web Enabled Commercial Application Development Using HTML, CSS, JavaScript & PHP*, BPB Publications.
3. David Flanagan, *JavaScript: The Definitive Guide*, O'Reilly Media.
4. Jon Duckett, *JavaScript and jQuery: Interactive Front-End Web Development*, John Wiley & Sons.

---

## Reference Books:
1. Rasmus Lerdorf & Kevin Tatroe, *Programming PHP*, O'Reilly Media.
2. Nicholas C. Zakas, *Professional JavaScript for Web Developers*, Wrox Press.
3. W3Schools Web Tutorials — https://www.w3schools.com
4. MDN Web Docs — https://developer.mozilla.org
5. PHP Official Documentation — https://www.php.net/docs.php
6. jQuery Official Documentation — https://api.jquery.com

---

## Evaluation Scheme:

| Types of Courses | Components of Evaluation | | % Weightage |
|---|---|---|---|
| Theory Courses with ESE | Continuous Internal Evaluation (CIE) | Mid Semester Examination (MSE) | 30% |
| | | Continuous Assessment (CA) | 20% |
| | End Semester Examination (ESE) | End Semester Examination (ESE) | 50% |

---

*Syllabus Designed for: B.C.A. Program — Web Technology - II (BCA-WT302)*
*Total Credits: 3 | Lecture Hours per Week: 3*
