📚 Lecture 5 Summary: HTML Images, Tables, and Lists
🖼️ Images in HTML
<img> Tag: Used to embed images.

Attributes:

src: Specifies the path to the image.

alt: Provides alternative text if the image cannot be displayed.

height and width: Define the dimensions of the image.

Example:

html
Copy
Edit
<img src="image.png" alt="Train image" height="230">
📊 Tables in HTML
Structure:

<table>: Defines the table.

<thead>: Groups the header content.

<tbody>: Groups the body content.

<tfoot>: Groups the footer content.

<tr>: Defines a row.

<th>: Defines a header cell.

<td>: Defines a standard cell.

Attributes:

colspan: Merges cells horizontally.

rowspan: Merges cells vertically.

Example:

html
Copy
Edit
<table>
  <caption>Employee Details</caption>
  <thead>
    <tr>
      <th>Name</th>
      <th>Designation</th>
      <th>Fav Language</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Harry</td>
      <td>Programmer</td>
      <td>JavaScript</td>
    </tr>
    <tr>
      <td colspan="2">Sam</td>
      <td rowspan="2">Java</td>
    </tr>
    <tr>
      <td colspan="2">Sam</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="2">Sam</td>
      <td rowspan="2">foot</td>
    </tr>
  </tfoot>
</table>
📋 Lists in HTML
Unordered Lists (<ul>):

Used for items where order doesn't matter.

type Attribute: Can be set to disc, circle, or square.

Example:

html
Copy
Edit
<ul type="square">
  <li>Harry</li>
  <li>Rohan</li>
  <li>Shubham</li>
</ul>
Ordered Lists (<ol>):

Used for items where order matters.

type Attribute: Can be set to 1, A, a, I, or i.

Example:

html
Copy
Edit
<ol type="A">
  <li>Harry</li>
  <li>Rohan</li>
  <li>Shubham</li>
</ol>















