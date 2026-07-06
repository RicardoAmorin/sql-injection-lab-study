# SQL Injection Lab Study

## Sobre

Este repositório documenta meus estudos sobre SQL Injection realizados em um ambiente de laboratório.

O laboratório foi desenvolvido pelo canal **AulasHack**, no curso **Dominando o Pentest Web**, sendo utilizado exclusivamente para fins educacionais.

O objetivo deste projeto foi compreender como uma vulnerabilidade de SQL Injection pode ser identificada, explorada e, principalmente, como pode ser corrigida.

---

## Ferramentas utilizadas

- Kali Linux
- Burp Suite Community
- sqlmap
- SQLite

---

## Etapas realizadas

### 1. Acesso ao laboratório

Foi realizado o acesso ao sistema vulnerável disponibilizado durante o curso.

![Login](images/1,jpeg)

---

### 2. Interceptação da requisição

Utilizei o Burp Suite para interceptar a requisição enviada pelo formulário de login.

![Burp](images/2.jpeg)

---

### 3. Exportação da requisição

A requisição HTTP foi salva em um arquivo para utilização no sqlmap.

![Request](images/3.jpeg)

---

### 4. Teste da vulnerabilidade

O sqlmap identificou uma vulnerabilidade de SQL Injection.

![SQLMap](images/4.jpeg)

---

### 5. Resultado

Foi demonstrado o impacto da vulnerabilidade em ambiente controlado.

> As informações sensíveis foram ocultadas nesta documentação.

![Resultado](images/5.jpeg)

---

## Aprendizados

- Interceptação de requisições HTTP
- SQL Injection
- Burp Suite
- sqlmap
- SQLite
- Segurança em aplicações Web
- Importância de Prepared Statements

---

## Aviso

Este estudo foi realizado **exclusivamente em ambiente de laboratório autorizado**, com finalidade educacional.

Todo o crédito pelo laboratório pertence ao canal **AulasHack** e ao curso **Dominando o Pentest Web**.