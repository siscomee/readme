<h1>Comee – Controle de Material, Estoque e Entregas</h1>
<p>Sistema para gerenciamento de material, fornecedores, estoque e entregas para micro e pequenos empreendedores do ramo de refeições (marmitex).
Sua arquitetura é baseada em microserviço, fornecendo uma API REST para ser consumida via HTTPS através de browsers e dispositivos móveis, assim como, consumida também por outras APIs, internas ou externas.</p>
<h2>🚀 Começando </h2>
<p>Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e testes.</p>
<h2> 📂Pré-requisitos</h2>
<p>Para instalar uma cópia do projeto, você precisará dos componentes e frameworks abaixo:</p>
<li>FrontEnd</li>
<li>Angular 12.2.5</li>
<li>Node 14.17.5</li>
<li>NPM 6.14.14</li>
<li>IDE VSCode/Eclipse </li>

<h2>BackEnd</h2>
<li>JDK8</li>
<li>Maven 3.5.2</li>
<li>Springboot 2.3.3</li>
<li>Hibernate 5.4.20</li>

<h2>Banco de Dados</h2>
<li>MYSQL 8.0.26</li>

<h2>🔧Instalação</h2>
<p>O sistema é estruturado em três repositórios:</p>
<ul>Database</ul>
<ul>BackEnd</ul>
<ul>FrontEnd</ul>

<h2>Para rodar o projeto localmente: </h2>
<ul>1 - Faça o clone do BackEnd - https://github.com/siscomee/backend.git</ul>
<ul>2 - Execute o projeto pelo caminho:</ul>
<p>Src> main> java> br>com>senac>siscomee> SiscomeeApp.java</p>
<li>Possui o microserviço CORE, escrito em Java 8 para tratar de operações relativas à camda de domínio da aplicação.</li>
<li>Utilizamos o Postman (https://www.postman.com/) para facilitar os testes de endpoints.</li>
<ul>3 - Clicar com o botão direito> escolher a opção run as> Java Application

<ul>4 - Faça o clone do database - https://github.com/siscomee/siscomeeDB.git</ul>
<ul>5 - Para rodar o database com criação automática de entidades:</ul>
<p>Utilizar a configuração no arquivo “application-dev-properties”: spring.datasource.url=jdbc:mysql://localhost:3306/sis_comee?allowPublicKeyRetrieval=true&rewriteBatchedStatements=true&useSSL=false&useUnicode=yes&characterEncoding=UTF8&useLegacyDatetimeCode=true&createDatabaseIfNotExist=true&useTimezone=true&serverTimezone=UTC
spring.datasource.username=root
spring.datasource.password=
spring.datasource.driver-class-name =com.mysql.cj.jdbc.Driver
spring.jpa.show-sql:true
spring.jpa.hibernate.ddl-auto=create
spring.jpa.properties.hibernate.format_sql=true
spring.jpa.properties.hibernate.show_sql=true
spring.jpa.properties.hibernate.use_sql_comments=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
spring.jpa.database-platform=org.hibernate.dialect.MySQL8Dialect
Estrutura de Entidades<p>

<ul>6 – Faça o clone do FrontEnd - https://github.com/siscomee/frontend.git </ul>
<ul>7 – Execute o projeto no VSCode com o comando ng serve</ul>

Após a instalação do projeto, como enunciado acima, poderá utilizar o sistema através de nossos formulários.
O sistema Comee conta com as configurações de ambientes abaixo:
FrontEnd
http://localhost:4200
http://localhost:9000
Para maiores detalhes sobre execução do front, acesse o readme.md específico deste repositório.

<h2>⚙️ Executando os testes</h2>
<p>Cadastro de Fornecedores:
Acessar o menu Administração> Fornecedores
Clicar no botão Novo
Preencher os campos:
Ramo Setor – Informar a partir da lista exibida, exemplo: Embalagens, HortiFrut, Açougue
Fornecedor: Informar o nome do fornecedor, social ou fantasia: Pão de Açucar
CNPJ: Informar o CNPJ do fornecedor
Telefone: Informar o telefone com DDD.
Situação: Informar se o fornecedor é ativo ou Inativo.
Para os cadastros iniciais, este campo é indicado como ativo.

Para pesquisar por fornecedores, poderá utilizar os filtros disponíveis em tela
Ramo Setor, Nome do Fornecedor ou Situação

Para consultar detalhes do cadastro, poderá utilizar o botão de detalhes 
Para edição de cadastros, poderá utilizar o botão de edição 
Para exclusão de cadastros, poderá utilizar o botão de remoção </p>

<h2>🚚 Implantação</h2>
Por possuir microseviço, a solução pode ser integrada à outros sistemas, consumida por browsers e dispositivos móveis, ou ainda, por outras APIs.
<h2>🛠 Construído com</h2>
<li>Angular – Framework para interface</li>
<li>Maven - Gerente de Dependência</li>
<li>VSCode – Execução FrontEnd</li>
<li>Eclipse com plugin STS (Spring Tool Suite) – Execução BackEnd</li>
<li>MySql – Banco de Dados</li>
<h2>🙋 Versão</h2>
<p>Utilizamos o GitHub para controle de versionamento, onde nossos colaboradores clonam o projeto, realizam os desenvolvimentos em branches individuais, e após a conclusão solicitam o merge request para o owner do projeto, que por fim realiza o merge para a branch principal (master) de cada repositório alterado.</p>
<h2>✒️ Autores</h2>
<p>Colaboradores para viabilização deste projeto:</p>
<p>👩Rita Pavão – Desenvolvedor inicial<p/>
<p>👨Márcio Nogueira – Dev FrontEnd </p>
<p>👨Lauro Leme – Dev BackEnd</p>
<p>👨William Dias – Dev BackEnd</p>
<p>👩Carlla Mesquita – Documentação </p> 
<p>👩Rebeca Rivas – Documentação</p>
<h2>🎁Expressões de gratidão</h2>
Para conhecer nossa solução e navegar por sua estrutura, siga o nosso projeto em: https://github.com/siscomee/

