# portfolio-website
html CopyEdit
<!DOCTYPE html>
<html>
<head>
<title>Portfolio</title>
</head>
<body>
<h1>Welcome to My Portfolio</h1>
<ul>
<% portfolio.forEach(item => { %>
<li><%= item.name %> - <%= item.email %></li>
<% }); %>
</ul>
</body>
</html>
