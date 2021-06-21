## Welcome to be More Confident Programmer

Writing down all nessesary informations to self-improve.

21.06.2021
### Domain Logic Patterns


  ## Transaction Script (110)

  ```markdown
  Most bussiness applications as a series of transactions.

  Questions:
  *What does view of transaction include?

  Information organized in a particular way
  Interaction between client system and server
  -contains certain ammount of logic;
  -as simple as displaying information in the database;
  -it may involve many steps validations and calculations;

  *What does transaction do?
  -Transaction will make change to information.
    Transaction script:
    - all logic as single procedure;
    -calls directly to databse through thin database wrapper;
    Each Transaction will have its own transaction script:
    - common subtasks can be broken into subprocedures;

  ```

  ## Domain Model
  ```markdown
  -business logic can be very complex. 
    -rules and logic describe many different cases and behaviors.
      -objects were designed to work with this complexity
     -object represents meaningful individual
        - DM creates web of interconnected objects
            - large as corporation
            -small as single line on an order form
  ```
  ![image](https://user-images.githubusercontent.com/84378754/122745139-f99af780-d288-11eb-85b8-76054010fc50.png)
