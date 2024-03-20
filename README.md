# Serviço para envio de email usando spring-boot e como provedor de email o mailtrap.io.

## 💻 Requisitos

No projeto foi utilizado o spring boot e a plataforma intelij idea. Você pode utilizar qualquer plataforma de desenvolvimento, exemplo: eclipse e o Netbeans.
Utilizei como servidor de email o [MailTrap](https://mailtrap.io/home), que fornece um serviço gratuito para testes de envio de email.

## 💻 Configuração do application.properties

Crie uma conta no [MailTrap](https://mailtrap.io/home), e com acesso as suas credenciais geradas configure:

```bash
spring.mail.host=sandbox.smtp.mailtrap.io
spring.mail.port=587
spring.mail.username=seu username
spring.mail.password=seu password
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true
```

## 🚀 Instalando

Primeiro, você deve clonar o projeto na sua máquina, para isso você
pode colar o seguinte comando em seu terminal

```bash
git clone https://github.com/Tiago-Silva/email-springboot-service.git
```

Para instalar as dependências, realize o reload com o Maven, se você preferir pode executar o camando via terminal:

```bash
mvn clean install
```


## 📝 Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais informações.

