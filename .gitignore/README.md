# HorseRace

Sample ASP.NET Application consuming C# Web APIs

## Version
1.0 - Initial Version

## Developer/s
  - Arthur Simon Ruiz

## Development

  - IDE: Visual Studio 2017
  - ASP.NET Web API
  - ASP.NET MVC
  - ReactJS
 
## Source Code Structure

The WebAPI and the Website are in the same project.
The website consumes the WebAPIs via ajax call.

  - WebAPI endpoints are declared in  ``/Controllers/API/`` folder
  - WebSite controllers are in ``/Controllers`` folder

## Dependencies
  - ReactJS
  - AutoMapper
  - Newtonsoft.Json

## Web API Endpoints
  - GET api/customers
  - GET api/customers/totalbetamount
  - GET api/customers/risky
  - GET api/customers/{id}
  - GET api/customers/{id}/totalbetamount
  - GET api/customers/{id}/totalbets
  - GET api/bets
  - GET api/races

## Data Sources
  - https://whatech-customerbets.azurewebsites.net/api/GetCustomers?name=yourName
  - https://whatech-customerbets.azurewebsites.net/api/GetBetsV2?name=yourName
  - https://whatech-customerbets.azurewebsites.net/api/GetRaces?name=yourName

