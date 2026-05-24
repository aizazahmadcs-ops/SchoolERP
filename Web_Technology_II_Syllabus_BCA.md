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
Building upon Web Technology - I, this course equips students with JavaScript for interactive web pages, jQuery for simplified DOM operations and effects, and PHP with MySQL for server-side scripting and database management. Students will further learn to integrate AJAX with PHP and MySQL to develop dynamic, real-time web applications without page reloads. The course bridges the gap between frontend and backend development, preparing students for full-stack web application development.

---

## Course Outcomes:
After completion of the course, the student will be able to:

1. **CO1:** Write JavaScript programs to add interactivity to web pages using variables, functions, DOM manipulation, and event handling.
2. **CO2:** Use jQuery to simplify DOM manipulation, handle events, apply visual effects, and perform AJAX calls to fetch and display data dynamically.
3. **CO3:** Develop server-side PHP scripts using core PHP syntax, functions, arrays, and string operations to process and manage web data.
4. **CO4:** Build PHP-based web applications with form handling, file operations, session management, and MySQL database CRUD operations.
5. **CO5:** Integrate AJAX with PHP and MySQL to build complete dynamic web applications with real-time, page-reload-free data communication.

---

## CO-PO Mapping
*(Scale — 1: Low, 2: Medium, 3: High)*

| CO-PO Mapping | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PO12 | PSO1 | PSO2 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CO1 | 3 | 2 | 2 | 1 | 3 | 1 | 1 | - | 2 | 2 | 1 | 2 | 3 | 2 |
| CO2 | 2 | 3 | 2 | 2 | 3 | 1 | 1 | - | 2 | 2 | 1 | 2 | 3 | 3 |
| CO3 | 3 | 2 | 2 | 2 | 3 | 1 | 1 | - | 2 | 2 | 1 | 2 | 3 | 2 |
| CO4 | 3 | 3 | 3 | 2 | 3 | 2 | 1 | - | 2 | 2 | 1 | 2 | 3 | 3 |
| CO5 | 3 | 3 | 3 | 3 | 3 | 2 | 2 | - | 3 | 3 | 2 | 3 | 3 | 3 |

---

## Unit 1 — JavaScript Core Programming &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Introduction to JavaScript: History, Role of JavaScript in Web Development, Client-side vs Server-side scripting, JavaScript Engines.
- Adding JavaScript to HTML: Inline, Internal (`<script>` tag), External JS file (`.js`), Best practices for script placement.
- Variables and Data Types: `var`, `let`, `const`; Primitive types — Number, String, Boolean, Null, Undefined, Symbol; `typeof` operator.
- Operators: Arithmetic, Assignment, Comparison (`==` vs `===`), Logical (`&&`, `||`, `!`), Bitwise, Ternary Operator (`? :`).
- Control Structures: `if`, `if-else`, `else-if` ladder, `switch-case`, Nested conditions.
- Loops: `for`, `while`, `do-while`, `for-in`, `for-of`, `break` and `continue` statements.
- Functions: Function Declaration, Function Expression, Arrow Functions (`=>`), Default Parameters, Rest Parameters, Return values, Anonymous Functions.
- Scope and Hoisting: Global Scope, Local Scope, Block Scope (`let`/`const`), Variable Hoisting, Function Hoisting, Closures.
- DOM (Document Object Model): Introduction to DOM Tree structure, Selecting Elements — `getElementById`, `getElementsByClassName`, `getElementsByTagName`, `querySelector`, `querySelectorAll`.
- DOM Manipulation: Changing content (`innerHTML`, `textContent`, `innerText`), Changing styles (`style` property), Adding/Removing/Toggling classes (`classList.add`, `classList.remove`, `classList.toggle`), Creating, Appending, Removing DOM elements (`createElement`, `appendChild`, `removeChild`).
- Events: `addEventListener`, `removeEventListener`; Common Events — `click`, `dblclick`, `mouseover`, `mouseout`, `mouseenter`, `mouseleave`, `keyup`, `keydown`, `keypress`, `submit`, `change`, `input`, `load`, `DOMContentLoaded`; Event Object properties, `preventDefault()`, `stopPropagation()`.

