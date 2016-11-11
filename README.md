Usage: 
zot [options] <search query>
use -r to refresh and sync zotero library.
Add query to search your database.
Search results will be shown alongside an index number (if asterisc next to number then url is missing)
add -n option and index number to open result in lynx


Options:
  -h, --help     show this help message and exit
  -r, --refresh  reload
  -n NUMBER      file to open, leave zero for search mode


Simple tool for using zotero from the commandline.

Need to install termcolor and pyzotero python packages:
pip install termcolor
pip install pyzotero

in the scripy change:
USER = '*****'
API = '*****'
to your zotero user id (not username), and api key (need to generate one)

put this script in your $PATH 

and ready to play.

