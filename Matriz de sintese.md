# Etapa 5 Matriz de síntese e organização da revisão

## Solicitação

Compare os artigos e organize a revisão por temas ou eixos. Não produza apenas uma sequência de resumos.

## Eixos da revisão

1. `Uso responsável e orientado da IA generativa no contexto acadêmico e de TI`
2. `Eficiência de uso e consumo de energia na inferência de modelos de linguagem`
3. `Impacto hídrico da infraestrutura de IA`

## Matriz de síntese

|Eixo|Artigos relacionados|Convergências|Divergências|Limitações|Lacunas|
|-|-|-|-|-|-|
|`1. Uso responsável e orientado da IA generativa`|`Garousi et al. (2026)`|`Defende que o uso da IA deve ser planejado e orientado, e não feito sem critério, o que dialoga com a proposta de boas práticas de Podder, Date e Murthy (2026).`|`Foca na aprendizagem e no pensamento crítico, sem tratar de impacto ambiental. Usa um modelo conceitual aplicado em contextos reais, enquanto os outros dois estudos são quantitativos.`|`O modelo é conceitual e não prescritivo. As aplicações (curso de teste de software na QUB e desenho de um novo curso de engenharia de software na AzTU) geram observações preliminares. O contexto é restrito à educação em engenharia de software.`|`Não define critérios sobre quando a IA não deve ser usada e não considera o custo ambiental do uso.`|
|`2. Eficiência de uso e consumo de energia`|`Podder, Date e Murthy (2026)`|`Com Herrera et al. (2025), reconhece que o uso da IA tem custo ambiental relevante. Com Garousi et al. (2026), mostra que uso estruturado traz resultados melhores do que uso sem método.`|`Mede energia e emissões de gases de efeito estufa, não água. Atua do lado da demanda (como o usuário formula o pedido), enquanto Herrera et al. (2025) tratam do lado da infraestrutura.`|`A redução de 32% a 48% refere-se aos modelos e cenários testados pelos autores e não deve ser generalizada.`|`Não avalia se a tarefa deveria ou não ser delegada à IA, apenas como reduzir tentativas repetidas. Não mede consumo de água.`|
|`3. Impacto hídrico da infraestrutura de IA`|`Herrera et al. (2025)`|`Confirma, com outra métrica (água), que a expansão da IA tem impacto ambiental crescente, em linha com a preocupação de Podder, Date e Murthy (2026).`|`Escala global e prospectiva (2030 e 2050), baseada em cenários probabilísticos, em vez de experimento. Propõe mitigação pela infraestrutura (resfriamento, tecnologias alternativas, localização), e não pelo comportamento do usuário.`|`Combina dados empíricos escassos com premissas de especialistas, por isso os resultados são projeções sob incerteza.`|`Não relaciona o consumo de água a decisões de uso individuais ou organizacionais da IA.`|

## Roteiro da revisão da literatura

### Eixo 1

* Ideia principal: `O uso da IA generativa deve ser orientado e explícito, para evitar dependência excessiva e perda de pensamento crítico.`
* Evidências que serão usadas: `Modelo Guide-AI-Ed e suas duas aplicações (Garousi et al., 2026).`
* Comparação entre estudos: `Assim como Podder, Date e Murthy (2026), propõe orientação ao usuário, mas com foco pedagógico e não energético.`
* Ligação com o problema: `Mostra que "usar bem" inclui saber quando a IA ajuda e quando atrapalha a aprendizagem, no âmbito acadêmico.`

### Eixo 2

* Ideia principal: `Pedidos mal formulados geram tentativas repetidas e aumentam o gasto de energia e as emissões.`
* Evidências que serão usadas: `Redução de 32% a 48% no consumo de energia e nas emissões operacionais com boas práticas de prompt (Podder; Date; Murthy, 2026).`
* Comparação entre estudos: `Complementa Herrera et al. (2025): um estudo trata do comportamento do usuário, o outro da infraestrutura que atende à demanda.`
* Ligação com o problema: `Evidencia que o desperdício também ocorre dentro do uso da IA, e não apenas na decisão de usá-la ou não.`

### Eixo 3

* Ideia principal: `A infraestrutura de IA consome grande volume de água, principalmente no resfriamento, e pode crescer muito sem mitigação.`
* Evidências que serão usadas: `Projeção de aumento de mais de sete vezes no consumo global de água de data centers até meados do século, sem mitigação (Herrera et al., 2025).`
* Comparação entre estudos: `Usa métrica diferente (água) e escala diferente (global) em relação a Podder, Date e Murthy (2026).`
* Ligação com o problema: `Fundamenta a justificativa ambiental do trabalho: usos desnecessários contribuem para uma demanda que tem custo hídrico.`

## Síntese crítica provisória

`Os três estudos convergem ao tratar o uso da IA como uma decisão que exige planejamento e que gera custos, seja de aprendizagem, de energia ou de água. Divergem no nível de análise (pedagógico e conceitual, experimental por prompt e prospectivo em escala global) e na métrica ambiental (energia e emissões versus água). Em conjunto, sugere-se que reduzir tentativas desnecessárias no uso individual contribui para conter a demanda que sustenta a infraestrutura, mas essa relação é uma interpretação do grupo, pois nenhum estudo a testa. As lacunas são: nenhum define critérios para decidir quando usar a IA e nenhum relaciona decisões de uso ao consumo de água.`

## Checklist

* \[x] Os artigos foram agrupados por ideias.
* \[x] Há comparações entre estudos.
* \[x] As divergências foram registradas.
* \[x] As lacunas são específicas e sustentadas pelas leituras.
