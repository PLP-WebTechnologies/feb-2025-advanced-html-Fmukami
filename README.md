# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HTML5 Advanced Elements and Forms</title>
</head>
<body>

  <!-- Ordered List with Roman Numerals -->
  <section>
    <h2>Ordered List (Roman Numerals)</h2>
    <ol type="I">
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>React</li>
    </ol>
  </section>

  <!-- External Image from Pexels -->
  <section>
    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/1103970/pexels-photo-1103970.jpeg" 
         alt="Nature landscape from Pexels" width="500" />
  </section>

  <!-- Table of Contacts -->
  <section>
    <h2>Contact List</h2>
    <table border="1" cellpadding="10" cellspacing="0">
      <thead>
        <tr>
          <th>Name</th>
          <th>Address</th>
          <th>Mobile</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Alice Wanjiru</td>
          <td>123 Elm St, NY</td>
          <td>+254 705551234</td>
          <td>alice@example.com</td>
        </tr>
        <tr>
          <td>Bob Mwangi</td>
          <td>456 Oak St, CA</td>
          <td>+254 785555678</td>
          <td>bob@example.com</td>
        </tr>
        <tr>
          <td>Carla Amondi</td>
          <td>789 Pine St, TX</td>
          <td>+254 755598012</td>
          <td>carla@example.com</td>
        </tr>
        <tr>
          <td>David Mwangi</td>
          <td>321 Birch St, FL</td>
          <td>+254 785553456</td>
          <td>david@example.com</td>
        </tr>
        <tr>
          <td>Ella Nyakio</td>
          <td>654 Maple St, WA</td>
          <td>+254 76557890</td>
          <td>ella@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Registration Form -->
  <section>
    <h2>Registration Form</h2>
    <form action="#" method="post">


