# Template: Streamlit

- docker-compose up --build
- http://localhost:8501
- Folder src can be edited 

## Run in Docker
- docker build -t streamlit .
- docker run -p 8501:8501 streamlit

## Run in Gitpod
https://gitpod.io/#https://github.com/aknip/Docker-Template-Python-Streamlit


## fly.io (NOT TESTED YET!)
- Install CLI: brew install flyctl
- Init existing app (first deploy): 
    - fly launch --now
- Update: 
    - fly deploy