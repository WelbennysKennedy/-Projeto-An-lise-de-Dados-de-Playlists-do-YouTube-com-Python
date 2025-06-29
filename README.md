# 📺 YouTube Playlist Video Stats

Este projeto em Python utiliza a **YouTube Data API v3** para listar os vídeos de uma *playlist pública* do YouTube e exibir o número de visualizações de cada vídeo.

## 🚀 Funcionalidades

- Autenticação com OAuth2 via `secrets.json`
- Acesso a vídeos de uma playlist pelo `playlistId`
- Coleta dos IDs dos vídeos presentes na playlist
- Consulta do número de visualizações de cada vídeo

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- [Google API Client](https://github.com/googleapis/google-api-python-client)
- [google-auth-oauthlib](https://github.com/googleapis/google-auth-library-python-oauthlib)
- YouTube Data API v3

## 📦 Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/youtube-playlist-stats.git
cd youtube-playlist-stats
pip install -r requirements.txt


