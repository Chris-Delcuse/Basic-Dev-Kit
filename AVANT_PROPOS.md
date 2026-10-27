👨🏽‍🔧 Introduction :
-----------------

For these machines, it’s necessary to distinguish several categories in TI-Basic.

User apps: (packaged apps)
- transmitted via cable
- contain multiple formats (PIC, TEXT, PRGM...)
These are the famous PC formats .89x 92x & .V2x

Installer:
- transmitted via cable
- contain only prgm

Your Projects:
- look like a final package (that’s the Goal)

This is what we’re going to cover through this repository.

⛔️ Variables to exclude :
-------------------------
Pay close attention when you create variables !

As well as your `Prgm` names,
the use of,

ALL THE NAME FUNCTIONS INTO THE `[CATALOG]` AND SYSTEM VARIABLES IN THE `[VAR-LINK]` MENU, ARE TO BE BANNED AS USER VARIABLES NAME.

In some cases, it may NOT crash the program but due stability reasons, CONSIDERABLY increase the debugging time.

This the case with the var `mode`, this var is unstable, prefer the use of `m0de`.

🛟 Pitfall to avoid :
---------------------
Avoid naming your folders with only one letter, to ensure stability with `For` Loops.

Unique variables type ALPHA, are commonly used for formal computation. (or `Func` for executables)

📌 My advice :
--------------
To protect your work, calculations, and personal settings, I strongly recommend to ban `NewProb` from your programs.

Go create your cfg file, see the linear scripts section.

Finally, I can just recommend, to create your own repository, even this one keep private.

Let’s codîng !
