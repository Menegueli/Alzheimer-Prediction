# Previsão da Doença de Alzheimer

## Descrição do Projeto

Este projeto utiliza técnicas de machine learning para prever a doença de Alzheimer com base em um conjunto de dados contendo informações sobre pacientes. O modelo escolhido para essa tarefa foi o **Random Forest Classifier**, um método de predição que cria várias "árvores de decisão" durante o treinamento. Essas árvores ajudam o modelo a fazer previsões mais precisas ao combinar os resultados de todas elas, tornando-o mais confiável e menos propenso a cometer erros por "aprender demais" com os dados de treinamento.

## Dataset

O dataset utilizado contém diversas variáveis relacionadas à saúde dos pacientes, incluindo dados clínicos e comportamentais. A variável alvo é o diagnóstico de Alzheimer.

### Principais Variáveis Utilizadas

Abaixo estão as 10 variáveis mais importantes para a previsão da doença de Alzheimer, de acordo com o modelo Random Forest:

1. **FunctionalAssessment**: Avaliação Funcional - Medida da capacidade funcional do paciente em realizar atividades diárias.
2. **ADL**: Atividades de Vida Diária - Refere-se à capacidade do paciente de realizar atividades cotidianas, como vestir-se, alimentar-se, etc.
3. **MMSE**: Exame do Estado Mental (Mini-Mental State Examination) - Uma medida de função cognitiva.
4. **MemoryComplaints**: Queixas de Memória - Indica se o paciente relata problemas de memória.
5. **BehavioralProblems**: Problemas Comportamentais - Refere-se à presença de problemas comportamentais, como agitação ou agressividade.
6. **PhysicalActivity**: Atividade Física - Nível de atividade física do paciente.
7. **CholesterolHDL**: Colesterol HDL - Níveis de colesterol HDL (conhecido como "colesterol bom") no paciente.
8. **SleepQuality**: Qualidade do Sono - Medida da qualidade do sono do paciente.
9. **CholesterolTriglycerides**: Triglicerídeos - Níveis de triglicerídeos no sangue do paciente.
10. **CholesterolTotal**: Colesterol Total - Nível total de colesterol no paciente.

## Resultados

O modelo de Random Forest atingiu uma acurácia de **92,55%**, mostrando-se eficaz na previsão da doença de Alzheimer com base nas variáveis disponíveis no dataset.

### Conclusões

- **Avaliação Funcional**, **Atividades de Vida Diária** e **Exame do Estado Mental** foram as variáveis mais influentes no modelo, indicando a importância desses fatores no diagnóstico da doença de Alzheimer.
- O modelo pode ser utilizado como uma ferramenta auxiliar para prever a doença, mas deve ser complementado com avaliações clínicas para um diagnóstico mais preciso.
- Fatores como **atividade física**, **qualidade do sono** e **níveis de colesterol** também mostraram uma influência significativa, sugerindo que intervenções nessas áreas podem ter um impacto na prevenção ou progressão da doença.

## Referências

- [Documentação do Pandas](https://pandas.pydata.org/)
- [Documentação do Numpy](https://numpy.org/)
- [Documentação do Matplotlib](https://matplotlib.org/)
- [Documentação do Seaborn](https://seaborn.pydata.org/)
- [Documentação do Scikit-learn](https://scikit-learn.org/)
