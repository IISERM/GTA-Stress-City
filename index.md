<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

.header {
  text-align: center;
  padding: 32px;
}

.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
  flex: 25%;
  max-width: 25%;
  padding: 0;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
}

figure {
    margin: 2px !important;
    border: solid 2px black;
    border-radius: 4px;
}

figure figcaption {
    text-align: center;
}

.poster {
    max-height: 85vh;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media (max-width: 800px) {
  .column {
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media (max-width: 600px) {
  .column {
    flex: 100%;
    max-width: 100%;
  }
}
</style>

<p align="center">
  <img src="Poster.png" class="poster"/>
</p>

**Registration Link-** [https://bit.ly/TuringHunt](https://bit.ly/TuringHunt)

**People outside IISER Mohali are welcome to participate. However, they can't win prizes. Feel free to register at the same link**

# Time

**1st April, 9 pm**
Join online and stay connected with us on WhatsApp. Or visit us in H6 study room if you have a doubt.

# Theme

You’re a master's student. Your thesis is coming up. You need an advisor. You can't find anyone. You’re stressed, you don't know what to do, the world seems to spin and your life seems meaningless but there's no way out and nowhere to go. The path is riddled with obstacles. Your life is getting absurd. When the going gets tough, will you still keep going?

## Trailer

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/AeqxuTZfrMI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Prizes

All in all, we are giving away **7 prizes**.

## 1) Main Quest

The main quest follows a linear storyline, like a game, and **No Knowledge of Coding Is Required to Solve it**. There are 3 prizes-

1. First Prize:- **An Amazon Gift Card worth ₹800 and a goody**
2. Second Prize:- **An Amazon Gift Card worth ₹500**
3. Third Prize:- **An Amazon Gift Card worth ₹300**

## 2) Side Quests

There are 4 side quests in the game spread across the games, and there's a prize for each. The prize would go to the team solving them first-

1. Labyrinth Side Quest- **An Amazon Gift Card worth ₹500 and a goody**
2. Side Quest 1 - **An Amazon Gift Card worth ₹100 and a goody**
3. Side Quest 2 - **An Amazon Gift Card worth ₹100 and a goody**
4. Side Quest 3 - **An Amazon Gift Card worth ₹100 and a goody**

The Labyrinth Side Quest requires a **minimal** knowledge of coding to solve it. You need to know `loops` and `if-else`. The other 3 side quests require some knowledge about computers in general. 

A prize would be given to a team that completes a side quest first.

The side quests are independent of the main quest. You can win the main quest without having any knowledge of coding.

# Interested?

Register at [https://bit.ly/TuringHunt](https://bit.ly/TuringHunt). Yep, we got a fancy link too! **OR ELSE-**

<p align="center">
  <img src="./baby duc.jpg" class="poster"/>
</p>

# Download Links

**Note: The game is about 50MB. So please make sure you don't use up all your data**

| OS             | `ldd` | Download from                                   |
| -------------- | ----- | ----------------------------------------------- |
| Windows        | NA    | [main-win.exe](./binaries/main-win.exe)         |
| Ubuntu 18.04   | 27    | [main-2-27](./binaries/main-2-27)               |
| Ubuntu 21.04   | 33    | [main-2-33-ubuntu](./binaries/main-2-33-ubuntu) | 
| Debian Testing | 33    | [main-2-33-debian](./binaries/main-2-33-debian) | 
| Arch/Manjaro   | 35    | [main-2-35](./binaries/main-2-35)               |

## How to Run

### Windows

1. Download the windows version of the game
2. Double click the downloaded file.
3. Click `Run Anyway` if a Security pop up comes up.
4. Once the font install pop up occurs, **INSTALL THE FONT, CLOSE THE APP AND RESTART**
5. Enjoy

### Linux

1. Download the Linux version. If you use a Linux not in the above list, run `ldd --version` in your terminal. This will give your `ldd` version number. Use the version with the **highest `ldd` value lower than yours**.
2. Open a terminal and run `chmod +x /path/to/file` wherever the file is located
3. Run `./path/to/file`
4. Once the font install pop up occurs, **INSTALL THE FONT, CLOSE THE APP AND RESTART**
5. Enjoy

### Mac

1. Throw your Mac into a trash can
2. Get a friend who has a Windows or Linux laptop
3. Follow the appropriate instructions
4. Enjoy
5. Light fire to the trash can

# Promotions

The event has been organized by the [Turing Club, IISER Mohali](https://iiserm.github.io/turing-club/). You can also find us on [Twitter](https://twitter.com/Turing_IISERM?s=20&t=rLMk5rEh60kLV31UfKQuKA) and [Instagram](https://instagram.com/turing_iiserm?utm_medium=copy_link). 

The game has been built using [Tetra](https://github.com/DhruvaSambrani/turing-hunt-engine). Tetra is a game engine/game development framework. You can use it for building your own treasure hunts as well. 

# Meet The Team

You can find the faces of our amazing team below-

<div class="row"> 
  <div class="column">
    <figure>
      <img src="Abhay.jpg" alt="Abhay" style="width:100%">
      <figcaption>Abhay "Assassin" Gupta</figcaption>
    </figure>
    <figure>
      <img src="Ajay.jpg" alt="Ajay" style="width:100%">
      <figcaption>Ajay "NatalTiger26" Sharma</figcaption>
    </figure>
    <figure>
      <img src="Akshay.jpg" alt="Akshay" style="width:100%">
      <figcaption>Akshay Shankar</figcaption>
    </figure>
  </div>
  <div class="column">
    <figure>
      <img src="Aprameyan.jpg" alt="Aprameyan" style="width:100%">
      <figcaption>Aprameyan "Apra Man" Desikan</figcaption>
    </figure>
    <figure>
      <img src="https://dhruvasambrani.github.io/images/dp.webp" alt="Dhruva" style="width:100%">
      <figcaption>Dhruva Sambrani</figcaption>
    </figure>
    <figure>
      <img src="Swastik.jpg" alt="Swastik" style="width:100%">
      <figcaption>Swastik "Swastika" Patnaik</figcaption>
    </figure>
  </div>
  <div class="column">
    <figure>
      <img src="Rochan.jpg" alt="Rochan" style="width:100%">
      <figcaption>Rochan "rorochan" Das</figcaption>
    </figure>
    <figure>
      <img src="Sachin.jpg" alt="Sachin" style="width:100%">
      <figcaption>Sachin Iyer</figcaption>
    </figure>
    <figure>
      <img src="Sourav.jpg" alt="Sourav" style="width:100%">
      <figcaption>Sourav Suresh</figcaption>
    </figure>
  </div>
  <div class="column">
    <figure>
      <img src="James.jpg" alt="James" style="width:100%">
      <figcaption>"Darkness Sensei" James</figcaption>
    </figure>
    <figure>
      <img src="Jayashree.jpg" alt="Jayashree" style="width:100%">
      <figcaption>Jayashree "J" Narayan</figcaption>
    </figure>
  </div>
</div>

