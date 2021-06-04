# _{Pierres Bakery}_

#### _{A flavor and treat assigning and organizing tool for pierres bakery}_

#### By _**{Thomas Friedrichs}**_

## Technologies Used

* _C#_
* _.NET_
* _SQL_
* _vsCode_
* _Entity Framework_
* _Entitiy Identity_

## Description

_{This program uses many to many relationships to create and track treats and flavors along with the assigned relationships they have with eachother.}_

## Setup/Installation Requirements

* _Clone this repository https://github.com/thomasfriedrichs/PierresTreats.Solution_
* _Do a 'dotnet restore' in the terminal_
* _Go into your sql workbench, under the 'Administration' tab, click on 'Data Import/Restore'._
* Select 'Import from self-contained file', on the right of the file path there is a button with two dots, click on that button and select the 'thomas_friedrichs.sql'
* _select 'dump structure only' near the bottom, then select start import._
* _make an appsettings.json file._
* _paste the following in your appsettings:_
```
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=thomas_friedrichs;userid=root;pwd=epicodus;"
  }
}
```
* _run the app by typing 'dotnet watch run' in the terminal_
* _visit the app via localhost:5000/_

## Known Bugs

* _no known bugs_

## License

MIT License

Copyright (c) [2021] [Thomas Friedrichs]

_{If you have any questions or concerns please feel free to contact me!}_

## Contact Information

_{Thomas Friedrichs friedrichs.tommy@gmail.com}_