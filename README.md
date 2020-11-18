# Traefik Course

The code in this repository is based on the
[The Complete Traefik Training Course](https://www.udemy.com/course/the-complete-traefik-training-course/).

The github repository for the course is
[here](https://github.com/56kcloud/traefik-training).

## 02-Configure-Traefik - failed

Did not get `curl -H Host:catapp.localhost 127.0.0.1` to work.

The magic line that got the router working form lesson 02 to 03 is:

```yaml
- "traefik.http.routers.catapp.service=catapp"
```
