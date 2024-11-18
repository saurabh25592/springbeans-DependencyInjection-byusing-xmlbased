<h1>Spring DI Setter Example</h1>

<p>This project demonstrates a basic example of Dependency Injection (DI) using setter methods in the Spring Framework.</p>

<h2>Overview</h2>

<p>The project includes the following:</p>
<ul>
    <li>Java classes for <code>Employee</code> and <code>Country</code>.</li>
    <li>Configuration using <code>springbeans.xml</code>.</li>
    <li>Spring dependencies defined in <code>pom.xml</code>.</li>
    <li>A main class to retrieve and display Spring beans.</li>
</ul>

<h2>Project Structure</h2>

<pre>
src/
├── main/
    ├── java/
    │   ├── com.entity/
    │   │   ├── Country.java
    │   │   ├── Employee.java
    │   ├── com.main/
    │       ├── Main.java
    ├── resources/
        ├── springbeans.xml
</pre>

<h2>Steps to Run</h2>

<ol>
    <li>Clone the repository:</li>
    <pre><code>git clone https://github.com/your-username/SpringDI_Setter.git</code></pre>
    <li>Navigate to the project directory:</li>
    <pre><code>cd SpringDI_Setter</code></pre>
    <li>Build the project using Maven:</li>
    <pre><code>mvn clean install</code></pre>
    <li>Run the <code>Main</code> class to see the output.</li>
</ol>

<h2>Dependencies</h2>

<p>The project uses the following dependencies:</p>
<ul>
    <li><a href="https://mvnrepository.com/artifact/org.springframework/spring-core" target="_blank">Spring Core (6.0.17)</a></li>
    <li><a href="https://mvnrepository.com/artifact/org.springframework/spring-context" target="_blank">Spring Context (6.0.17)</a></li>
</ul>

<h2>Output</h2>

<p>When the application runs, it prints the following output to the console:</p>

<pre>
Employee [e_id=1, name=saurabh, salary=23000, con=Country [cid=101, cname=Ind]]
Country [cid=101, cname=Ind]
</pre>

<h2>License</h2>

<p>This project is licensed under the MIT License.</p>
