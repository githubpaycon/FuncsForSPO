# FuncsForSPO - Funcoes para Selenium; Python; Openpyxl; SQLite3

## pip install FuncsForSPO | NECESSÁRIO PYTHON 3.10

### Antes de tudo instale o Psutil para evitar erros. (pip install psutil)

Aqui voce achara funcoes produzidas para ter maior agilidade nos desenvolvimentos nas tecnologias abaixo:

* Selenium
  * Existem diversas funcoes em pt-br que vao te ajudar a desenvolver os seus projetos mais rapidamente em selenium
* Openpyxl (ainda em desenvolvimento para mais funcoes)
  * Algumas funcoes que minimizarao o trabalho pesado de mexer com openpyxl
* Python
  * Funcoes criadas para o Python, como excluir varios arquivos, criar, verificar se um programa / executavel esta aberto, entre outras funcionalidades

## Instalacao

**Para evitar erros, por favor, instale anteriormente o psutil (pip install psutil)**

de pip install FuncsForSPO em seu ambiente virtual e pronto!

Powered By https://github.com/gabriellopesdesouza2002

# Current Version -> 0.0.3.15

version==0.0.3.15 -> melhoria em funcao que recupera lista de elementos, agora e possivel enviar argumentos, como, recuperar com tudo upper

version==0.0.3.14 -> adicionada 1 funcao que espera webelement estar visivel

version==0.0.3.13 -> adicionada 2 funcoes que retornam data e hora dias a frente e uma que envia send_keys e da um esc. Foi adicionada também 2 funcoes do PySimpleGUI que mostra uma mensagem de erro e outra de finalizado

version==0.0.3.12 -> adicao de funcao para enviar e-mails pelo outlook; melhoria da funcao regex extrair email com base no padrão RFC2822

version==0.0.3.11 -> melhoria na Licenca. Adicionada funcao que executa o garbage_collector, melhorias na documentacao, melhoria na funcao que pega data e hora atual via formatacao strftime, adiciona data no caminho de qualquer arquivo, que pode ter inclusive sufixo em caso de arquivos repetidos, melhoria da funcao de baixar arquivo via link. adicionada um modulo com varias funcoes regex. melhoria na recuperacao de dados de coluna que ao achar um datetime, convertera para uma data normal

version==0.0.3.10 -> removida funcao que retorna uma tupla ao reverso, e adicionada a funcao (reverse_iter) que retorna ao reverso qualquer iteravel | adicionada a funcao que retorna os valores absolutos de qualquer arquivo e/ou diretorio de um caminho relativo de um diretorio (arquivos_com_caminho_absoluto_do_arquivo); adicionada tambem uma funcao que faz download de arquivos na internet (download_file); melhorias nas DocStrings

version==0.0.3.9 -> criada uma funcao que retorna somente numeros utilizando re

version==0.0.3.8 -> adicionada 2 funcoes 1-> retorna os valores absolutos de qualquer arquivo 2-> remove qualquer arquivo que contenha (1), (2), (3) (etc) em qualquer pasta

version==0.0.3.7 -> criada uma funcao que retorna um user-agent do tipo random

version==0.0.3.6 -> melhoria na funcao pega_id

version==0.0.3.5 -> adicionada uma funcao para retornar uma tupla ao reverso, (1,2,3,4,5,6,7,8,9,0), -> (0,9,8,7,6,5,4,3,2,1); adicionada execao do wget, correcoes: 1- correcao ao fazer log, ao enviar um objeto, automaticamente ele e convertido para string removido os print na funcao de pegar colunas no openpyxl

version==0.0.3.4 -> webdriver-manager e instalado automaticamente como dependencia

version==0.0.3.3 -> Adicao de varias funcoes do openpyxl* necessita TDD's

version==0.0.3.2 -> Adicao de 2 funcoes no functions_for_py (pega_caminho_atual; pega_caminho_atual_e_concatena_novo_dir)

version==0.0.3.1 -> Adicao de excecao para erro de login no Gmail; adicao de funcao para pegar codigo fonte de um WebElement Selenium

version==0.0.3.0 -> Adicao de funcoes para SQLite

version==0.0.2.8 ->Melhoria nos imports das execoes em Selenium

version==0.0.2.7 -> Corrigido erro ao enviar as funcoes de openpyxl

version==0.0.2.6 -> Corrigido erro ao utilizar a funcao "faz_log()"
