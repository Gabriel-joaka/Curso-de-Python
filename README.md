#  Curso-de-Python 

aqui estão algumas descrições de projetos que já fiz em python 

## Ambientes Virtuais no Python 

Essencialmente usamos o virtualenv, mas o anaconda tem um método próprio para isso 

Objetivo: Ter outras versões do Python instalados no computador com 2 objetivos: 

1. Usar ferramentas que funcionam apenas com versões específicas do Python 

2. Isolar de todo o resto tudo aquilo que é estritamente necessário para o programa rodar. Importante para sites e programas que vão ser distribuídos 

Observação Importante: 

Quando você cria um ambiente virtual, ele vem praticamente sem nada, então você precisa usar o pip ou o conda para instalar cada pacote que for usar 

  

## Automatizar o envio de mensagens no WhatsApp 

Vamos usar o Selenium (vídeo da configuração na descrição) 

Temos 1 ferramenta muito boa alternativas: 

Usar o wa.me (mais fácil, mais seguro, mas mais demorado) 

  

## Automatizar envio de nota fiscal 

Entro em uma pag que simula faço login e cadastro 
Pego o dataset trato ele 
Aí envio a emissão de cada nota fiscal tudo isso automático 

  

## Automação de Indicadores 

Todo dia, pela manhã, a equipe de análise de dados calcula os chamados One Pages e envia para o gerente de cada loja o OnePage da sua loja, bem como todas as informações usadas no cálculo dos indicadores. 
Um One Page é um resumo muito simples e direto ao ponto, usado pela equipe de gerência de loja para saber os principais indicadores de cada loja e permitir em 1 página (daí o nome OnePage) tanto a comparação entre diferentes lojas, quanto quais indicadores aquela loja conseguiu cumprir naquele dia ou não. 
O seu papel, como Analista de Dados, é conseguir criar um processo da forma mais automática possível para calcular o OnePage de cada loja e enviar um email para o gerente de cada loja com o seu OnePage no corpo do e-mail e também o arquivo completo com os dados da sua respectiva loja em anexo. 

  

## Automatizar pesquisa de preço 

Procurar cada produto no Google Shopping e pegar todos os resultados que tenham preço dentro da faixa e sejam os produtos corretos 
O mesmo para o Buscapé 
Enviar um e-mail para o seu e-mail (no caso da empresa seria para a área de compras por exemplo) com a notificação e a tabela com os itens e preços encontrados, junto com o link de compra. (Vou usar o e-mail pythonimpressionador@gmail.com. Use um e-mail seu para fazer os testes para ver se a mensagem está chegando) 

  

## Pegar cotações de moedas atuais com API 

montar gráfico em relação as moedas tempo e valor 

  

## Utilização de API de ARCgis 

  

## Transformando Códigos em Python para Executáveis 

Os arquivos do jupyter que temos até aqui no curso são scripts que podemos usar para rodar códigos e fazer diversas tarefas. 
Mas, algumas vezes, não seremos nós que iremos rodar os códigos e também não necessariamente o computador que vai executar o código não necessariamente tem python instalado. Por isso, podemos transformar esses códigos em arquivos .exe (executáveis que funcionam em qualquer computador). 

  

## Python para executável em programas mais complexos 

auto-py-to-exe para transformar o arquivo python em executável 
pathlib ou os para adaptar todos os "caminhos dos arquivos" 
Alternativamente, podemos usar o tkinter para permitir a gente escolher manualmente o arquivo, independente do computador que vamos rodar o programa 

  

## Python e Finanças 

Uma das grandes aplicações do Python é para Finanças/Mercado Financeiro. Não é bem uma integração, pois usaremos bibliotecas que já conhecemos, só que aplicadas a ativos financeiros, como por exemplo: Analisando com Média Móvel, ver a performance de uma carteira de ativos, criando nosso data frame de Cotações dos ativos da carteira, vamos ver como que as ações foram individualmente, criando um data frame da Carteira com as quantidades de ações e comparação e correlação da Carteira com o IBOV 

  

# Python com Power BI 

Usar o Python para fazer os tratamentos de bases de dados, criar colunas, etc. para importar para o Power BI depois -> biblioteca pandas -> exatamente como aprendemos no módulo de pandas. Focado em usar scripts em Python diretamente dentro do Power BI 
