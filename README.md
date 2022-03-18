# Factory Engineer Tracker

#### MVC web application for factory owner to monitor engineers and equipment

#### By Will Greenberg

## Technologies Used

* HTML
* CSS
* Bootstrap
* C#
* .NET
* SQL
* mySQLWorkbench

## Description

This MVC web application allows the owner of a factory to keep track of the engineers working at the factory, and the machines and equipment they are licensed to fix.

## Setup/Installation Requirements

* Clone this repository to your desktop.
* Navigate to directory `Factory.Solution` in your terminal.
* Add an `appsettings.json` file to the directory `Factory`.
* Add the following code to the `appsettings.json` file, with your password in the appropriate location:
  ```
  {
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=will_greenberg;uid=root;pwd=[YOUR-PASSWORD];"
    }
  }
  ```
* Run `dotnet ef database update --project Factory/` to build the database from the Migrations files.
* To run the application, run `dotnet run --project Factory/`.
* Navigate to `http://localhost:5000` in your browser.

## Known Bugs

* None so far.

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright (c) 2022 Will Greenberg