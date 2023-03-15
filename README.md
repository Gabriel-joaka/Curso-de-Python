##  Curso-de-Python
aqui estao algumas descrições de projetos que ja fiz em python
# Ambientes Virtuais no Python
Essencialmente usamos o virtualenv, mas o anaconda tem um método próprio para isso
Objetivo: Ter outras versões do Python instalados no computador com 2 objetivos:
1. Usar ferramentas que funcionam apenas com versões específicas do Python
2. Isolar de todo o resto tudo aquilo que é estritamente necessário para o programa rodar. Importante para sites e programas que vão ser distribuídos
Observação Importante:
Quando você cria um ambiente virtual, ele vem praticamente sem nada, então você precisa usar o pip ou o conda para instalar cada pacote que for usar

# automatizar o envio de mensagens no Whatsapp¶
Vamos usar o Selenium (vídeo da configuração na descrição)
Temos 1 ferramenta muito boa alternativas:
Usar o wa.me (mais fácil, mais seguro, mas mais demorado)

# automzatizar envio de nota fiscal
entro em uma pag que simula faco login e cadastro
pego o dataset trato ele
ai envio a emissao de cada nota fiscal tudo isso automatico

# Automação de Indicadores
Todo dia, pela manhã, a equipe de análise de dados calcula os chamados One Pages e envia para o gerente de cada loja o OnePage da sua loja, bem como todas as informações usadas no cálculo dos indicadores.
Um One Page é um resumo muito simples e direto ao ponto, usado pela equipe de gerência de loja para saber os principais indicadores de cada loja e permitir em 1 página (daí o nome OnePage) tanto a comparação entre diferentes lojas, quanto quais indicadores aquela loja conseguiu cumprir naquele dia ou não.
O seu papel, como Analista de Dados, é conseguir criar um processo da forma mais automática possível para calcular o OnePage de cada loja e enviar um email para o gerente de cada loja com o seu OnePage no corpo do e-mail e também o arquivo completo com os dados da sua respectiva loja em anexo.
