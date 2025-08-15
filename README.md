# 🦸‍♂️ Super Powers — O Catálogo dos Superpoderes Mais Inúteis do Mundo

![Java](https://img.shields.io/badge/Java_17-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.5.4-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%2300f.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-%23005C0F.svg?style=for-the-badge&logo=thymeleaf&logoColor=white)

## 📌 Sobre o Projeto
O **Super Powers** é um sistema web divertido feito em **Java + Spring Boot** que lista alguns dos **superpoderes mais inúteis** já imaginados.  
O objetivo é treinar conceitos de **Spring Boot, JPA, Thymeleaf, validação e Flyway**... mas com um toque de humor.

Exemplos de superpoderes inúteis:
- 🥤 **Encher um copo d’água... mas só até a metade**
- 🌽 **Transformar qualquer objeto em milho (cru)**
- 🐢 **Correr na velocidade de uma tartaruga com preguiça**
- 📚 **Ler mentes... mas apenas quando a pessoa está contando carneirinhos**

---

## ⚙️ Tecnologias Utilizadas
- **Java 17**
- **Spring Boot 3.5.4**
- **Spring Data JPA**
- **Spring Web**
- **Spring Validation**
- **Thymeleaf**
- **Flyway (migração de banco de dados)**
- **PostgreSQL**
- **Lombok**
- **JUnit 5**

---

## 🛠️ Como Executar o Projeto

### 1️⃣ Pré-requisitos
- Java 17+
- Maven ou Gradle
- PostgreSQL instalado e rodando

### 2️⃣ Configuração do Banco de Dados
Crie um banco no PostgreSQL:
```sql
CREATE DATABASE superpowers;
```

No arquivo `application.properties` (ou `application.yml`), configure:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/superpowers
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=validate
spring.jpa.show-sql=true
```

### 3️⃣ Rodando a aplicação
Via Gradle:
```bash
./gradlew bootRun
```

Ou via Maven:
```bash
./mvnw spring-boot:run
```

---

## 🚀 Funcionalidades
- 📋 Listar superpoderes
- ➕ Adicionar novos superpoderes inúteis
- ✏️ Editar superpoderes existentes
- ❌ Remover superpoderes (para liberar espaço para poderes ainda mais inúteis)

---

## 🧪 Testes
Rodar testes:
```bash
./gradlew test
```

---

## 📄 Licença
Este projeto é livre para uso e modificação. Apenas não utilize para conquistar o mundo — esses superpoderes não vão ajudar muito.

---

> 😄 *“Nem todo herói usa capa... alguns só conseguem descascar bananas com o pensamento.”*
