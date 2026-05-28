# AmityOS
Simple mock-kernel OS coded in C# for simulation and testing. Comes pre-built with a fully implemented command system, simple networking and a work-in-progress scriptor using a custom language, alongside having a full filesystem that runs off of memory.

##  About Antivirus Warnings

Some antivirus tools may flag AmityOS as a trojan.  
**This is a false positive.**

- AmityOS uses a `.bat` file to run `dotnet run`
- Windows sometimes flags batch files that launch executables with different names

There is **no malicious code** in AmityOS.  
Everything runs inside a simulated environment.
