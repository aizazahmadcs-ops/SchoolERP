# Syllabus

| Department | Computer Science |
|---|---|
| **Program** | B.C.A. (Bachelor of Computer Applications) |
| **Course Code** | BCA-WTL302 |
| **Course Name** | Web Technology - II Lab |
| **L** | **T** | **P** | **C** |
| 0 | 0 | 2 | 1 |

---

## Pre-requisite:
Web Technology - I Lab (BCA-WTL301); Co-requisite: Web Technology - II (BCA-WT302) — Knowledge of HTML5, CSS3, and Bootstrap 5.

---

## Course Objectives:
Building upon Web Technology - I, this lab course provides hands-on experience in JavaScript programming, jQuery-based DOM manipulation and effects, and PHP with MySQL for server-side development. Students will practically implement dynamic features using AJAX with PHP and MySQL to build real-time, data-driven web applications. The lab bridges the gap between frontend interactivity and backend functionality, preparing students for full-stack web development.

---

## Course Outcomes:
After completion of the course, the student will be able to:

1. **CO1:** Implement JavaScript programs to manipulate the DOM, handle events, and validate forms interactively on web pages.
2. **CO2:** Use jQuery to perform DOM operations, apply animations and effects, handle user events, and fetch data asynchronously using jQuery AJAX methods.
3. **CO3:** Develop server-side PHP scripts using core syntax, functions, arrays, string operations, and form handling to process web data effectively.
4. **CO4:** Build PHP-based web applications with file handling, session management, cookies, and MySQL CRUD operations using prepared statements.
5. **CO5:** Integrate AJAX with PHP and MySQL to develop dynamic, real-time web applications with live search, dependent dropdowns, and no-reload data operations.

---

## CO-PO Mapping
*(Scale — 1: Low, 2: Medium, 3: High)*

| CO-PO Mapping | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PO12 | PSO1 | PSO2 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CO1 | 2 | - | 2 | - | 3 | 2 | 2 | - | - | - | - | 2 | 3 | 2 |
| CO2 | 2 | - | 2 | - | 3 | 2 | 2 | - | 2 | - | - | 2 | 3 | 3 |
| CO3 | 3 | - | 2 | 2 | 3 | 2 | 2 | - | 2 | - | - | 2 | 3 | 2 |
| CO4 | 3 | - | 3 | 2 | 3 | 2 | 2 | - | 2 | - | - | 2 | 3 | 3 |
| CO5 | 3 | 2 | 3 | 3 | 3 | 2 | 2 | - | 2 | - | - | 2 | 3 | 3 |

---

## List of Practicals *(Indicative & not limited to)*

---

### Section A — JavaScript Core Experiments

1. Write a JavaScript program to demonstrate variables (`var`, `let`, `const`), all data types (Number, String, Boolean, Null, Undefined), operators (arithmetic, comparison, logical, ternary), and type conversion using `typeof` — display results dynamically on a webpage.

2. Create a web page using JavaScript control structures (`if-else`, `elseif`, `switch-case`) and loops (`for`, `while`, `do-while`, `for-of`, `for-in`) — implement a multiplication table generator, number pattern printer, and a number guessing game.

3. Write JavaScript programs demonstrating user-defined functions, function expressions, arrow functions (`=>`), default parameters, rest parameters, and closures — demonstrate global vs local vs block scope with practical DOM output examples.

4. Create a web page demonstrating JavaScript DOM manipulation — select elements using `getElementById`, `getElementsByClassName`, `querySelector`, `querySelectorAll`; dynamically change text (`innerHTML`, `textContent`), styles (`style`), attributes (`setAttribute`), and classes (`classList.add`, `classList.remove`, `classList.toggle`); create and append new elements dynamically.

5. Design an interactive web page handling multiple JavaScript events — `click`, `dblclick`, `mouseover`, `mouseout`, `mouseenter`, `mouseleave`, `keyup`, `keydown`, `submit`, `change`, `input` — using `addEventListener`, `removeEventListener`, Event Object properties, `preventDefault()`, and `stopPropagation()`.

6. Build a **Live Character Counter & Password Strength Checker** — real-time feedback as user types using `keyup` event; character count updates live and password strength (Weak / Medium / Strong) is shown based on length and character types using JavaScript DOM events.

7. Create a **Dynamic Quiz Application** — display questions one at a time, allow user to select answers, calculate and display final score with result summary using JavaScript DOM manipulation, event handling, and arrays.

---

### Section B — jQuery Experiments

1. Create a web page demonstrating all types of jQuery Selectors — element, class (`$('.class')`), ID (`$('#id')`), attribute (`[attr=value]`), pseudo-class (`:first`, `:last`, `:odd`, `:even`, `:nth-child(n)`, `:not()`, `:contains()`) — and jQuery DOM methods (`html()`, `text()`, `val()`, `attr()`, `css()`, `addClass()`, `removeClass()`, `toggleClass()`, `append()`, `prepend()`, `remove()`, `empty()`).

