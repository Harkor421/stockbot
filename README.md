<div align="center">

# stockbot

### Caza stock de GPUs y CPUs mientras duermes

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Shell](https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white) ![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=for-the-badge&logo=puppeteer&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

[**📦 Repositorio**](https://github.com/Harkor421/stockbot)

</div>

---

## 📖 Sobre el proyecto

Bot que vigila el inventario de tiendas (Amazon, Best Buy, Newegg, Micro Center, B&H, Walmart) y avisa en cuanto aparece stock de la GPU, CPU o consola que busques.

## ✨ Qué hace

- Scrapers por tienda con configuración YAML por producto
- Alertas por Discord, Slack, Telegram y correo
- Docker y Vagrant listos, pensado también para Raspberry Pi
- CI en GitHub Actions

## 🧰 Stack

| | |
|---|---|
| **Lenguajes y runtime** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Shell](https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white) |
| **Calidad** | ![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=for-the-badge&logo=puppeteer&logoColor=white) |
| **Infraestructura** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) |

## 📂 Estructura

```
src/alerter
src/scraper
tests/newegg  # Tests
```

## 🚀 Empezar

```bash
git clone https://github.com/Harkor421/stockbot.git
cd stockbot
pip install -r requirements.txt
```

## ☁️ Despliegue

- **Docker**

---

<div align="center">

Hecho por [**Samir González**](https://github.com/Harkor421)

</div>
