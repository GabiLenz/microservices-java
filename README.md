# Microservices Java

Projeto desenvolvido utilizando arquitetura de microsserviços com Java e Spring Boot.

## 📁 Estrutura do Projeto

```
microservices-java/
│
├── cambio-service/
├── config-service/
├── configs/
│   └── saudacao-service/
├── produto-service/
└── saudacao-service/
```


## 🛠️ Tecnologias

- Java
- Spring Boot
- Spring Cloud Config
- Maven
- REST API

---

## 📌 Arquitetura

```
                  +-------------------+
                  |   Config Server   |
                  +---------+---------+
                            |
          ------------------+-------------------
          |                 |                  |
          |                 |                  |
+----------------+  +----------------+  +----------------+
| Cambio Service |  | Produto Service|  | SaudacaoService|
+----------------+  +----------------+  +----------------+
```

---

Desenvolvido para estudos de arquitetura de microsserviços utilizando Java e Spring Boot.
