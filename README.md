NOTE:@PostAuthorised was not used because the authorization alwalys gets delayed after execution of the target method.
    @Secured allows OR only that is why l have used @PreAuthorised to have AND operator.




This project contains a shell for bootraping the access control assignment. Fork the repository and then clone your forked repo on 
your local machines and configure it according to the steps outlines below


        a) Look at env-example located in resources and create a .env [naming is important,
           name it exactly as specified!] file that will be local to your environment
           
        b) Add the content from env-example but replace with the actual values for exaple where
           it says <your_database_name> replace it with the database name you will 
           create in your local database [User postgres]. Do the same for all the environmental variables.
           
        c) After filling in the variables and after the project has succefully installed the dependences, 
           you will be good to go. Hit that run button!
