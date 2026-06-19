
# 🏆 Brasil em Copas

> "Todo mundo tenta, mas só o Brasil é penta!"

Hotsite responsivo e dinâmico que celebra as cinco páginas de ouro do futebol brasileiro: as edições históricas da Copa do Mundo em que a Seleção Canarinho conquistou o topo do mundo. Projeto focado no desenvolvimento de layouts adaptáveis, semântica limpa e interatividade mobile.

🔗 **[Clique aqui para ver o projeto ao vivo](https://daniloabreudev.github.io/brasil-em-copas/)**

---

## 📱 Demonstração do Projeto
O site foi construído com foco total na experiência do usuário (**UX**), contando com:
*   **Menu Hambúrguer Interativo:** Manipulado via JavaScript para otimizar espaço em telas menores.
*   **Links Âncora com Rolagem Suave:** Navegação direta entre as seções através do menu.
*   **Layout Fluido:** Design que flutua perfeitamente desde telas de celulares antigos até monitores Desktop de alta resolução.

---

## 🛠️ Tecnologias Utilizadas

Para este projeto, apliquei conceitos modernos de desenvolvimento Web Front-End:

*   **HTML5 Semântico:** Uso estratégico de tags como `<header>`, `<nav>`, `<main>`, `<article>` e `<footer>` para melhor acessibilidade e SEO.
*   **CSS3 Avançado & Media Queries:** Estruturação responsiva com o uso de **Variáveis Globais (`:root`)** para padronização da paleta de cores (Verde, Amarelo e Azul da Seleção) e arquitetura modular de arquivos (`style.css` e `media-query.css`).
*   **JavaScript (Vanilla):** Funções nativas para controle dinâmico do DOM e monitoramento do tamanho da tela (`onresize`).

---

## 📂 Estrutura de Arquivos

```text
brasil-em-copas/
│
├── estilos/
│   ├── style.css          # Estilização base (Mobile First/Celular)
│   └── media-query.css    # Configurações para telas grandes (Tablet/PC)
│
├── imagens/               # Fotos históricas e assets do projeto
│
├── index.html             # Estrutura principal do site e lógica JS
└── README.md              # Documentação do repositório
