# virtualTicketPrinter
Sabre script to replace a ticket printer by putting tickets, MCOs, etc into a daily spreadsheet

Still at an experimental phase, this is a Sabre script that only works with accumulated response turned off,
and you must have a file in the directory Z:\data.

Currently creates a file called TKTLIST.csv that shows 8 columns:
1. Record Locator
2. Airline Carrier Code
3. Ticket Number
4. Passenger Last name
5. Passenger First Name
6. FCI code
7. Agent ID
8. Total fare

Plans are to include all important fields (or make them selectable) so that agents can decide what they want included
in their reports.
