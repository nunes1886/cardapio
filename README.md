# 🍔 Cardápio Digital & Painel em Tempo Real

Um sistema web completo para restaurantes, lanchonetes e deliverys, focado na experiência do usuário e na agilidade do atendimento. O projeto é dividido em duas interfaces que se comunicam em tempo real através da nuvem.

## 🚀 Funcionalidades

### 📱 App do Cliente (`index.html`)
- **Catálogo Dinâmico:** Produtos consumidos diretamente do banco de dados.
- **Carrinho Inteligente:** Adição, remoção e cálculo automático do subtotal.
- **Mesa vs. Delivery:** Formulário adaptável dependendo da escolha do cliente (esconde/mostra campos de endereço e troco).
- **Máscara Automática:** Formatação em tempo real do número de WhatsApp (JS puro).
- **Checkout e Pagamento:** Simulação de geração de QR Code dinâmico para pagamentos via Pix.

### 💻 Painel Gerencial (`painel.html`)
- **Tempo Real (Real-time):** Os pedidos aparecem na tela da cozinha/caixa no exato segundo em que o cliente finaliza a compra, sem necessidade de atualizar a página (via `onSnapshot`).
- **Diferenciação Visual:** Cards com bordas e ícones diferentes (Azul para Mesa, Laranja para Delivery) para rápida identificação.
- **Detalhamento Completo:** Exibe itens, observações, endereço de entrega, forma de pagamento e necessidade de troco.

## 🛠️ Tecnologias Utilizadas

- **Front-end:** HTML5, CSS3, JavaScript (Vanilla / ES6 Modules)
- **Framework UI:** Bootstrap 5 (Grid, Offcanvas, Modals, Cards)
- **Back-end / Banco de Dados:** Firebase Firestore (NoSQL)
- **Integração:** Firebase Web SDK v12.9

## ⚙️ Como rodar o projeto localmente

1. Clone este repositório:
   ```bash
   git clone (https://github.com/nunes1886/cardapio.git)