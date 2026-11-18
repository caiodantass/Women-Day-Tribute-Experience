# 🌸 Tribute & Interactive UI/UX Experience in React

[![React](https://img.shields.io/badge/Frontend-React%2018-61DAFB.svg?logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Bundler-Vite-646CFF.svg?logo=vite&logoColor=white)](https://vitejs.dev/)
[![CSS3](https://img.shields.io/badge/Styling-CSS3%20Keyframes%20%26%20Animations-1572B6.svg?logo=css3)](https://www.w3.org/Style/CSS/)
[![Deploy](https://img.shields.io/badge/Deploy-Vercel-black.svg?logo=vercel&logoColor=white)](https://site-homenagem-ao-dia-das-mulheres.vercel.app)
[![Status](https://img.shields.io/badge/Status-Live%20Production-brightgreen.svg)](https://site-homenagem-ao-dia-das-mulheres.vercel.app)

Aplicação Web imersiva com foco em **Design Emocional**, **Micro-interações em CSS3**, **Animações Fluidas** e **Controle Multimídia**, desenvolvida em **React** e **Vite** com deploy contínuo na **Vercel**.

O projeto transforma mensagens e memórias em uma experiência digital delicada e interativa, apresentando cartões estilo Polaroid, envelope interativo com carta animada, partículas em suspensão e sincronização de áudio de fundo.

---

## 🌐 Demonstração Online

Acesse a aplicação em produção:  
👉 **[site-homenagem-ao-dia-das-mulheres.vercel.app](https://site-homenagem-ao-dia-das-mulheres.vercel.app)**

---

## ✨ Destaques de Frontend & UI/UX

* **Micro-interações & Animações CSS3 Avançadas**:
  * Efeito dinâmico de partículas contínuas (`@keyframes`) no background.
  * Cartões de fotos com estética **Polaroid**: sombras difusas, inclinações rotacionais (`transform: rotate`) e animações de elevação no hover.
  * Envelope interativo com animação de abertura de aba e revelação de carta estilo modal.

* **Tratamento de Áudio & Interação do Usuário**:
  * Mecanismo de inicialização de áudio respeitando as políticas modernas de *Autoplay* dos navegadores (acionamento por clique deliberado na tela de boas-vindas).
  * Controle de estado da mídia integrado ao ciclo de vida da interface.

* **Design Responsivo & Mobile-First**:
  * Layout fluido adaptado para qualquer resolução de tela (smartphones, tablets e desktops) sem distorção das proporções fotográficas.

* **Deploy Automatizado (CI/CD)**:
  * Pipeline integrado com a **Vercel**, garantindo builds otimizados a cada commit através do empacotador de alta performance **Vite**.

---

## 📁 Estrutura do Projeto

site-homenagem/ ├── public/ │ └── musica.mp3 # Trilha de áudio de fundo ├── src/ │ ├── assets/ # Acervo de imagens e fotografias │ ├── DiaDasMulheresPremium.jsx # Componente central com regras de apresentação │ ├── DiaDasMulheresPremium.css # Design System customizado e keyframes de animação │ ├── App.jsx # Ponto de entrada do React │ └── main.jsx # Renderização no DOM ├── index.html # Base HTML5 com viewport responsiva ├── vite.config.js # Configuração de build do Vite └── package.json # Metadados e dependências


---

## 🛠️ Stack Tecnológica

* **Frontend Library**: React 18
* **Build Tool**: Vite
* **Estilização**: CSS3 Puro (Custom Properties, Flexbox, Grid, Keyframe Animations)
* **Controle de Versão**: Git & GitHub
* **Hospedagem & CI/CD**: Vercel

---

## 🚀 Como Executar Localmente

### Pré-requisitos
* [Node.js](https://nodejs.org/) instalado (versão 18 ou superior).

### Passo a Passo

```bash
# 1. Clone o repositório
git clone https://github.com/caiodantass/Site-homenagem-ao-dia-das-mulheres.git
cd Site-homenagem-ao-dia-das-mulheres

# 2. Instale as dependências
npm install

# 3. Inicie o servidor de desenvolvimento
npm run dev
```

Acesse [http://localhost:5173](http://localhost:5173) no seu navegador para visualizar a aplicação localmente.

---

## 👨‍💻 Autor

**Caio Lívio Dantas**  
* Engenheiro de Software / Desenvolvedor  
* LinkedIn: [linkedin.com/in/caio-lívio](https://www.linkedin.com/in/caio-l%C3%ADvio/)  
* GitHub: [@caiodantass](https://github.com/caiodantass)
