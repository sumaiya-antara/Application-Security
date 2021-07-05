# Application-Security

## SAST Tools:
Static Application Security Testing (SAST) tools are designed to provide source code analysis techniques to find security flaws and vulnerabilities in developer code and provide best practices tips for better coding. SAST tools can integrate into the IDE offering a ‘shift-left’ security approach and can be integrated in CI/CD pipelines.
The approach taken is static, that is the code analysis is done in a non-running state where the code is at rest and not in use.

Popular SAST tools include:
1.	SonarQube
2.	Veracode Static Analysis
3.	Fortify Static Code Analyser
4.	Codacy
5.	AppScan
6.	Checkmarx CxSAST

## DAST Tools
DAST (Dynamic Application Security Testing) is a type of testing that looks for security vulnerabilities by safely exploiting a running application from the outside. This type of testing is not dependent on the framework or programming language used.
SAST (Static Application Security Testing) is a type of testing that includes code analyzers. It tests the source code for vulnerabilities by identifying the common patterns in it. These tools are language-specific and should be used only if you are developing your applications.
One of the most important attributes of security testing is coverage. In order to assess the security of an application, an automated scanner must be able to accurately interpret that application.
SAST scanners not only support the languages (PHP, C#/ASP.NET, Java, Python, etc.), but also the web application framework that is used. If your SAST scanner does not support your selected language or framework, you may hit a brick wall when testing your applications.
On the other hand, DAST scanners are, mostly, technology independent. This is because DAST scanners interact with an application from the outside and rely on HTTP. It makes them work with any programming languages and frameworks, both off-the-shelf and custom-built ones.
Why should businesses use Dynamic Application Security Testing software?
Manual vulnerability auditing of all your web applications is a complex and often time-consuming procedure. Automated vulnerability scanning allows you to always be on the lookout for new attack paths that attackers can use to access your web application or the data behind it.
Within minutes, an automated web application scanner can scan your web application, identify all the files accessible from the Internet, and simulate hacker activity in order to identify vulnerable components.

Here is the list of popular DAST Tools:
1.	Netsparker (Recommended Tool)
2.	Acunetix (Recommended Tool)
3.	PortSwigger
4.	Detectify
5.	AppCheck Ltd
6.	Hdiv Security
7.	AppScan
8.	Checkmarx
9.	Rapid7
10.	MisterScanner


