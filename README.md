# SkinDex & PaintDex Discord Bots – Privacy Policy

This document explains what data is collected and how it is used by **SkinDex** and **PaintDex**.

---

## Disclaimer

**SkinDex** and **PaintDex** are **not affiliated with, endorsed by, or sponsored by Fingersoft** or any other third-party company.  
The bots do **not interact with Hill Climb Racing 2 (HCR2)** and do **not provide paints, skins, or any in-game content in HCR2**. All collectibles exist only within the Discord bots.

---

## Glossary

- **Application / Discord application:** Refers to the bot user, its owners, and the servers it operates in.  
- **Data:** Refers to information stored by an instance, including personal data.  
- **Bot / instance:** A copy of the bot running the Discord application with its own data.  
- **Collectible:** Any virtual object meant to be collected within the bot (e.g., skins, paints, virtual currency).  
- **Application owners / Bot Team:** The owners of the bot with access to authentication and instance data.  
- **Moderation team:** Administrators or staff users chosen by the Bot Team.  

---

## Open Source

The code of **SkinDex** and **PaintDex** is **open source under the MIT license**.  
You may check the source code to see how data is managed, in addition to the following policy.

---

## What Data is Collected

The bots collect the following data from Discord:

- **User IDs** – Used to identify users in the database.  
- **Server (guild) IDs** – Used to store server-specific settings.  
- **Channel IDs** – Used to determine where collectibles spawn.  

Additionally, the following bot-specific data is stored:

- List of collectibles owned by users.  
- Trade history, including previous owners of collectibles.  
- User and server settings, such as player policies or spawn options.  

The bots **have access to message content only temporarily** for anti-cheat purposes.  
- Content is processed **for less than one second** and **not stored**.  
- Administrators cannot read user messages.  

---

## How Data is Stored

- Persistent data is stored on a **PostgreSQL server**.  
- Communication between the bot and database is **local and secure**.  

---

## Access to Data

- Only **application owners / Bot Team** may access the data.  
- Moderators or staff **do not have access** to user data.  
- Data is never made public and must be secured at all times.  

---

## Your Rights

- You may request a **copy or deletion** of your personal data by contacting the Bot Team.  
- Recommended contact: `nipatsuplaying@gmail.com`  

---

## Optional / Event-Based Data

For special events, temporary exceptions may occur (e.g., analyzing voice messages):

- Only if the user explicitly consents via `/player consent`.  
- The message is replying to a spawned collectible.  
- The user is not blacklisted.  
- Message length is limited (e.g., <5 seconds).  

In these cases, the message may be uploaded temporarily to a third-party service for processing (e.g., Google Speech-to-Text). **No data is stored permanently**.  

Read more about third-party data handling here:  
[Google Speech-to-Text Data Usage FAQ](https://cloud.google.com/speech-to-text/docs/data-usage-faq)  

---

## Last Updated

**22nd November 2025**
