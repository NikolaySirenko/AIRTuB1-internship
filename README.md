# AIRTuB1-internship
Repository for a AIRTuB 1 follow-up internship

## 🚀 Usage

Make sure you have [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed. 
Launch it. Open Terminal in the project folder and run:
```sh
docker-compose up --build
```
Running this for the first time may take some time to download all dependencies. 
When it's ready you will see a "Jupyter Server is running" message in the terminal.

Go to [http://127.0.0.1:8888/lab/workspaces/auto-7/tree/volume](http://127.0.0.1:8888/lab/workspaces/auto-7/tree/volume)

Create a folder named scanData in the project folder. You can put scan files in it.

## 💻 Misc

If you want, you can use [VS Code](https://code.visualstudio.com/) as developing environment. 
You will need these extensions for it:
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

When the Docker container is running go to the VS Code Command Palette by pressing <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>.
Select _Dev Containers: Attach to Running Container..._ and choose _AIRTuB1-internship_.

Enjoy!
