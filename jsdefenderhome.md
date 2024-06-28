# Why Protect?

There are reasons you should protect your JavaScript apps:

- To make it more difficult for a hacker to reverse engineer your code
- To hide business logic and unique algorithms
- To make it more difficult for a hacker to debug your application and look for vulnerabilities
- To make it more difficult for an attacker to exploit those vulnerabilities, once found
- To make it more difficult for an attacker to modify or steal your code

Unlike languages like .NET and Java that are compiled to intermediate, stack-based assembly instructions before being distributed in binary form, JavaScript apps are typically distributed in source form. This means that your code is directly visible to anyone with access to the execution environment (like a browser). So, potential attackers can very easily step through the running code using a debugger built into their browser, or use other tools to statically analyze the code for vulnerabilities.

The professional-grade application protection of JSDefender helps you keep your secrets.

## Why JSDefender?

_PreEmptive Protection™ JSDefender™_ (JSDefender) protects JavaScript from attacks like reverse engineering and tampering with multiple code transformation and injection techniques.

JSDefender has been providing professional-grade obfuscation and in-app protection for JavaScript apps for over 20 years. 

## How it works

Our layered approach to JavaScript hardening provides multiple layers of protection for your application. Some of the elements we use to layer your application’s security include:

* **Domain lock** binds your JavaScript source code to a specific domain or subdomain.
* **Control flow protection** adds false conditional statements and misleading constructs to your code, creating spaghetti logic.
* **Boolean literals** transforms the false and true literals into other expressions, resulting in the same false and true logic.
* **Integer literals** transforms integer literals into less obvious expressions that result in the same value.
* **Function reordering** moves functions from their original locations to another one in the same lexical scope, including randomization.
* **Tamper detection**: If JSDefender detects that an unauthorized party has been tampering with your code, it can shut down the application to protect it.
* **Property indirection** transforms direct property access in your app's code to indirect property access.
* **Date Lock** injects code to test if the current date is within an interval you set. If true, the code runs normally; if not, it can either exit or run a custom script.
* **String literals** extracts literals into variables, replacing the original string with corresponding variables.
* **Expression sequence obfuscation** collects adjacent expression statements in the code and combines them into a sequence that's harder to understand.
* **Local declaration** mangles the name of local declarations so decompiling tools can't easily read them.
* **Property parsing** turns literal expression assignments into multiple assignment statements so they're harder to parse out.
* **Debugger removal** can detect when a user's browser has a debugger and can prevent the user from tampering with the code.
* **Variable grouping** separates variable declarations and initializations, moving them to the end of the scope.

## Getting Started
To get started using *PreEmptive Protection JSDefender*, [install and activate](intro_installation.html) JSDefender on your development machine, then see the Getting Started page.
