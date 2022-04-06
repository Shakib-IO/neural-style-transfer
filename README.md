### Neural Style Transfer
[Perceptual Losses for Real-Time Style Transferand Super-Resolution](https://cs.stanford.edu/people/jcjohns/eccv16/)<br>
[Perceptual Losses](https://towardsdatascience.com/perceptual-losses-for-image-restoration-dd3c9de4113)
#### Tools used
- FastAPI: for the API
- streamlit : for the interface
- Docker: to containerize the app
- Docker-compose: to compose the backend and frontend container
#### Download the models
```bash
./download_models.sh
```

#### Run
```bash
docker-compose up -d
```
**Resource**
- [Github Pre-trained Models](https://github.com/jcjohnson/fast-neural-style)
