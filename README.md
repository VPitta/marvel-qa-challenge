# 🦸 Marvel API Test

![Em Desenvolvimento](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)  

<p align="center">
  <img src="https://raw.githubusercontent.com/abhisheknaiidu/awesome-github-profile-readme/master/assets/programming.svg" width="400"/>
</p>

## 💻 Sobre o Projeto
Este projeto é um **desafio de Quality Assurance (QA)** utilizando a **Marvel API**, com foco em:  
- Testes **automatizados de API** com **Cypress**  
- Testes **manuais de API** com **Postman**  
- Testes **E2E** em interface web  
- Documentação de testes no **Jira**  
- Boas práticas de QA, rastreabilidade e cobertura de testes  

---

# 🗺️ Roadmap QA – Marvel API Test

## Semana 1 – Preparação
- [ ] Criar conta no Marvel Developer  
- [ ] Gerar API Key (public e private)  
- [ ] Ler documentação dos endpoints principais:
  - `/v1/public/characters`  
  - `/v1/public/comics`  
  - `/v1/public/series`  
- [ ] Configurar ambiente:
  - Criar repositório GitHub `marvel-api-tests`  
  - Inicializar Node + Cypress (`npm init` + `npm install cypress`)  
  - Criar estrutura de pastas:  
    ```
    /cypress
      /integration
      /fixtures
      /support
    README.md
    package.json
    ```
- [ ] Configurar **Postman**:
  - Criar **Collection** `Marvel API Tests`  
  - Criar requisições para cada endpoint e organizar pastas (Characters, Comics, Series)  
  - Adicionar variáveis de ambiente para API Key  

---

## Semana 2 – Testes de API com Postman e Cypress
- [ ] **Postman – Testes manuais**:
  - Validar status code 200 para endpoints principais  
  - Conferir campos obrigatórios (`name`, `id`, `description`, `title`, etc.)  
  - Testar filtros e buscas específicas (ex.: Spider-Man)  
  - Testar respostas inválidas (ID inexistente → 404 ou mensagem de erro)  
- [ ] **Postman – Testes automáticos na aba “Tests”**:
  - Criar scripts para validar status code e campos obrigatórios  
  - Automatizar verificações de filtros e respostas de erro  
- [ ] **Cypress – Testes automatizados**:
  - Criar testes para cada endpoint reproduzindo os testes do Postman  
  - Validar:
    - Status code correto  
    - Campos obrigatórios  
    - Filtros funcionando  

---

## Semana 3 – Testes Manuais & Documentação no Jira
- [ ] Criar casos de teste no Jira:
  - Pré-condições (API Key, endpoint)  
  - Passos de teste  
  - Resultado esperado  
  - Status  
- [ ] Executar testes manuais no **Postman**  
- [ ] Comparar resultados dos testes **Postman** com os testes automatizados **Cypress**  

---

## Semana 4 – Testes E2E 
- [ ] Criar interface web simples consumindo a Marvel API:
  - Lista de personagens  
  - Pesquisa por nome  
- [ ] Criar testes **Cypress E2E**:
  - Validar que os dados exibidos correspondem à API  
  - Testar filtros e interações  

---

## Semana 5 – Finalização & GitHub
- [ ] Estruturar `README.md` do projeto:
  - Descrição do desafio  
  - Tecnologias usadas  
  - Como rodar os testes  
- [ ] Commit final dos testes **Cypress**  
- [ ] Commit dos casos de teste no **Jira**  
- [ ] Linkar README com badges das tecnologias utilizadas  

---

✨ **Objetivo:** Evoluir em QA, praticar testes automatizados e manuais de API, documentar tudo com rastreabilidade e mostrar resultados profissionais no GitHub.

