# xssoneventmanagement
[Suggested description]
> Cross Site Scripting vulnerability in eventmanagement
> allows a remote attacker to execute arbitrary code on the register first name is vulnerable parameter for xss 
> 
>
> ------------------------------------------
>
> [Additional Information]
> To remediate XSS and HTML Injection vulnerabilities:
>
> Implement strict input validation.
> Encode output data properly.
> Apply Content Security Policy (CSP).
> Configure security headers.
> Conduct regular security audits.
> Educate users about safe browsing practices.
>
> ------------------------------------------
>
> [Vulnerability Type]
> Cross Site Scripting (XSS)
>
> ------------------------------------------
>
> [Vendor of Product]
> event-management
> https://github.com/PuneethReddyHC/event-management
>
> ------------------------------------------
>
> [Affected Product Code Base]
> event-management
>
> ------------------------------------------
>
> [Affected Component]
> http://localhost/event-management-master/register.php?event_id=1
>
> ------------------------------------------
>
> [Attack Type]
> Remote
>
> ------------------------------------------
>
> [Impact Code execution]
> true
>
> ------------------------------------------
>
> [Attack Vectors]
> 
> download the project file and host it on localhost.
> 
> go to register option in home page 
>
> and fill all random details KEEP NOTE vulnerable parameter is First name in register function add XSS payload
>
> try this custom payload because i have bypass the filter XSS payload :- <script>alert("XSS");</script>    <script>alert(document.cookie);</script>
> 
>
> ------------------------------------------
>
> [Reference]
> (https://github.com/ShahSarfaraz/xssoneventmanagement/edit/main/README.md)
>
> ------------------------------------------
>
> [Discoverer]
> Shah Sarfaraz

