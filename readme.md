# API REST Ingresse Dev Test Backend
**Este projeto foi criado para teste de processo seletivo de desenvolvedor beckend da empresa Ingresse**

## Pré requisitos de software
* **Java 8**
* **Eclipse**
* **Springboot 2.1.3(framework)**
* **Mavem**
* **Swagger 2.9.2**
* **PostgreSQL 10**
* **Navegador atualizado** *(Recomenda-e a utilização do chrome para este exemplo)*

### Por onde começar
1º Dentro do PostgreSQL crie um banco de dados chamado "produtos-apirest".
2º Dentro do Eclipse, abra o projeto "apirest", em seguida abra a pasta "src/main/java", depois abra o pacote "com.produtos.apirest", selecione o arquivo "ApirestAplication.java" clicando com o botão direito do mouse e vá em Run As e escolha a opção Java Aplication, isso rodará o projeto no servidor tomcat embutido dentro framework Spring Boot.
3º No navegador digite http://localhost:8080/swagger-ui.html, agora clique em "produto-resource" que mostrarar na tela as opções: POST, PUT, DELETE, e GET, onde conseguirar interagir com o banco de dados.
4º O projeto está publicado no Heroku, através de https://apirest-pdt.herokuapp.com/swagger-ui.html, conseguirar interagir com o banco de dados em produção. 