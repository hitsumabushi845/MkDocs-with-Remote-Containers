
![image](./img/image.gif)
# MkDocs-with-Remote-Containers
This is a template repository to edit [MkDocs](https://www.mkdocs.org) document with VSCode [Remote - Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).

## Requirements

- VSCode
- Remote - Containers (as Visual Studio Code extension)
- Docker

## Usage

1. Click the top right `Use this template` then select `Create a new repository` to create your own repository.
2. Open created repository via VSCode
3. Open the project on Remote - Containers  
   `Cmd + Shift + P -> Remote-Containers: Reopen in Container`
4. Open `Run` tab on left side-bar, then run `Launch Chrome against localhost`.
   - It executes `mkdocs serve` command and open `http://locahost:8000` via Google Chrome automatically.
5. You can enjoy real-time edit your MkDocs document!
6. If you would like to terminate `mkdocs serve` and close the browser, you only need to do is clicking `stop` button.
