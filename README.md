
> This is a brief summarization for some of the projects I've been working on!

## Table of Contents
- [Personal Projects](#personal-projects)
  - [Gravitas: A 2D Tower Defense Indie Game](#gravitas-a-2d-tower-defense-indie-game)
  - [Shared Canvas: An In-person Collaboration App on iOS/iPadOS](#shared-canvas-an-in-person-collaboration-app-on-iosipados)
  - [Faruzan Senpai: A Discord Bot for My Private Server](#faruzan-senpai-a-discord-bot-for-my-private-server)
  - [MC Marketplace: Prototype of a Game Item Marketplace on Ethereum](#mc-marketplace-prototype-of-a-game-item-marketplace-on-ethereum)
  - [iOS/iPadOS mini Apps](#iosipados-mini-apps)
  - [Minecraft Mod Localizations](#minecraft-mod-localizations)
- [Courseworks](#courseworks)
  - [Disney-BSDF-forLa-Jolla-Renderer](#disney-bsdf-for-la-jolla-renderer)
  - [SVE-Optimized Matrix Multiplication](#sve-optimized-matrix-multiplication)
  - [Java Painting GUI](#java-painting-gui)
  - [User-Book Read and Rating Prediction for Recommendar System](#user-book-read-and-rating-prediction-for-recommendar-system)
  - [Simulation of OS Components - CPU & I/O Task Scheduler, Memory & Disk, File System](#simulation-of-os-components---cpu--io-task-scheduler-memory--disk-file-system)


## Personal Projects


### [Gravitas: A 2D Tower Defense Indie Game](https://misakizzzzz.itch.io/gravitas) 
![C#](https://img.shields.io/badge/Language-C%23-blueviolet) ![Unity](https://img.shields.io/badge/Tool-Unity-000000?logo=unity&logoColor=white) ![Visual Studio](https://img.shields.io/badge/IDE-Visual%20Studio-5C2D91?logo=visual-studio&logoColor=white) [![Static Badge](https://img.shields.io/badge/Download%20at%20itch.io-purple)](https://misakizzzzz.itch.io/gravitas) 

- An indie game for the VGDC game jam @ UCSD, in a great team of 2 programmers and 1 writer.
- Featured a **gravity-based battlefield**, where units have weights that influences the land's balance.
- Units and projectiles now affected by gravity, leading to a more fun and strategic tower defense experience.

  > Act as a saviour to save the world of magic, restoring the balance between light and darkness.
  > Summon all heroes from the ancient past to fight against the wicked enemies.

<table style="border: 0; margin: auto;">
  <tr >
    <td style="border: 0; text-align: right; vertical-align: bottom; padding: 5px;"><img src="./images/Gravitas_Showcase_HomeScreen.png" alt="Gravitas_Showcase_HomeScreen" width="480" style="border-radius: 12px;"s></td>
    <td style="border: 0; text-align: left; vertical-align: bottom; padding: 5px;"><img src="./images/Gravitas_Showcase_Lore.png" alt="Gravitas_Showcase_Lore" width="380" style="border-radius: 15px;"></td>
  </tr>
  <tr >
    <td style="border: 0; text-align: right; vertical-align: top; padding: 5px;"><img src="./images/Gravitas_Showcase_Tarot.png" alt="Gravitas_Showcase_Tarot" width="380" style="border-radius: 15px;"></td>
    <td style="border: 0; text-align: left; vertical-align: top; padding: 5px;"><img src="./images/Gravitas_Showcase_Battle.png" alt="Gravitas_Showcase_Battle" width="480" style="border-radius: 12px;"></td>
  </tr>
</table>

- (And...I also contributed to some Easter egg's art assets!)
<center>
    <img src="./images/Gravitas_Showcase_Pawn.png" alt="Gravitas_Showcase_Pawn" width="200" style="border-radius: 18px;">
</center>
<br></br>


### [Shared Canvas: An In-person Collaboration App on iOS/iPadOS](https://github.com/Samekichi/iOS-App-Projects/tree/main/Shared%20Canvas)
![Swift](https://img.shields.io/badge/Language-Swift-FA7343?logo=swift&logoColor=white) ![Xcode](https://img.shields.io/badge/IDE-Xcode-3AA6D8?logo=xcode&logoColor=white) ![SwiftUI](https://img.shields.io/badge/SwiftUI-E28330?logo=swift&logoColor=white) ![Swift Data](https://img.shields.io/badge/Swift%20Data-E28330?logo=swift&logoColor=white) ![Multi Peer](https://img.shields.io/badge/Multi%20Peer-E28330?logo=swift&logoColor=white)

- Focused on small groups of in-person meetings.
- Consists of Canvas List view, Connection view, Canvas view, and various pop-ups for canvas settings, color picker, and scribble / eraser / shape tool customizations.
- Share current canvas with nearby people, or join nearby sessions.
- Utilized **Multi-Peer Framework** for canvas hosting / data synchronization between endpoints.
- Leveraged `Codable` data structure to persist and transfer canvases using `JSON` or **Swift Data**.

<center>
<img src="./images/SharedCanvas_PrototypeAndCanvas.png" alt="Prototype of Shared Canvas App" height="300">
<p style="color: gray; font-size: 12px;"><b>Prototype</b> (Left)  and  <b>Running on a real device</b> (Right)</p>
</center>
<br></br>


### [Faruzan Senpai: A Discord Bot for My Private Server](https://github.com/Samekichi/DiscordBot-Faruzan_Senpai)
 ![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow) ![Discord.js](https://img.shields.io/badge/Library-Discord.js-5865F2?logo=discord&logoColor=white) ![AWS](https://img.shields.io/badge/Cloud-AWS-232F3E?logo=amazon-aws&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-336791?logo=postgresql&logoColor=white) ![ChatGPT API](https://img.shields.io/badge/API-ChatGPT-00A67E?logo=openai&logoColor=white) ![Spotify API](https://img.shields.io/badge/API-Spotify-1DB954?logo=spotify&logoColor=white)  


- A **Discord Bot** for my private server need (multilingual support is planned), such as:
    - User's daily luck
    - Game server time getter
    - Slash Command stats
    - Basic game Wiki inquiry
    - User Title system
    - ...
- Now on **AWS** with a local **PostgreSQL** database.
- Other features planned:
    - **Redis** cache layer
    - Enhanced User Title system
    - **Chat bot** integration (ChatGPT/DeepSeek API)
    - Spotify/NetEase Music integration
<center>
<img src="./images/FaruzanSenpai_Showcase3.png" alt="Faruzan Senpai's working command responses showcase" width="600">
<p style="color: gray; font-size: 12px;">Some working command responses</p>
</center>
<br></br>


### [MC Marketplace: Prototype of a Game Item Marketplace on Ethereum](https://github.com/Samekichi/Prototype-Trade-Web3-DApp)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow) ![Solidity](https://img.shields.io/badge/Language-Solidity-363636?logo=solidity&logoColor=white) ![VS Code](https://img.shields.io/badge/Tool-VS%20Code-007ACC?logo=visual-studio-code&logoColor=white) ![Next.js](https://img.shields.io/badge/Framework-Next.js-000000?logo=nextdotjs&logoColor=white) ![Web3.js](https://img.shields.io/badge/Library-Web3.js-F16822?logo=javascript&logoColor=white)
 ![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind%20CSS-38B2AC?logo=tailwind-css&logoColor=white) ![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?logo=ethereum&logoColor=white) ![Sepolia Testnet](https://img.shields.io/badge/Sepolia-3C3C3D?logo=ethereum&logoColor=white) ![Alchemy](https://img.shields.io/badge/Platform-Alchemy-0E76FD?logo=alchemy&logoColor=white)

- Designed a smart contract which later deployed on Ethereum's Test Network.
- Implemented a simple front end for the marketplace with connection to MetaMask wallet and ABI's of the smart contract.
- Validated real-world blockchain connection and trades on Sepolia Test Network through Alchemy.

<center>
<img src="./images/TradeDApp_Showcase_Marketplace.jpg" alt="TradeDApp_Showcase_Marketplace" height="300">
<p style="color: gray; font-size: 12px;">Marketplace with test items</p>
<img src="./images/TradeDApp_Showcase_Inventory.jpg" alt="TradeDApp_Showcase_Inventory" height="300">
<p style="color: gray; font-size: 12px;">Inventory with item status & Putting Item #9 off sale</p>
</center>
<br></br>


### [iOS/iPadOS mini Apps](https://github.com/Samekichi/iOS-App-Projects)
![Swift](https://img.shields.io/badge/Language-Swift-FA7343?logo=swift&logoColor=white) ![Xcode](https://img.shields.io/badge/IDE-Xcode-3AA6D8?logo=xcode&logoColor=white) ![SwiftUI](https://img.shields.io/badge/SwiftUI-E28330?logo=swift&logoColor=white)

- A set of iOS Apps that practices my skill. Mostly based on SwiftUI and MVVM principle, with some UIKit and MapKit hacks.

    1. **Spelling Challenge**
        - A **word-spelling game** for 3 languages (`en_US`, `fr_FR`, `de_DE`).
        - Support 5~7 candidate characters (with bonus and in different layouts), history, shuffle, hint, and restart.
        - Beautiful UI in both light & dark mode.
        <center>
        <img src="./images/iOSApp_LionSpell.png" alt="iOSApp_LionSpell" height="400">
        <p style="color: gray; font-size: 12px;">Solving a 7-char game in dark mode</p>
        </center>
        <br></br>
    2. **Pentominoes**
        - A **puzzle game** in which player needs to form different patterns using all pentominoes.
        - Support reset and auto-solve.
        - Fluent and beautiful animations based on gesture and piece status.
        <center>
        <img src="./images/iOSApp_Pentominoes_Before_and_after_solved.png" alt="iOSApp_Pentominoes_Before_and_after_solved" height="400">
        <p style="color: gray; font-size: 12px;">Before and after solved (simulated on 11' and 12.9' iPad Pro)</p>
        </center>
        <br></br>
    3. **Campus Map**
        - A **campus map** with data of all on-campus buildings.
        - Support favorites, search, filter, data persistence across launches, pins and pop-ups, and step-by-step routing between 2 buildings or from / to current location.
        <center>
        <img src="./images/iOSApp_CampusMap_Showcase.png" alt="iOSApp_CampusMap_Showcase" height="360">
        <p style="color: gray; font-size: 12px;">Map overview; Building detail and buttons; Route planning; and Step-by-step routing.</p>
        </center>
        <br></br>
    4. **Pokédex**
        - A **Pokémon collection** with attribute inquiry, ancestor and successor, and “captured” labels.
        - Dynamically render transition color, index, and status in both List and Detail Views.
        <center>
        <img src="./images/Pokedex_Showcases.png" alt="Pokedex_Showcases" height="320">
        <p style="color: gray; font-size: 12px;">Home screen; Detail View; List of Fire Pokémons; "Our favorite!";  Ancestor and successor.</p>
        </center>

### Minecraft Mod Localizations
- Localized a bunch of Minecraft Fabric Mods.
- Report bugs & submit PR's while examining mod logics (for better translation and writing Wiki).
<br></br>


## Courseworks


### [Disney BSDF for La Jolla Renderer](https://github.com/Samekichi/La_Jolla_with_Disney_BSDF)
- Utilized C++ `std::variant` pattern to implement Disney BSDF materials in *[La Jolla](https://github.com/BachiLi/lajolla_public)* renderer:
  1. Diffuse with subsurface
  2. Metal
  3. Clearcoat
  4. Glass
  5. Sheen
- Converted a self-made Blender scene to La Jolla and rendered correctly.


  <br></br>
  <center>
  <img src="./images/DisneyBSDF_Blender_Showcase.png" alt="Blender converted scene using Disney BSDF." height="360">
  <p style="color: gray; font-size: 12px;">A rendered self-made Blender scene using DisneyBSDF. </p>
  </center>
  <center>
  <img src="./images/Volumetric_Path_Tracing_Showcase.png" alt="Blender converted scene with volumes." height="360">
  <p style="color: gray; font-size: 12px;">Volumetric version of the scene above.<br> Foggy air, a blue volumetric interior of the ice cube, and a softer ice cream ball.</p>
  </center>

  <center>
  <img src="./images/DisneyBSDF_Glass.png" alt="Sample scene of DisneyGlass material." height="300">
  <p style="color: gray; font-size: 12px;">A rendered sample using DisneyGlass material</p>
  </center>

### SVE-Optimized Matrix Multiplication
- Implemented and modified BLISlab GEMM blocking algorithm in C.
- Improve row-major matrix multiplication efficiency, reducing cache misses on AWS EC2 Ubuntu machines by more than 33%.
- Accelerated microkernel by 4x with ARM SVE, loop unrolling, and pointer techniques (comparing to naïve).

### Java Painting GUI
- A Painter GUI implemented using Java with `SpringLayout`.
- Support 1st / 2nd colors, different shapes and lines, and options including stroke parameter, filled, gradients, and dashed.
  <br></br>
  <center>
  <img src="./images/PaintingGUI.png" alt="PaintingGUI by Java and SpringLayout" height="360">
  <p style="color: gray; font-size: 12px;">My masterpiece of a beautiful scenary!</p>
  </center>

### User-Book Read and Rating Prediction for Recommendar System
- Predict *whether a user reads a book* in various approaches and compared their performance, including:
  - Logistic Regression
  - Bayesian Personalized Ranking (Implicit)
  - *Trivial thresholds based on Popularity & Jaccard / CosineSet Similarities
- Predict *a user's rating on a given book*:
  - *BiasOnly Latent Factor Model (Surprise, Tenserflow, & PyTorch)
  - Latent Factor Model w/ Dimensionality Reduction (Tensorflow)

### Simulation of OS Components - CPU & I/O Task Scheduler, Memory & Disk, File System
- Used C to emulate the following components:
  - multi-threaded CPU/IO task schedulers,
  - disk and virtual memory access with support of TLB and second-level page table, and
  - a file system with symbolic links and security constraints.