**Practical Application:** Creating an interactive web page featuring a live character counter, dynamic background colour changer, image show/hide toggle, and a JavaScript-powered quiz application using DOM manipulation and Event handling.

---

## Unit 2 — jQuery &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Introduction to jQuery: What is jQuery, Advantages over plain JavaScript, CDN vs Local setup, jQuery syntax, `$(document).ready()` vs `$(function(){})`.
- jQuery Selectors: Element, Class (`$('.class')`), ID (`$('#id')`), Attribute (`[attr=value]`), Pseudo-class — `:first`, `:last`, `:even`, `:odd`, `:nth-child(n)`, `:not()`, `:contains()`, Multiple selectors.
- jQuery DOM Manipulation: `html()`, `text()`, `val()`, `attr()`, `removeAttr()`, `prop()`, `css()`, `width()`, `height()`; `addClass()`, `removeClass()`, `toggleClass()`, `hasClass()`; `append()`, `prepend()`, `appendTo()`, `after()`, `before()`, `remove()`, `empty()`, `clone()`, `wrap()`, `unwrap()`.
- jQuery Event Handling: `click()`, `dblclick()`, `hover()`, `mouseenter()`, `mouseleave()`, `focus()`, `blur()`, `change()`, `submit()`, `keyup()`, `keydown()`, `on()`, `off()`, `one()`; Event Delegation using `.on()`, `$(this)` context.
- jQuery Effects and Animations: `show()`, `hide()`, `toggle()` with speed parameter; `fadeIn()`, `fadeOut()`, `fadeToggle()`, `fadeTo()`; `slideUp()`, `slideDown()`, `slideToggle()`; Custom `animate()` — properties, duration, easing; `stop()`, `finish()`, `delay()`, Callback functions in effects.
- jQuery DOM Traversal: `parent()`, `parents()`, `parentsUntil()`, `children()`, `find()`, `siblings()`, `next()`, `nextAll()`, `nextUntil()`, `prev()`, `prevAll()`, `closest()`, `filter()`, `first()`, `last()`, `eq()`.
- jQuery Form Handling: Reading and setting form values (`val()`), Serializing form data (`serialize()`, `serializeArray()`), Dynamic form validation with jQuery.
- jQuery AJAX: `$.ajax()` — `type`, `url`, `data`, `dataType`, `success`, `error`, `complete` callbacks; `$.get()`, `$.post()`, `$.getJSON()`, `$.load()`; Handling JSON responses, `beforeSend` and `complete` for loading indicators.
- jQuery Plugins: Introduction to jQuery Plugins, Integrating popular plugins — **DataTables** (sortable, searchable, paginated tables), **Slick Slider** / **Owl Carousel** (image sliders), **Select2** (enhanced dropdowns), **Toastr** (notifications).
- jQuery UI: Introduction to jQuery UI widgets — Draggable, Droppable, Sortable, Resizable, Datepicker, Dialog (modal), Accordion, Tabs, Autocomplete.

**Practical Application:** Building an interactive product filter page with jQuery selectors and DOM manipulation, an animated image gallery with jQuery effects and transitions, a live table search filter, a dynamic Accordion/Tab panel using jQuery UI, and an AJAX-based data fetching demo using `$.get()` and `$.ajax()`.

---

