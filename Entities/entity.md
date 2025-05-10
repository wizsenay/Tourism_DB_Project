## Entity Descriptions

| **Entity Name**   | **Description**                                                        | **Aliases**     | **Occurrence**                                                                 |
|-------------------|------------------------------------------------------------------------|------------------|--------------------------------------------------------------------------------|
| Tourist           | Represents individuals who use the service to travel and explore.      | Visitor, Client  | Each tourist can book one or more tour packages and participate in events.     |
| Tour Guide        | Guides responsible for leading tourists through tour packages.         | Guide            | Each tour guide can be assigned to multiple tour packages or events.           |
| Place             | Tourist attraction sites listed within the system.                     | Location, Site   | Each place may be part of one or more tour packages and host multiple events.  |
| Transportation    | Vehicles and transport services offered to tourists.                   | Vehicle, Transport| Each transport option may serve multiple tourists but only one package at a time.|
| Hotel             | Accommodation available to tourists during their stay.                 | Lodging          | A hotel can host many tourists, and may be linked to multiple packages.        |
| Tour Package      | A bundled plan including places, transport, and hotels.                | Package          | A tourist can book multiple packages, and a package can include many components.|
| Event             | Scheduled activities at specific places for tourists to join.          | Activity         | An event can involve many tourists and one or more guides.                     |
