In Task.rar se vor gasi 3 foldere : WindowsFormsApp1 (codul sursa), node si openssl(pentru securizarea serverului)

Requirements :
-Visual Studio (Eu am folosit 2017, insa nu cred ca versiunile mai vechi ar crea probleme)
-Node.js
-npm mysql
-npm express
-XAMPP
-Trebuie creata o baza de date cu urmatoarele setari :
   -host : localhost
   -user : root
   -password : rootpassword
   -database : mysqlcsharp
   -table : users  -> In tabela users trebuie sa exista coloanele id, username, password, admin(1-este admin; 0-nu este admin)
   
In VS : 
  - punem path-ul catre rootCA.pem in public Form1()   
   
