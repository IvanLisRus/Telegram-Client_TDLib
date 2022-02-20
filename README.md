# Telegram-Client_TDLib

<b>LabVIEW Implementation Telegram Client with TDLib (JSON)</b>

For start the client, you need to fill in the config file (config.ini):
- <b>phone number</b> — You must specify the phone number associated with Telegram (will require confirmation of access through a digital code);
- <b>api_id</b> — Application identifier for accessing the Telegram API, which can be obtained at https://my.telegram.org;
- <b>api_hash</b> — Hash of the Application identifier for accessing the Telegram API, which can be obtained at https://my.telegram.org.

Video: https://youtu.be/CW82ESEGEPc

<p>Implemented parsing of only text messages of the JSON type: <i>message.content.@type = messageText</i>
<p>Sending only text messages.
<p>There may be problems with the conversion of UNICODE characters, which can lead to an error parsing the string.

<p>Contains library version: TDLib 1.8.1 (JSON interface) binary
<p>Windows - 32bit | Windows - 64bit | Unix - 64bit
<p>For Linux need install <b>zlib1g-dev</b> & <b>libssl-dev</b>

<p>In Unix, if not work, then you need to transfer library file (<i>libtdjson.so</i>) to the <i>/usr/local/lib/<i> folder and correct the paths in the <i>.../Project_lv2015/Telegram Library/Telegram Class/Methods/Initialize Path.vi</i> file to <i>/usr/local/lib/libtdjson.so</i>