# Traefik v3

Traefik is the leading open-source reverse proxy and load balancer for HTTP and TCP-based applications that is easy, dynamic and full-featured.

Traefik allows you to access multiple containers on the same IP via port HTTP/HTTP and hostnames. Since Traefik reads the Docker containers it automatically searches for an open port and makes it available.

By default Traefik will use port `81` for `HTTP`, port `443` for `HTTPS` and port `8080` for the dashboard. If you want to use port `80` for `HTTP`, then you have first to change the WebUI port of CasaOS first under the settings in the top left menu. After deploying the container you can change the port mapping from `81` to `80`.

---

**Homepage:** https://traefik.io

**Documentation:** https://doc.traefik.io/traefik/v3.0

**WebUI Port:** `8080`
