LINK: https://lanaia-cloud.github.io/AceleracaoSantander/

Perguntas escolhidas:

Quais carros têm os maiores preços de venda quando comparo  ano e distância rodada ?
Essa pergunta trás quais veículos estão sendo os principais ativos, quais estão entregando maior valor, novo ou seminovo, e quais modelos.
Como o preço médio dos veículos varia entre estados e cidades?
Essa pergunta é essencial para criação de estratégias de marketing/crescimento e conquista de novos clientes em regiões de baixas vendas.
Em quais meses aparecem os maiores volumes e valores de vendas registrados?
Investigar a sazonalidade é essencial para tentar prever picos ou depressões nos valores brutos de faturamento

Foi usado chat GPT com canvas, pois não possuo acesso à recursos de agentes de IA
 Os dados precisaram ser organizados para estarem todos no padrão de texto ou número, valores de datas foram filtrados e ajustados ao modelo DD/MM/AAAA, valores numéricos que estavam fora do padrão foram normalizados, valores de cidade e estado foram abreviados e organizados.
 
PROMPT

Estou fazendo um projeto para um bootcamp e quero criar, no Canvas, um dashboard interativo sobre vendas da Porsche. Use os dados reais da aba “Planilha1” da planilha anexada, sem inventar registros.

Quero organizar a análise em torno destas três perguntas de negócio:

Quais modelos têm os maiores preços de venda quando comparo veículos de ano e distância rodada semelhantes?

Como o preço médio dos veículos varia entre estados e cidades?

Em quais meses aparecem os maiores volumes e valores de vendas registrados?


Identifique os filtros com palavras e índices, assim:

F01 — Modelo

F02 — Ano do veículo

F03 — Estado

F04 — Cidade

F05 — Distância rodada

F06 — Método de pagamento

F07 — Situação da entrega

F08 — Faixa de preço

F09 — Período da venda

Os filtros precisam funcionar em conjunto. Cada lista deve mostrar apenas opções que existam na base e sejam compatíveis com os outros filtros, incluindo as faixas de preço, distância e período. Por exemplo, escolher um estado deve limitar as cidades, e escolher uma cidade deve limitar os estados. O mesmo vale para modelo, ano e demais opções. Preserve as seleções que continuarem válidas e avise caso alguma precise ser removida por incompatibilidade. Inclua um botão “Limpar filtros”.

Mantenha os preços em USD e a distância em milhas, como estão na planilha. Diferencie claramente o ano do veículo da data da venda. Exclua cancelamentos por padrão, mas permita incluir todos os registros ou selecionar somente os entregues.

Datas inválidas devem continuar nas comparações gerais, mas ficar fora dos gráficos mensais e dos resultados quando houver um filtro de período ativo. Inclua também uma opção para incluir ou excluir datas futuras, sinalizando esses registros em relação à data de referência exibida no painel. Não ajuste valores ambíguos por suposição.

Nos gráficos mensais, identifique meses sem registros como “sem dados na amostra”. Quando um recorte não tiver resultados, mostre uma mensagem clara e mantenha os gráficos e indicadores funcionando.

Quero um visual elegante, com fundo escuro, detalhes discretos em dourado e tipografia sem serifa, legível. Use textos em português e um layout que funcione no computador e no celular. No final, inclua uma seção recolhível para consultar os registros filtrados.

Deixe apenas notas curtas necessárias para interpretar os dados. Não inclua a seção “Como este dashboard responde às suas perguntas” nem explicações sobre prompts, pois vou colocar essa documentação no README.

Entregue um único arquivo chamado index.html, com CSS, JavaScript e dados incorporados, sem dependências externas. Ele deve abrir diretamente no navegador e estar pronto para publicação no GitHub Pages.

Antes de entregar, confira os cálculos, as combinações dos filtros, o botão de limpeza e o comportamento quando não houver resultados.

