# Humberto Freitas — Portfolio Landing Page

> Portfólio pessoal moderno e responsivo, com suporte bilíngue PT/EN e deploy automatizado via GitHub Actions.

🔗 **[Ver online](https://humbertoff.github.io/PortfolioGit/)**

---

## 🚀 Como este portfólio foi construído

### Tecnologias

| Camada | Tecnologia | Detalhe |
|--------|-----------|---------|
| Estrutura | **HTML5** | Semântico, sem frameworks |
| Estilo | **CSS3** | Variáveis CSS, glassmorphism, gradientes, keyframe animations |
| Interatividade | **JavaScript Vanilla** | Canvas 2D, IntersectionObserver, toggle PT/EN |
| Hospedagem | **GitHub Pages** | HTTPS + CDN global, 99.9% de disponibilidade |
| CI/CD | **GitHub Actions** | Deploy automático a cada `push` na `main` |

### Pipeline CI/CD

```
💻 Edição local → git push → ⚙️ GitHub Actions → 🔨 Build/Validação → 🚀 GitHub Pages ✅
```

A cada commit na branch `main`, o GitHub Actions detecta a mudança e publica automaticamente no GitHub Pages — sem nenhuma etapa manual de deploy.

### Funcionalidades

- **Fundo animado** com partículas interconectadas via Canvas 2D
- **Scroll reveal** com IntersectionObserver (fallback: conteúdo visível sem JS)
- **Toggle PT / EN** em tempo real via atributos `data-pt` / `data-en` no DOM — sem requisição ao servidor
- **Contadores animados** nos cards de estatísticas
- **Responsivo** para mobile, tablet e desktop com CSS Grid e Flexbox
- **Zero dependências externas** — nenhuma biblioteca ou framework

---

## 📁 Estrutura

```
PortfolioGit/
├── portfolio-landing.html   # Landing page do currículo (PT/EN)
├── profile-photo.jpg        # Foto de perfil
├── inpi-cert.png            # Certificado INPI — BeCheck
├── index.html               # Página principal do portfólio
└── assets/
    └── media/               # Mídias dos projetos
```

---

## 👨‍💻 Sobre o autor

**Humberto Freitas** — Desenvolvedor Full Stack Java | Spring Boot | Angular

- 📧 humbertofilho8@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/humberto-freitasfilho/)
- 💻 [GitHub](https://github.com/HumbertoFF)
- 🌐 [Portfólio](https://humbertoff.github.io/PortfolioGit/)
