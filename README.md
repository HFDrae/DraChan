# Dra-chan

### Author : Dra

---

Hello, here is the repo for my utilitarian Discord Bot made in Kotlin.

## Why creating her ?

There is already a lot of bots present on Discord, but I still wanted
to make a bot for 2 main reasons :

- Bots online don't really do exactly what I want
- I prefer to have the fewer bots possible on my servers
- That's always a good way of training

## How to use her ?

To use this bot you'll need 3 things :
- Clone this repo
```shell
# ssh
$ git clone git@github.com:HFDrae/DraChan.git

#https
$ git clone https://github.com/HFDrae/DraChan.git
```
- Get a Discord token for your bot [here](https://discord.com/developers/applications).
- Find a way to host it (for example, I'm hosting it on my Raspberry PI).

## How to contribute ?

To contribute to this repo, feel free to fork it and make a pull request or DM me on Discord (@Dra#5092) !

## Libraries/Language(s) used

On this project I used :
- [Kotlin](https://kotlinlang.org/)
> As the main language for the bot, I recently took a liking to it.
- [Discord4j](https://github.com/Discord4J/Discord4J)
> To communicate between my scripts and Discord.
- [Kotlin Coroutines (Reactor)](https://github.com/Kotlin/kotlinx.coroutines/tree/master/reactive/kotlinx-coroutines-reactor)
> To make asynchronous calls as Discord4J uses [Project Reactor](https://projectreactor.io/).
- [Exposed](https://github.com/JetBrains/Exposed) // [SQLite](https://sqlite.org/index.html)
> To use a SQL database
- [Retrofit](https://square.github.io/retrofit/)
> To make calls to REST API
- [SWarFarm](https://swarfarm.com/api/v2/)
> SWarFarm's API for Summoners War related commands