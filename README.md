# SNHU_CS_350

Artemis Financial is our client, they came to us looking for a solution to encrypt data securely to be able to exchange with customers, and it must be export compliant. 

When the base code was given, the maven dependencies used had many vulnerabilities and this was a security risk. We checked these vulnerabilities and suppressed the false positives in order to alert the client of the vulnerabilities posing threat to security. This is important because as a financial company security is the most important reputation to uphold. Any leaks or cyber-attack incidents could prove disastrous for the client.

The most difficult part of vulnerability assessment is identifying the false positives. I struggled with this because it takes a lot of existing knowledge or research to know what you are looking for to identify a real threat.

After implementing the encryption method to the client’s code, we tested it using S AST. Static app security testing scans the code for existing security concerns. The first scan is always manual, checking the code by eye for any issue that may not be as secure for the user. Next, the dependency checks as discussed before are a form of static testing.

I think the Oracle website for Java and keytool was something new for me and I can see myself using it again in the future. I referenced it for most assignments where I felt stuck and always found my answer there.
