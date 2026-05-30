# Ultimate-Discord-Bot-Development-Guide: Learn and Build Discord Bots
---

## Overview

A simple open source repo for learning Discord bot development. It includes guides, examples, and small projects to help beginners start making Discord bots. Started by [@shellmonbhai](https://github.com/shellmonbhai) and maintained by [@UIU-Developers-Hub](https://github.com/UIU-Developers-Hub).

---

Welcome to Discord-Bot-Development-Guide.
This repo is made for students and new developers who want to learn how Discord bots work and how to build them step by step.

Here you will find easy examples, useful commands, bot features, and clean project structures. The goal is to make learning simple and fun without making things confusing.

You can build moderation bots, music bots, utility bots, AI bots, and many other cool projects from here. Anyone can learn, practice, and also contribute to the repo.

---

## What Is a Discord Bot?

Discord keeps getting more popular. As servers grow, it gets harder to manage everything by hand. Tasks like banning users who break the rules or replying to common requests can take a lot of time. That's why automation becomes so useful.

A Discord bot is a program that acts a lot like a regular user. It can watch for events, respond to commands, and handle tasks on its own. Bots can be used for almost anything. In fact, there are nearly unlimited ways to use them. You can see plenty of examples on [top.gg](https://top.gg/).

For example, imagine you're running a new Discord server. A new member joins for the first time. You might be excited and send them a welcome message yourself. Maybe you point them to a few channels or ask them to introduce themselves.
The new member feels welcome and joins the conversation. If they enjoy the community, they may invite their friends too.

As time goes on, your server gets bigger. At some point, it becomes difficult to personally greet every new member. Still, you probably want each person to feel noticed when they join.
This is where a bot can help. It can automatically welcome new members the moment they join. You can also decide how the bot should behave in different situations and what messages it should send.
That's just one simple example. Bots can do much more than welcome users. Once you learn how to build them, you'll find all kinds of ways to make your server more helpful, fun, and easier to manage.

**Note:** Discord bots can work with voice features too, but this guide focuses only on text-based features.We'll discuss voice features later.

### Two Main Steps to Create a Bot

Creating a Discord bot comes down to two main steps:

1. Create a bot account on Discord and add it to your server.
2. Write code that uses Discord's API and tells the bot how to behave.

---

## How to Make a Discord Bot in the [Developer Portal](https://discord.com/developers/home)

Before you start writing any Python code, there are a few things you need to set up in Discord first:
* A Discord account
* An application
* A bot
* A server (guild)

You'll learn what each of these does in the next sections.
Once everything is ready, you'll connect them together and add your bot to your server.
To get started, open the [Discord Developer Portal](https://discord.com/developers/applications). That's where you'll create and manage your Discord applications and bots.

**1. Creating a Discord Account**

First, you will see a login page. You can log in if you already have an account. If not, you need to make a new one.
Click the **Register** button under Login. Then fill in your details.

<img width="1512" height="881" alt="image" src="https://github.com/user-attachments/assets/9030ae5f-cfcf-42e7-8537-d4d4ed95686f" />

**Important:** You must verify your email before you go next.

After that, you will be redirected to the Developer Portal home page. That is where you create your application.

**2. Creating an Application**

An application lets you use Discord’s API. It also gives you things like auth tokens and permissions.
To start, click **New Application**.

<img width="1230" height="486" alt="image" src="https://github.com/user-attachments/assets/17f179e0-5d2e-4d6c-b176-49c4918a8c9c" />

Next, you will see a box to name your application. Pick a name you like. Then click **Create**.

<img width="1255" height="575" alt="image" src="https://github.com/user-attachments/assets/30b6915b-9769-4084-aec1-502f2b13a16e" />

Congrats. You just made a Discord application.

<img width="1255" height="702" alt="image" src="https://github.com/user-attachments/assets/e9df7b40-9ae0-4c7f-bd2a-1ba5e1a16e4c" />

Keep in mind, not every program that uses Discord needs a bot. All tools that use Discord API start with an application. Bots are just one part of it.
Since this guide is about bots, click the **Bot** tab on the left side menu.


**3. Creating a Bot**

A bot is a user that can listen to things on Discord and react on its own.
To make your code work in Discord, you need to create a bot user. Click **Add Bot**.

<img width="3021" height="1761" alt="image" src="https://github.com/user-attachments/assets/894cc648-2625-4ffd-adfe-bfba4642b4f0" />


**Note:** This step used to be required earlier, but in the current Discord update, the bot is created automatically when you create an application.


<img width="1876" height="1037" alt="image" src="https://github.com/user-attachments/assets/5912fa3e-20f9-45cb-9851-c08050683f4a" />
