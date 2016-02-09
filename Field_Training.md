#OWASP Security Shepherd #
## Level : Field Training ##

###1. Insecure Direct Object References
Change the value of the **username** parameter to `admin` using burp suite software intercept function.

###2. Poor Data Validation
Change the value of the **userdata** parameter to `minus value like -10` using burp suite software intercept function.

###3. Security Misconfiguration
submit default username and password to the fields. `admin / password`

###4. Broken Session Management
Change the **Cookie: lessonComplete=lessonNotComplete** value to `Cookie: lessonComplete=lessonComplete`

###5. Failure to Restrict URL Access
1. Open the web page code using browser **inspect element** function
2. Search for the admin only url code.
3. Remove the `style="display: none` attribute from the relevant div.
4. Click the **Administrator Result Page** link.

###6. Cross Site Scripting
1. type a script to text box that retrieve a alert box.
`<SCRIPT>alert('XSS')</SCRIPT>`
2. Click "get This User" button.

###7. Cross Site Scripting One
1. type a script to text box that retrieve a alert box .
`<INPUT TYPE="BUTTON" ONCLICK="alert('XSS')"/>`
2. Click "get This User" button.
