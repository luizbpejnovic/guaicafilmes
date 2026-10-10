# Guaica Filmes — Site institucional

**Site oficial da Guaica Filmes**, uma produtora audiovisual de Porto Alegre (RS). O site apresenta a produtora, o fundador e um portfólio de vídeos com player próprio.

🔗 **Ver o site no ar:** [luizbpejnovic.github.io/guaicafilmes](https://luizbpejnovic.github.io/guaicafilmes/)

![Página inicial do site da Guaica Filmes](docs/desktop.jpg)

---

## Sobre o projeto

A Guaica Filmes precisava de uma presença online que transmitisse a identidade da marca, *"Histórias com raízes"*, e que mostrasse os trabalhos em vídeo de forma direta para clientes e parceiros.

Desenvolvi o site do zero, cuidando de:

- **Design e identidade visual:** paleta terrosa (marrom, dourado e pergaminho) derivada do logotipo, tipografia editorial (Fraunces, Work Sans e Space Mono) e textura de granulação de filme
- **Desenvolvimento front-end:** HTML, CSS e JavaScript puros, sem frameworks e sem dependências
- **Publicação e hospedagem:** GitHub Pages, com custo zero de servidor

## Funcionalidades

| Recurso | Descrição |
|---|---|
| 🎬 **Portfólio em vídeo** | Cards com prévia em loop. Ao clicar, o vídeo abre em tela cheia num *lightbox*, que fecha pelo botão, com a tecla Esc ou com um clique fora |
| 📱 **Responsivo** | Layout adaptado para celular, tablet e desktop, com menu hambúrguer no mobile |
| ✨ **Animações sutis** | Seções que surgem com a rolagem (`IntersectionObserver`), folhas flutuando e granulação de filme em `<canvas>` |
| ♿ **Acessibilidade** | Respeita a preferência `prefers-reduced-motion`, usa HTML semântico e tem textos alternativos nas imagens |
| ⚡ **Leve** | Uma única página estática; o logo e a foto ficam embutidos no HTML e os vídeos carregam sob demanda |

## Seções do site

1. **Início:** logotipo, slogan e apresentação
2. **Sobre:** a produtora e seus serviços (direção, produção, narrativa e parceria)
3. **Fundador:** perfil de Guilherme Medaglia
4. **Portfólio:** *Linha Couro* (publicidade), *Running* (cinematografia esportiva) e *Corrida de Rua* (cobertura de evento)
5. **Contato:** e-mail e Instagram

<p align="center">
  <img src="docs/portfolio.jpg" alt="Seção de portfólio com os três vídeos" width="68%">
  &nbsp;
  <img src="docs/mobile.jpg" alt="Versão para celular" width="22%">
</p>

## Tecnologias

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat&logo=githubpages&logoColor=white)

## Estrutura

```
guaicafilmes/
├── index.html          # página completa (HTML, CSS e JS)
├── assets/
│   ├── projeto-01.mp4  # Linha Couro
│   ├── projeto-02.mp4  # Running
│   ├── projeto-03.mp4  # Corrida de Rua
│   └── thumb-0X.jpg    # miniaturas dos vídeos
└── docs/               # capturas de tela deste README
```

## Como rodar localmente

Não precisa instalar nada. Basta clonar o repositório e abrir o `index.html` no navegador:

```bash
git clone https://github.com/luizbpejnovic/guaicafilmes.git
```

---

**Desenvolvido por [Luiz Eduardo Brunelli Pejnovic](https://github.com/luizbpejnovic)**, criação e administração de soluções digitais e de TI.

*Vídeos, marca e conteúdo © Guaica Filmes. Todos os direitos reservados.*
