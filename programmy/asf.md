# \[ASF] ArchiSteamFarm

#### **ArchiSteamFarm** is a free, open-source program for working with a large number of Steam accounts at once. For a farmer it's the main tool for warming up and mass operations.

<h2 align="center">🧰 <mark style="color:green;">What it can do</mark></h2>

* #### Farm trading cards on dozens of accounts at once
* #### Rack up hours in games (warming up)
* #### Mass-change nicknames and avatars
* #### Mass-activate keys
* #### Run in the background without getting in the way of using the computer

<h2 align="center">⚙️ <mark style="color:green;">Installation</mark></h2>

1. #### Download the latest release from the ArchiSteamFarm project's **official GitHub**.
2. #### Unpack it into a separate folder, a path with no Cyrillic characters.
3. #### Run `ArchiSteamFarm.exe` — a console will open.
4. #### Open the web interface in your browser at the address the console shows.

<h2 align="center">🤖 <mark style="color:green;">Adding accounts</mark></h2>

#### Each account in ASF is a "bot" with its own `.json` config in the `config` folder. You can create it through the web interface or by hand.

#### The minimum you need to specify: login, password and a flag that the bot is enabled. Everything else — as the task requires.

{% hint style="success" %}
With a large number of accounts, it's more convenient to generate the configs with a script from your spreadsheet of logins and passwords. Filling in a hundred by hand is a road to nowhere.
{% endhint %}

<h2 align="center">▶️ <mark style="color:green;">Operation</mark></h2>

#### **Launching.** The toggle next to the bot's name in the web interface. Or the `start asf` command — it brings everyone up at once.

{% hint style="warning" %}
Don't launch more than **50 accounts** at a time. More than that — it'll start choking the system and the connection, and some of the bots simply won't log in.
{% endhint %}

#### **Stopping.** With the same toggle or the `stop asf` command in the "Commands" tab.

#### **Runtime.** Up to you — an hour, a day, a week. The main thing is not to close the ASF console and the interface tab.

<h2 align="center">💡 <mark style="color:green;">Useful commands</mark></h2>

* #### `start asf` — start all bots
* #### `stop asf` — stop all
* #### `status asf` — overall status
* #### `redeem <bot> <key>` — activate a key on an account
