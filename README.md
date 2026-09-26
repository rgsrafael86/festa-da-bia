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
   - Receita e montagem das **13 pizzas** com quantidades balanceadas ao orçamento (R$ 398,50).
   - Proporção calibrada: ~180g de mussarela por pizza salgada (1,8 kg total no atacado).
   - 4 Queijos adaptada com ingredientes acessíveis e saborosos: Mussarela + Requeijão Culinário + Cheddar Cremoso + Parmesão.
   - Alerta especial de destaque para o convidado com **Intolerância a Lactose** (Pizza nº 3 — Calabresa sem queijo e assada sobre folha de papel alumínio para evitar contaminação cruzada).
   - Destaque para ingredientes colocados **após o forno** (Rúcula com Tomate Seco, Margherita e Sensação com Morangos).
   - Controle de status: `Na Fila` ➔ `No Forno` ➔ `Servida`.
   - **⏱️ Timer individual no próprio card**: Cada pizza que entra no forno ganha seu cronômetro com botão de pausa, +1 min e finalização.

2. **⏱️ Forno & Timers Independentes (Multi-Pizzas):**
   - **Timers Concorrentes e Independentes**: As pizzas podem entrar em momentos diferentes no forno sem que uma interfira no tempo da outra.
   - Motor imune a travamento no celular: cálculo baseado em `Date.now() - startedAt`, mantendo a precisão mesmo se a tela desligar ou a aba mudar.
   - Alerta sonoro e visual aos 5 minutos (3 minutos restantes) para acionar o **Gratinador (resistência superior)** para dourar o queijo.
   - Seletor de pizza rápida para envio direto ao forno.

3. **🛒 Lista de Compras & Orçamento Real (R$ 398,50 cravados):**
   - 27 itens essenciais precificados para compra no Fort Atacadista / Cooper Atacarejo:
     - 🧀 Frios & Laticínios: R$ 127,30 (1,8 kg Mussarela a R$ 46/kg, Requeijão 1kg, Cheddar, Presunto, Parmesão)
     - 🥩 Carnes & Aves: R$ 31,50 (Calabresa 600g, Peito de Frango 600g, Bacon 200g)
     - 🥫 Mercearia & Empório: R$ 19,10 (Molho de tomate 3x, Azeitona, 6 Ovos, Ervilha)
     - 🥦 Hortifruti: R$ 33,00 (Tomate seco, Morangos, Rúcula, Manjericão, Tomates, Cebolas, Bananas)
     - 🍬 Doces & Coberturas: R$ 23,00 (Doce de leite 400g, Chocolate meio amargo, Chocolate branco)
     - 🥤 Bebidas & Gelo: R$ 45,00 (8 Litros de refrigerante + 5 kg de Gelo filtrado)
     - 🍴 Descartáveis & Apoio: R$ 16,00 (Copos 300ml, Guardanapos, Rolo de Papel Alumínio protetor)
   - Discos de massa pré-assados (13 unidades compradas): R$ 104,00
   - **Total Geral da Festa: R$ 398,50** (Margem residual de R$ 1,50 dentro do teto de R$ 400,00).
   - Checkbox interativo com barra de progresso em tempo real e persistência local.

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
