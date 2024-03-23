<!-- PROJECT INTRO -->

OrpheusDL - Qobuz
=================

A Qobuz module for the OrpheusDL modular archival music program

[Report Bug](https://github.com/OrfiTeam/OrpheusDL/issues)
·
[Request Feature](https://github.com/OrfiTeam/OrpheusDL/issues)


## Table of content

- [About OrpheusDL - Qobuz](#about-orpheusdl-qobuz)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
- [Usage](#usage)



<!-- ABOUT ORPHEUS -->
## About OrpheusDL - Qobuz

OrpheusDL - Qobuz is a module written in Python which allows archiving from **Qobuz** for the modular music archival program.


<!-- GETTING STARTED -->
## Getting Started

Follow these steps to get a local copy of Orpheus up and running:

### Prerequisites

* Already have [OrpheusDL](https://github.com/OrfiTeam/OrpheusDL) installed

### Installation

1. Clone the repo inside the folder `orpheusdl`
   ```sh
   git clone https://github.com/thekvt/orpheusdl-qobuz modules/qobuz
   ```
2. Execute:
   ```sh
   python orpheus.py
   ```
3. Now the `config/settings.json` file should be updated with the Qobuz settings

<!-- USAGE EXAMPLES -->
## Usage

Just call `orpheus.py` with any link you want to archive:

```sh
python orpheus.py https://open.qobuz.com/album/c9wsrrjh49ftb
```
