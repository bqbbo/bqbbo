# My Repositories & Projects

I've developed a few dozen repositories since joining GitHub around three years ago. Although most have been deleted due to a lack of maintenance or have been completely revamped, below are my notable repositories and the information surrounding them.

## Info on Repos

Repositories are entirely made by me; code is possibly inspired by sections of other online sources. Sections where this is not the case are noted in an inline comment or the project's respective README; respective authors are credited accordingly.

Many of my "finished" projects are not being maintained and probably have a messy codebase. I plan to revive them later to fix major bugs and implement missing features. All non-archived repositories are open to any contributions.

## Projects

*This file does not include all my repositories. If a description cannot be found here, refer to the project's README.*

---

### [birthday-bot](https://github.com/bqbbo/birthday-bot) - Automated birthday announcements

Birthday bot served to announce birthdays in my old Discord server, something I found as an administrator was somewhat hard to keep track of with a larger server.

Birthday bot allows server users to freely enter their birthdays, ages, and allows server administrators to configure messages and announcement times in a birthday channel.

This bot was created using a NodeJS framework called Discord.js, and was good for experimenting with JS barrelling and module syntax. It is my largest server-side JS project, and my second major Discord bot.

### [math-game-bot](https://github.com/bqbbo/math-game-bot) - Math-inspired Discord Bot

This repository is currently my largest project, as of this commit. This bot is inspired by math worksheets that limit the numbers you can use in combination with mathematical operations to evaluate a certain product. I started this project after almost completing a "2024 Challenge" worksheet, which involved calculating every number from 1 to 100 using only 2, 0, 2, and 4.

The bot is initialized with a dictionary-like or list-like string with somewhat interpreted validation. This part is somewhat messy and was the most difficult part of the project. After a game is initialized, the bot keeps track of a list of numbers, and users can submit and view their equations.

This was the first project where I fully utilized object-oriented programming. It is complete with a simple math **interpreter** for handling user input, complete with a scanner and parser.

### [tester](https://github.com/bqbbo/tester) - Online "Flashcards"

Tester is a static HTML project that aims to help aid memorization using an importable JSON file to randomize and score multiple-choice questions presented to the user. Originally a Python script, I eventually expanded it to a static website for easier access on multiple devices and the ease of adding beneficial features.

This was created during our school's Constitutional Challenge. It includes 300+ questions across five different categories, all available as presets on the website.

Despite its simplicity, I hope to expand this project as it was extremely beneficial for memorization. The website can be accessed [here](https://bqbbo.github.io/tester).

### [jlox-interpreter](https://github.com/bqbbo/jlox-interpreter) - Dynamically typed, interpreted programming language

This project is guided by *[Crafting Interpreters](https://craftinginterpreters.com/)* written by Robert Nystrom. jlox is a dynamic, interpreted programming language written in Java. It is complete with standard control flow with support for functional and object-oriented programming.

Developing this has taught me the orientation of Java's structures and paradigms, which were surprisingly easy to grasp with prior experience in statically-typed languages.

I started this project in 6th grade and successfully wrote the lexer with some additional tokens. However, I ended up forgetting about it and only revisited it from scratch recently. The new code up to Chapter 9 is available in the updated repository, which can parse completed statements.

I would highly recommend the book. The C portion of the project will be developed after I finish the Java section.
