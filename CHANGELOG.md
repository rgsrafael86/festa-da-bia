# Changelog — Pizzaria da Bia 🍕

Todas as modificações notáveis deste projeto serão documentadas neste arquivo seguindo o padrão [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/) e [Semantic Versioning](https://semver.org/lang/pt-BR/).

---

## [1.1.0] - 2026-09-26 (MINOR)

### Adicionado
- **Timers Independentes Concorrentes**: Motor em tempo real baseado em `Date.now() - startedAt`, permitindo que múltiplas pizzas entrem no forno em horários distintos com contagem e alertas individuais.
- **Widgets de Timer no Card da Pizza**: Exibição da contagem regressiva, botões de pausa, +1 minuto e finalização diretamente no card da pizza na aba "Pizzas".
- **Painel Multi-Slot no Forno**: Visualização no estilo painel com todas as assadeiras ativas e alerta pulsante aos 5 minutos para acionar o Gratinador (resistência superior).
- **Lista de Compras Precificada (R$ 398,50)**: Rateio exato em 27 itens de supermercado (R$ 294,50) somados aos 13 discos pré-comprados (R$ 104,00), garantindo sobra de R$ 1,50 sob o teto de R$ 400,00.

### Modificado
- **Calibração das Receitas**: Readequação das 10 pizzas salgadas para ~180g de mussarela cada (total 1,8 kg comprados no atacado).
- **Substituição Econômica na Pizza 4 Queijos**: Uso inteligente de Mussarela + Requeijão Culinário + Cheddar Cremoso + Parmesão, eliminando queijos nobres de alto custo (gorgonzola e provolone).
- **README.md**: Atualização da documentação detalhando o novo módulo de forno e o balanço financeiro.

---

## [1.0.0] - 2026-09-26 (MAJOR)

### Adicionado
- Lançamento inicial do aplicativo Web Mobile-First para a festa de 18 anos da Bia.
- Controle de status das 13 pizzas (Na Fila, No Forno, Servida).
- Timer digital circular de 8 minutos com áudio sintetizado e vibração.
- Lista de compras dividida por corredores do mercado com persistência em `localStorage`.
- Dicas de forno elétrico convencional a 250°C.
- Cardápio digital visual com fotos fotorrealistas para os convidados.
- Deploy automático no GitHub Pages.