## Unit 3 — PHP — Core Scripting & Functions &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Introduction to PHP: What is PHP, Features and Advantages of PHP, Client-side vs Server-side scripting, How PHP works with a web server, Setting up environment — XAMPP / WAMP / LAMP.
- PHP Syntax: PHP tags (`<?php ?>`), `echo` and `print`, PHP comments (single-line `//`, multi-line `/* */`), PHP in HTML.
- Variables and Data Types: Variable declaration (`$`), naming rules; Data types — Integer, Float, String, Boolean, Array, Object, NULL; `var_dump()`, `gettype()`, Type casting.
- Constants: `define()`, `const` keyword, Magic constants (`__FILE__`, `__LINE__`, `__DIR__`).
- Operators: Arithmetic, Assignment, Comparison (`==`, `===`, `!=`, `!==`), Logical (`&&`, `||`, `!`, `and`, `or`), String Concatenation (`.`), Increment/Decrement, Null Coalescing (`??`), Spaceship (`<=>`).
- Control Structures: `if`, `if-else`, `elseif`, `switch-case`, Ternary Operator, Null Coalescing assignment.
- Loops: `for`, `while`, `do-while`, `foreach` (for arrays); `break`, `continue`; Nested loops.
- Functions: User-defined functions, Function arguments (by value, by reference `&`), Default parameter values, Variable number of arguments (`func_get_args()`), Return values, Variable scope — local, global, static; `global` keyword, `static` keyword.
- String Functions: `strlen()`, `strtoupper()`, `strtolower()`, `ucfirst()`, `ucwords()`, `str_replace()`, `substr()`, `strpos()`, `strrpos()`, `str_contains()`, `str_starts_with()`, `str_ends_with()`, `trim()`, `ltrim()`, `rtrim()`, `explode()`, `implode()`, `str_repeat()`, `str_word_count()`, `sprintf()`, `number_format()`, `nl2br()`, `htmlspecialchars()`, `strip_tags()`.
- Math Functions: `abs()`, `ceil()`, `floor()`, `round()`, `sqrt()`, `pow()`, `max()`, `min()`, `rand()`, `mt_rand()`, `pi()`.
- Date and Time Functions: `date()`, `time()`, `mktime()`, `strtotime()`, `date_create()`, `date_format()`, `date_diff()`.

**Practical Application:** Writing PHP programs to perform string operations, mathematical computations, date/time formatting, and building a simple PHP-based calculator and unit converter embedded in an HTML page.

---

## Unit 4 — PHP — Arrays, Forms, File Handling & Sessions &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Arrays in PHP: Indexed Arrays, Associative Arrays, Multidimensional Arrays; Creating arrays (`array()`, `[]`), Accessing elements, Modifying arrays.
- Array Functions: `count()`, `sizeof()`, `array_push()`, `array_pop()`, `array_shift()`, `array_unshift()`, `array_merge()`, `array_slice()`, `array_splice()`, `array_reverse()`, `sort()`, `rsort()`, `asort()`, `arsort()`, `ksort()`, `krsort()`, `array_search()`, `in_array()`, `array_keys()`, `array_values()`, `array_unique()`, `array_flip()`, `array_combine()`, `array_map()`, `array_filter()`, `array_chunk()`, `compact()`, `extract()`.
- Form Handling in PHP: HTML Forms with PHP, `$_GET`, `$_POST`, `$_REQUEST`, `$_SERVER` superglobals; Form validation — `isset()`, `empty()`, `filter_var()` (FILTER_VALIDATE_EMAIL, FILTER_VALIDATE_INT, FILTER_SANITIZE_STRING), `htmlspecialchars()`, `trim()`, `stripslashes()`; Handling multiple form submissions, Sticky forms.
- File Handling: Opening files — `fopen()` modes (`r`, `w`, `a`, `r+`, `w+`); Reading — `fread()`, `fgets()`, `fgetc()`, `file()`, `file_get_contents()`; Writing — `fwrite()`, `file_put_contents()`; `fclose()`, `feof()`, `rewind()`; Checking files — `file_exists()`, `is_file()`, `is_dir()`, `filesize()`; Creating/Deleting — `mkdir()`, `rmdir()`, `unlink()`, `rename()`, `copy()`.
- File Upload: Handling `$_FILES` superglobal, File upload form (`enctype="multipart/form-data"`), Validating file type (`mime_content_type()`, file extension check), Validating file size, Moving uploaded file (`move_uploaded_file()`), Security best practices for file upload.
- Sessions in PHP: What are Sessions, `session_start()`, `$_SESSION` — setting, reading, modifying, unsetting session variables; `session_destroy()`, `session_regenerate_id()`, Session timeout, Passing data across multiple pages using sessions.
- Cookies in PHP: What are Cookies, `setcookie()` — name, value, expiry, path, domain, secure; `$_COOKIE` — reading cookies; Deleting cookies, Difference between Sessions and Cookies, Use cases.
- PHP Include and Require: `include`, `require`, `include_once`, `require_once` — creating reusable header, footer, and navigation components.

