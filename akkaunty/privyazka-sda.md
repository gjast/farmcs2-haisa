# Linking SDA

<figure><img src="../.gitbook/assets/аккаунты.png" alt=""><figcaption></figcaption></figure>

#### **SDA (Steam Desktop Authenticator)** is Steam's mobile authenticator, just on your computer. It generates login codes and confirms trades, and most importantly — it gives you the **maFile**, the file with the account's keys.

{% hint style="warning" %}
The maFile is essentially the account itself. Lose the file — lose the ability to confirm trades. Give away the file — give away the account. Back up the entire `maFiles` folder to a separate place immediately.
{% endhint %}

<h2 align="center">⚙️ <mark style="color:green;">Installation</mark></h2>

1. #### Download SDA **only from the official repository** on GitHub. Builds from shady sites and Telegram are the most popular way to gift someone your farm.
2. #### Unpack it into a separate folder. A path with no Cyrillic characters.
3. #### First launch — the program will ask you to create an encryption password. Come up with one and write it down.

<h2 align="center">🔗 <mark style="color:green;">Linking an account</mark></h2>

1. #### Click **Setup New Account**.
2. #### Enter your Steam login and password.
3. #### The program will ask for the code from your email — grab the message, paste the code.
4. #### Enter a phone number if Steam requires it.
5. #### You get a **Revocation Code (R-code)** — write it down separately; without it you can't recover the account.

{% hint style="warning" %}
**Always write down the R-code.** It's the only way to remove the authenticator if something goes wrong. People lose accounts exactly at this step because they scrolled past the code window without looking.
{% endhint %}

<h2 align="center">📌 <mark style="color:green;">Important nuances</mark></h2>

* #### Do the linking **from the same IP** you registered the account from.
* #### After linking, Steam puts a one-week restriction on trades and selling — that's normal, it's the same for everyone.
* #### Don't link a hundred accounts in a row without breaks; let the process look alive.
* #### Keep the `maFiles` folder backed up in at least two places, one of them offline.

{% hint style="success" %}
When accounts go into a panel, it usually needs exactly the maFile — it lets it log in automatically and confirm sending the drop without any manual input.
{% endhint %}
