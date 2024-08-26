EN- Proiect_Final (Final_Project).  

This project wants to be an exercise and a model through which to present the interaction between two email addresses in which the data from the first email is used to access the next email where certain of its files are verified.  
Of principle, this can be done in cascade, and if the system is thought out correctly, access can be made from the first email to email number "n" (n>= 2).  
Based on Java, Selenium, TestNG and Maven, the program shows how to access and how to check the content of an email address using the SOFTASSERT command. In order to run this program, you must have installed on your computer  Java, IntelliJ IDEA, Selenium, TestNG, Maven and the Chrome (in this project is chromedriver).  
The location where all these programs and utilities are installed will be specified in files pom.xmal and in the DriverManager class, in line:  
System.setProperty("webdriver.chrome.driver", "C:/Users/crist/IdeaProjects/- driver_Selenium-Maven/ChromeDriver/chromedriver.exe");  
where at the address "C:/Users/crist/IdeaProjects/- driver_Selenium-Maven/ChromeDriver/chromedriver.exe" the new path to the chromedriver from the computer on which the program is run will be specified.  
In pom.xml, will be specified modules for Selenium, TestNG and Maven.

ATTENTION: Inside the program have been inserted several lines of Thread.sleep. These have the role of reducing the execution speed of the program if it is used in the didactic purpose.
In the existing repository, these lines have been commented. In order to have an effect, they must be uncommented, those signs "//" in front of the command line must be deleted.

Only for study ( will be erase this "//")

PS: In general, to search for a specific address, I preferred to use XPATH or CssSelector instead of an ID. The Xpath allows us to walk up and down its branches while the ID is unique and must be correctly identified to can run correct the programs.

  
RO - Proiect_Final.  

Acest proiect doreste sa fie un exercitiu si un model prin care este prezintata interactiunea dintre doua adrese de email in care cu datele din primul email este accesat urmatorul email si in acesta sunt verificate anumite fisiere si proprietati ale sale (continut , forma, aranajment).
In principiu acest lucru se poate face in cascada si daca sistemul este gandit corect se poate realiza accesare din primul email pana la email-ul numarul "n" ("n" mai mare sau egal cu 2).  
Avand la baza Java, Selenium, TestNG si Maven programul prezinta modul in care se poate accesa si apoi verifica continutul fisierului din cadrul unei adrese de email folosind comanda SOFTASSERT. Pentru a putea rula acest porgram trebuie sa aveti instalat pe computerul dvs. Java, IntelliJ IDEA, Selenium , TestNG, Maven si driverele de Chrome (chromedriver in acest proiect).   
Locatia unde sunt instalate toate acestea propgrame si utilitati se va preciza in pom.xmal si in clasa DriverManager, in linia:  
System.setProperty("webdriver.chrome.driver", "C:/Users/crist/IdeaProjects/- driver_Selenium-Maven/ChromeDriver/chromedriver.exe");
unde la adresa "C:/Users/crist/IdeaProjects/- driver_Selenium-Maven/ChromeDriver/chromedriver.exe" se va preciza noua calea spre chromedriver-ul din computerul pe care este rulat programul.  
In pom.xml se vor preciza modurile de apelare ale Selenium, TestNG si Maven.
  
ATENTIE: In cadrul programului au fost inserate mai multe linii de Thread.sleep. Aceste linii au rolul de a reduce viteza de executie a programului in cazul in care acesta este folosit in domeniu didactic - se pot vedea pasii pe care programul ii parcurge in timpul rularii.
In repository-ul existent aceste linii au fost comentate. Pentru a avea efect acestea trebuie decomentate , adica trebuie sterse acele semne  "//" din fata liniei de comanda. 

Doar pentru studiu ( se vor sterge acele "//")

PS: In general pentru cautarea unei adrese anume am preferat sa folosesc XPATH sau CssSelector in locul unui ID. Varinat  Xpath-ul ne permite sa se plimbam in sus si in jos pe ramurile acestuia in timp ce ID-ul este unic si trebuie corect identificat pentru a rula corect programul.

