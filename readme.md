program flow
0. tf2 starts up with console logging
1. autohotkey or python program listens for a specified key
2. key is grabbed, then the hotkey presses another key
3. team fortress 2 is configed that this second key executes "clear; status; print end"
4. main program launches
5. main program opens console.log, searches for "# userid" and parses the table into a list/array with these elements
      ... [[userid], [name], [connected time]
6. program first searches "name" against a list of common bots

split
7a. if common bot is found, ignore everything else and kick the most recent
