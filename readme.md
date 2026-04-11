

Análises Estatísticas (além das solicitadas):
Frequência por dezena ao longo do tempo (linha do tempo)
"Atraso" de números (há quantos sorteios um número não sai)
Pares de números que saem juntos com frequência (correlação)
Análise por quadrante/faixa (1-10, 11-20, etc.)
Distribuição soma total das dezenas sorteadas


Gerador Inteligente:
Algoritmo baseado em frequência + atraso ponderado
Filtros configuráveis (mínimo de pares/ímpares, soma mínima/máxima)
Evitar combinações já sorteadas
Opção aleatório (como pedido)
📈 Extras Premium:

Simulador: 
"Se eu tivesse jogado X números por Y sorteios, quanto gastei/ganhei?"
Gráfico de calor (heatmap) das dezenas
Exportar cartão para imagem/PDF
Histórico dos seus jogos salvos
Vou construir agora um app completo com React + API da Caixa:

------------------------------

O que foi construído

9 módulos funcionais:
Visão Geral — KPIs instantâneos: número mais/menos sorteado, distribuição pares/ímpares, último sorteio, par mais frequente, sequências consecutivas

Frequência — Barra completa de todas as dezenas com ordenação por número, mais/menos sorteados. Cores automáticas: 🔴 quente / 🔵 frio

🔥 Heatmap — Mapa de calor visual RGB (azul→verde→vermelho) + frequência por faixa de dezenas

⏱ Atraso — Quantos sorteios cada número está sem sair. Cores por urgência + Top 10 mais atrasados

🔗 Pares & Trios — Os 20 pares e 15 trios que mais saem juntos

🔬 Padrões — Distribuição pares×ímpares por sorteio, curva da soma das dezenas, sequências consecutivas, desvio padrão

⚡ Gerador IA — 6 estratégias (Inteligente, Quentes, Frios, Misto, Pares, Aleatório) + 4 filtros avançados (evitar repetidos, incluir atrasados, balancear faixas, limite de consecutivos) + salvar jogos no localStorage

🎮 Simulador — Simula N sorteios com sua estratégia: quanto gastaria, quantas vezes acertaria, ROI estimado

📋 Histórico — Lista completa de todos os sorteios carregados



Para usar: 
Selecione o jogo → clique "⬇ Carregar Dados" (busca da API da Caixa) ou "🎲 Demo" para testar offline imediatamente.

