## Bem-vindo

Este repositório contem docker-compose com o Apache Airflow

Para que este projeto funcione corretamente é necessário seguir os passos em: [Docker - Instalar e Configurar](https://github.com/pauloricardoferreira/docker_instalar_configurar)

[Documentação Apache Airflow](https://airflow.apache.org)

### **Observações**
Caso o horário esteja diferente do GMT-3, atualize o horário do servidor e adicione os itens abaixo na sessão de volumes
- /etc/timezone:/etc/timezone:ro
- /etc/localtime:/etc/localtime:ro
