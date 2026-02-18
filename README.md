# Awesome Programming Games

## An ultra mega giga curated list of programming games

(N.b.: Only *readily playable* games will be included here. This means that
original code is available (as well as a separate emulator if needed), or one
or more reimplementations, or both. Examples such as
[Struggle](https://pages.lip6.fr/Christian.Queinnec/WWW/Concurrency.html) are
all well and good but are excluded by this criterion. Additionally there have
to be at least some scraps of documentation. This would appear to exclude a
game like ['bot](https://corewar.co.uk/bot.htm). Lastly, I have now specified
as a [response to a question on a pull
request](https://github.com/readyready15728/awesome-programming-games/pull/18),
namely "What qualifies a game as being gamified?" that "The application or
site should have many of the trappings of a traditional computer or video
game." Currently, a number of entries included in the `README.md` do not fit
this criterion and will eventually be moved to a separate
`awesome-coding-challenges` `README.md`.

## Classic Games (in Order of Release)

| Title | Description and Notes |
|---|---|
| [*Darwin* (1961)](https://corewar.co.uk/darwin.htm) | A historically significant game and experiment in artificial life first implemented on an IBM 7090 at Bell Labs. Players create machine code "organisms" with the twofold goals of becoming the most prolific replicators and wiping out all of their foes. |
| [*RobotWar* (1970s)](https://corewar.co.uk/robotwar.htm) | A programming game originally written for the legendary PLATO system. (For more information on PLATO, consider picking up [*The Friendly Orange Glow*](http://friendlyorangeglow.com/) by Brian Dear.) The original object of the game was to use a register-based language apparently inspired by assembly and BASIC to control the movement, radar and gun of a battle robot and be the last standing out of two. A later Apple II release available on the linked website expanded the number of contestants to as many as five. There is even a [Clojure reimplementation](https://github.com/richardharrington/robotwar), though it seems incomplete. |
| [*Color Robot Battle* (1981)](https://corewar.co.uk/colorrobotbattle.htm) | A game with a similar premise as *RobotWar*, though competing robots are now armed with missiles as well as a laser gun. In addition, the language created for this game appears to be partially inspired by Logo. The retrocomputing site [Color Computer Archive](https://colorcomputerarchive.com/) hosts the [original TRS-80 binary](https://colorcomputerarchive.com/repo/Disks/Games/Color%20Robot%20Battle%20(Tandy).zip) as well as a [PDF of the original manual](https://colorcomputerarchive.com/repo/Documents/Manuals/Games/Color%20Robot%20Battle%20(Tandy).pdf). |
| [*Rocky's Boots* (1982)](http://www.warrenrobinett.com/rockysboots/) | An educational logic puzzle game that teaches the fundamentals of digital logic circuits for ages 9 and up, which received wide acclaim. The Internet Archive has the [manual](https://archive.org/details/A2_Rockys_Boots_manual/mode/2up) corresponding to the Apple II binary found at the title link. |
| [*Robot* (1983)](https://corewar.co.uk/robot.htm) | Another *RobotWar* derivative with a language inspired by assembly and BASIC written for the somewhat obscure early home computer known as the [Sol-20](https://www.sol20.org/). *Robot* innovates on the existing formula with the addition of shields and cloaking devices to protect the fighting robots and the addition of land mines, electric fences and blockades on the battleground. The title link has binaries written in a text format with the extension of `.ent`, which are to be used with the emulator, called [Solace](https://www.sol20.org/solace.html). |
| [*Core War* (1984)](https://corewar.co.uk/) | Another game in the vein of *Darwin*, which is a bit more refined as I understand it. The website hosts a number of resources on Core War, including executables and documentation, along with a [1998 Usenet post from `rec.games.corewar`](https://corewar.co.uk/darwin/kline73.txt) that draws more concrete comparisons between the two aforementioned games than what I can provide here. |
| [*DROID* (1984)](https://corewar.co.uk/droid.htm) | A rather obscure one for an obscure family of computers, the [HP-3000 series](https://en.wikipedia.org/wiki/HP_3000). The game itself is written in [Systems Programming Language](https://en.wikipedia.org/wiki/Systems_Programming_Language), while the robots are programmed with a stack-based language called "D-code". |
| [*Robot Odyssey* (1984)](https://en.wikipedia.org/wiki/Robot_Odyssey) | The sequel to *Rocky's Boots* and even more challenging! |
| [*ChipWits* (1984-1985)](https://en.wikipedia.org/wiki/ChipWits) | A programming game originally released on Macintosh (1984), and later ported to Commodore 64 and Apple II (1985), written by Doug Sharp and Mike Johnston. The player uses a visual programming language called IBOL to teach a virtual robot how to navigate various environments of varying difficulty. The game straddles the line between entertainment and programming education. The original versions are easily [playable via in-browser emulation](https://chipwits.com/retro/) on the game's [official website](https://chipwits.com/). The [FORTH source code](https://github.com/chipwits/chipwits-forth) for the game was [recovered](https://chipwits.com/2024/11/16/chipwits-40th-birthday-original-forth-code-open-sourced/) and released for the game's 40th anniversary. The game has a [modern reboot on Steam](https://store.steampowered.com/app/2330720/ChipWits/). |
| [*Arena* (1985)](https://corewar.co.uk/arena.htm) | Another one where robots duke it out on a shared battleground. The language appears to be a fairly pure assembly language without too many other influences. |
| [*Crobots* (1985)](https://corewar.co.uk/crobots.htm) | The "C" is pronounced like in "C programming language", because this variant of the battling robot formula uses a subset of C as opposed to an assembly variant. In addition to the title link there is also a dedicated [*Crobots* website](https://crobots.deepthought.it/home.php). It includes a somewhat buried [HTML-formatted manual](https://crobots.deepthought.it/html/manual.html). |
| [*P-Robots* (1988)](https://corewar.co.uk/probots.htm) | Inspired by *Crobots* but players use Pascal to program contestants. Includes various embellishments on the basic formula, including the option of teams instead of a battle royale. |
| [*Omega* (1989)](https://corewar.co.uk/omega/) | Automated tank battler with a campaign that requires the player to overcome increasingly difficult challenges (while being allowed increased budgets at each stage) until they unlock the titular "omega" unlimited budget for tank design. As in several previous titles, team tactics are possible. The tank language was subject to intense quality testing during development and is a BASIC variant, easing the difficult task of programming the tanks. The website includes dozens of tank designs. |
| [*Jintori* (1990)](https://corewar.co.uk/jintori.htm) | "*Jintori* is played on a 180×180 grid by programs written in an assembly-like programming language. The aim of the game is to surround as much territory as possible." It appears to be loosely inspired by the game of Go but I can't tell you more because the documentation is in Japanese. |
| [*Battle Droids* (1991)](https://corewar.co.uk/battledroids.htm) | Another, perhaps lesser-known tank battler using BASIC. The documentation seems quite excellent. |
| [*ARobots* (1992)](https://corewar.co.uk/arobots.htm) | Tank battle royale using 8086 assembly. Documentation is fairly scant but several pre-built robots are available. The available primitives include a random number generator, reminding me of how science fiction author Fred Saberhagen's fictional killing machines known as "[Berserkers](https://tvtropes.org/pmwiki/pmwiki.php/Literature/Berserker)" use random numbers based on radioactive decay to make their behavior unpredictable. |
| [*AT-Robots* (1992)](http://necrobones.com/atrobots/) | Tank battler using assembly-like with languages with a few interesting nuances in addition to the standard milieu, such as the need to manage heat. Website includes the results of past tournaments and the source code of robot tanks entered into said tournaments. |
| [*Combat Zone* (1993)](https://corewar.co.uk/combatzone.htm) | Shareware robot battler for Windows 3.x. Language possibly inspired by Logo. |
| [*CoreLife* (1993)](https://corewar.co.uk/corelife.htm) | "Programs are written in a two-dimensional assembly-like language. Each instruction has one or two arguments and direction flags to indicate the flow of control." An influence on the later *TIS-100*? |
| [*TclRobots* (1994)](https://wiki.tcl-lang.org/page/TclRobots) | Like *Crobots* but with Tcl instead of C. Both written by the same author, Tom Poindexter. |
| [*TORCS* (2001)](http://torcs.sourceforge.net/) | *The Open Racing Car Simulator*, developed since 1997 and usable both with human driving and the automated sense relevant here. Has been used in [numerous research papers](https://scholar.google.com/scholar?q="Open+Racing+Car+Simulator") since its release. |

## Recent Games, Traditional Software

### Tomorrow Corporation (in Order of Release)

| Title | Description and Notes |
|---|---|
| [*Human Resource Machine*](https://tomorrowcorporation.com/humanresourcemachine) | Rather than being a tank battler, this newer title expects you to use a toy assembly language to match inputs to expected outputs in a cute corporate office environment. Having played this game myself, I liked the idea but the lack of labeled subroutines and resulting visual spaghetti code really started getting to me after level 20. |
| [*7 Billion Humans*](https://tomorrowcorporation.com/7billionhumans) | The sequel to *Human Resource Machine*, but with parallel computing! Haven't played this one yet. |

### Zachtronics (in Order of Release)

(N.b.: I am not including *all* Zachtronics games but only those that fall
under the "programming" rubric. I have now excluded a number of titles such as
*SpaceChem*.)

| Title | Description and Notes |
|---|---|
| [*KOHCTPYKTOP: Engineer of the People*](http://www.zachtronics.com/kohctpyktop-engineer-of-the-people/) | The title appears to be Cyrillic but those are really just capitalized ASCII characters that match their Cyrillic counterparts. Presumably pronounced "CONSTRUCTOR". The game is based on designing integrated circuits based on specifications provided by a manager in what is presumably some sort of Soviet factory, with an overarching plot somehow involving a mysterious connection to communism. |
| [*TIS-100*](http://www.zachtronics.com/tis-100/) | 80's-themed assembly language puzzle with multiple independently programmable nodes capable of communication with each other, apparently a sort of [MIMD architecture](https://en.wikipedia.org/wiki/Multiple_instruction,_multiple_data). Features extensive manual that reads "like the real thing". |
| [*SHENZHEN I/O*](http://www.zachtronics.com/shenzhen-io/) | Build increasingly complex digital logic circuitry, this time not for your Soviet boss, but as a worker for a private firm in the "electronics capital of the world". Shares the same sort of extensive, realistic documentation present in *TIS-100* and includes a solitaire minigame. |
| [*EXAPUNKS*](http://www.zachtronics.com/exapunks/) | Multi-agent programming in assembly with a strong cyberpunk flair. [Users have likened the overall architecture to multi-threading or even the more advanced model put forward by Erlang.](https://www.reddit.com/r/exapunks/comments/hxwyzv/whats_the_analog_to_exas_in_realworld_programming/) |

### Others

| Title | Description and Notes |
|---|---|
| [*Adventure Land*](https://adventure.land/) | Indie MMORPG with optional automation of tedious grinding by programming player characters with JavaScript. (Appears to be abandoned.) |
| [*Algo Bot*](http://www.algo-bot.com/) | Rescue a colony ship's mission in space using a visual programming language. Users have claimed to experienced various difficulties including with a buggy Linux native version. |
| [*AntMe!*](http://www.antme.net/) | Learn to program by automating computerized cartoon ants in C# or VB.NET! Much documentation appears to be only available in the original German. |
| [*Automachef*](https://store.steampowered.com/app/984800/Automachef/) | Meet the demands of a hectic commercial kitchen the best way anyone can: with programming! There are two related assembly languages used in game with some helpful visual elements for neophytes. |
| [*Autonauts*](https://store.steampowered.com/app/979120/Autonauts/) | Build and, of course, automate a colony of agriculture and industry using a Scratch-like visual programming language. |
| [*Bashcrawl*](https://gitlab.com/slackermedia/bashcrawl) | "Learn Linux commands by playing a simple text adventure." |
| [*Battlesnake*](https://play.battlesnake.com) | Multi-player "Snake" game with the standard goal of becoming a bigger snake by eating but also of avoiding other snake bots. Game is entirely language-, platform- and algorithm-agnostic and demands only that you implement a web server that implements the game's API, which is used to map the state of the board to the next move at any given time step. |
| [*Botomy*](https://botomy.com/) | RPG-style game with free-for-all and cooperative survival modes, also driven by a technology-agnostic API approach. |
| [*Bug Brain*](http://www.biologic.com.au/bugbrain/) | Automate a digital ladybug and perform other experiments by building neural networks. Since exclusive OR (XOR) is one of the examples it appears safe to assume these aren't only perceptrons depicted on the website. |
| [*ChipWits*](https://store.steampowered.com/app/2330720/ChipWits/) | A modern reboot of the original 1984 version, ChipWits combines a 60+ mission factory automation campaign that doubles as a tutorial, 8 classic missions from the original, and periodic "ChipWit Challenge" puzzles with a global leaderboard. You program your robot using IBOL, a visual programming language, which makes it accessible to non-programmers as well. |
| [*Code E.D.*](https://jaywee1115.itch.io/code-ed) | Use Lua to program a robot exploring a new habitable planet for humankind. Features a fairly sophisticated editor with help features and interactive debugger. |
| [*Codemancer*](https://codemancergame.com/) | Learn to program using a specialized visual programming language. Targeted at ages 6-12, but suitable for all ages. |
| [*Colobot*](https://colobot.info/) | Use a bespoke language similar to C++ and Java to explore and colonize hostile planets after life on Earth is threatened by a great cataclysm. |
| [*Comet 64*](https://store.steampowered.com/app/1397290/Comet_64/) | Use a hybrid of assembly and C-like syntax to unlock the mysteries of the titular fictional computer. Includes leaderboards for minimizing instruction and cycle counts. |
| [*Craftomation: Programming & Craft*](https://luden.io/craftomation/) | Automate the terraforming of a frozen planet with robots programmed using a visual programming language. |
| [*Crescent Loom*](https://crescentloom.com/) | Evolve digital creatures using biologically plausible neural nets. |
| [*Cyber Sentinel*](https://store.steampowered.com/app/485970/Cyber_Sentinel/) | Experience the hacker's side of cyberpunk by using visual programming to create computer viruses.  |
| [*DeepestWorld*](https://deepestworld.com/) | Explore, hunt monsters, gather resources, craft and grind using JavaScript to automate the actions of your character. |
| [*Debugger 3.16: Hack 'n' Run*](http://www.spiderwork-games.com/debugger.htm) | Help a sentient debugger get rid of all the bugs in a developer's game worlds. |
| [*Dreamjob: Programmer Simulator*](https://store.steampowered.com/app/1264390/Dreamjob_Programmer_Simulator__Learn_Programming_Games/) | Climb the corporate ladder and level up as a programmer using Python, C++, C#, Java or JavaScript. (TBA.) |
| [*Duskers*](http://duskers.misfits-attic.com/) | "Pilot drones into derelict spaceships to find the means to survive and piece together how the universe became a giant graveyard Pilot drones into derelict spaceships to find the means to survive and piece together how the universe became a giant graveyard." |
| [*Echoes of the Architects*](https://store.steampowered.com/app/3136490/Echoes_of_the_Architects/) | Use a very high-level programming language to compete in an RTS autobattler. |
| [*Else Heart.Break()*](http://elseheartbreak.com/) | 3-D graphical adventure game in which numerous everyday objects can be programmed as a means of solving the game's puzzles. |
| [*The Farmer Was Replaced*](https://store.steampowered.com/app/2060160/The_Farmer_Was_Replaced/) | "Program and optimize a drone to automate a farm and watch it do the work for you. Collect resources to unlock better technology and become the most efficient farmer in the world. Improve your problem solving and coding skills." |
| [*git-game*](https://github.com/git-game/git-game) | "Terminal game to test Git skills." |
| [*git-game-v2*](https://github.com/git-game/git-game-v2) | Sequel to git-game testing the user on more advanced aspects of Git. |
| [*Gladiabots*](https://gladiabots.com/) | Configure squads of robots with a visual programming language. Test and improve your strategies then deploy them on the battlefield against against computer opponents or online against other humans. |
| [*Glitchspace*](https://spacebudgie.itch.io/glitchspace) | Use a physics- and geometry-based visual programming language to reprogram the game itself and solve puzzles to find your way home from a cyberspace world. |
| [*GNU Robots*](https://www.gnu.org/software/gnurobots/) | Program a little robot in Scheme (specifically GNU Guile) to navigate a maze, finding food for energy, prizes to increase your score, and evading or neutralizing "baddies". |
| [*Graphomata*](https://graphomata.com/) | Use a visual programming language to create [graphs](https://www.britannica.com/topic/graph-theory) (as in "mathematical networks") matching desired specifications and see your solutions come to life both as graphs and as a number of other programming languages. |
| [*Grey Hack*](https://greyhackgame.com/) | MMO hacking simulation with vast procedurally generated network of potential target computers. |
| [*hackmud*](https://hackmud.com/) | Another hacking MMO with deliberately campy "retro" hacking aesthetics and strong player-run elements, all powered by the (love it or hate it) universal language of the Internet, JavaScript (ES6, with "strict" mode enabled). |
| [*Hacknet*](https://hacknet-os.com/) | Terminal-driven hacking game with campy Hollywood aesthetics. Pretty fun, but consider a caveat from one of the reviews on Steam: "Solid game, but if you want to do real hacking, go to TryHackMe or HackTheBox." |
| [*Hack 'n' Slash*](https://www.doublefine.com/games/hack-n-slash) | Imagine *The Legend of Zelda* but you can hack the game itself to move towards victory. |
  | [*Joy of Programming*](https://store.steampowered.com/app/2216770/JOY_OF_PROGRAMMING__Software_Engineering_Simulator/) | Use Python for automation and machine learning. The focus appears to be on manufacturing and uncrewed autonomous combat vehicles. Author recommends that you have prior experience with programming and don't go in as a beginner. |
| [*Kodu*](https://www.kodugamelab.com/) | Create 3-D worlds with agents and objects and control them using a visual programming language. Intended for children but can be used at all ages. |
| [*KnotBot*](https://store.steampowered.com/app/1269830/KnotBot/) | "Solve coding problems with knots and yarn-balls instead of text and numbers." Also has a visual programming language. |
| [*Learn Git Branching*](https://learngitbranching.js.org/) | Interactive Git tutorial from basic commands to increasingly arcane ones. |
| [*Logic World*](https://logicworld.net/) | Think Minecraft, but exclusively for digital logic. Includes multiplayer options. |
| [*LogicBots*](https://store.steampowered.com/app/290020/LogicBots/) | Design and build robots in a 3-D world and combine logic gates to control their behavior and meet various objectives. |
| [*Marvellous Inc.*](https://marvellous.itch.io/marvellous-inc) | Get hired by a sketchy international conglomerate and uncover its secrets as you write assembly code to solve increasingly complex tasks. |
| [*Mechanica*](https://store.steampowered.com/app/1226990/Mechanica/) | Automate manufacturing and base defenses using a visual programming language in an inhospitable desert wasteland. |
| [*MHRD*](https://store.steampowered.com/app/576030/MHRD/) | Work for the startup company "Microhard" and build circuitry with a hardware description language starting from basic logic gates and leading all the way up to a full-fledged CPU.   |

* [The Magic Circle](https://store.steampowered.com/app/323380/The_Magic_Circle/)
* [Midnight Protocol](https://www.midnightprotocol.net/)
* [MindRover](https://en.wikipedia.org/wiki/MindRover)
* [Minecraft Hour of Code](https://code.org/minecraft)
* [Move Code Lines](https://store.steampowered.com/app/1300310/Move_Code_Lines/)
* [NebuLeet](https://store.steampowered.com/app/3024370/NebuLeet)
* [Neon Noodles](http://vividhelix.com/neonnoodles/)
* [Oh My Git](https://ohmygit.org/)
* [One Dreamer](https://www.one-dreamer.com/thegame/)
* [Pony Island](https://www.pony-island.com/)
* [Prelogate](https://store.steampowered.com/app/332830/Prelogate/)
* [Prime Mover](https://store.steampowered.com/app/693700/Prime_Mover/)
* [Pure Logic](https://store.steampowered.com/app/1861500/Pure_Logic/)
* [Quadrilateral Cowboy](https://blendogames.com/qc/)
* [Rec Room](https://recroom.com/rec-room/)
* [Robo Instructus](https://www.roboinstruct.us/)
* [Robocode](https://robocode.sourceforge.io/)
* [Robocoder - Dwarf Mountain](https://store.steampowered.com/app/2212850/Robocoder__Dwarf_Mountain/)
* [Rogue Bit](https://store.steampowered.com/app/949790/Rogue_Bit/)
* [Roody:2d](https://store.steampowered.com/app/2345220/Roody2d/)
* [Sand:box](https://store.steampowered.com/app/2179380/Sandbox/)
* [Scalatron](http://scalatron.github.io/)
* [Screeps](https://screeps.com/)
* [Selfless Heroes](https://store.steampowered.com/app/1273450/Selfless_Heroes/)
* [[the Sequence]](https://store.steampowered.com/app/454320/the_Sequence/)
* [SIC-1](https://store.steampowered.com/app/2124440/SIC1/)
* [Silicon Zeroes](http://pleasingfungus.com/Silicon%20Zeroes/)
* [Stone Story RPG](https://stonestoryrpg.com/)
* [Stormworks: Build and Rescue](http://mcro.org/stormworks)
* [Super Markup Man](https://www.roppychop.com/pc/markup-man/)
* [Swarm](https://swarm-game.github.io/)
* [Swift Playgrounds](https://apps.apple.com/app/id1496833156)
* [ToonTalk](http://www.toontalk.com/)
* [trAInsported](http://trainsportedgame.no-ip.org/)
* [Turing Complete](https://turingcomplete.game/)
* [TwilioQuest](https://www.twilio.com/quest)
* [Virtual Circuit Board](https://www.virtualcircuitboard.com/)
* [Uplink](https://store.steampowered.com/app/1510/Uplink/)
* [while True: learn()](https://luden.io/wtl/)

## Recent Games, Mobile

* [Automaton](https://play.google.com/store/apps/details?id=com.JeremyFriesen.AutomationInc) (Android only)
* Cyber Sentinel
  * [Android](https://play.google.com/store/apps/details?id=pl.mindhelix.cybersentinel)
  * [iOS](https://apps.apple.com/us/app/cyber-sentinel/id1199120752)
* Gladiabots
  * [Android](https://play.google.com/store/apps/details?id=com.GFX47.Gladiabots)
  * [iOS](https://apps.apple.com/app/gladiabots/id1469623947)
* Human Resource Machine
  * [Android](https://play.google.com/store/apps/details?id=com.tomorrowcorporation.humanresourcemachine)
  * [iOS](https://apps.apple.com/us/app/human-resource-machine/id1005098334)
* LightBot
  * [Android](https://play.google.com/store/apps/details?id=com.lightbot.lightbot)
  * [iOS](https://apps.apple.com/us/app/light-bot/id657638474)
  * [Amazon](https://www.amazon.com/Lightbot-Inc-Programming-Puzzles/dp/B00LVDC27Y)
* LightBot Jr
  * [Android](https://play.google.com/store/apps/details?id=com.lightbot.lightbotjr)
  * [iOS](https://apps.apple.com/us/app/lightbot-jr-coding-puzzles-for-ages-4/id858640629)
  * [Amazon](https://www.amazon.com/Lightbot-Jr-Coding-Puzzles-Ages/dp/B00LW65HN6)
* [Make It True](https://play.google.com/store/apps/details?id=com.ViacheslavRud.Circuit) (Android only)
* [Perfect Paths](http://perfectpaths.hyperbolicmagnetism.com/) (iOS only)
* [Rec Room](https://apps.apple.com/us/app/rec-room/id1450306065) (iOS only)
* RoboZZle
  * [Android](https://play.google.com/store/apps/details?id=com.team242.robozzle)
  * [iOS](https://apps.apple.com/us/app/robozzle/id350729261)
* SpriteBot
  * [Android](https://play.google.com/store/apps/details?id=com.spritebox.coding)
  * [iOS](https://apps.apple.com/us/app/light-bot/id1270538471)
* [Swift Playgrounds](https://apps.apple.com/app/id908519492) (iPad only)
* [TIS-100P](https://apps.apple.com/kr/app/tis-100p/id1070879899) (iOS only)
* [7 Billion Humans](https://apps.apple.com/us/app/7-billion-humans/id1393923918) (iOS only)

## Recent Games, Browser- or Server-Based

* [AI Cup](https://russianaicup.ru/)
* [Artifacts MMO](https://artifactsmmo.com/) - Artifacts is a Sandbox MMORPG where you can use any programming language to control your characters with our API.
* [Bitburner](https://danielyxie.github.io/bitburner/)
* [BOX-256](http://box-256.com/)
* [Battlecode](https://www.battlecode.org/)
* [Blockly](https://blockly.games/)
* [Carnival](https://codepen.io/una/pen/NxZaNr)
* [CodeCraft](http://www.codecraftgame.org/)
* [CSS Diner](http://flukeout.github.io/)
* [CTF Learn](https://ctflearn.com/)
* [CheckiO](https://checkio.org/)
* [Code Games](http://codegames.io)
* [Code Monkey](https://www.codemonkey.com/)
* [Code.org](https://code.org/)
* [CodeCombat](https://codecombat.com/)
* [Codingame](https://www.codingame.com/)
* [corewars8086_js](https://shooshx.github.io/corewars8086_js/)
* [Cube Composer](https://david-peter.de/cube-composer/)
* [Elevator Saga](http://play.elevatorsaga.com/)
* [Flexbox Defense](http://www.flexboxdefense.com/)
* [Flexbox Froggy](http://flexboxfroggy.com/)
* [Flexbox Zombies](https://mastery.games/p/flexbox-zombies)
* [generals.io](http://generals.io/)
* [Graphomata](https://graphomata.com/)
* [Grid Critters](https://gridcritters.com/)
* [Grid Garden](https://cssgridgarden.com/)
* [Hack The Box](https://www.hackthebox.eu/)
* [hackable.ca](https://hackable.ca/)
* [hacker.org](http://www.hacker.org/)
* [HackThisSite](https://www.hackthissite.org/)
* [Hacker 101 CTF](https://ctf.hacker101.com/)
* [Halite](https://halite.io/)
* [Hellbound Hackers](https://www.hellboundhackers.org/)
* [Imagegram](https://zaratustra.itch.io/imagegram)
* [io.netgarage.org](https://io.netgarage.org/)
* [JavaScript Fight Club](https://jsfight.club/)
* [Komodo Consulting CTF](http://ctf.komodosec.com/)
* [Leek Wars](https://leekwars.com/)
* [LogicBox](https://logicbox.jahooma.com/)
* [Manufactoria](http://pleasingfungus.com/Manufactoria/)
* [Microcorruption](https://microcorruption.com/)
* [Much Assembly Required](https://muchassemblyrequired.com/)
* [NandGame](http://nandgame.com/)
* [OverTheWire](https://overthewire.org/wargames/)
* [picoCTF](https://picoctf.com/)
* [Practice CTF List / Permanent CTF List](http://captf.com/practice-ctf/) (a
  comprehensive list of CTF challenges specifically; have not examined every
entry; see also this [Stack Exchange
thread](https://security.stackexchange.com/questions/3592/what-hacking-competitions-challenges-exist)
and this [Reddit
thread](https://www.reddit.com/r/HowToHack/comments/4qxhjn/21_hacking_sites_ctfs_and_wargames_to_practice/))
* [Programming Game](https://programming-game.com/) - A realtime survival MMORPG played via websockets. There's a super simple in browser [demo](https://programming-game.com/demo) that showcases how to play.
* [pwnable.kr](http://pwnable.kr)
* [pwnable.tw](https://pwnable.tw/)
* [Regex Crossword](https://regexcrossword.com/)
* [RingZer0 Team Online CTF](https://ringzer0ctf.com/)
* [Robot Rumble](https://robotrumble.org/)
* [RoboZZle](http://robozzle.com/)
* [Ruby Warrior](https://www.bloc.io/ruby-warrior)
* [Schemaverse](https://schemaverse.com/)
* [Service Workies](https://serviceworkies.com/)
* [ShortcutFoo](https://www.shortcutfoo.com/)
* [Smash the Stack](http://smashthestack.org/)
* [SpaceTraders API](https://spacetraders.io/) (RESTful API MMO Space Trading game)
* [Tic-Tac-Toe](https://codepen.io/alvaromontoro/pen/BexWOw)
* [Tynker](https://www.tynker.com/)
* [Untrusted](https://alexnisnevich.github.io/untrusted/)
* [Vim Adventures](https://vim-adventures.com/) (n.b.: $25 for six months access to the full version)
* [VimGolf](https://www.vimgolf.com/)
* [Vindinium](https://github.com/ornicar/vindinium)
* [VulnHub](https://www.vulnhub.com)
* [W3Challs](https://w3challs.com/)
* [WarriorJS](https://warriorjs.com/)
* [WeChall](http://www.wechall.net/) (not the same as the other, similar-sounding entry!)
* [XSS Game](https://xss-game.appspot.com/)

## Recent Games, Console

* [Baba Is You](https://www.nintendo.com/games/detail/baba-is-you-switch/) (Switch)
* [Carnage Heart](https://en.wikipedia.org/wiki/Carnage_Heart) (PlayStation)
* [Dreams](https://en.wikipedia.org/wiki/Dreams_(video_game)) (PlayStation 4)
* Exception
  * [PlayStation 4](https://store.playstation.com/en-us/product/UP4469-CUSA12827_00-EXCEPTION0000001)
  * [Switch](https://www.nintendo.com/games/detail/exception-switch/)
  * [Xbox One](https://www.microsoft.com/en-us/p/exception/bssklhhh96ds)
* [7 Billion Humans](https://www.nintendo.com/games/detail/7-billion-humans-switch/) (Switch)

<!-- reversing.kr category TBD -->
<!-- Riddles.io -->
<!-- Empire of Code -->
<!-- God Is A Cube -->
<!-- Search through Google Play Store -->
<!-- Remaining Steam entries -->
<!-- More generally, searches for "Zachlike" and "programming", and the "progamming" tag on itch.io all bring up more games, most of which are actually programming games. Similar searches/tags on GOG and Steam also bring up more games. -->
