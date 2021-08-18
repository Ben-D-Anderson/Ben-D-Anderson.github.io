# Repositories #

* Software Development Projects
    * [Backed-Site](#backed-site)
    * [Backed-SDK](#backed-sdk)
    * [ClassCharts-API](#classcharts-api)
    * [PublicSMS](#publicsms)
* Minecraft Plugins
    * [InstantReplay](#instantreplay)

<hr>

<a name="backed-site"></a>
## Backed-Site ([Link](https://github.com/Ben-D-Anderson/Backed-Site))
Backed-Site is the website backend for the file backup system I made called Backed.
Backed is very security focused and therefore has encryption on user data with files never being stored on the server unencrypted.
<br />

Features:
- Account management
- MySQL integration
- REST API
- File management and cryptography
- Mailing

<br />

<a name="backed-sdk"></a>
## Backed-SDK ([Link](https://github.com/Ben-D-Anderson/Backed-SDK))
Backed-SDK is the software development kit for the file backup system I made called Backed.
The SDK interacts with the REST API in the website and creates user-friendly objects to be interacted with.
<br />

Features:
- Login as users
- Upload files
- Download files
- Delete files
- Get hashes of files
- List files
- Logout as users

<br />

<a name="classcharts-api"></a>
## ClassCharts-API ([Link](https://github.com/Ben-D-Anderson/ClassCharts-API))
ClassCharts-API is an API that I made to easily interact with the website "ClassCharts" through Java.
<br />

Features:
- Login as a student
- Access and interact with student homeworks
- Access and interact with student timetable

<br />

<a name="publicsms"></a>
## PublicSMS ([Link](https://github.com/Ben-D-Anderson/PublicSMS))
PublicSMS is a program which scraped implemented sites for public temporary phone numbers and uses them to receive text messages from a target phone. It also uses implemented sending methods to spoof messages from that number so that the target phone can have a fully functional conversation with the public temporary phone without the user of the application using their real phone number.

Warning:
- All text messages sent by the target phone to the public temporary phone are publicly accessible and readable, including the number of the target phone.
- Implementations from the websites it scrapes are subject to change at any time so may not always be functional.
- To spoof messages from the public temporary phone number, the program currently uses a service called Clockwork-SMS (renamed TextAnywhere) which requires an account, api key and credit - each text costs approximately £0.055 to send. This service is not necessarily anonymous as they do not support anonymous payment methods. If you wish to utilise this application with an anonymous sms sender, it is recommended you find a service that can spoof messages and create an issue referencing the service so it can be implemented - or implement it yourself with a pull request.
<br />

Features:
- Send and receives SMS messages without using your own phone number.
- Easily add your own implementations of websites to get public temporary phone numbers from or services to send sms messages from.

<br />

<a name="instantreplay"></a>
## InstantReplay ([Link](https://github.com/Ben-D-Anderson/InstantReplay))
Replay is a 1.7.10 Minecraft plugin I made which stores and replays player-based-events that occurred on a server.
Replay displays the events in chronological, packet based way, this means that when an administrator is replaying the events only they can see anything that is happening as to not disturb other players.

Demonstration: https://youtu.be/whTTk4MZhgg
<br />

Features:
- View player's inventory (right click them)
- View rough player movements
- View block changes
- View player joining and leaving
- View skins
- Change speed of replay
- Change radius of replay
- Choose time to play replay from (either from time unit ago or UNIX timestamp)
- Pause and resume replays
- Death and damage events in chat
- Optimized for performance
- Highly configurable

<br />
