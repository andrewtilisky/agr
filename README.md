# AGR (Automated Game Rental)
A site, web app, and schema for a fictitious game rental business.

This is a simple MVC frontend with some data assets I prepared over the course of a weekend to support a database term project for spring 2014.

The VGRental project dictates the business object model (customers, games to rent, game orders, etc.).  EF6 can dynamically generate the schema in a fresh SQL server database that the web app dll can query and modify.  The Configuration.cs seed code initializes the game records and records for the consoles on which they're available.

The front end project has controller classes for viewing and manipulating customer accounts, games, orders, and subscriptions.  It contains the viewmodels that account for the mismatch between the business objects and how their relevant attributes are displayed.  At last, this project has the cshtml views.
