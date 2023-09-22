# Global Alignment Tool

Global Alignment Tool é uma ferramenta de alinhamento global que foi desenvolvida para alinhar duas sequências de entrada, sejam elas de aminoácidos ou nucleotídeos. Além disso, a ferramenta permite a avaliação da similaridade entre as sequências com base em um trecho de tamanho personalizado, o que a torna versátil e adaptável a diversas aplicações.

## Visão Geral
O alinhamento de sequências é uma tarefa fundamental na análise de dados biológicos, e essa ferramenta foi projetada para simplificar e aprimorar esse processo. Aqui estão algumas das principais características e funcionalidades:

Alinhamento Global: A ferramenta realiza alinhamentos globais, o que significa que ela tenta encontrar o melhor alinhamento possível entre as duas sequências, levando em consideração todas as posições ao longo das sequências de entrada.

Aminoácidos e Nucleotídeos: Esta ferramenta é capaz de alinhar tanto sequências de aminoácidos quanto sequências de nucleotídeos. Isso a torna útil para uma ampla variedade de aplicações, desde análises de proteínas até estudos genômicos.

Similaridade Personalizada: Você pode especificar o tamanho do trecho a ser usado para avaliar a similaridade entre as sequências. Isso permite adaptar o alinhamento de acordo com as necessidades específicas do seu projeto.

## Como Usar
Aqui estão os passos básicos para utilizar esta ferramenta:

Requisitos: Java 17

Instalação: É necessário apenas o arquivo myaligner.jar 

Parâmetros: Match Score quando nucleotídeos forem correspondentes, Mis Match em caso de não correspondencia e Gap Penalty para penalidade de inserção de gaps

Execução: Inserir a Query Sequence, Subject Sequence, especificar um diretório de saída para os resultados e escolher o tipo de alinhamento

Análise dos Resultados: Após a execução, será gerado um arquivo txt com o alinhamento e dados estatísticos sobre o mesmo e uma planilha avaliando as janelas do alinhamento conforme o tamanho especificado
