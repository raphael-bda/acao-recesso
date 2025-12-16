<div align="center">
  <img src="assets/img/logo.png" alt="IEFE Logo" width="120" />
  <br />
  <br />

  # 🎓 IEFE — Oportunidade Final Magistério
  
  **Landing Page de Alta Performance & Conversão**
  <br />
  *Focada em Urgência, Escassez e Retenção de Leads.*

  <p align="center">
    <a href="https://acao-recesso.vercel.app/">
      <img src="https://img.shields.io/badge/DEMO_AO_VIVO-VER_AGORA-00bfa5?style=for-the-badge&logo=vercel&logoColor=white" alt="Demo">
    </a>
  </p>
  
  <p align="center">
    <img src="https://img.shields.io/badge/Performance-100%25-success?style=flat-square" alt="Performance">
    <img src="https://img.shields.io/badge/Tailwind_CSS-3.4-38bdf8?style=flat-square&logo=tailwindcss" alt="Tailwind">
    <img src="https://img.shields.io/badge/License-Proprietary-red?style=flat-square" alt="License">
  </p>
</div>

---

## 🖼️ Visão Geral

![Preview da Landing Page](https://i.imgur.com/AocgiFB.jpeg)

> *"Não deixe o MEC trancar seu futuro."*

Este projeto é uma **Landing Page Estratégica** desenvolvida para a campanha de fim de ano do **IEFE**. O objetivo é capturar matrículas antes da mudança legislativa do MEC, utilizando uma arquitetura focada em **gatilhos mentais** e **velocidade de carregamento**.

---

## 🚀 Engenharia & Funcionalidades

Não é apenas bonito. É rápido e inteligente.

### ⚡ Performance (Core Web Vitals)
* **Zero-Config Build:** Arquitetura estática pura para carregamento instantâneo.
* **GPU Acceleration:** Animações e cards com `will-change` e `transform: translateZ(0)` para 60fps constantes.
* **Resource Prioritization:** *Lazy loading* em imagens secundárias e *Preload* inteligente de mídia.
* **Assets Split:** Separação física de Imagens e Vídeos para melhor estratégia de cache.

### 🧠 Lógica de Conversão (Psychology-First)
* **Cronômetro Regressivo:** Lógica JS que calcula o tempo restante até 31/12 em tempo real.
* **Barra de Escassez Dinâmica:** Algoritmo que simula a ocupação de vagas (94% a 100%) baseado na data atual, gerando pressão de decisão.
* **Modal de Pagamento Imersivo:** Evita redirecionamentos desnecessários, mantendo o usuário no ambiente seguro.

### 🎨 Design System (Dark/Neon)
* **Estética:** Dark Mode profundo (`#050505`) com acentos em *Neon Brand Green* (`#00bfa5`).
* **Feedback Visual:** Efeitos de *Glow*, *Glassmorphism* e micro-interações em todos os elementos clicáveis.

---

## 📂 Estrutura de Arquivos

Organização profissional para escalabilidade e manutenção simplificada.

```text
/
├── index.html              # O Core (Markup + Lógica + Estilos Críticos)
├── LICENSE.md              # Termos de Uso Proprietário
├── README.md               # Documentação
└── assets/                 # Ativos Otimizados
    ├── img/                # Imagens Estáticas (WebP/JPG/PNG)
    │   ├── favicon.ico
    │   ├── logo.png
    │   ├── reclame-aqui-2024.jpg
    │   ├── reclame-aqui-2025.jpg
    │   └── poster-campanha.jpg
    │
    └── video/              # Mídia Pesada (MP4)
        └── video-campanha.mp4