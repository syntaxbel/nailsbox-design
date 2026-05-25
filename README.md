# 💅 NailBox - Landing Page & Clube de Assinatura

> Uma landing page moderna, elegante e totalmente responsiva desenvolvida para um clube de assinatura de estética e nail care.

---

## 🚀 Sobre o Projeto

O **NailBox** é um projeto de Front-end focado na experiência do usuário (UX/UI) e em estratégias de conversão visual para o modelo de negócios de e-commerce e assinaturas. A interface foi projetada para transmitir sofisticação através de uma paleta de cores equilibrada, tipografia moderna e elementos fluidos.

## 🌟 Diferenciais Técnicos e Funcionalidades

### 🔍 1. Otimização para Motores de Busca (SEO) e Social Sharing
* **Meta Tags Estruturadas:** Configuração minuciosa de palavras-chave, descrição e autoria para garantir uma boa indexação orgânica no Google.
* **Protocolo Open Graph & Twitter Cards:** O código conta com a integração de tags de compartilhamento (`og:title`, `og:description`, `twitter:card`). Isso garante que, ao compartilhar o link do site no WhatsApp, Twitter ou Facebook, o card visual seja gerado de forma perfeita com imagem e título chamativos.

### 🎨 2. Arquitetura CSS Avançada e Sustentável
* **Variáveis de Ambiente (`:root`):** Centralização de toda a paleta de cores, sombras (`--shadow`) e estados do sistema em propriedades customizadas. Isso facilita a manutenção do código (mudar o tema visual do site exige alterar apenas uma linha).
* **Efeitos de Microinteração:** Transições suaves de escala e elevação (`translateY`) aplicadas aos cards de planos ao passar o mouse (*hover*), gerando um feedback visual fluido e agradável para o usuário.

### 📱 3. Responsividade e Design Fluido
* **Layout Adaptável:** Utilização estratégica de **Flexbox** e propriedades flexíveis para que os elementos se reajustem organicamente.
* **Foco no Mobile-First:** Uso de regras de `@media queries` para garantir que em telas menores (smartphones) o layout se reestruture perfeitamente — como a barra de pesquisa que se oculta para poupar espaço e os cartões de planos que se empilham perfeitamente.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico:** Uso correto de tags estruturais (`<header>`, `<main>`, `<section>`, `<nav>`, `<footer>`) visando acessibilidade e SEO.
* **CSS3 Moderno:** Aplicação de variáveis globais, Flexbox, efeitos de transição e responsividade nativa.
* **Google Fonts:** Integração inteligente com carregamento otimizado (`preconnect`) das fontes *Poppins*, *Send Flowers* e *Grand Hotel*.
* **SVG Integrado:** Utilização de vetores puros em formato SVG para o ícone de busca, garantindo nitidez máxima em qualquer resolução de tela.

---

## 📂 Estrutura de Arquivos

```text
├── assets/  
│   └── CSS                 # Variáveis globais, layout e responsividade  
│   └── imagens                         
├── index.html               # Página principal da Landing Page
└── pagina_assinatura.html   # Fluxo de checkout/assinatura
