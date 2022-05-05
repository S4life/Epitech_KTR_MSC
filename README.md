# Epitech_KTR_MSC

# Saad MOHAMMAD : Test KTR for MSc PRO

---as soon i started, i had to leave for a family matter, i bearly had an hour to do what i did (incomplete)---

For the entry test, i decided to go with Symfony framework(PHP) since i've been learning it for a month now. 

Environment : 
- Windows 11 pro
- Xampp (open-source server solution)
- VS Code
- MySQL
- PHPMyAdmin
- PHP version 8.1.2
- Composer version 2.2.9
- Symfony CLI version 5.4.2 
- MVC pattern


Configuration : 

1. Install packages
    - Composer install
2. Composer require
    - Doctrine
    - Annotations
     
3. Create a local .env file or use the one already included
    - Add : DATABASE_URL="mysql://db_user:db_password@127.0.0.1:3306/epitech_ktr?serverVersion=5.7&charset=utf8mb4"  (or any other database)
    - [x] use your local server credentials (db_user, db_password) and make sure that the port 3306 corresponds to your MySQL port if not change it

4. Run on commande line : (make sur you are on the current project)
    - symfony console doctrine:database:create
    - symfony console make:migration
    - symfony console doctrine:migration:migrate

If i'm not forgetting anything, the application should be able to run
