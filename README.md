# vrp_shoowroomprotection
 This script brings a change to Sighmir's resource, which prevents the Cheat-Engine from running on your servers.


#If you get SQL errors it should be because its made to work with databases that accept ADD IF NOT EXISTS.
To create the tables on your database follow the steps:

Remove every IF NOT EXISTS from server.lua
Run the server once.
Comment out the MySQL.query("vRP/showroom_columns") adding -- before it
Restart the server one more time.
You're good to go from now on.

