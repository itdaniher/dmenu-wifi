This "wifi" script is the culmination of several revisions and
pieces of code. Designed to provide an easy way to handle wifi
connections, it can use either dmenu or arguments to select a
profile. Profiles are stored in csv(comma-seperated value) 
format in $HOME/.wifi. An example profile file is included for
reference. The code is very easy to read and is fairly solid,
but as I'm a new coder, there may be areas that are slightly 
less elegant than they could be. Suggestions, comments, and 
questions are appreciated!

To use the dmenu interface, execute the script with no args.
If the first argument is the name of a profile, the script 
will use the information and attempt to associate to the AP.
If the first argument is not the name of a profile but is 
present,the script will try and use that for the name of an AP.
