# IEFE - Campanha Oportunidade Final Magistério 🎓

> Landing page de alta conversão focada em urgência e captura de leads para o curso de Magistério antes da mudança da legislação do MEC.

[![Demo Ao Vivo](https://img.shields.io/badge/DEMO-VER%20AO%20VIVO-00bfa5?style=for-the-badge&logo=vercel)](https://acao-recesso.vercel.app/)

## 📋 Sobre o Projeto

Este projeto é uma **Landing Page Promocional** desenvolvida para a campanha de recesso do IEFE (Instituto de Evolução Funcional Educacional). O objetivo é maximizar as matrículas durante o período de fim de ano, utilizando gatilhos mentais de **urgência** (timers regressivos) e **escassez** (barra de progresso de vagas).

A interface utiliza uma estética **Dark Mode** com acentos em neon (Brand Colors), transmitindo modernidade e seriedade, ao mesmo tempo que guia o usuário para a conversão (Call-to-Action).

## 🚀 Funcionalidades Principais

* **⚡ Performance First:** Otimização agressiva com *Lazy Loading*, *GPU Hardware Acceleration* e scripts não-bloqueantes para garantir 60fps no scroll.
* **⏳ Lógica de Urgência:**
    * *Countdown Timer:* Contagem regressiva dinâmica ajustada para o fim do ano (31/12).
    * *Barra de Progresso:* Simulação visual de ocupação de vagas baseada em datas, criando senso de escassez.
* **📱 Design Responsivo:** Layout fluido construído com **Tailwind CSS**, perfeitamente adaptado para Mobile e Desktop.
* **🎨 UI/UX Imersivo:**
    * Efeitos de *Glow* e *Glassmorphism*.
    * Animações sutis para retenção de atenção.
    * Accordion FAQ para dúvidas rápidas.
    * Modal de Pagamento integrado visualmente.
* **🔒 Segurança & Credibilidade:** Seções dedicadas à validação do MEC e prêmios (Reclame Aqui), reforçando a confiança da marca.

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico:** Estrutura sólida e acessível.
* **Tailwind CSS (CDN):** Estilização utilitária rápida e consistente.
* **Vanilla JavaScript (ES6+):** Lógica leve e otimizada, sem dependência de frameworks pesados, garantindo carregamento instantâneo.

## 📂 Estrutura de Arquivos (Asset Split)

A estrutura foi otimizada para separar tipos de mídia, facilitando manutenção e cache.

```text
/
├── index.html              # O Arquivo Mestre (Markup + Scripts + Styles Inline otimizados)
├── LICENSE.md              # Proteção Legal
├── README.md               # Documentação
└── assets/
    ├── img/                # Apenas imagens estáticas
    │   ├── favicon.ico
    │   ├── logo.png
    │   ├── reclame-aqui-2024.jpg
    │   ├── reclame-aqui-2025.jpg
    │   └── poster-campanha.jpg
    │
    └── video/              # Apenas arquivos de vídeo
        └── video-campanha.mp4