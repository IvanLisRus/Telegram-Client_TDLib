# Telegram-Client_TDLib

<b>LabVIEW Implementation Telegram Client with TDLib (JSON)</b>

For start the client, you need to fill in the config file (config.ini):
- <b>phone number</b> — You must specify the phone number associated with Telegram (will require confirmation of access through a digital code);
- <b>api_id</b> — Application identifier for accessing the Telegram API, which can be obtained at https://my.telegram.org;
- <b>api_hash</b> — Hash of the Application identifier for accessing the Telegram API, which can be obtained at https://my.telegram.org.

Video: https://youtu.be/CW82ESEGEPc

Implemented parsing of only text messages of the JSON type: <i>message.content.@type = messageText</i>

Sending only text messages.

Contains library version: TDLib 1.8.1 (JSON interface) binary
Windows - 32bit | Windows - 64bit | Unix - 64bit
