<!DOCTYPE html>
<html>


<head>
<title>Form Assignment</title>
</head>

<body>

Please answer the following questions.
Thank you.

<hr>
      <form method=post action="http://tomcat.eng.utah.edu/hamlet/echo" tartget="echo">

<p> What is your age?</p>

<br>
      <input type=radio name="age" value="0-17">
      <input type=radio name="age" value="18-64">
      <input type=radio name="age" value="65 and over">

<hr>

<p>Which of these do you own?</p>
<br>
     <input type=checkbox name="own" value="phone">
     <input type=checkbox name="own" value="stereo">
     <input type=checkbox name="own" value="TV">
     <input type=checkbox name="own" value="VCR">
     
<hr>

<p>Which continents have you visited?</p>

<br>

  <select name="continents" multiple size=7>
    <option value="NA"> North America </option>
    <option value="SA"> South America </option
    <option value="AS"> Asia          </option>
    <option value="AF"> Africa        </option>
    <option value="EU"> Europe        </option>
    <option value="AUS"> Australia    </option>
    <option value="ANT"> Antarctica   </option>
    
    
  </select>

<hr>

<p>What did you think of this survey?</p>

<br>

   <textarea name="thoughts" cols=20 rows=10></textarea>
   
<hr>

   <input type=submit value="Click here to submit">
   

</form>
</body>
</html>
