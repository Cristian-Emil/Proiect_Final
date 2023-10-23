EN- Proiect_Final (Final_Project).  

This project wants to be an exercise and a model through which to present the interaction between two email addresses in which the data from the first email is used to access the next email where certain of its files are verified.  
Of principle, this can be done in cascade, and if the system is thought out correctly, access can be made from the first email to email number "n" (n>= 2).  
Based on Java, Selenium, TestNG and Maven, the program shows how to access and how to check the content of an email address using the SOFTASSERT command.  
In order to run this program, you must have installed on your computer  Java, IntelliJ IDEA, Selenium, TestNG, Maven and the Chrome (in this project is chromedriver).  
The location where all these programs and utilities are installed will be specified in files pom.xmal and in the DriverManager class, line:  
System.setProperty("webdriver.chrome.driver", "C:/Users/crist/IdeaProjects/- driver_Selenium-Maven/ChromeDriver/chromedriver.exe");  
where at the address "C:/Users/crist/IdeaProjects/- driver_Selenium-Maven/ChromeDriver/chromedriver.exe" the new path to the chromedriver from the computer on which the program is run will be specified.  
In pom.xml, will be specified modules for Selenium, TestNG and Maven.


RO - Proiect_Final.  

Acest proiect doreste sa fie un exercitiu si un model prin care sa se prezinte interactiunea dintre doua adrese de email in care cu datele din primul email este accesat urmatorul email in care sunt veridfciate anumite fisiere ale acestuia.  
In principiu acest lucru se poate face in cascada si daca sistemul este gandit corect se poate face accesare din primul email pana la email-ul numarul "n" ("n" mai mare sau egal cu 2).  
Avand la baza Java, Selenium, TestNG si Maven programul prezinta modul in care se poate accesa si apoi verifica continutul unei adrese de email folosind comanda SOFTASSERT.  
Pentru a putea rula acest porgram trebuie sa aveti instalat pe computerul dvs. Java, IntelliJ IDEA, Selenium , TestNG, Maven si driverele de Chrome (chromedriver in acest proiect).   
Locatia unde sunt instalate toate acestea propgrame si utilitati se va preciza in pom.xmal si in clasa DriverManager, linia:  
System.setProperty("webdriver.chrome.driver", "C:/Users/crist/IdeaProjects/- driver_Selenium-Maven/ChromeDriver/chromedriver.exe");
unde la adresa "C:/Users/crist/IdeaProjects/- driver_Selenium-Maven/ChromeDriver/chromedriver.exe" se va preciza noua calea spre chromedriver-ul din computerul pe care este rulat programul.
In pom.xml se vor preciza modurile de apelare ale Selenium, TestNG si Maven.
