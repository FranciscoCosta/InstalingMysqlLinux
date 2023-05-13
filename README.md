<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
</head>
<body>
	<h1>MySQL Installation Guide for Linux</h1>
	<p>Follow these steps to install MySQL on a Linux system:</p>
	<ol>
		<li>Update package lists:</li>
		<pre><code>sudo apt-get update</code></pre>
		<li>Install MySQL:</li>
		<pre><code>sudo apt-get install mysql-server</code></pre>
		<li>Start MySQL:</li>
		<pre><code>sudo systemctl start mysql</code></pre>
		<li>Secure MySQL:</li>
		<pre><code>sudo mysql_secure_installation</code></pre>
		<li>Verify installation:</li>
		<pre><code>sudo systemctl status mysql</code></pre>
	</ol>
	<p>That's it! You have now installed MySQL on your Linux system.</p>
</body>
</html>
