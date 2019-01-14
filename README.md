# myTinyToDo

An update to the original awesome tool by Max Pozdeev at mytinytodo.net

This updates the code from having depreciated PHP5 dependancies to use new PHP7 versions (Mainly MySQL to MySQLi) and replacing the depreciated Jquery UI Autocomplete module and early versions of JQuery and JQuery UI

Installation

Requires the PHP 7 modules for either SQLite or MySQL depending on the database that you want to use as storage (MySQL users will need to create a database with all priviliges before installing)
All files should be owned by www-data (or whatever user your webserver runs under) 


Test with Apache and MySQL/SQLite

I did a quick check with SQLMap to check that the move from MySQL to MySQLi didn't leave any low hanging SQL injections.


There are still a few things that need fixing :-
- Tag autocomplete is broken 
- No autoredirect to the mobile version
- Some monior CSS changes needed to make the buttons easier to work with on mobile.
