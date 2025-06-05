# Projeto 2

Este projeto aplica técnicas de computação gráfica e edição de vídeo usando a biblioteca `moviepy`. O objetivo é transformar um vídeo original em uma versão editada com cortes, efeitos visuais e modulação de áudio.

## Drive com os vídeos:

https://drive.google.com/drive/folders/1NIPPhIv6ItcSrGG022IRObHj3o3GBJIZ?usp=sharing

## Funcionalidades

- Inversão horizontal do vídeo a cada 20 segundos.
- Redução gradual do volume a cada 30 segundos.
- Silêncio total nos últimos 10 segundos.
- Corte do trecho entre 60s e 80s.
- Reorganização dos segmentos: início (0–60s), final (80s–fim) e inserção do trecho cortado (60–80s) ao final.
- Exportação final em `.mp4`.

---

## 🔧 Requisitos

- Recomendado: venv

### Instalação das dependências

```bash
pip install moviepy==1.0.3 numpy
```

![esqueci da prova kkkj](https://media.tenor.com/4wA2HHwzJmQAAAAi/sonic-adventure.gif)
