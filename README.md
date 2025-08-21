# 
<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Invisible Game Mode CS2</h3>
  <p align="center">
    Game mode to set a player invisible if he don't make noise.
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project introduces a plugin for Counter-Strike 2 (CS2) that allows players to be made invisible, providing a unique gameplay experience. The core functionality focuses on granting invisibility to specific players, which can be managed through simple in-game commands.
Key Features

  Toggle Invisibility: Players can be made invisible or visible at will.
  Customizable Visibility Duration: Set a specific duration for how long a player remains invisible.

This plugin offers flexibility in gameplay by enabling dynamic control over visibility, ideal for creating unique challenges and stealth-based scenarios.
<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Dotnet][Dotnet]](https://dotnet.microsoft.com/en-us/languages/csharp)
* [![CSharp][CSharp]](https://dotnet.microsoft.com/en-us/download)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
### Prerequisites

    CounterStrikeSharp version 284
    Metamod version 2.0.0


### Installation
Extract the release inside the server\game\csgo\addons\counterstrikesharp\plugins folder

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage
This plugin enables you to control player visibility in Counter-Strike 2. Below are the commands available for managing player invisibility:
Commands

    Make a Player Invisible
    Use the !invis command followed by the player's name to make them invisible.

!invis playerName

    Example: !invis JohnDoe – This command makes the player "JohnDoe" invisible.

Make a Player Visible
To make a player visible again, use the !uninvis command followed by the player's name.

!uninvis playerName

    Example: !uninvis JohnDoe – This command makes "JohnDoe" visible again.

Set Invisibility Duration Multiplier
You can control how long a player remains invisible by using the !invis_time command, followed by multiplier wanted. ( default 1.2 )

!invis_time number

    Example: !invis_time 0.7 – Sets invisibility duration multiplied by 0.7 for all invisible players.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap
- [ ] Disable the bomb blinker

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.




<!-- CONTACT -->
## Contact

- [Discord] - Juju) / kaliqot



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Original Invis plugin](https://github.com/maniolos/InvisPlugin)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Dotnet]: https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white
[CSharp]: https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white
