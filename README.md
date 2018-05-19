docker run -it --rm -p 8888:8888 --user root -e GRANT_SUDO=yes -v $(pwd):/home/jovyan/work --shm-size=512m jupyter/datascience-notebook

Notes:
Gotta replace cookie before using api