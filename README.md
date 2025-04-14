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
sudo mapache-anon
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
Como mover el `.ovpn` desde `Descarcas`. te posicionas en `Descargas` y colocas `sudo mv` el nombre del `.ovpn` que descargaste recomendable que use el puerto 443 y a continuancion `/etc/openvpn/anon.ovpn` como se muentra en el ejemplo de abajo.
```bash
 sudo mv vpnbook-us178-tcp443.ovpn /etc/openvpn/anon.ovpn
```
---

## 🦝 ¿Qué hace?

- Cambia tu MAC aleatoriamente.
- Cambia DNS a DNS.Watch.
- Inicia una conexión VPN.
- Enruta tráfico a través de Tor.
- Limpia logs y bash history.
- Restaura configuración de red.

---

## 🌐 Configurar el navegador para usar Tor (SOCKS v5)

Si querés navegar de forma anónima luego de ejecutar `mapache-anon`, podés configurar tu navegador para que todo el tráfico pase por **Tor**.

### 🔧 Firefox u otros navegadores compatibles

1. Abrí tu navegador.
2. En la barra de direcciones, escribí:
   ```
   about:preferences#general
   ```
3. Bajá hasta **Configuración de red** y hacé clic en **"Configuración..."**.
4. Elegí **"Configuración manual del proxy"**.
5. Completá los campos:

   - **SOCKS Host:** `127.0.0.1`  
   - **Puerto:** `9050` (o `9150` si estás usando el navegador Tor)  
   - Marcá **SOCKS v5**  
   - Activá la opción **"Proxy DNS cuando se use SOCKS v5"** (si está disponible)

6. Hacé clic en **Aceptar**.

### ✅ Verificar si estás navegando por Tor

Entrá a:  
👉 [https://check.torproject.org](https://check.torproject.org)

Si todo está OK, verás un mensaje como:  
> 🟢 **"Congratulations. This browser is configured to use Tor."**

---

## ☠️ Advertencia

Este script es solo con fines educativos. Usalo bajo tu propia responsabilidad.

---

## 📬 Contacto

**MARTO**  
📧 marto.endpoint@gmail.com  
🔗 [Linkedin](https://www.linkedin.com/in/sergio-ignacio-martorell)
