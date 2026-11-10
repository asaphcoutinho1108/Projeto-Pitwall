# 🏁 Desafio Pit Wall — GP de São Paulo de F1

Um projeto web responsivo construído exclusivamente com **HTML5** e **CSS3** para simular a página oficial do GP de São Paulo de Formula 1. 

Este projeto foi desenvolvido como parte de uma atividade da disciplina de **Linguagem de Marcação (LIMA)**, sob orientação dos professores **André Denani** e **Raul Lopes**.

---

## 📌 Sobre o Projeto

O objetivo principal do **Desafio Pit Wall** é aplicar e consolidar conceitos fundamentais de front-end, replicando um layout moderno com temática de alta velocidade, foco em alinhamento de grid/flexbox e boa experiência visual em diferentes dispositivos.

### 🎯 Funcionalidades & Visualizações
* **Topo & Hero Banner:** Apresentação impactante com a marca do evento, estatísticas da pista de Interlagos e background estilizado com degradê angular e a zebra da pista.
* **Grid de Pilotos:** Exibição dos cartões dos pilotos com a cor temática da respetiva equipa (Ferrari, McLaren, Mercedes, Audi) e números em efeito marca d'água.
* **Tabela de Classificação:** Placar com destaques visuais para o líder do campeonato e identificadores coloridos por equipa.
* **Secção de Ingressos:** Formulário estruturado para reserva de ingressos e recado para os pilotos.
* **Design Responsivo:** Adaptação completa do layout para ecrãs de tablets e smartphones.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica da página.
* **CSS3:** Estilização, layout e responsividade.
  * Variáveis CSS (`:root`) para padronização da paleta de cores.
  * **Flexbox** e **CSS Grid** (`auto-fit`, `form-grid`) para controlo de layout.
  * `repeating-linear-gradient` para criação da zebra da pista.
  * Media Queries (`@media`) para responsividade mobile.
* **Google Fonts:** Tipografia oficial importada (`Titillium Web`).

---

## 📂 Estrutura de Ficheiros

```text
pit-wall/
├── index.html        # Estrutura principal em HTML
├── styles.css        # Estilos globais e media queries
└── img/              # Imagens e recursos visuais
    └── piloto.jpg    # Imagem de fundo do Hero
