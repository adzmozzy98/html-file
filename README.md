# html-file
<!DOCTYPE html>
<html>
<head>
<title>first class agency</title>
</head>
<CENTER>
<body bgcolor="#66ffff">
<img src="logo1.jpg" width="150" height="150">
<hr>
<h3><a href="homepage.html">HOME </a> |<a href="flightspage.html">HOLIDAY PACKAGES </a> | <a href="aboutus.html">ABOUT US </a> | <a href="contactus.html">ENQUIRIES </a> | <a href="externaloffers.html">EXTERNAL OFFERS</a></h3></hr>
</body>
<hr><h1><i><u>Vietnam</h1></u></i></hr><br><!--- This is the title of the page.-->
&nbsp;</b>
</center>
<style>
table {
    font-family: arial, sans-serif;
    border-collapse: collapse;
    width: 90%;
}

td, th {
    border: 1px solid #dddddd;                   <!--- These codes are the base of the table. They dictate the size, location, height and width of the table, it also gives programmers the ability to custom the padding of the table.-->
    text-align: left;
    padding: 10px;
}

tr:nth-child(even) {
    background-color: #dddddd;
}
</style>
</head>
<body>

<table>
  <tr>
  <center>
    <th><font size="5"><U><I>City</u></i></th>
    <th><font size="5"><u><i>price</u></i></th><!--- These codes are for the title names within the top of the table, the font size of each title will be 5 and the <u> and <i> will make the titles have an underline and also change the font to Italic.-->
    <th><font size="5"><u><i>link</u></i></th>
  </tr>
  <tr>
    <td><u><font size="4">hanoi</u></td>
    <td>7,798</td>
    <td><a href="http://www.travelagenthanoi.com/vietnam-package-holidays.html"><img src="hanoi.jpg" width="300" height="180"></a></td><!--- Each table will have the name of the city, the price of the whole holiday package and also a picture which has a link to an external website which has the specific holiday package.-->
  </tr>
  <tr>
    <td><u><font size="4">Pha Quoc</u></td>
    <td>6,502</td>
    <td><a href="http://discoverphuquoc.com/byair.html#a1"><img src="phu_quoc.jpg" width="300" height="180"></a></td>
  </tr>
  <tr>
    <td><u><font size="4">Ho chi minh city</u></td>
    <td>2,101</td>
    <td><a href="http://www.saigontravelvietnam.com/"><img src="ho_chi.jpg" width="300" height="180"></a></td>
  </tr>
  <tr>
    <td><u><font size="4">Sa Pa</u></td>
    <td>4,940</td>
    <td><a href="http://lilystravelagency.com/tour/sapa-3d4n-over-2-nights-in-home-stay/"><img src="sa_pa.jpg" width="300" height="180"></a></td>
  </tr>
  </table>
  <Br>
<center><FORM><INPUT Type="button" VALUE="Back" onClick="history.go(-1);return true;" align="bottom>"</FORM></br></center>
</body>
