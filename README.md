# eureka-server

# Docker


```bash
  mvn clean install
```
Crear imagen 

```bash
  docker build -t unir-zuul-server:latest .
```

Ejecutar imagen

```bash
  docker run -p 8762:8762 unir-zuul-server:latest
```