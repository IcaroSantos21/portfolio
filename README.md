# Portfólio — Ícaro Santos

Portfólio pessoal de **Ícaro Rodrigues Santos**, estudante de Análise e Desenvolvimento de Sistemas e desenvolvedor back-end em formação (Java · Spring Boot · Python).

🔗 GitHub: [github.com/IcaroSantos21](https://github.com/IcaroSantos21)
🔗 LinkedIn: [linkedin.com/in/icarorod21](https://www.linkedin.com/in/icarorod21/)

## Sobre o projeto

Site de página única (one-page) apresentando sobre, stack, projetos em destaque e contato. O design usa uma identidade "terminal" — prompts de shell como eyebrows de seção e um card estilo `neofetch` no hero — inspirada no meu uso diário de Linux (Arch + Hyprland).

## Stack

- **HTML5** — estrutura semântica
- **CSS3** — variáveis CSS, Grid/Flexbox, media queries (sem framework)
- **JavaScript (vanilla)** — `IntersectionObserver` para animações de scroll
- Fontes: [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) + [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts

## Estrutura de arquivos

```
portfolio/
├── index.html   # marcação/estrutura da página
├── style.css    # todo o estilo (tokens, layout, responsivo)
├── script.js    # animações de reveal ao rolar a página
└── README.md    # este arquivo
```

## Como rodar localmente

Não há build nem dependências — é só abrir o `index.html` no navegador:

```bash
git clone https://github.com/IcaroSantos21/<nome-do-repo>.git
cd <nome-do-repo>
```

No Linux/macOS:
```bash
xdg-open index.html   # ou: open index.html no macOS
```

Ou, para servir localmente (recomendado para evitar bloqueios de CORS em alguns navegadores):
```bash
python3 -m http.server 8000
```
e acesse `http://localhost:8000`.

## Responsividade

Layout testado com breakpoints em `1024px`, `768px` e `480px`, cobrindo desktop, tablet e mobile. Também respeita `prefers-reduced-motion` para quem desativa animações no sistema.

## Seções

- **Hero** — headline, CTAs e card `neofetch` com resumo do perfil
- **Sobre** — bio curta + ficha técnica (`cat sobre.env`)
- **Stack** — ferramentas agrupadas por categoria
- **Projetos** — repositórios em destaque, puxados direto do GitHub
- **Contato** — WhatsApp, LinkedIn e GitHub

## Projetos em destaque no portfólio

| Projeto | Descrição | Link |
|---|---|---|
| helpdesk-api | API de helpdesk em Spring Boot, TDD estrito, JWT | [repo](https://github.com/IcaroSantos21/helpdesk-api) |
| Budgeting API | Assistente financeiro por voz com Spring AI + Gemini | [repo](https://github.com/IcaroSantos21/Budgeting-API) |
| task-manager-api | API REST de gerenciamento de tarefas | [repo](https://github.com/IcaroSantos21/task-manager-api) |
| developer-registration-api | Cadastro de desenvolvedores com Design Patterns | [repo](https://github.com/IcaroSantos21/developer-registration-api) |
| food_stock_manager | Gestão de estoque em Rust/Axum (projeto em grupo) | [repo](https://github.com/ExpoTech-Fecaf/food_stock_manager) |
| MLCB_AIR_2026 | Aulas e entregas de Machine Learning | [repo](https://github.com/IcaroSantos21/MLCB_AIR_2026) |

## Contato

- WhatsApp: [(11) 99293-3540](https://wa.me/5511992933540)
- LinkedIn: [linkedin.com/in/icarorod21](https://www.linkedin.com/in/icarorod21/)
- GitHub: [github.com/IcaroSantos21](https://github.com/IcaroSantos21)

---

© 2026 Ícaro Rodrigues Santos
