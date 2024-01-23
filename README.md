
![image](./img/image.gif)
# MkDocs-with-Remote-Containers
This is a template repository to create [MkDocs](https://www.mkdocs.org) document with VSCode [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.

## Requirements

- VSCode
- Dev Containers (as VSCode extension)
- Docker

## Usage

1. [Generate](https://github.com/hitsumabushi845/MkDocs-with-Remote-Containers/generate) a new repository based on this template.
2. Clone it and open via VSCode
3. Open the project on Dev Containers
   `Cmd + Shift + P -> Dev Containers: Reopen in Container`
4. Open `Run` tab on left side-bar, then run `Launch Chrome against localhost`.
   - It executes `mkdocs serve` command and open `http://locahost:8000` via Google Chrome automatically.
5. You can enjoy real-time edit your MkDocs document!
6. If you would like to terminate `mkdocs serve` and close the browser, you only need to do is clicking `stop` button.
