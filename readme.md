# Docker ready to run Jupyper Notebook

## Requirements
   Install [docker](https://www.docker.com/get-started)
## Install

1. `git clone https://github.com/zxcvtm/aim.git`
2. `docker build -t aim-base:1.0 .`

## Run

`docker run -it --name ambiente-aim -v ~/aim/vol:/home/zxcvtm/work/vol -p 8889:8888 aim-base:1.0 start-notebook.sh --NotebookApp.token=''`
