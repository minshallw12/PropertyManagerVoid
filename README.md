# PropertyManager

Real estate portfolio manager for Real Estate Investors.

This application gives users to ability to keep control of their real estate portfolio by giving users the ability to add addresses to their account,
calculate mortgages for specific property, and display their overarching statisitics such as total portfolio value/cost, number of properties,
mortgage info, and other stats. The user can also add contact information for a local property management company.


# CRUD

C 
  - User can create a new property entry to their portfolio.
  - User can create a new manager entry and assign them to a property. (name, phone, email, office location)
  - User can create mortgage statistics for their property with help from mortgage calc API. (monthly cost, total interest)
  - User can create rental statistics for their property. (monthly income, monthly cost, vacancy)
  
R 
  - Homepage is a dashboard showing total portfolio value, current portfolio income, current portfolio cost,
        current monthly/annual profit/loss, and current map of all properties in their portfolio
  - User can search for a specific address in their portfolio and see each property statistics.
  - User can search for a specific address outside of their portfolio and see geographical statistics then add it to their portfolio if desired.

U 
  - User can update mortgage stats, current rental stats, current managers, etc.

D 
  - User can sell properties from their portfolio and delete associated information.


# APIs
  
free Mortgage calculator --> https://www.commercialloandirect.com/amortization-schedule-api.html
Google Maps API --> https://developers.google.com/maps/documentation/javascript


# Database

- One table for users and accounts
- One table for properties and statistics
- One table for property managers
- One table for mortgage information? Stretch goal?

------------

# Will's Resources

google markers - https://medium.com/@limichelle21/integrating-google-maps-api-for-multiple-locations-a4329517977a
