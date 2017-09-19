# Get started with using the Object Lair
1. Clone this repo
2. This is a PHP-based framework, so you'll need PHP running on your computer.
3. Either place these files into a folder that's accessible by your PHP installation or point to this folder.
4. Point your PHP server to the main cloned folder. The one that has the phpinfo.php file in it.
5. If you want to check that you've got the setup right, open the browser and do:
http://localhost:[port number]/[some folders]/phpinfo.php
6. Open the datainfo.json file and put your mySQL connection data in there
7. Create a table in your database called `appuser`.
8. Make sure the `appuser` table primary key is `id` (*mandatory*)
9. But also make sure there are other fields in the `appuser` table (*more so that you can see some data when you run things*)
10. To see that anything is happening, put at least one row into the `appuser` table
11. Now open some tool like [Postman](https://www.getpostman.com/) 
