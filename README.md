# 🍕 Pizzaria da Bia — 18 Anos (Guia da Festa)

> Aplicativo Web Mobile-First leve e prático para organizar fornadas, compras e preparo em festas, aniversários, churrascos e eventos entre amigos.

---

## 📱 Como Abrir o Aplicativo

### Opção 1: Direto no Navegador (Sem instalar nada)
Dê um duplo clique no arquivo [`index.html`](index.html) ou abra-o em qualquer navegador (Google Chrome, Edge, Safari, Firefox).

### Opção 2: Servidor Local (Acesso pelo celular no Wi-Fi da casa)
1. Abra o terminal nesta pasta (`c:\Maintply\Festa da Bia`).
2. Execute:
   ```bash
   python -m http.server 8080
   ```
3. Veja o IP da sua máquina (via `ipconfig`) e abra no navegador do celular:
   ```
   http://192.168.1.X:8080
   ```

### Opção 3: Deploy no GitHub Pages
Como o projeto é **Single-File (`index.html`) com assets locais**, ele pode ser publicado no GitHub Pages para qualquer convidado acessar direto pelo link do WhatsApp.

---

## 🧭 Os 5 Módulos da Festa

1. **👨‍🍳 Controle de Fornadas (Pizzas):**
   - Receita e montagem das **13 pizzas**.
   - Quantidades calculadas para massa de 35 cm (molho ~85g, mussarela ~270g, recheios ~170g).
   - Alerta especial de destaque para o amigo com **Intolerância a Lactose** (Pizza nº 3 — Calabresa sem queijo).
   - Destaque para ingredientes colocados **após o forno** (Rúcula com Tomate Seco, Margherita e Sensação com Morangos).
   - Controle de status com memória local: `Na Fila` ➔ `No Forno` ➔ `Servida`.
   - Botão rápido "🔥 Colocar no Forno (Timer)".

2. **⏱️ Timer do Forno:**
   - Display digital circular com contagem regressiva de 8 min (presets de 7, 8 e 9 min).
   - Alarme sonoro integrado no próprio navegador (funciona 100% offline).
   - Alerta sonoro e visual aos 5 minutos para acionar o **Gratinador (resistência superior)** para dourar o queijo.
   - Vibração de aviso no celular.

3. **🛒 Lista de Compras no Mercado:**
   - 38 itens organizados pelos corredores reais do supermercado:
     - 🧀 Frios e Laticínios
     - 🥩 Carnes & Aves
     - 🥦 Hortifruti
     - 🥫 Mercearia & Empório
     - 🍬 Doces & Confeitaria
     - 🥤 Bebidas & Gelo (10 Litros de refrigerante para 15 pessoas com folga)
     - 🍴 Descartáveis & Apoio
   - Barra de progresso dinâmica com percentual de itens já colocados no carrinho.
   - Marcações salvas no aparelho (pode fechar e abrir que continua marcado).

4. **🔥 Dicas & Segredos do Forno:**
   - Dicas práticas para assar perfeito em forno elétrico convencional.
   - Pré-aquecimento a 250°C por 30 minutos.
   - Pincelar azeite na borda da massa pré-assada (mantém macia e dourada sem endurecer).
   - Ordem das camadas para a massa não amolecer com a umidade dos ingredientes.
   - Tabela de ingredientes frescos que entram só depois de assar.
   - Cuidados com contaminação para quem não pode comer queijo.

5. **🎉 Cardápio dos Convidados:**
   - Visual bonito e apetitoso dos 10 sabores para mostrar aos convidados no celular ou projetar na TV/tablet.

---

## 💡 Adaptável para Outros Eventos
A estrutura deste projeto foi desenvolvida para ser facilmente duplicada e adaptada para:
- **Churrasco da Empresa / Firma:** Controle de cortes (picanha, linguiça, fraldinha), timer da grelha, lista de compras por quilo/pessoa e bebidas geladas.
- **Noite de Hambúrguer Artesanal:** Ponto das carnes, montagem dos pães e acompanhamentos.
- **Eventos de Família & Amigos:** Praticidade total, zero complicação, sem custo de servidor.

---

## 📸 Fotos das Pizzas
Fotos fotorrealistas salvas na pasta [`assets/images/`](assets/images/):
- `calabresa_acebolada.jpg`
- `calabresa_zero_lactose.jpg`
- `frango_catupiry.jpg`
- `rucula_tomate_seco.jpg`
- `bacon_supreme.jpg`
- `quatro_queijos.jpg`
- `margherita.jpg`
- `portuguesa.jpg`
- `sensacao_morango.jpg`
- `banana_nevada.jpg`
