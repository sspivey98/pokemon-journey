# Starting your Pokemon journey

- Namespace: challenges
- ID: pokemon-journey
- Type: custom
- Category: Overflow
- Points: 30
- Templatable: no
- MaxUsers: 1

## Description

Welcome new pokemon trainer to the world of pokemon! You are starting your journey and you'll need a pokemon pal to be your companion. I have a pikachu for you! Please don't mind any other pokemon I may have in the back... 

## Details

Connect to the program with netcat:

`$ nc {{server}} {{port}}`

The program's binary can be downloaded {{url_for("pokemon", "here")}}.

## Hints

- Have you ever heard of a heap overflow?
- You may need to dig around to find the correct function pointer.

## Solution Overview

Figure out how to overflow the buffer. Then, figure out where the address of the vulnerable function is and change it.

## Challenge Options

## Learning Objective

Understand how a heap overflow works.

## Attributes

- author: sspivey