## Whatsapp chat analysis

<img align="left" width="60" height="60" src="https://lh3.googleusercontent.com/bYtqbOcTYOlgc6gqZ2rwb8lptHuwlNE75zYJu6Bn076-hTmvd96HH-6v7S0YUAAJXoJN">

Although WhatsApp doesn’t have a public API, it does allow users to export their chat history into a txt file.

With this data (from Android OS) and using Python, I tried some analysis about chat groups I belong. 

How to save your chat history:\
Android --> https://faq.whatsapp.com/en/android/23756533/


The project goals are to determine:

- the most "active" year, in terms of messages sent;
- the most active member on the group (highest number of messages sent);
- the activity per hour (30 minutes windows) across the days (per member);
- the most "image sender" member and "audio sender" member;
- the most typing member (characters per message);
