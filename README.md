<p align="center">
  <img src="img/banner.jpg" alt="Case DN Cestas & Doces: delivery próprio para uma confeitaria" width="100%">
</p>

<p align="center">
  <a href="https://dn-cestas-doces.vercel.app"><img src="https://img.shields.io/badge/Ver_a_loja_no_ar-C8FF1F?style=for-the-badge" alt="Ver a loja no ar"></a>
  <a href="https://www.instagram.com/__techsolution__"><img src="https://img.shields.io/badge/Siga_no_Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Siga no Instagram"></a>
  <a href="https://wa.me/5514991556986"><img src="https://img.shields.io/badge/Fale_no_WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"></a>
</p>

> **Sobre este case:** a DN Cestas & Doces é uma confeitaria real de Promissão/SP, e o sistema está **no ar e recebendo pedidos**. Aqui estão as telas e as decisões do projeto. O **código é privado**, porque tem o banco de dados e os dados dos clientes da loja.

---

## O problema

A confeitaria vendia **só pelo WhatsApp e pelo Instagram**:

- Cada pedido virava uma conversa longa: qual sabor, quanto custa, tem para amanhã, como paga.
- Os pedidos ficavam espalhados nas mensagens, e era fácil esquecer algum.
- Os aplicativos de delivery cobram **comissão por pedido**, o que pesa no preço de um doce artesanal.

## A solução

Um **delivery próprio**, com a cara da marca: o cliente monta o pedido sozinho, escolhe a data e paga, e a dona recebe tudo organizado em um painel, **sem pagar comissão**.

<p align="center">
  <img src="img/video-real.gif" alt="Vídeo real: pedido feito no celular e chegando no painel" width="300"><br>
  <sub>Vídeo real: o pedido feito no celular e chegando no painel da loja.</sub>
</p>

---

## A loja, tela por tela

### 1. Página inicial
<img src="img/01-inicio.jpg" alt="Página inicial" width="100%">

- Fotos reais dos produtos, cores da marca e **cupom de boas-vindas** logo na abertura.
- Faixa no topo avisa que a loja trabalha **sob encomenda** e mostra a próxima data disponível.
- Botões fixos do **WhatsApp** e da **sacola**, sempre à mão no celular.

### 2. Cardápio
<img src="img/02-cardapio.jpg" alt="Cardápio" width="100%">

- Produtos separados por categoria (doces, bolos e cestas), com **filtro** e carrossel.
- Preço e botão "Adicionar" em cada card.

### 3. Escolha do produto
<img src="img/03-produto.jpg" alt="Escolha do produto" width="100%">

- Galeria de fotos com **toque para ampliar**.
- Escolha de **sabor**, campo de **observação para a produção** (ex.: mensagem no cartão) e opção de **adicionar outro sabor** do mesmo item.

### 4. Sacola
<img src="img/04-sacola.jpg" alt="Sacola" width="100%">

- Resumo do pedido com **cupom de desconto**, taxa de entrega e total.
- Aviso de que a loja trabalha **sob encomenda**, com a antecedência mínima.

### 5. Finalizar o pedido em 4 passos
<img src="img/05-finalizar.jpg" alt="Finalizar pedido" width="100%">

1. Dados do cliente.
2. **Entrega ou retirada** e a **data** no calendário.
3. Pagamento, inclusive **Pix**.
4. Confirmação. O pedido chega **pronto no WhatsApp** da loja.

### 6. Acompanhar pedido
<img src="img/06-acompanhar.jpg" alt="Acompanhar pedido" width="100%">

- O cliente acompanha a situação do pedido pelo link que recebe no WhatsApp, sem precisar perguntar "já saiu?".

### 7. Modo escuro
<img src="img/07-modo-escuro.jpg" alt="Modo escuro" width="100%">

- Um toque troca para o tema escuro, mantendo a identidade da marca.

---

## O painel da loja

Área só da dona, com login. Por segurança, ela **não aparece em prints aqui**, mas você vê o painel funcionando no vídeo acima.

| Seção | O que faz |
|---|---|
| **Pedidos** | Quadro com os pedidos por etapa (novos, confirmados, em preparação, em entrega) e **aviso sonoro** quando chega pedido novo. |
| **Agenda de entregas** | Mostra o que precisa ficar pronto em cada dia. |
| **Produtos, categorias e adicionais** | Cadastro com foto, preço e sabores. O que muda no painel **aparece na loja na hora**. |
| **Cupons** | Cria cupons de desconto, como o de boas-vindas. |
| **Áreas de entrega** | Bairros e cidades atendidos, cada um com a sua taxa. |
| **Banners e promoções** | Destaques que aparecem na loja. |
| **Abrir e fechar a loja** | Um botão pausa os pedidos, e a loja avisa o cliente. |

## Destaques técnicos

| | |
|---|---|
| **Zero comissão** | O pedido vai direto para a loja, sem intermediário. |
| **Atualização em tempo real** | Preço, foto, produto esgotado e loja pausada aparecem para o cliente sem recarregar a página. |
| **Segurança** | Senhas criptografadas, limite de tentativas de login, regras de acesso no banco de dados e monitoramento de erros. |
| **Feito para o celular** | Quase todos os pedidos vêm do celular. A loja foi desenhada primeiro para ele. |

## Tecnologias

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000" alt="JavaScript">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel">
  <img src="https://img.shields.io/badge/Upstash_Redis-00E9A3?style=flat-square&logo=upstash&logoColor=000" alt="Upstash Redis">
  <img src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white" alt="Sentry">
</p>

## O que é público e o que é sigiloso

| Público neste repositório | Fica privado |
|---|---|
| Telas da loja, fluxo de compra, funcionalidades e o vídeo real | Código-fonte, banco de dados, pedidos, dados dos clientes e o acesso ao painel |

---

<p align="center">
  <b>Quer um delivery próprio, sem comissão, para o seu negócio?</b><br>
  Eu sou o Danilo, da <b>TechSolution</b>. Crio sites, sistemas e aplicativos sob medida.<br><br>
  <a href="https://www.instagram.com/__techsolution__"><b>Siga @__techsolution__ no Instagram</b></a> para ver mais projetos e bastidores ·
  <a href="https://wa.me/5514991556986">WhatsApp</a> ·
  <a href="https://techsolution-links.vercel.app">Site</a>
</p>
