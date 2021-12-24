<h3 align="center">Auto Download and Folder Choosing</h3>

<br>

## About the project

Auto Download and Folder Choosing is a small script made to automate the downloading and "foldering" process of media video files (e.g. TV shows, movies, anime, etc).

It's by no means an universal script that will correctly sort the media you want to download. It was made with my case and context in mind.

### Why

Sorting files is already a tedious process. It turned even more tedious when I created a specific way of sorting all my media video files. I also download all my TV shows and movies from multiple places, with multiple ways to download them.

So I decided to create a program that would take all that burden from me and do it much faster.

(The real reason: it only takes me a few seconds but I wanted to save those precious seconds)

### Used libraries

The project used the following third-party libraries:

* [Qbittorrent-api](https://pypi.org/project/qbittorrent-api/)

### Download Sources

This script accepts links from:

Source   | Single file | Folder | Choose files
-------- | ----------- | ------ | ------------
Mega     | ✔          | ❌     | ❌
Torrents | ✔          | ❌     | ❌

It's planned in the future to support more sources.

## Getting Started

### Prerequisites

If you don't already have Git and Python, download them [here](https://git-scm.com/download) and [here](https://www.python.org/downloads/) respectively.

### Installation

#### Using Git (Recommended)

1. Open the terminal and clone the repository using git:

    ```bash
    git clone https://github.com/OfficialBispo/Auto-Download-and-Folder-Choosing.git
    ```

2. Change the directory to the one where git cloned the repository:

    ```bash
    cd Auto-Download-and-Folder-Choosing/
    ```

#### Downloading the zip file

1. Click the green button named "Code"

2. Then click the button named "Download ZIP"

3. Open the folder where it saved the file and extract the zip contents

4. Open the terminal and navigate to the folder where you extracted it

## Usage

Run the file with Python:

```bash
python auto.py
```

It will show up a list of types of media:

```bash
Escolhe uma das opções:
    1 - Anime
    2 - Filmes
    3 - Séries
    4 - Sair
-------------------------------
```

Choose an option by typing the number in front of the types of media you want to download.

If you type any number except the one linked with "Sair", the following text will show up:

```bash
Escreve o link de download: 
```

Type or paste the download link next to the colon and click enter.

## Roadmap

* [ ] Add custom folders
* [ ] Add custom media types
* [ ] Save links for folders to download later
  * [ ] Mark which file was downloaded last, so the person know which episode they need to download
* [ ] Add more sources
