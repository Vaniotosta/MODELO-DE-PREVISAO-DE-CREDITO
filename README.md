 #PROJETO DE ANÁLISE DE PREVISÃO DE CRÉDITO#
##INTRODUÇÃO AO PROBLEMA DE NEGÓCIO##
Um crédito é uma quantia de dinheiro que se deve a uma entidade (por exemplo, um banco) ou a uma pessoa. No caso do crédito que se obtém através de um banco (chamado de “crédito bancário”), ele pode tanto ser oferecido pelo banco a uma pessoa física (pessoa comum) como para uma pessoa jurídica (uma empresa). Os créditos estão relacionados às compras e qualquer operação financeira que envolva confiança e empréstimos com objetivo de movimentar a economia.

No entanto, todo crédito envolve riscos que são a probabilidade de alguém adquirir uma dívida e não honrar com seu pagamento, e é algo que deve ser avaliado em todas as transações e operações financeiras envolvendo um lado que “empresta” dinheiro (independentemente do formato) e outro que recebe esse empréstimo.

-Nesse sentido este projeto tem como objetivo: PREVER OS CRÉDITOS NÃO APROVADOS PARA DETERMINADOS CLIENTES.
-Tal objetivo nasce da necessidades de gerar insights sobre o perfil da carteira de cliente para mapear possíveis oportunidades de crescimento, além de evitar o risco de possíveis inadimplência.

É importante ressaltar que o projeto analisa os créditos aprovados e não aprovados, e que não leva em consideração o tipo de empresa que fornece o crédito, haja visto, que o mesmo pode ser cedido por qualquer instituição que trabalhe com essa modalidade de negócio.
ETAPAS DO PROJETO
BUSCA DOS DADOS;
CONHECER OS DADOS;
EXPLORAR E TRATAR OS DADOS;
FAZER ANÁLISE EXPLORATÓRIA E GERAR INSIGHTS;
FAZER EDA PARA MODELAGEM;
PRÉ-PROCESSAMENTO PARA MODELAGEM;
7.FAZER A MODELAGEM NOS DADOS;
8. CONSIDERAÇÕES FINAIS.

CONSIDERAÇÕES FINAIS
Quanto à análise exploratória alguns dados se mostram relevantes:
1 Existem uma discrepância normal entre os créditos não aprovados e aprovados, sua relação com a renda pressupõe uma margem de crescimento entre os não aprovados.

2 Os créditos aprovados têm uma relação direta com os endividamentos e quanto maiores os créditos aprovados, maiores são os investmentos.

3 A faixa etária dos clientes estão em média de 44 anos, e não interfere para aprovação do crédito, quanto ao gênero, o masculino é a maioria dos clientes (chegando a ser o dobro) com 20% dos créditos aprovados, enquanto o feminino apenas 3%. Isso pressupõe margem de crescimento nos gêneros em especial o feminino.

4.Quanto à escolarização, 32% dos clientes não possui nenhuma graduação, 22% em algum colégio e 16% bacharelado, e mais de 25% dos creditos não aprovados refere-se a quem não tem graduação.

5.Quanto ao estado civil, 45% são casados, 32% nunca casou, 13% divorciados e 0,03% viúvos, é interessante saber esse perfil pois quanto maior a composição da familia, existe uma tendência a maiores créditos tanto no valor quanto à necessidades.

Quanto ao tipo de emprego, 69% é do setor privado, isso significa que a maioria do clientes pode variar a renda e a estabilidade no emprego, o qual pode aumentar as taxas de juros do crédito devido aos riscos envolvidos

Quanto ao modelo escolhido dado o objetivo de prever os créditos não aprovados, foi escolhido o bagging por uma acuracidade de 91%, precisão de acerto de 87%, levando em consideração que todas métricas levaram ao resultado para o melhor modelo.
Apesar do objetvo 'prever os créditos não aprovados', o modelo prever também os aprovados.
É importante frisar que os outros modelos testados como: Gradienteboost e a combinado por voto são modelos considerdos de ótimos resultados para os objetivos proposto.
A acurácia e a precisão do modelo, pode tender a aumentos das métricas de negócios.
