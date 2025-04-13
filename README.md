# mapache-anon
🦝 Herramienta de anonimato extremo para Kali Linux. Cambia MAC, VPN, Tor, DNS, Restablece y limpia logs.
 
Creada por **MARTO** · marto.endpoint@gmail.com

---

## 📦 Instalación

1. Descargá el paquete `.deb` desde la [sección de Releases](https://github.com/Marto-EndPoint/mapache-anon/releases)) o directamente desde este [link directo](https://github.com/Marto-EndPoint/mapache-anon/releases/latest/download/mapache-anon_1.0.deb).
2. Instalalo con:

```bash
sudo dpkg -i mapache-anon_1.0.deb
```

---

## 🚀 Uso

Ejecutá el menú desde la terminal:

```bash
mapache-anon
```

---

## 🛠️ Requisitos

Se instalarán automáticamente si no están:

- `bash`
- `curl`
- `tor`
- `macchanger`
- `openvpn`
- `net-tools`

---

## 🔐 VPN

Para que la VPN funcione, necesitás:

1. Descargar un archivo `.ovpn` desde [VPNBook](https://www.vpnbook.com/).
2. Colocarlo en:

```bash
/etc/openvpn/anon.ovpn
```

---

## 🧼 ¿Qué hace?

- Cambia tu MAC aleatoriamente.
- Cambia DNS a DNS.Watch.
- Inicia una conexión VPN.
- Enruta tráfico a través de Tor.
- Limpia logs y bash history.
- Restaura configuración de red.

---

## ☠️ Advertencia

Este script es solo con fines educativos. Usalo bajo tu propia responsabilidad.

---

## 📬 Contacto

**MARTO**  
📧 marto.endpoint@gmail.com  
🔗 [@mapache.tech](https://instagram.com/mapache.tech)
