# _Vendor Order_

#### _This application allows a user to add clients and stylists to a hair salon page_

#### By _**William Sercombe**_

## Technologies Used

* _C##_
* _GIT_
* _Visual Studio_
*_ASP Net Core_
*_ASP NET MVC_
* _Entity_
*_MySql Database_

## Description

* _The user adds stylists and clients, clients are paired to stylsts by a stylist id field_

## Setup/Installation Requirements

* _Ensure that Dot.Net, MySql Community and MySql Workbench are installed on your computer_
* _Navigate to the gitub page to find the application_
* _Clone the application from the github address to their local computer_
* _Open MySql Workbench, import the sql file (willsercombe.sql) into mysql workbench_
* _Create an app settings.json file using the following code and point the database parameter correctly to the sql file_
```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=[will_sercombe.sql];uid=root;pwd=[YOUR-PASSWORD];"
  }
}
```
* _Run "dotnet build" within the terminal of the HairSalon directory_
* _Run "dotnet run" within the terminal of the HairSalon directory_

## Known Bugs

* _N/A_

## License

_MIT © 2021 William Sercombe_

## Contact Information

_William Sercombe | wsercombe@gmail.com | 503-545-9535_
