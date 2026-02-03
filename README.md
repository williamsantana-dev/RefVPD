# 🌿 Referência VPD - Referência e Calculadora de Cultivo

![VPD Master](https://img.shields.io/badge/Status-Completo-brightgreen)
![SEO-Friendly](https://img.shields.io/badge/SEO-Otimizado-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

A **referência de VPD** é uma ferramenta web de código aberto projetada para growers que buscam o controle total do ambiente de cultivo. Utilizando a fórmula científica de pressão de vapor de saturação (Equação de Tetens), a ferramenta ajuda a encontrar o equilíbrio perfeito entre temperatura e umidade.

## 🚀 Funcionalidades

-   **Calculadoras Dinâmicas:** -   Informe a temperatura e descubra o gap de umidade ideal.
    -   Informe a umidade e descubra o gap de temperatura ideal.
-   **Tabela VPD Completa:** Gráfico interativo cobrindo de 15°C a 35°C com marcações visuais de zonas de risco (Vermelho), transição (Amarelo) e ideal (Verde).
-   **Tema Dark/Light:** Conforto visual para conferir os dados em qualquer horário.
-   **Foco em SEO:** Estruturado com JSON-LD e tags semânticas para indexação em buscadores e IAs.
-   **Mobile First:** Totalmente responsivo, feito para ser usado no celular dentro do grow.

## 🛠️ Tecnologias Utilizadas

-   **HTML5** (Semântico)
-   **CSS3** (Custom Properties e Flexbox/Grid)
-   **JavaScript** (Vanilla - sem bibliotecas externas)
-   **JSON-LD** (Dados estruturados para SEO)

## 📖 Como usar

1. Faça o clone do repositório ou baixe o arquivo `index.html`.
2. Abra o arquivo em qualquer navegador moderno.
3. Não é necessário servidor ou instalação de dependências.

## 🧠 A Ciência por trás

O VPD (Déficit de Pressão de Vapor) é calculado no código através da fórmula:
```javascript
SVP = 0.61078 * exp((17.27 * T) / (T + 237.3))
VPD = SVP * (1 - (UR / 100))
