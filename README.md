## O acesso das famílias em situação de vulnerabilidade social a programas de transferência de renda no município de Campinas/SP

### TEMA DO PROJETO

Este projeto consiste na *análise exploratória de dados abertos do Ministério do Desenvolvimento e Assistência Social, Família e Combate à Fome (MDS) relativos às *famílias que estão inseridas no Cadastro Único e que são beneficiárias de programas de transferência de renda* do município de Campinas/SP, especificamente dados do Programa Bolsa Família (PBF) e do Benefício de Prestação Continuada (BPC). 

### CONTEXTUALIZAÇÃO

* O que é o Cadastro Único?

O [Cadastro Único](https://www.gov.br/mds/pt-br/acoes-e-programas/cadastro-unico) é um sistema que registra informações sobre as a realidade das pessoas de baixa renda no país, incluindo aspectos relacionados à renda, moradia, saúde, trabalho, dentre outros fatores que impactam nas condições de vida da população em situação de vulnerabilidade. 

É por meio deste cadastro que as famílias podem ter acesso aos programas e/ou benefícios sociais do país, Estado e/ou município. O Cadastro precisa ser atualizado a cada dois anos no máximo, ou a qualquer momento caso haja alteração da situação da família, como mudança de endereço, nascimento ou óbito de um membro familiar, mudança de trabalho ou renda, entre outras.

* O que é o Programa Bolsa Família - PBF?

O [Programa Bolsa Família](https://www.gov.br/mds/pt-br/acoes-e-programas/bolsa-familia) é um programa de transferência de renda destinado a famílias e indivíduos que encontram-se em situação de vulnerabilidade social mensurada pela renda per capta declarada no Cadastro Único, atualmente no limite de R$218,00 per capta para famílias compostas por duas ou mais pessoas, e de R$ 109,00 para pessoas que moram sozinhas. 

O valor do benefício varia de acordo com as características da família, como número de pessoas que moram juntas ou a presença de crianças ou adolescentes. Além da segurança de renda, busca-se por meio do programa integrar as políticas de assistências social, saúde e educação por meio das condicionalidades do programa: frequência escolar para famílias com crianças e adolescentes com idade entre 4 a 17 anos e acompanhamento de saúde como vacinação de crianças e pré-natal para gestantes.

* O que é o Benefício de Prestação Continuada - BPC?

O [Benefício de Prestação Continuada](https://www.gov.br/mds/pt-br/acoes-e-programas/assistencia-social/beneficios-assistenciais/beneficio-assistencial-ao-idoso-e-a-pessoa-com-deficiencia-bpc), no valor de 1 salário mínimo, destina-se a idosos com mais de 65 anos e pessoas com deficiência, que se encontrem em situação de vulnerabilidade social mensurada pela renda per capta familiar. Atualmente, para ter acesso ao benefício, a renda familiar do idoso ou pessoa com deficiência não pode ultrapassar o limite de 1 ⁄ 4 do salário mínimo per capta.

### Objetivos gerais e específicos do projeto

O objetivo geral desse projeto é identificar quais marcadores sociais .....

O objetivo específico do projeto é construir um indicador da taxa de cobertura do programa Bolsa Família na cidade de Campinas/SP, diante da hipótese de que existe uma lacuna entre famílias cadastradas e famílias atendidas: *haveria famílias no Cadastro Único que atendem os critéiros de inclusão do Bolsa Família mas não estão contempladas pelo programa?*

### Bases escolhidas

[Portal da Transparência](https://portaldatransparencia.gov.br/download-de-dados/auxilio-brasil) #Portal da transparencia nov/21 a fev/23

28/11 - precisei importar o metodo zipfile para acessar os dados do periodo de out/21 a fev/23

[Tabulador do Cadastro Único - CECAD 2.0](https://cecad.cidadania.gov.br/tab_cad.php) # caracterização socio-demográfica das famílias em situação de vulnerabilidade socioeconômica que estão cadastradas no CadÚnico - base set/23

## FERRAMENTAS UTILIZADAS
Para desenvolver esse projeto, desenvolvi uma análise exploratória de dados do Ministério de Desenvolvimento Social, extraídos da base do Cadastro Único e disponibilizados no banco de dados abertos do governo. Para a análise, utilizei o python, pandas, matplotlib. Por fim, o Tableau foi utilizado para gerar a visualização das análises.

## Insights e visualizações

[Dashboard disponível do Tableau com a visualização dos dados analisados neste projeto](https://public.tableau.com/app/profile/lais.meireles.alves/viz/projeto_final_reprograma_lais/resumo)
