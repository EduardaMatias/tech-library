# 💜 NLW Connect | Rocketseat

O **Next Level Week (NLW)** é o maior evento de programação na prática da Rocketseat, proporcionando uma semana intensa de aprendizado, desafios e networking. Durante o evento, os participantes têm a oportunidade de desenvolver um projeto inédito em apenas uma semana, explorando novas tecnologias na prática e aprimorando suas habilidades técnicas e profissionais.

<p align="center">
  <img src="https://img.shields.io/badge/Trilha%20Escolhida-C%23-7B61FF?style=for-the-badge&logo=c-sharp&logoColor=white">
</p>

## 💻 Projeto

Nesta trilha, os participantes exploram conceitos essenciais do ecossistema C# e .NET, mergulhando na prática para compreender todo o potencial dessa linguagem. Ao longo da trilha, são criadas e desenvolvidas APIs, abordando tópicos fundamentais, como criação de usuários e autenticação, criptografia de senhas, integração com banco de dados, implementação de tokens de acesso JWT, definição e tratamento adequado de exceções personalizadas, paginação e filtragem na recuperação de livros e muito mais!

O projeto final consiste em um sistema de reserva de livros, no qual os usuários podem se cadastrar, fazer login, visualizar a lista de livros de forma paginada, aplicar filtros e realizar reservas.

## 🚀 Como Executar

Siga os passos abaixo para configurar e rodar a API localmente:

### 📌 Pré-requisitos
Antes de começar, certifique-se de ter os seguintes requisitos instalados:
- [.NET SDK](https://dotnet.microsoft.com/en-us/download) (versão 8.0 ou superior)

### 📥 Clonando o Repositório
```bash
https://github.com/EduardaMatias/tech-library.git
```

### 🖥️ Abrindo o Projeto no Visual Studio
- Abra o Visual Studio no seu computador. <br>
-  No menu inicial, selecione `"Abrir um projeto ou solução"`. <br>
-  Navegue até o diretório onde você clonou o repositório e selecione o arquivo de solução (.sln) do projeto. <br>
-  Clique em Abrir. <br>
-  Aguarde o Visual Studio carregar o projeto e todas as dependências. <br>

### ⚙️ Configurando o Banco de Dados
> O projeto utiliza **SQLite** como banco de dados. Para garantir que a API funcione corretamente, é necessário atualizar o caminho do arquivo do banco no código. <br>
- No arquivo `TechLibraryContext.cs`, altere o método `OnConfiguring` para apontar para o caminho correto do banco de dados na sua máquina: <br>
   ```csharp
   protected override void OnConfiguring(DbContextOptionsBuilder optionsBuilder)
   {
       optionsBuilder.UseSqlite("Data Source=CAMINHO/DO/ARQUIVO/TechLibraryDb.db");
   }
   ```

### 🎉 Executando o projeto
- Para executar o projeto, pressione F5 ou clique em Iniciar na barra de ferramentas.

### 🧩 Swagger

![image](https://github.com/user-attachments/assets/210c7172-253c-4865-aa6f-547428f789dc)

---

Feito com 💜 por <a href="https://linkedin.com/in/eduarda-matias">Eduarda Matias</a>
