+----------------+           +----------------+           +---------------------+           +------------------------+           +------------------------+
|    Employee    |           |    UserAuth    |           |   SalaryCalculator  |           |      DataPersister     |           |  SignInActivityLogger  |
+----------------+           +----------------+           +---------------------+           +------------------------+           +------------------------+
| - firstName    |           | - userName     |           | - amount            |           | - data                 |           | - user                 |
| - lastName     |           | - password     |           |                     |           |                        |           |                        |
| - userName     |           |                |           |                     |           |                        |           |                        |
| - password     |           |                |           |                     |           |                        |           |                        |
| - designation  |           +----------------+           +---------------------+           +------------------------+           +------------------------+
+----------------+           | +authenticate()|           | +calculateSalary()  |           | +saveDataToFile()      |           | +logSignInActivity()   |
|+displayEmployee|           |                |           |                     |           |                        |           |                        |
|  Info()        |           |                |           |                     |           |                        |           |                        |
+----------------+           +----------------+           +---------------------+           +------------------------+           +------------------------+
