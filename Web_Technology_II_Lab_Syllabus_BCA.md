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
1. To provide hands-on experience in writing JavaScript programs for creating interactive and dynamic web pages.
2. To develop practical skills in using jQuery for DOM manipulation, event handling, visual effects, and AJAX operations.
3. To equip students with server-side scripting skills using PHP — form handling, file operations, sessions, and MySQL CRUD.
4. To enable students to build real-world dynamic web applications by integrating AJAX with PHP and MySQL backend.

---

## Course Outcomes:
After completion of the course, the student will be able to:

1. **CO1:** Implement JavaScript programs to manipulate the DOM, handle events, validate forms, and apply ES6+ features in real web scenarios.
2. **CO2:** Use jQuery to perform DOM operations, apply animations/effects, handle user events, and fetch data asynchronously using jQuery AJAX methods.
3. **CO3:** Develop server-side PHP scripts with form handling, session management, file operations, and MySQL database CRUD functionality.
4. **CO4:** Integrate AJAX with PHP and MySQL to build dynamic, real-time web applications with features like live search, dynamic dropdowns, and no-reload data operations.

---

## CO-PO Mapping
*(Scale — 1: Low, 2: Medium, 3: High)*

| CO-PO Mapping | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PO12 | PSO1 | PSO2 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CO1 | 2 | - | 2 | - | 3 | 2 | 2 | - | - | - | - | 2 | 3 | 2 |
| CO2 | 2 | - | 2 | - | 3 | 2 | 2 | - | 2 | - | - | 2 | 3 | 3 |
| CO3 | 3 | - | 3 | 2 | 3 | 2 | 2 | - | 2 | - | - | 2 | 3 | 3 |
| CO4 | 3 | 2 | 3 | 3 | 3 | 2 | 2 | - | 2 | - | - | 2 | 3 | 3 |

---

## List of Practicals *(Indicative & not limited to)*

---

### JavaScript Core Experiments

1. Write a JavaScript program to demonstrate variables (`var`, `let`, `const`), all data types, operators (arithmetic, comparison, logical, ternary), and type conversion — display results dynamically on a webpage.
2. Create a web page that uses JavaScript control structures (`if-else`, `switch`) and loops (`for`, `while`, `do-while`, `for-of`) — implement a number guessing game and multiplication table generator.
3. Write JavaScript programs to demonstrate user-defined functions, arrow functions, default parameters, closures, and scope (global vs local vs block) with practical DOM output examples.
4. Create a web page demonstrating JavaScript DOM manipulation — select elements using `getElementById`, `querySelector`, `querySelectorAll`; dynamically change text, styles, attributes, and classes using JavaScript.
5. Design an interactive web page handling multiple JavaScript Events (`click`, `dblclick`, `mouseover`, `mouseout`, `keyup`, `keydown`, `submit`, `change`) with `addEventListener` and `preventDefault()`.
6. Build a **Live Character Counter & Password Strength Checker** using JavaScript DOM events — real-time feedback as user types in input fields.
7. Create a **Dynamic Image Gallery with Lightbox** using JavaScript — clicking a thumbnail opens full image with next/previous navigation using DOM manipulation and event listeners.

---

### Advanced JavaScript Experiments

1. Write JavaScript programs demonstrating all important Array methods — `map()`, `filter()`, `reduce()`, `find()`, `forEach()`, `sort()`, `splice()`, `slice()` — with practical examples displayed on the webpage.
2. Create a web page demonstrating JavaScript Object Literals, Destructuring (array and object), Spread Operator, Rest Parameters, Template Literals, and ES6 Modules (`import`/`export`).
3. Build a **To-Do List Application** using JavaScript with full CRUD (Add task, Mark complete, Delete task) and `localStorage` for data persistence across browser sessions.
4. Implement client-side **Form Validation** using JavaScript — validate name (no numbers), email (regex), phone (10 digits), password (min 8 chars, 1 uppercase, 1 number, 1 special char) and confirm password match.
5. Demonstrate **Asynchronous JavaScript** — implement callbacks, Promises (`.then()`, `.catch()`), and `async/await` with practical examples; use **Fetch API** to call a public REST API (e.g., JSONPlaceholder / OpenWeatherMap) and display results dynamically.

---

### jQuery Experiments

