# Teste-Leilao-SelleniumWebDriver

# 🧪 Automação de Testes E2E com Selenium WebDriver e Java (Sistema de Leilões)

Projeto de automação de testes End-to-End (E2E) desenvolvido em **Java** utilizando **Selenium WebDriver** e o padrão de projeto **Page Objects**, focado na validação funcional de uma aplicação web completa de gerenciamento de leilões online.

---

## 📋 Sobre o Projeto

O objetivo deste projeto é garantir a qualidade e o comportamento esperado das principais jornadas de usuário em uma plataforma de leilões (baseada no ecossistema Spring Boot com Thymeleaf e Spring Security). A suíte de testes cobre desde a autenticação de usuários até o fluxo completo de cadastro, listagem, visualização e registro de lances em leilões.

---

## 🛠️ Tecnologias e Padrões Utilizados

* **Linguagem:** Java
* **Automação Web:** Selenium WebDriver
* **Arquitetura de Testes:** Page Object Model (POM)
* **IDE:** Eclipse
* **Aplicação Alvo (Backend/Frontend):** Spring Boot, Spring Security, Spring Data JPA, Thymeleaf e Bootstrap

---

✅ Funcionalidades e Cenários Cobertos
Autenticação (LoginTest): Validação de login com credenciais válidas, tratamento de erro para credenciais inválidas e controle de acesso a rotas protegidas.

Gerenciamento de Leilões (LeiloesTest): Fluxo de criação de novos leilões, preenchimento de formulários, validação de campos obrigatórios e verificação na listagem geral.

Interação com Lances (LancesPage): Navegação para a página de detalhes de um leilão específico e estruturação para envio e validação de lances.

Reutilização e Manutenibilidade (PageObject): Centralização do gerenciamento do WebDriver, esperas e navegação entre páginas para evitar duplicação de código nos testes.


🚀 Como Executar o Projeto
Pré-requisitos:

-JDK instalado (Java 8 ou superior)
-Navegador Google Chrome e chromedriver compatível com a versão do navegador
-IDE Java (Eclipse ou IntelliJ IDEA)

Passos para execução:

-Clone este repositório:
Bash
git clone [https://github.com/Salvatore-V/seu-repositorio.git](https://github.com/Salvatore-V/seu-repositorio.git)

-Importe o projeto como um projeto Java/Maven existente na sua IDE.

-Certifique-se de que o caminho do chromedriver está configurado corretamente no projeto.

-Inicie a aplicação executando a classe LeilaoApplication.java.

-Execute as classes de teste (LoginTest.java e LeiloesTest.java) utilizando o executor de testes da IDE (JUnit).
