# batclient-hitcounter V1.0? By Jkk<br>
A hit message counter for batclient.<br>
Counts and reports your attacks.<br>
Thanks to Kohothegreat for advice with regexp<br>
Tell me if something bugs or it misses hits or records something that it should not<br> 

<b>Instructions</b><br>
Copy hitcounter.bcs into your batclient\scripts folder, type /scriptreload and /scriptbootup in batclient or restart the client.<br>
You have to have correct battle settings for the trigger to work:<br> 
'battle listen all 3' or 'battle listen yourname 3'. Replace yourname with your name.<br>

<b>$hits</b> - View your hits.<br>
<b>$hits (r)eset</b> - Reset your hit counter. Restarting the client or reloading the scripts also resets the counter.<br>
<b>$hits (s)tore</b> - Store current hits so you can compare them later. Does NOT store hits over resets.<br>
<b>$hits (c)ompare</b> - Compare current and stored hits.<br>
<b>$hits slash</b> - View all slash type attacks.<br>
<b>$hits pierce</b> - View all pierce type attacks.<br>
<b>$hits bash</b> - View all bash type attacks.<br>
<b>$hits shield</b> - View all shield attacks.<br>
<b>$hits unarmed</b> - View all unarmed attacks.<br>


<b>'$hits' output looks like this:</b><br>

Slash attacks:<br>
lightly cut    1  (1%)<br>  
cut            65 (47%)<br>
tear           35 (26%)<br> 
incise         1  (1%)<br>
incisively cut 1  (1%)<br>  
cruelly tatter 2  (1%)<br>  

Missed attacks:<br>
missed         22 (16%)<br>
dodged         6  (4%)<br>
parried        4  (3%)<br>


<b>'$hits compare' output looks like this:</b><br>
Hit              Stored         Current  Diff<br>
Slash attacks:<br>
lightly cut     1  (1%)   --->  0  (0%)  -1%<br>
cut             65 (47%)  --->  14 (64%) +17%<br>
tear            35 (26%)  --->  4  (18%) -8%<br>
incise          1  (1%)   --->  0  (0%)  -1%<br>
incisively cut  1  (1%)   --->  0  (0%)  -1%<br>
incisively tear 0  (0%)   --->  1  (5%)  +5%<br>
cruelly tatter  2  (1%)   --->  0  (0%)  -1%<br>
savagely shave  0  (0%)   --->  1  (5%)  +5%<br>

missed attacks:<br>
missed          22 (16%)  --->  1  (5%)  -11%<br>
dodged          6  (4%)   --->  1  (5%)  +1%<br>
parried         4  (3%)   --->  0  (0%)  -3%<br>