1. Create a web page demonstrating all types of jQuery Selectors (element, class, ID, attribute, pseudo-class `:first`, `:last`, `:odd`, `:even`, `:nth-child`, `:not`) and DOM methods (`html()`, `text()`, `val()`, `attr()`, `css()`, `addClass()`, `removeClass()`, `toggleClass()`).
2. Design an interactive page demonstrating jQuery DOM Traversal methods — `parent()`, `children()`, `siblings()`, `next()`, `prev()`, `find()`, `closest()` — highlighting selected elements visually.
3. Build an **Animated Image Gallery / Accordion / Tab Panel** using jQuery Effects — `show()`, `hide()`, `toggle()`, `fadeIn()`, `fadeOut()`, `slideUp()`, `slideDown()`, `animate()` with `delay()` and `stop()`.
4. Create a **Live Table Search Filter** using jQuery — user types in a search box and rows in a table are filtered in real-time using jQuery DOM manipulation and `.filter()` method.
5. Implement **jQuery AJAX** — use `$.get()`, `$.post()`, and `$.ajax()` to fetch JSON data from a PHP script / public API and display the results dynamically in a Bootstrap Card layout without page reload.
6. Integrate a **jQuery Plugin** in a project page — implement **DataTables** plugin for sortable/searchable/paginated table and **Slick Slider** or **Owl Carousel** for an image slider.

---

### PHP Experiments

1. Set up XAMPP/WAMP local server environment; write PHP programs demonstrating variables, data types, constants, operators, `echo`/`print`, and embedding PHP in HTML.
2. Write PHP programs demonstrating all control structures (`if-else`, `switch`) and loops (`for`, `while`, `do-while`, `foreach`) — generate patterns, multiplication tables, and prime number checker.
3. Create PHP programs demonstrating user-defined functions, default arguments, return values, variable scope (`global` keyword), and all important String functions (`strlen`, `strtoupper`, `str_replace`, `explode`, `implode`, `substr`, `trim`).
4. Write PHP programs demonstrating Indexed Arrays, Associative Arrays, and Multidimensional Arrays using all important array functions (`array_push`, `array_merge`, `sort`, `count`, `in_array`, `array_keys`, `array_search`).
5. Design an HTML form and handle it using PHP — demonstrate `$_GET`, `$_POST`, `$_REQUEST`, form validation using `filter_var()` and `htmlspecialchars()`, and display submitted data.
6. Implement **PHP File Handling** — create, read, write, and delete a text file using `fopen()`, `fread()`, `fwrite()`, `fclose()`; implement a **File Upload** feature using `$_FILES` with file type and size validation.
7. Implement **PHP Sessions and Cookies** — create a Login page using sessions (`session_start()`, `$_SESSION`), a protected dashboard page, and a Logout page (`session_destroy()`); also demonstrate cookie creation and retrieval.
8. Build a complete **PHP + MySQL Student Management System** — Connect to MySQL using MySQLi; implement full CRUD: Add Student (INSERT), View All Students (SELECT), Edit Student (UPDATE), Delete Student (DELETE) using Prepared Statements to prevent SQL Injection.

---

### AJAX with PHP & MySQL Experiments

1. Implement **AJAX using XMLHttpRequest (XHR)** — send a GET request to a PHP file, receive a plain text / JSON response, and display it on the page without reload; demonstrate all `readyState` values and status codes.
2. Demonstrate **AJAX with Fetch API (JavaScript)** — send GET and POST requests to PHP scripts, pass data, receive JSON response using `json_encode()` in PHP and display results dynamically in DOM.
3. Implement **AJAX with jQuery** (`$.ajax()`, `$.get()`, `$.post()`) — fetch data from a PHP+MySQL script, display records in a Bootstrap table dynamically without page refresh.
4. Build a **Live Search** feature — as the user types in a search box, send a `keyup` AJAX request to a PHP script that queries the MySQL database and returns matching results displayed as a dropdown suggestion list.
5. Implement **Dynamic Dependent Dropdown** using AJAX — selecting a State from the first dropdown triggers an AJAX call to fetch corresponding Cities from MySQL and populate the second dropdown dynamically.
6. Build **AJAX-based CRUD operations** — Add, Edit, Delete records from a MySQL table without any page reload using AJAX POST requests to PHP backend scripts, updating the DOM table dynamically on every operation.
7. Implement **Real-time Username / Email Availability Check** — as the user fills the registration form, an AJAX call checks the MySQL database and shows "Available ✅" or "Already Taken ❌" instantly.

---

### Integrated Project Experiment

1. Develop a complete **Dynamic Web Application** integrating all topics:
   - **Frontend:** HTML5 + CSS3 + Bootstrap 5 + JavaScript + jQuery
   - **Backend:** PHP + MySQL
   - **Features to implement:**
     - User Registration & Login with PHP Sessions
     - Dashboard protected by session authentication
     - Add / Edit / Delete records using AJAX (no page reload)
     - Live Search with AJAX + PHP + MySQL
     - File Upload (Profile Photo) with AJAX
     - Responsive UI using Bootstrap 5
     - Client-side validation (JavaScript) + Server-side validation (PHP)
   - **Sample Project Ideas:**
     - Student Portal (Manage Students, Courses, Marks)
     - Product Inventory Management System
     - Online Notice Board / Announcement System
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
