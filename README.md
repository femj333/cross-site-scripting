Mia Frattasio, Fem Jansen, Craig Salois

XSS Vulnerability Project
Cs4404

How To Run:
1. Enter the following command in the terminal: npx server .
2. Go to http://localhost:3000/ in your local browser

Some Examples of XSS Vulnerabilities
In the comment box enter:
<img src="x" onerror="alert(1)">
  - creates an image with an invalid src, will show alert

<b>This text is bold because there is a XSS vulnerability</b>
  - will display text as bold, shows user can modify script

<a href="javascript:alert(1)">Delicious Chocolate Chip Cookie Recipe</a>
  - posts a link which when clicked opens alert
