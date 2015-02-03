# troubleshooter
Intro to trouble shooting techniques - exercises

# 1 Using JDR
a) Download JBoss EAP 6.2 or above and install it  
b) Run <JBOSS_HOME>/bin/jdr.bat or <JBOSS_HOME>/bin/jdr.sh  
c) Inspect the results  
d) Verify which version of java you are using, what it the version of EAP etc etc  

# 2 Taking a thread dump
a) Build badApp from ???  
b) Deploy this to EAP 6.3.0  
c) Follow 2 of https://access.redhat.com/solutions/18178  
c) Analyse the thread dump using TDA and samuraiwhich thread what is stuck ?  

# 3 Tattletale
a) Download tattletale as shown in https://access.redhat.com/solutions/623533  
b) Follow instructions in https://access.redhat.com/documentation/en-US/JBoss_Enterprise_Application_Platform/6.1/html-single/Migration_Guide/index.html#Use_Tattletale_to_Find_Application_Dependencies  

# 5 Garbage Collection logs
a) Follow https://access.redhat.com/solutions/18656 to enable garbage collections logs  
b) Analyse them using GarbageDOg https://access.redhat.com/labs/garbagedog/  

# 6 Byteman
a) Follow https://access.redhat.com/solutions/31283  
