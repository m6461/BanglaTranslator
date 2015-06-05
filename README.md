# BanglaTranslator
This is a shell program that translates English to Bangla/Bengali based on Swadesh dictionary. This project is done as part of the Erasmus Mundus Master in PERCCOM program's seminar in ITMO, St Petersburg, Russia.

This is a server-client model this translation service. It is assumed that the whole service will be available in a particular server where telnet is enabled for the clients.

The client will download an "expect" script and will runt it. This will automatically downlaod the necessary dictionary files. A Makefile could be made for the "expect" script and the associated language databases as per client's language.

For simplicity of testing, this file works with the user: "test" and password: "qwerty" only. 


