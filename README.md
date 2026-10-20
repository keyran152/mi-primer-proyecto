# 🛡️ Despliegue de Cloudflare Zero Trust para Servidor NAS

## 📌 Descripción del Proyecto
Este repositorio contiene la configuración, plantillas de despliegue y documentación técnica para asegurar el acceso remoto al servidor NAS corporativo de **Azul Marino - Agencia Digital** utilizando **Cloudflare Zero Trust** (Cloudflare Tunnels + Access Applications).

---

## 🚀 Arquitectura e Infraestructura
* **Conector:** Cloudflare Tunnel (`cloudflared`) mediante Docker Compose.
* **Seguridad:** Autenticación por correo corporativo (`@empresa.com`) y OTP (PIN de 6 dígitos).
* **Control Geográfico:** Bloqueo perimetral restringido únicamente a Costa Rica.
* **Red:** Sin puertos abiertos en el enrutador físico de la oficina.

---

## 🛠️ Requisitos Previos
1. Servidor NAS con Docker y Docker Compose instalados.
2. Cuenta activa en Cloudflare con el dominio corporativo asignado.
3. Git instalado en el equipo local.

---

## ⚙️ Pasos de Despliegue Rápido
1. Clonar este repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/proyecto-cloudflare-nas.git](https://github.com/tu-usuario/proyecto-cloudflare-nas.git)
   cd proyecto-cloudflare-nas