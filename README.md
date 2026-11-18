# WeBot

## About

THis project is used to open a website into a tkinter window. You can make a list of website and it switches between all the websites.

## Getting started

### Installation

1. Download and launch [WeBot.exe](WeBot.exe)
2. Else, download [webot.py](webot.py) and launch it with python 3.13

## Features

- Add and remove several URLs in a list
- Random delay between page changes (minimum and maximum, in seconds)
- Optional **AutoStop** timer (in minutes)
- Start and Stop buttons

## Usage

### 1. Add URLs
1. Type a URL in the text field.
2. Click **Ajouter** (you can add as many as you want).
3. To remove one, select it in the list and click **Supprimer URL**.

### 2. Set the delay and the timer
- **Delta minimum / Delta maximum (sec):** the program waits a random time between these two values before switching to the next page. A very small gap between the two is not recommended, since the pattern would be too regular and could be spotted more easily by browsers.
- **AutoStop (optional):** tick the box and enter a duration in minutes. The program stops by itself when the time is up.

### 3. Run
1. Click **Start** to launch.
2. Click **Stop** to end the program. A page confirms that it has stopped.

## Credits

- **Author**: [MarceauMRS](https://github.com/MarceauMRS)

## License

Distributed under the [GNU GPL v3.0](LICENSE).
