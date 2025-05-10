| Attribute        | Type                      | Notes                       |
| :--------------- | :------------------------ | :-------------------------- |
| package\_id      | Primary Key               | Unique identifier           |
| name             | Text                      | Package title               |
| description      | Text                      | About the package           |
| price            | Decimal                   | Total cost                  |
| duration\_days   | Integer                   | e.g., 5 days, 7 days        |
| places\_included | Many-to-Many Relationship | A list of Places in package |
