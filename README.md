
![image](./img/image.gif)
# MkDocs-with-Remote-Containers
This is a sample repository to create [MkDocs](https://www.mkdocs.org) document with VSCode [Remote - Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).

## Requirements

- VSCode
- Remote - Containers (as Visual Studio Code extension)
- Docker

## Usage

1. Clone this repository
2. Open via VSCode
3. Open this project through Remote - Containers  
   `Cmd + Shift + P -> Remote-Containers: Reopen in Container`
4. Open `Run` tab on left side-bar, then run `Launch Chrome against localhost`.
5. It executes `mkdocs serve` command and open `http://locahost:8000` via Google Chrome automatically.
6. Edit your MkDocs document!
7. If you want to terminate `mkdocs serve` and close the browser, you only need to do is clicking `stop` button.
