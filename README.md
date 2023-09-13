# Automatização do Imposto de Renda

A declaração de Imposto de Renda sempre foi algo trabalhoso e custoso, levando vários dias ou até semanas para ser concluida.

Pensado nisso, para facilitar essa atividade, utilizei o Python para me ajudar a automatizar a maior parte dela.

# Módulos utilizados

- Pandas

- Pyautogui

- Time

- Pyperclip

- Openpyxl

  # Arquivos

  - Declaração Pessoal -> base criada por mim para concentrar informações recebidas pelos bancos escriturados dos meus investimentos.
 
  - Negociação -> base forneciada pela B3 com todas as negociações de renda variável (Ações, FIIs, BDRs e ETFs) já realizadas por mim.
 
  - Relatório Consolidado -> base fornecida pela B3 com a posição de todos os ativos de renda variavél que possuo.
 
# Modo de utilização

Na primeira etapa é feito a consolidação de todas as informações recebidas de forma física na planilha Declaração Pessoal.

Após essa estapa o código utilizarada o módulo Pandas para ler os arquivos em Excel, tratar os dados recebidos, realizar a ligação entre as informações comuns entre as planilhas e calcular o Preço Médio de cada ativo negociado. 

Utilizamos o Pyautogui e o Pyperclip para preencher as informações no programa da Receita Federal que teremos baixado. Em alguns pontos dos códigos, ele utiliza imagens para clicar no ponto desejado.

O projeto não preenche todas as informações, só ajuda automatizar as que são repetitivas.
 


https://github.com/guilhermediasmartins2/automatizar_IR/assets/125048539/d2d44821-8abe-4962-885c-4b527c68228d

