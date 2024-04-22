# VPN Wireguard + Pi-hole

## docker-compose Wireguard + Pi-hole | Servidor VPN WireGuard

Cómo instalar y configurar servidor VPN Wireguad junto con Pi-hole y gestionar conexiones de usuarios con WG-EASy y bloquear los Ads y rastreadores.

- Crea directorio de trabajo

- Situate en el directorio y crea el fichero docker-compose.yml

- Levanta el contenedor con comando; docker-compose up -d

- Acceder al la interfaz web UI de VPN Wireguard poniendo dirección Acceso vía http://IP-SERVER-DOCKER:51821

Los ficheros de configuración se guardan en; ./wireguard

- Para acceder a Pi-hole, es http://IP-SERVER-DOCKER:8080/admin
  
Vídeo en Youtube:



![wg + pihole miniatura yt](https://github.com/JLalib/docker-wireguard-pihole/assets/57844755/065f2803-4bd2-4dc4-98f0-3a29e728c0e2)


Fuente: https://github.com/wg-easy/wg-easy - https://www.wireguard.com/ - https://pi-hole.net/

