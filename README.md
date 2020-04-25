<!-- Headings -->
# CBoard
CBoard is a self hosted, anonymous imageboard with support for images and comments
## Features
* Backend in Golang with dynamic routing using [mux](https://github.com/gorilla/mux)
* Styling provided by [Terminal](https://github.com/panr/hugo-theme-terminal)
* Multiple themes
* Responsive and asynchronous Python API using [FastAPI](https://github.com/tiangolo/fastapi) and [Uvicorn](https://www.uvicorn.org/)
* Quick and automated builds using docker-compose
## Getting Started
1. `git clone` this repo and `cd` into it
1. Run `docker-compose up --build`
1. Access CBoard at `http://localhost/`
