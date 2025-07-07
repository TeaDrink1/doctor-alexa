<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="Doctor_Alexa_0"></a>Doctor Alexa</h1>
<p class="has-line-data" data-line-start="2" data-line-end="4">An open source, self-hosted discord bot built for Fundamental Paper Education servers.<br>
This bot is designed to ban almost every member of multiple Anti-FPE/Anti-Fandom groups, as well as individual trolls who may cause problems in your server.</p>
<p class="has-line-data" data-line-start="5" data-line-end="6">(Note: Users frequently join and leave these servers, so trolls may still slip through the cracks! Do not expect this bot to be the perfect solution.)</p>
<h1 class="code-line" data-line-start=6 data-line-end=7 ><a id="Tutorial_Application_Setup_6"></a>Tutorial (Application Setup)</h1>
<p class="has-line-data" data-line-start="7" data-line-end="16">Go to the Discord Developer Portal: <a href="https://discord.com/developers/applications">https://discord.com/developers/applications</a><br>
Log into your Discord account (if you are not already logged in).<br>
Click “New Application” on the top right, and name the app whatever you’d like.<br>
Once you’re in the app’s “General Information” page, click “Bot” on the left. Scroll down to “Privileged Gateway Intents”. Toggle on all three of them, and save your changes.<br>
After that, click “Installation” on the left and scroll down to “Guild Install” at the bottom of the page.<br>
Click the dropdown box under “Scopes”, then click “bot”.<br>
Click the new dropdown box that has appeared under “Permissions”, and make sure the bot has permission to Ban Members, Send Messages, and View Channels. After that, save your changes.<br>
On the same page, go to “Install Link” and click “copy”. Paste the link into a new tab.<br>
Click “Add to Server”, and choose your server of choice. Click “Continue”, then “Authorize”. Your bot will now be in the server.</p>
<h1 class="code-line" data-line-start=17 data-line-end=18 ><a id="Tutorial_2_Bot_Setup_17"></a>Tutorial #2 (Bot Setup)</h1>
<p class="has-line-data" data-line-start="18" data-line-end="29">(Note: This tutorial is for Windows only! The installation process may be different on Mac or Linux.)<br>
Download the latest Doctor Alexa .zip file from the releases page, and extract it.<br>
Go to <a href="https://www.python.org/downloads/">https://www.python.org/downloads/</a> and download the most recent version of Python.<br>
Run the downloaded .exe file and go through the installer.<br>
After python has successfully installed, open command prompt.<br>
Type in &quot;pip install <a href="http://discord.py">discord.py</a>&quot; and press Enter.<br>
Go back to the Discord Developer Portal. Click “Bot” on the left.<br>
Click “Reset Token”, then “Yes, do it!”<br>
Your new bot token will now appear. Click “Copy”.<br>
Open “token.txt” in Notepad or your preferred text editor.<br>
Paste your bot’s token into the blank page, and press CTRL+S to save your changes.</p>
<h1 class="code-line" data-line-start=30 data-line-end=31 ><a id="Running_the_Bot_30"></a>Running the Bot</h1>
<p class="has-line-data" data-line-start="31" data-line-end="36">Open &quot;<a href="http://bot.py">bot.py</a>&quot;. If everything properly started, the console should stay open.<br>
Go to the Discord server you previously invited your app to, and say !massban to begin the banning process.<br>
(Note: You will need the “ban members” permission to run !massban. The app will also have to be able to view the channel you run the command in.)<br>
If the console starts outputting “[USER] was banned”, the bot is properly working. Make sure to leave it open during the banning process.<br>
The app will send a message in the same channel after every user was successfully banned.</p>
