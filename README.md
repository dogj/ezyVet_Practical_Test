Requirements:
	All data from the CSV must be processed into the provided tables.
	Data must be sanitized to be safely inserted
	Data must be consistent when exported as is when imported.
	First and Last names must have the first letter capitalized.
	Business Names must have acronyms be capitalized.
	Mobile numbers must have a 64 prefixed
	Landline numbers must have 09 prefixed
	The `contact_id` field in the address and phone tables must match to an existing record with the same value in the `id` field of the contact table
	You can use any language for any code that is written. Preferably use PHP 7.0 where possible.
	MySQL 5.7 is to be used


addtional:
if landline is a mobile and mobile or other is empty, it will tranferred to a mobile or other  
creteria is the landline start with 02 or 64 and longer than 8 (not so sure about that)
my laptop is an Chinese laptop so I have to use charset="utf8mb4"
data sampe is too small, probaly will have other problem during ETL, wrong data will be printed 