2. Design an interactive page demonstrating jQuery DOM Traversal — `parent()`, `parents()`, `children()`, `find()`, `siblings()`, `next()`, `nextAll()`, `prev()`, `prevAll()`, `closest()`, `filter()`, `first()`, `last()`, `eq()` — visually highlight traversed elements on click.

3. Build an **Animated Web Page** using jQuery Effects — demonstrate `show()`, `hide()`, `toggle()`, `fadeIn()`, `fadeOut()`, `fadeToggle()`, `fadeTo()`, `slideUp()`, `slideDown()`, `slideToggle()` with speed parameters and callback functions; implement a custom `animate()` for moving and resizing elements with `stop()` and `delay()`.

4. Create an **Interactive Accordion and Tab Panel** using jQuery — clicking a tab/header shows its content panel while hiding others; implement smooth slide/fade transitions using jQuery Effects and Event handling.

5. Create a **Live Table Search Filter** using jQuery — as the user types in a search input box, table rows are filtered in real-time using jQuery `.filter()`, `.show()`, `.hide()` — case-insensitive search across all columns.

6. Implement **jQuery AJAX** — use `$.get()`, `$.post()`, and `$.ajax()` (with `type`, `url`, `data`, `dataType`, `success`, `error`, `beforeSend` callbacks) to fetch JSON data from a PHP script / public REST API (JSONPlaceholder) and display the results dynamically in Bootstrap Cards without page reload.

7. Integrate **jQuery Plugins** into a project page — implement **DataTables** plugin for a sortable, searchable, paginated HTML table and **Slick Slider** or **Owl Carousel** for a responsive image slider/carousel.

---

### Section C — PHP Core Scripting Experiments

1. Set up XAMPP/WAMP local server; write PHP programs demonstrating PHP syntax, embedding PHP in HTML, variables (`$`), data types (Integer, Float, String, Boolean, NULL), `var_dump()`, `gettype()`, type casting, constants (`define()`, `const`), and all types of operators (arithmetic, comparison, logical, concatenation `.`, null coalescing `??`).

2. Write PHP programs demonstrating control structures (`if-else`, `elseif`, `switch-case`, ternary operator) and loops (`for`, `while`, `do-while`, `foreach`) — generate number patterns, prime number checker, factorial calculator, and Fibonacci series.

3. Create PHP programs demonstrating user-defined functions — function arguments (by value, by reference `&`), default parameter values, variable number of arguments (`func_get_args()`), return values, `global` keyword for variable scope, and `static` variables — with practical examples embedded in HTML output.

4. Write PHP programs demonstrating all important **String Functions** — `strlen()`, `strtoupper()`, `strtolower()`, `ucfirst()`, `ucwords()`, `str_replace()`, `substr()`, `strpos()`, `str_contains()`, `trim()`, `explode()`, `implode()`, `str_repeat()`, `sprintf()`, `htmlspecialchars()`, `strip_tags()` — with real-world string processing examples.

5. Write PHP programs demonstrating **Math and Date/Time Functions** — `abs()`, `ceil()`, `floor()`, `round()`, `sqrt()`, `pow()`, `rand()`, `max()`, `min()`; `date()`, `time()`, `strtotime()`, `date_create()`, `date_format()`, `date_diff()` — build a simple age calculator and event countdown using PHP date functions.

---

### Section D — PHP Advanced Experiments

1. Write PHP programs demonstrating **Indexed Arrays**, **Associative Arrays**, and **Multidimensional Arrays** using all important array functions — `count()`, `array_push()`, `array_pop()`, `array_merge()`, `array_slice()`, `array_reverse()`, `sort()`, `rsort()`, `asort()`, `arsort()`, `ksort()`, `array_search()`, `in_array()`, `array_keys()`, `array_values()`, `array_unique()`, `array_map()`, `array_filter()`, `array_chunk()`.

2. Design an HTML form and handle it using PHP — demonstrate `$_GET`, `$_POST`, `$_REQUEST`, `$_SERVER` superglobals; implement full form validation using `isset()`, `empty()`, `filter_var()` (FILTER_VALIDATE_EMAIL, FILTER_VALIDATE_INT), `htmlspecialchars()`, `trim()`, `stripslashes()`; implement sticky form (retaining values on error).

3. Implement **PHP File Handling** — create, open, read (`fread()`, `fgets()`, `file_get_contents()`), write (`fwrite()`, `file_put_contents()`), and delete files (`unlink()`); check file existence (`file_exists()`, `filesize()`); implement a simple **Visitor Log** system that writes each visit timestamp to a text file and displays all logs.

4. Implement **PHP File Upload** — create a file upload form with `enctype="multipart/form-data"`, handle `$_FILES` superglobal, validate file type (allowed extensions check) and file size, move uploaded file to server folder using `move_uploaded_file()`, display uploaded image preview.

5. Implement **PHP Sessions and Cookies** — build a multi-page Login system: Login page (validate credentials, set `$_SESSION`), Protected Dashboard page (check session, display user info), Logout page (`session_destroy()`); also implement a **Remember Me** feature using `setcookie()` and `$_COOKIE` for persistent login.

