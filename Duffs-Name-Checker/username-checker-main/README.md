##### 𝕎𝕖𝕝𝕔𝕠𝕞𝕖 𝕥𝕠 𝔻𝕦𝕗𝕗𝕤 𝕌𝕤𝕖𝕣ℕ𝕒𝕞𝕖 ℂ𝕙𝕖𝕔𝕜𝕖𝕣, ℍ𝕖𝕣𝕖 𝕒𝕣𝕖 𝕥𝕙𝕖 ℙ𝕝𝕒𝕥𝕗𝕠𝕣𝕞𝕤 𝕚𝕥 𝕚𝕟𝕔𝕝𝕦𝕕𝕖𝕤, 𝕒𝕟𝕕 𝕖𝕧𝕖𝕣𝕪𝕥𝕙𝕚𝕟𝕘 𝕪𝕠𝕦 𝕟𝕖𝕖𝕕.



\---

Platform       | 	Method         |	min length     |	Speed

\-----------------------------------------------------------------------------------------------------------

Roblox         |	Official API   |	3 letters      |	Fast	                DUFFS
Minecraft      |	Mojang API     |	3 letters      |	Fast	                DUFFS
TikTok         |	Profile pages  |	4 letters      |	medium	                DUFFS
YouTube        |        Profile pages  |	4 letters      |	medium	                DUFFS

Twitch         |	Profile pages  |	4 letters      |	Fast	                DUFFS
GitHub         |	Official API   |	3 letters      |	Slow (rate limited)	DUFFS
Twitter / X    |	Profile pages  |	4 letters      |	Slow (rate limited)	DUFFS
guns.lol       |	Profile pages  |	3 letters      |	Fast	                DUFFS



features
8 platforms supported in one tool
3, 4, 5 and 6 letter username checking
letters only / letters + numbers / letters + underscore / all combined
load your own custom `.txt` wordlist
live estimated time remaining while checking
run again option after finishing — no need to restart
multithreaded — up to 50 threads
auto saves results to a separate file per platform
colored terminal UI
works on Windows, Mac and Linux



**installation
Windows**
---

**clone the repo**

```
download zip, and extract

```

**install dependencies**

```
pip install requests colorama
```

**run**

```
python username\\\\\\\_checker.py
```

\---

##### **Linux**

clone the repo

```
download zip, and extract

```

install dependencies

```
pip3 install requests colorama --break-system-packages
```

run

```
python3 username\\\\\\\_checker.py
```

\---

##### **macOS**

clone the repo

```
download zip, and extract

```

install dependencies

```
pip3 install requests colorama
```

run

```
python3 username\\\\\\\_checker.py
```

\---

usage
when you run the tool it asks you step by step:

```
[ Platform ]     pick which platform to check
[ Input Mode ]   generate automatically or load from .txt file
[ Length ]       3, 4, 5 or 6 letters
[ Charset ]      letters / letters+numbers / letters+underscore / all
[ Speed ]        normal / fast / turbo
-------------------------------------------------
-------------------------------------------------
press `ENTER` to start — hits get printed live and saved automatically.
press `Ctrl+C` at any time to stop, results already found are kept.
press `y` when prompted to run again with new settings.
-------------------------------------------------
-------------------------------------------------
output files:
```

available\_roblox.txt
available\_minecraft.txt
available\_tiktok.txt
available\_youtube.txt
available\_twitch.txt
available\_github.txt
available\_twitter.txt
available\_gunslol.txt

```
-------------------------------------------------
-------------------------------------------------
custom wordlist
you can load your own `.txt` file instead of generating names automatically:
put your `.txt` file in the same folder as `username\\\\\\\_checker.py`
run the script and choose `\\\\\\\[2] Load from custom .txt file`
type the filename when asked (e.g. `usernames.txt`)
format — one username per line, lines starting with `#` are ignored:
---------------------------------------------------------------------
tips
for GitHub and Twitter use normal speed — they rate limit hard
for Roblox 3-letter names use letters+numbers, pure letters are mostly gone
results are random every run so everyone checks different names
if you get lots of `\\\\\\\\\\\\\\\[ERR]` try lowering the thread count
on Linux if install fails add `--break-system-packages` to the pip command
-----------------------------------------------------------------------





