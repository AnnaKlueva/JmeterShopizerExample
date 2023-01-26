<h1>Jmeter scripts for Shopizer app</h1>

<h2>Before run:</h2>

<h3>
- Install Java11 <br>
- Install Jmeter (v 5.4.3 ) <br>
- Change emvironment properties for Jmeter and Java <br>
</h3>

<h2>How to run:</h2>
<h3> GUI mode <br></h3>
<h4><p> 1. Navigate to "apache-jmeter-5.4.3/bin" in console<br>
  2. For Mac: "sh jmeter.sh"
</p>
</h4>
<h3>Non GUI mode <br></h3>
<h4>
  <p>1. Navigate to "apache-jmeter-5.4.3/bin" in console </p>
  <p>2. For Mac: jmeter -n -t <script_name></p>
<br>
<p>Additional options:</p>
  <p>Increase heap and RAM that can be taken by Jmeter:<br>
"set HEAP="-Xms1G -Xmx1G -XX:MaxMetaspaceSize=192m" && jmeter -n -t <script_name>"
  </p>
</h4>


