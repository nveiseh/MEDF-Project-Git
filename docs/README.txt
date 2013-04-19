Two Apps in the MEDF Client Interface API:
polls.app: initial front end interface, so our clients can input their bi-weekly information into the database.

MESELECT.app: the place where all of the information is compiled into financial statements, and we include the financial drivers of growth
Models: 4
Enterprise -- db with all of the enterprises char
Drivers -- db of drivers associated with that enterprise
PeriodEntry -- db of bi-weekly entries, indexed by date and enterprise
BalanceSheet -- some kind of output???