6. Build a **PHP Include/Require Template System** — create reusable `header.php`, `navbar.php`, `footer.php` files and include them across multiple pages using `include` and `require`; demonstrate `include_once` and `require_once` for avoiding duplicate inclusions.

7. Build a complete **PHP + MySQL Student Management System** — connect to MySQL using MySQLi; implement full CRUD operations: Add Student (INSERT with prepared statements), View All Students (SELECT with `fetch_assoc()`), Edit Student (pre-filled UPDATE form), Delete Student (DELETE with confirmation); use prepared statements throughout to prevent SQL Injection.

---

### Section E — AJAX with PHP & MySQL Experiments

1. Implement **AJAX using XMLHttpRequest (XHR)** — create an XHR object, use `open()`, `send()`, `onreadystatechange`; demonstrate all `readyState` values (0–4) and HTTP status codes; fetch a plain text and JSON response from a PHP file and display results in DOM without page reload.

2. Demonstrate **AJAX with Fetch API (JavaScript)** — send GET and POST requests to PHP scripts using `fetch()`; pass form data, receive JSON response (`json_encode()` in PHP); parse using `JSON.parse()` / `.json()` and update DOM dynamically; handle errors using `.catch()`.

3. Implement **AJAX with jQuery** — use `$.get()`, `$.post()`, and `$.ajax()` (with `beforeSend` loading spinner, `success`, `error`, `complete` callbacks) to fetch records from PHP + MySQL and display in a Bootstrap styled table dynamically without page refresh.

4. Build a **Live Search** feature — as the user types in a search input (`keyup` event), send an AJAX request to a PHP script that queries the MySQL database using a LIKE query and returns matching results as JSON; display results as a real-time dropdown suggestion list below the input field.

5. Implement **Dynamic Dependent Dropdown** using AJAX — on selecting a Department from the first dropdown, trigger an AJAX call to fetch corresponding Courses/Programs from MySQL and populate the second dropdown dynamically without page reload.

6. Build complete **AJAX-based CRUD Operations** — Add, Edit, and Delete student records from a MySQL table entirely without page reload; use AJAX POST requests to PHP backend scripts; dynamically update the Bootstrap table in DOM after every Add, Edit, and Delete operation.

7. Implement **Real-time Username & Email Availability Check** — as the user types in the registration form, an AJAX call queries the MySQL database and instantly shows "Available ✅" or "Already Taken ❌" feedback below the input field without any page reload.

---

### Section F — Integrated Project Experiment

1. Develop a complete **Dynamic Full-Stack Web Application** integrating all topics covered in the lab:
   - **Frontend:** HTML5 + CSS3 + Bootstrap 5 + JavaScript + jQuery
   - **Backend:** PHP + MySQL
   - **Features to Implement:**
     - User Registration & Login with PHP Session authentication
     - Protected Dashboard — accessible only after login
     - Add / Edit / Delete records using AJAX (zero page reload)
     - Live Search with AJAX + PHP + MySQL
     - Dynamic Dependent Dropdown (e.g., Department → Course)
     - File Upload (Profile Photo) with validation
     - Responsive UI using Bootstrap 5 Grid and Components
     - Client-side Validation (JavaScript) + Server-side Validation (PHP)
     - Prepared Statements for all MySQL queries (SQL Injection prevention)
   - **Sample Project Ideas:**
     - Student Portal (Manage Students, Courses, Marks, Attendance)
     - Product Inventory Management System
     - Online Notice Board / Announcement System
     - College Event Management System
     - Personal Blog with Admin Panel

---

## Textbooks:
1. Robin Nixon, *Learning PHP, MySQL & JavaScript*, O'Reilly Media.
2. Jon Duckett, *JavaScript and jQuery: Interactive Front-End Web Development*, John Wiley & Sons.
3. Ivan Bayross, *Web Enabled Commercial Application Development Using HTML, CSS, JavaScript & PHP*, BPB Publications.
4. PHP Official Documentation — https://www.php.net/docs.php

---

## Reference Books:
1. David Flanagan, *JavaScript: The Definitive Guide*, O'Reilly Media.
2. Nicholas C. Zakas, *Professional JavaScript for Web Developers*, Wrox Press.
3. jQuery Official Documentation — https://api.jquery.com
4. W3Schools Web Tutorials — https://www.w3schools.com
5. MDN Web Docs — https://developer.mozilla.org

---

## Evaluation Scheme:

| Types of Courses | Components of Evaluation | | % Weightage |
|---|---|---|---|
| Lab / Practical Courses | Continuous Internal Evaluation (CIE) | Continuous Lab Assessment (CLA) | 60% |
| | End Semester Examination (ESE) | Practical Exam + Viva Voce | 40% |

---

*Syllabus Designed for: B.C.A. Program — Web Technology - II Lab (BCA-WTL302)*
*Total Credits: 1 | Practical Hours per Week: 2*
