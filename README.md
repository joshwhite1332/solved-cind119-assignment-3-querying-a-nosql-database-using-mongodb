Download Link: https://assignmentchef.com/product/solved-cind119-assignment-3-querying-a-nosql-database-using-mongodb
<br>
<strong>Querying a NoSQL database using MongoDB </strong>

Complete this assignment using MongoDB.

<ol>

 <li>Create a database called “sample”. (1 point)</li>

 <li></li>

</ol>

<table>

 <tbody>

  <tr>

   <td width="94"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Create a collection called “test_data” and load the following data into the collection. (6 points)</li>

</ul>

<table width="541">

 <tbody>

  <tr>

   <td width="54"><strong>class </strong></td>

   <td width="45"><strong>age </strong></td>

   <td width="103"><strong>menopause </strong></td>

   <td width="93"><strong>deg_malig </strong></td>

   <td width="66"><strong>breast </strong></td>

   <td width="110"><strong>breast_quad </strong></td>

   <td width="69"><strong>irradiat </strong></td>

  </tr>

  <tr>

   <td width="54"><strong>NO </strong></td>

   <td width="45">35</td>

   <td width="103">premeno</td>

   <td width="93">3</td>

   <td width="66">left</td>

   <td width="110">left_low</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>NO </strong></td>

   <td width="45">42</td>

   <td width="103">premeno</td>

   <td width="93">2</td>

   <td width="66">right</td>

   <td width="110">right_up</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>NO </strong></td>

   <td width="45">30</td>

   <td width="103">premeno</td>

   <td width="93">2</td>

   <td width="66">left</td>

   <td width="110">left_low</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>NO </strong></td>

   <td width="45">61</td>

   <td width="103">ge40</td>

   <td width="93">2</td>

   <td width="66">right</td>

   <td width="110">left_up</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>NO </strong></td>

   <td width="45">45</td>

   <td width="103">premeno</td>

   <td width="93">2</td>

   <td width="66">right</td>

   <td width="110">right_low</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>NO </strong></td>

   <td width="45">64</td>

   <td width="103">ge40</td>

   <td width="93">2</td>

   <td width="66">left</td>

   <td width="110">left_low</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>NO </strong></td>

   <td width="45">52</td>

   <td width="103">premeno</td>

   <td width="93">2</td>

   <td width="66">left</td>

   <td width="110">left_low</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>NO </strong></td>

   <td width="45">67</td>

   <td width="103">ge40</td>

   <td width="93">1</td>

   <td width="66">left</td>

   <td width="110">left_low</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>YES </strong></td>

   <td width="45">41</td>

   <td width="103">premeno</td>

   <td width="93">2</td>

   <td width="66">left</td>

   <td width="110">left_low</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>YES </strong></td>

   <td width="45">43</td>

   <td width="103">premeno</td>

   <td width="93">2</td>

   <td width="66">right</td>

   <td width="110">left_up</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>YES </strong></td>

   <td width="45">41</td>

   <td width="103">premeno</td>

   <td width="93">3</td>

   <td width="66">left</td>

   <td width="110">central</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>YES </strong></td>

   <td width="45">44</td>

   <td width="103">ge40</td>

   <td width="93">2</td>

   <td width="66">left</td>

   <td width="110">left_low</td>

   <td width="69">no</td>

  </tr>

 </tbody>

</table>

1 of 2




<table width="541">

 <tbody>

  <tr>

   <td width="54"><strong>YES </strong></td>

   <td width="45">61</td>

   <td width="103">lt40</td>

   <td width="93">1</td>

   <td width="66">left</td>

   <td width="110">right_up</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>YES </strong></td>

   <td width="45">55</td>

   <td width="103">ge40</td>

   <td width="93">3</td>

   <td width="66">left</td>

   <td width="110">right_up</td>

   <td width="69">no</td>

  </tr>

  <tr>

   <td width="54"><strong>YES </strong></td>

   <td width="45">44</td>

   <td width="103">premeno</td>

   <td width="93">3</td>

   <td width="66">left</td>

   <td width="110">left_up</td>

   <td width="69">no</td>

  </tr>

 </tbody>

</table>




<ol start="3">

 <li>Write MongoDB queries to select/compute data from the “test_data” collection. (2 points each)

  <ol>

   <li>Select all rows where the menopause column has the value “ge40”.</li>

   <li>Select all rows where age is less than 41.</li>

   <li>Select all rows where age is less than 41 or the menopause column has the value “ge40”.</li>

   <li>Compute the average age across all rows.</li>

  </ol></li>

</ol>




Reference: Full dataset available at <a href="https://grouplens.org/datasets/movielens/">GroupLens</a>