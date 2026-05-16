# Antigravity Dashboard 🚀

Este é um painel (dashboard) criado para ser a minha primeira página do dia. Ele ajuda-me a organizar o trabalho, ver compromissos e acompanhar os meus estudos num só lugar.

Este projeto foi desenvolvido durante a **Sprint de IA no trabalho** da **PrograMaria**, seguindo o tutorial [Vibe Coding](https://gabisurita.github.io/gabisurita/courses/vibecoding/#parte-4).

---

## 🌌 O que o painel faz?

A ideia é abrir esta página assim que começo a trabalhar para saber exatamente por onde começar. O visual é inspirado no espaço (tema escuro de galáxia) e usa o emoji de foguete (🚀) para representar o crescimento na carreira.

### Principais funções:
* **Resumo do dia:** Mostra quantos e-mails novos tenho no Gmail.
* **Agenda:** Lista as minhas próximas reuniões e entrevistas.
* **Tarefas:** Mostra o que tenho para fazer e os prazos da minha lista profissional.
* **Progresso de Cursos:** Lê automaticamente uma [planilha do Google Sheets](https://docs.google.com/spreadsheets/d/193WeCbB1y5Pxz4iR8DCKQj-v1GYfmexTTSpOhF7V7Ic/edit?usp=sharing) para mostrar quanto % já concluí de cada curso.
* **Gráfico de E-mails:** Um gráfico simples que mostra se a minha semana está muito cheia ou tranquila.
* **Frases do dia:** Uma saudação que muda conforme a hora (Bom dia, Boa tarde) e mensagens de incentivo que variam a cada acesso.

---

## 🛠️ Ferramentas utilizadas

* **Visual:** HTML e CSS (feito para funcionar no computador e no telemóvel).
* **Dados:** APIs do Google (Gmail, Agenda, Tarefas e Sheets).
* **Gráficos:** Chart.js.
* **Linguagem:** JavaScript para conectar tudo.

---

## 🚀 Como testar no teu computador

1.  Copia os arquivos para o teu computador.
2.  Configura o teu `Client ID` do Google no código.
3.  Abre o terminal na pasta do projeto e digita:
    ```bash
    python -m http.server 8000
    ```
4.  No navegador, acede a: `http://localhost:8000`.

---

## 📚 Créditos

* **Tutorial:** [Vibe Coding - Gabi Surita](https://gabisurita.github.io/gabisurita/courses/vibecoding/#parte-4).
* **Apoio:** Sprint de IA - **PrograMaria**.
