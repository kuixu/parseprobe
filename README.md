# ParseProbe
Automatically Parse Stellaris® Probe Designer Data using Javascript code.

## How to Run
1. open `https://www.biosearchtech.com/stellarisdesigner` using Chrome.
2. Login, using your own account and passwd. 
3. Open the `JavaScript console`, (Option+Command+J, ⌥⌘J) or Mean --> View --> Developer --> JavaScript console, in Chrome.
4. Paste the code in `parseprobe.js` file into `JavaScript console` and Run it By ENTER.

	
	
## Results
Put your sequence into `var sequence` in the code, just like:

		var sequenses={ "tusc7": "GGGGTACCAAAGTCCACTCTGAGCTTTTCCTCTGGGAACAGATCCCAGATTATTCCAGACTTAAGACATGGAGATATATCTTGCTAGAGGTAGGAAGATGATAAGATCAGTTTCTATAGGTAGAGGATAATGTGTCCTAAAATGTAGGTAGAGATAAGTCTGACAGTGGTTTAGACAAAAAGGGCCTCTGCTAATGGTGGAGAGATCAAGGAAGAAAAGAGCAACGTTAAAGTGAGGCTGTACCCACAGATCATGCTCAAGCAAATTCGAACCGTGAGCGCATTTCTCTTAAACAATGAACACTTAGAATAAAAATTAAAATTTCCCACAAATTTCTAATTTTAAAATAGTTTCCCAAGATTTCAGTGGTATTGTATATATGCCCATATAATTTTTTGGATTACTATTCCCACAAGTGTAAGATGAAAGAGGACCTGCCCTCCATTCTATCTACTCCCTCTCTGCAAAGGCCATTTTGAAGATCTCAGTTTTACTGAAAGGGGTCTGCCACACATAACTTCCCTGGTGTACCAGCAACAAGTGTTCAGTGGACCATGGCAACACAAAGAATGACGGAGGAGAGAAAATGCCATGCAGAAGTGATAGTCAAGATGAAGATGTGGGAGAGGAGCAGCCCCCAGTATATATTCAGTGTGTCCTCTGAAGTAACAACCATCCCATCTGGCTGAGAAGTGATGGACACGGCTCCTTAACCACACTGTACCCTCTGTTCTTGGCACCTCTCTACCAGAAAGATATCAACAAATTGGATGGAATTCAGAGAACAGTAAGAAAAATGATTAAAGAGATGGAGGCAGTGACTTATGAGGAAAGATGAAAAGGACTAAATCTATGTAGCTTGGCAAAGCAACAACTGAGGTGGCGTATGAAAACTGTCTACAAGCATTTGAAGAATATAAACACCAAGGGAAGAGAGGGAACTTTTTAGAATGGTCTGGGGAATAAGCAGAGTAAGAGGACAGAATTGAAGAAAGGAGAGAGATATGCTAAGTTGGGGGTGGGGGCGTTTTCTCATCAATTGTAAATTTTGATAAATAACAAAATTAAGTCTGGAGAGAAAGAGTTGCATCTCATGCTTTTAGGTTACAATCAGTGTTGACCTGCACTGAGAAAATGTGACTTCCTATTATCCTTCTCAAAGTTATTGCTGCAGAGGAAAGAAGCATACATCTTTTACCCACCAGGAAACCCCCAAAGCATCTATTACCATAATAGCCATGGGAAACAGAAGGCACCTCAAATAAAGGTGGGGAAAAGAATGAAAGAAATGGCTTTGGCCTGTGCCTGTTTGACCTCTGAGAGATACTTTTTGCAAGAAATTGTTAAGTTTTGGCCCAAAAAGTGGTCGGTCTTTTATCCTTCCTTGTGGAGGCCAAACTGCAAACCAGGATGAAGAAACCATCAGTGGCAGTTTGGGGAGGTGGAGGAGGGACTATCTAGACTCAGTGAATCACCAAGGAAACATGAGGCCTATTTCTCTGTGAAGCTGAACTTCAAAAAACAATCTAAGAGATACAAAGGGAAAAGTGTGACTGCTCTGACAGCAAAAACAAGCAAATATCTCCAGAGGGGATTAATCCTTCTGCTTCAAAGTAACTAAAACAAAGAAAGCTGAGCCAGCTTCACTGGAAACAACACCTGTCCATCAGACAAGGATGAGCTAATCAAAAGAAAACACTGCCTATGTGCACGACTCAGCAGCCTGGACAGCTAATACCAAGGAACACGTTTTCACTATAAAGATTCAGCTTTCAAAATCCAGTTCCCTCTTGTAGAGCCACAGGGTTAAAAGGGACCTTAGAGATCATCTACATACAGGCCAAACCCTCAATGAATGCCAGTGTTCGCCTTATGTTCTTCTTGCCGGACTCTTTTCTGGCCTCTGTTCTGTCAGGATGTTTCCTGTTTTGCAAAACAGCTTTAATCCTTGAGTATATTTAATTGTTAGAAAACAGTTCCTCAAATTTGACCCCAAATTTAAGTCTAATTTATGAAGAAAGTTTTGCCTTTGGAGACAGGTTTAATTTTACTTCCATGTGGAAAACCTTCAAATAAAATGATGACTATTGTGTACTCACGAAAAA"};

Results	are listed in the current chrome browser page.

|	id	    |key     	|$id	|gc		|position| sequence|
| -------- 	| ---------	| -----	| -----:| ----:| :-------- |
|0			|tusc7		|2		|50		|4		|ctcagagtggactttggtac |
|1			|tusc7		|3		|40		|145	|gtcagacttatctctaccta |
|2			|tusc7		|4		|45		|257	|cacggttcgaatttgcttga |
|...

## To Do
1. Scripts which can convert fasta to json.
2. More beautiful presentation in browser page.
