// Nekys
What does not work (work in progress):
CONFIG::g()->cb('service_fix', false);											// Enable fixing feature for offline character
CONFIG::g()->cb('service_unstuck', false);										// Enable unstuck feature for offline character

This is because l2jserver doesn't use mapregion databasetable anymore and uses xml instead. I will work on this later.

// lenoxys
If you get this message during the registration : 

"Database problem : Account was not created. Please report this to the Staff."


You probably mistake to parse the db.sql on your database.
