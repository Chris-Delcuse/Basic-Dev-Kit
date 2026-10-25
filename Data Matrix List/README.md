THEMATIC FOLDER

For Nspire owners interested in the method,

To go further and generate code, it's necessary to investigate the system and equip yourself with structured databases like the setMode...

📒 C4tlg (List)
--------
- Complete list of the [CATALOG] functions
- ( No "quotation mark", no duplicates )

![Screenshot](https://raw.githubusercontent.com/Chris-Delcuse/TI-Basic_OS-v3.10/refs/heads/main/Data%20Matrix%20List/C4talog_preview.png)

Note: Locations respected with 391 functions, commands placed under character strings, such as called on your IDE i.e. space included !

🗄 Mode (All)
-------------
- `setMode` mergeable database
- ( Compatible 89, Titanium, 92, 92+ & V200 )

![Screenshot](https://raw.githubusercontent.com/Chris-Delcuse/Basic_DevKit/refs/heads/main/Data%20Matrix%20List/setModeDB.gif)

To be placed in the `\main` folder to be merged according to your convenience.

<details>
<summary>⌨️ Merging cmd : (Example)
</summary>

    Data▸Mat m1d,m1de    ( convert m1d in a new Mat m1de )

    Data▸Mat m2d,m2de    ( convert m2d in a new Mat m2de )

    Augment(m1de;m2de)→m0d3    Merging ⚠️ Augment Syntax need ; 

    Mat▸Data m0d3,m0de   ( m0de will need manual cleaning. )

    DelVar m1de,m2de,m0d3


</details>

<details>
<summary>⌨️ Usage cmd : (Sentence Example)
</summary>
    
    "setMode("Display Digits","FIX 0")"    (Sentence to write with your new var m0de)
    
    (m0de[1][1])&string(m0de[2][1])&","&string(m0de[3][1])&(m0de[4][1])    (phrasing)

</details>

