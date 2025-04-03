# 📝 **To-Do List - Config Server** 📝

## 📜 **Descrição**

Este repositório armazena os arquivos de configuração (`.properties`) dos microsserviços do projeto **To-Do List**, utilizando o **Spring Cloud Config Server** para fornecer uma abordagem centralizada e escalável na gestão de configurações.

O projeto é constituído por alguns microsserviços e repositório de configuraçöes. A seguir, estão os principais componentes do sistema:

- **[ms-service-notification](https://github.com/iaugustoz/ms-main-service/)**: reponsável pelo gerenciamento e envio de notificações no sistema de To-Do List
- **[ms-tasks-service](https://github.com/iaugustoz/ms-tasks-service)**: reponsável pelo processamento e administração das tarefas disponíveis
- **[ms-main-service](https://github.com/iaugustoz/ms-main-service/)**: microsserviço centralizador responsável por atuar como servidor de configuração (Config Server) e serviço de descoberta (Eureka Server).
  
---

## 🚀 **Status do Projeto**

✅ Projeto concluído.

---

## ⚙️ **Tecnologias Utilizadas**

- **Java 21**
- **Spring Boot**
- **Spring Cloud Config Server**
- **Git como Backend de Configuração**
- **Docker e Kubernetes (GKE) para orquestração**

---

## 🛠️ **Como Funciona o Config Server?**

O **Spring Cloud Config Server** permite que os microsserviços recuperem suas configurações de um repositório central, garantindo:  
✔ **Gerenciamento centralizado** das configurações de cada serviço  
✔ **Separação entre código e configuração**, seguindo o princípio _12-Factor App_  
✔ **Facilidade de atualização** sem necessidade de reimplantar os microsserviços  
✔ **Segurança e versionamento**, garantindo controle sobre mudanças nas configurações

---

## 📢 **Contribuições**

Caso tenha sugestões ou melhorias, fique à vontade para abrir uma **issue** ou enviar um **pull request**.

---

## 📜 **Licença**

Este projeto está sob a licença **MIT**.
