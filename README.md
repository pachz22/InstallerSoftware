# Instalador con Validación por Key + Webhook de Registro

Este proyecto es una herramienta escrita en Python que muestra una GUI para validar una clave (key), registrar información del sistema (HWID) y descargar un archivo desde una URL pública. También envía información del usuario (HWID y contraseña generada) a un webhook de Discord.

> ⚠️ **Advertencia:** Este código recoge información del usuario y la envía a un servidor externo (Discord Webhook). Asegúrate de contar con el consentimiento del usuario si vas a distribuir o usar este software.

---

## ✨ Características

- Validación por clave (key/password).
- Generación y almacenamiento de datos locales (`hwid`, `password`) en un archivo JSON.
- Envío automático de datos al iniciar vía Webhook.
- Descarga de archivos con barra de progreso.
- Interfaz gráfica con `tkinter`.

---

## 🔧 Requisitos

- Python 3.x
- Módulos estándar: `tkinter`, `subprocess`, `requests`, `os`, `json`, `string`, `random`, `threading`.

Instálalos si es necesario:

```bash
pip install requests