**Practical Application:** Building a PHP multi-page Student Registration System — a registration form with full validation, file upload for student photo, display of registered students, navigation using sessions for logged-in state, reusable header/footer with `include`, and cookie-based remember-me feature.

---

## Unit 5 — PHP with MySQL & AJAX Integration &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Introduction to MySQL: What is MySQL, Relational Database concepts, MySQL data types, Creating databases and tables using phpMyAdmin and SQL queries.
- PHP with MySQL (MySQLi): Connecting to MySQL — `mysqli_connect()` / Object-Oriented `new mysqli()`; Checking connection errors, Closing connection `mysqli_close()`; Executing queries — `mysqli_query()`, `mysqli_fetch_assoc()`, `mysqli_fetch_array()`, `mysqli_fetch_all()`, `mysqli_num_rows()`, `mysqli_affected_rows()`, `mysqli_insert_id()`.
- CRUD Operations with PHP & MySQL: **Create** — INSERT query with form data; **Read** — SELECT query, displaying records in HTML table; **Update** — UPDATE query with pre-filled edit form; **Delete** — DELETE query with confirmation; Search and filter records.
- Prepared Statements: What are Prepared Statements, Preventing SQL Injection, `mysqli_prepare()`, `bind_param()`, `execute()`, `get_result()`, PDO basics and advantages over MySQLi.
- Introduction to AJAX: What is AJAX, Synchronous vs Asynchronous communication, How AJAX works — Browser → XMLHttpRequest → PHP Script → MySQL → JSON Response → DOM Update.
- AJAX with JavaScript (Fetch API): Sending GET and POST requests to PHP scripts, Sending form data, Receiving and parsing JSON responses (`JSON.parse()`), Updating DOM without page reload.
- AJAX with jQuery: `$.ajax()`, `$.get()`, `$.post()` — sending data to PHP, receiving JSON response (`json_encode()` in PHP), Handling `success`, `error`, `complete` callbacks, Showing loading spinner during AJAX call.
- Real-World AJAX + PHP + MySQL Applications:
  - **Live Search:** Fetching matching database records on `keyup` event using AJAX.
  - **Dynamic Dependent Dropdown:** Populating Cities based on selected State from MySQL.
  - **AJAX CRUD:** Add, Edit, Delete records without page refresh, updating DOM table dynamically.
  - **Real-time Availability Check:** Checking username/email existence in database via AJAX on form input.
  - **Like / Counter System:** Incrementing/decrementing counts in MySQL without reload.
- JSON in AJAX: `json_encode()` and `json_decode()` in PHP, `JSON.stringify()` and `JSON.parse()` in JavaScript, Sending and receiving complex data objects.
- Security in Web Applications: Sanitizing and validating AJAX inputs server-side, CSRF token concept, Preventing direct access to PHP scripts, Secure file upload, Password hashing with `password_hash()` and `password_verify()`.

**Practical Application:** Building a complete **Dynamic Student Management Portal** — User Login/Registration with session authentication, Add/Edit/Delete student records using AJAX (no page reload), Live search by name or roll number, Dependent dropdown for department/course selection, Bootstrap DataTable for record display, Profile photo upload via AJAX, all integrated with PHP + MySQL backend and responsive Bootstrap 5 frontend.

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
