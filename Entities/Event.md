| Attribute   | Type                | Notes                   |
| :---------- | :------------------ | :---------------------- |
| event\_id   | Primary Key         | Unique identifier       |
| name        | Text                | Event name              |
| description | Text                | Details about the event |
| start\_date | Date                | Event starting day      |
| end\_date   | Date                | Event ending day        |
| place\_id   | Foreign Key (Place) | Where the event happens |
