# 🖨️ O Gomes 3D | Produtos Criativos Impressos em 3D

Vitrine virtual e catálogo interativo desenvolvido para a **O Gomes 3D**, uma loja especializada em decoração, utilidades, acessórios e itens colecionáveis produzidos por impressão 3D.

---

## ✨ Visão Geral do Projeto

O site foi projetado com uma interface moderna em **Dark Mode** e detalhes em neon (ciano, roxo e magenta), oferecendo uma experiência de navegação fluida, responsiva e focada na conversão direta via **WhatsApp**.

### 🚀 Principais Funcionalidades

* **Catálogo Interativo & Filtros:**
  * Filtragem instantânea por categorias (*Decoração*, *Utilidades*, *Acessórios* e *Geek & Colecionáveis*).
  * Barra de busca em tempo real (desktop e mobile) que filtra por nome, descrição e categoria.
* **Visualização Rápida (Quick View):**
  * Modal dedicado para visualizar detalhes ampliados e descrições completas de cada peça antes de adicionar ao carrinho.
* **Carrinho de Compras Dinâmico:**
  * Gaveta lateral (*Drawer*) interativa com adição animada de produtos, controle de quantidade, remoção de itens e cálculo automático de subtotal.
* **Checkout Integrado ao WhatsApp:**
  * Formulário completo de entrega (Nome, Telefone, CEP, Endereço) e seleção de pagamento preferido (*PIX* ou *Cartão*).
  * Gera automaticamente uma mensagem formatada com o resumo do pedido e redireciona o cliente diretamente para o atendimento no WhatsApp.
* **Formulário de Contato Direto:**
  * Seção de atendimento que também integra o envio de dúvidas diretamente ao WhatsApp da loja.
* **Painel Administrativo Local (Gestão de Pedidos):**
  * Área restrita protegida por PIN (`Acesso administrativo` no rodapé) utilizando `localStorage` do navegador.
  * Permite lançar pedidos manualmente, acompanhar o fluxo de produção (*Confirmado* → *Em andamento* → *Concluído*) e exportar relatórios em formato **CSV**.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico:** Estruturação acessível com atributos ARIA e suporte a dispositivos móveis.
* **Tailwind CSS (via CDN):** Estilização responsiva, tema escuro personalizado (`brand-dark`, `brand-cyan`, `brand-purple`, `brand-pink`) e efeitos de vidro (*glassmorphism*).
* **JavaScript Vanilla (ES6+):** Toda a lógica de estado do carrinho, filtros de busca, animações de interface (Web Animations API), geração de links de WhatsApp e persistência local de pedidos.
* **Lucide Icons:** Ícones vetoriais leves e modernos.
* **Google Fonts (Inter):** Tipografia limpa e de alta legibilidade.

---

## 📂 Estrutura de Arquivos

```text
├── index.html                        # Estrutura completa, estilos customizados e lógica JS da loja
├── maker3d-logo.png / .jpg           # Identidade visual e logotipo da O Gomes 3D
├── impressora-ad5x-fundo.jpg         # Imagem de destaque da impressora 3D (Flashforge AD5X)
├── impressora-ad5x.png               # Asset complementar da impressora
├── impressora-ad5x-transparente.png  # Asset com fundo transparente
└── mascote-rubro-negro.jpg           # Imagem de produto em destaque no catálogo
```

---

## 💻 Como Executar Localmente

Por ser uma aplicação front-end estática sem necessidade de etapa de build (*zero-build*), basta seguir os passos abaixo:

1. Clone ou baixe os arquivos deste repositório para uma pasta no seu computador.
2. Certifique-se de que todas as imagens (`.png` e `.jpg`) estejam na mesma pasta que o arquivo `index.html`.
3. Abra o arquivo `index.html` diretamente no seu navegador de preferência (Chrome, Edge, Firefox, Safari) ou utilize uma extensão como o **Live Server** no VS Code.

---

## 📱 Responsividade e Acessibilidade

* Layout totalmente adaptável para **smartphones, tablets e desktops**.
* Respeito às preferências do sistema para redução de movimento (`prefers-reduced-motion`).
* Áreas de toque otimizadas para dispositivos móveis e suporte a navegação por teclado nos modais.

---

<p align="center">
  Desenvolvido para <strong>O Gomes 3D</strong> — <em>Pequenos detalhes, grandes ideias.</em>
</p>