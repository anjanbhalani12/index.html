# index.html
<html>
<head>
<title>practical</title>
</head>
<body>

<form>                <!--used to collect data form the user-->

<input type="text" placeholder="user name"><br>
<input type="password" placeholder="password"><br>
<label for="101">                                  <!--used to collect circle any choos-->
<input type="radio" value="class II" name="class" id="101">classII<br>
</label>

<label for="102">
<input type="radio" value="class III" name="class" id="102">classIII<br>
</label>

<h3>Select your subject</h3>

<label for="math">
<input type="checkbox" value="math" name="sub" id="1">maths<br>
<label for="phy">
<input type="checkbox" value="phy" name="sub" id="2">phy<br>
<label for="chem">
<input type="checkbox" value="chem" name="sub" id="3">chem<br>
<label for="computer">
<input type="checkbox" value="computer" name="sub" id="4">computer<br>

<textarea name="feedback" id="101" placeholder="please give your value able here" raw="5">
feedback 
</textarea><br>
</label>

<select name="city">
<option value="delhi"> delhi </option>
<option value="pune" >pune </option>
<option value="banglure"> banglure </option>
<option value="junagadh"> junagadh </option>
</select><br>

<input type="submit" value="submit">

</form>


</body>
</html>
