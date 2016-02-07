# Python---P2P-Implementation   In Progress

Secure Skype like P2P implementation for text chat or voice/video calling. Free service for developers and people without having to go through complex registration mechanisms and avoid adtracking. Completely encrypted with decryption keys as independant responsibility of the user of the service since no central system or server will hold the data of the people using this service.

To understand better, on how it works please bear the following points in your mind:

>> The files clientPrimary.py and clientSecondary.py are the actual scripts that will perform the connectivity between the systems or users.

>> All the rest of the files will provide support and various functionality like audio, video, emoji etc. These files can be removed or altered however the user wishes to customize their usage.

>> The primary purpose of this repository is to create a completely secure communication channel between two computers/users. These scripts are written in order to provide a service free of Adtrackers or behaviour recognition algorithms. (which all the IT giants like Apple, Google or Microsoft unfortunately do)

>> The security or decryption key will be generated in pairs that you can share to enable communication. Please note that the system will not keep any record of the keys whatsoever so there is no support mechanism if you lose the key. You will just have to create a new key-pair if you lose one pair.

>>The scripts are designed to encrypt information before sending packets or information out so you will have impeccable security even if your OS security is breached. The scripts are disgned to encapsulate sending data (text, voice, video, image, file etc) before the network headers are put in place by the OS

Last but not least Have fun with it and create your own versions of it ;-)
