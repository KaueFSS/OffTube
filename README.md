<div align="center">



**Baixe vídeos e músicas do YouTube sem complicação.**

[![Release](https://img.shields.io/github/v/release/KaueFSS/OffTube?style=flat-square&color=4f8ef7&label=versão)](https://github.com/KaueFSS/OffTube/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/KaueFSS/OffTube/total?style=flat-square&color=22c55e&label=downloads)](https://github.com/KaueFSS/OffTube/releases)
[![Platform](https://img.shields.io/badge/plataforma-Windows-blue?style=flat-square&color=222236)](https://github.com/KaueFSS/OffTube)

<br>

</div>

---

## ⚡ O que é?

**OffTube** é um app desktop para Windows que permite baixar vídeos e áudios do YouTube de forma simples e rápida — sem instalar nada além do próprio `.exe`.

---

## ✨ Funcionalidades

- 🎬 **Download de vídeos** em MP4, MKV ou WebM
- 🎵 **Extração de áudio** em MP3
- 📺 **Qualidades disponíveis:** 360p, 480p, 720p, 1080p, 4K e Melhor
- 📋 **Playlists inteiras** com um clique
- 💬 **Legendas automáticas** em português e inglês
- 🖼️ **Salvar thumbnail** do vídeo
- 👁️ **Preview do vídeo** ao colar o link (título, duração, views, canal e thumbnail)
- 📂 **Histórico** dos últimos 50 downloads
- 🔄 **Atualização automática** via GitHub Releases

---

## 🚀 Como usar

1. Acesse a página de [**Releases**](https://github.com/KaueFSS/OffTube/releases/latest)
2. Baixe o arquivo `OffTube.exe`
3. Abra o arquivo — **não precisa instalar nada**
4. Cole o link do YouTube, escolha o formato e clique em **Baixar**

> ⚠️ **Aviso do Windows SmartScreen:** Por ser um app novo, o Windows pode exibir um aviso de segurança. Clique em **"Mais informações" → "Executar mesmo assim"** para prosseguir. O app é seguro e o código está disponível aqui neste repositório para quem quiser verificar.

---

## 🖥️ Interface


<img width="1181" height="792" alt="image" src="https://github.com/user-attachments/assets/75ea9485-d801-4eac-8c7e-7fbe7804da05" />




---

## 🛠️ Tecnologias

| Lib | Função |
|-----|--------|
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Engine de download |
| [FFmpeg](https://ffmpeg.org/) (via imageio-ffmpeg) | Processamento de vídeo/áudio |
| [customtkinter](https://github.com/TomSchimansky/CustomTkinter) | Interface gráfica |
| [Pillow](https://python-pillow.org/) | Preview de thumbnails |
| [PyInstaller](https://pyinstaller.org/) | Empacotamento do `.exe` |

---

## 🔨 Rodando o código fonte

Requer Python 3.10+

```bash
git clone https://github.com/KaueFSS/OffTube.git
cd OffTube
python OffTube.py
```

As dependências são instaladas automaticamente na primeira execução.

Para gerar o `.exe`:

```bash
python -m PyInstaller --onefile --windowed --name OffTube OffTube.py
```

---

## 📄 Aviso legal

Este projeto é para uso pessoal. Respeite os [Termos de Serviço do YouTube](https://www.youtube.com/t/terms) e os direitos autorais dos criadores de conteúdo.

---

<div align="center">

Feito por [KaueFSS](https://github.com/KaueFSS)

</div>
