# observability-example

Exemplo de aplicacao Java demonstrando conceitos de observabilidade, incluindo metricas, logs estruturados e rastreamento distribuido.

---

## Tecnologias

- Java
- Spring Boot
- Prometheus
- Grafana
- Docker / Docker Compose

---

## Pre-requisitos

- Java 11+
- Docker e Docker Compose instalados

---

## Instalacao

```bash
git clone https://github.com/fabiodocarmo/observability-example.git
cd observability-example
```

---

## Como usar

```bash
docker-compose up -d
./mvnw spring-boot:run
```

Acesse as metricas em `http://localhost:8080/actuator/prometheus`.

---

## Contato

- Site: [fabiodocarmo.com](http://www.fabiodocarmo.com)
- E-mail: contato@fabiodocarmo.com
