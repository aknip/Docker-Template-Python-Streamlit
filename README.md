# Template: Streamlit

docker-compose up --build
http://localhost:8501

Folder src can be edited 

## Run in Gitpod
https://gitpod.io/#https://github.com/aknip/Docker-Template-Python-Streamlit



# TODO:
docker build -t marimo .  
docker run -p 8080:8080 -it marimo




## fly.io
- Install CLI: brew install flyctl
- Init existing app (first deploy): 
    - fly launch --now
- Update: 
    - fly deploy


# Start marimo

marimo edit 
marimo edit hello-world-marimo.py

# Run as app
marimo run hello-world-marimo.py

# Run as script from CLI
python hello-world-marimo.py

# Run / Deploy as Docker
https://docs.marimo.io/guides/deploying/deploying_docker.html

or via FastAPI App: https://docs.marimo.io/guides/deploying/programmatically.html