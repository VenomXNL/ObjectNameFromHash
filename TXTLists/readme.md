These files can be used for your own object scanner or what ever,
they can ofcourse also be used to simply search for the hashes with Notepad for example.

I have posted 4 different files:
Objects-HashFirst.txt		= Are the hashes with the model name second in the list (Example: -1267889684=02gate3_l)
Objects-ModelNamesFirst.txt	= Are the hashes with the model first second in the list (Example: 02gate3_l=-1267889684)

The other two files are basically exactly the same, but with the 'extra add-on' to them that on every line
INFRONT of over line it says <FRONT>, and at the END of everyline it says <BACK>

This to make it easier for you to use them in Notepad(++) for example and do a "Search And Replace" for all
<FRONT> portions and the same for all the <BACK> portions. This should make it much easier to put them
in you own array when you for example replace all <BACK> with , 

(I guess you'll get the point ;) )

Those 'prefixed files' can be found here:
Objects-HashFirst-WITHPREFIX.txt
Objects-ModelNamesFirst-WITHPREFIX.txt

Ofcourse you can also just use the 'pre-supplied' script/lua which gives you the option to type:
objectname HashNumberHere

In your F8 console (in FiveM),
This will instantly report back the (known) modelname for the hash you've entered (all hashes are in int32 btw)

