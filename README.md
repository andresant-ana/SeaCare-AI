### Link para modelo:
https://universe.roboflow.com/seacare/seacare/model/2

# SeaCare: Modelo de Detecção de Lixo Marinho
Este repositório referencia o modelo de detecção de lixo marinho treinado no Roboflow.

## Descrição do Problema
A poluição marinha causada pelo descarte inadequado de resíduos sólidos representa uma ameaça crescente para os ecossistemas marinhos e a vida marinha. Resíduos plásticos, metais e outros detritos acumulam-se nos oceanos, prejudicando a biodiversidade e a saúde dos ambientes aquáticos. Identificar e remover esses resíduos é crucial para a preservação dos oceanos. No entanto, a detecção eficiente de lixo marinho apresenta desafios devido à falta de tecnologias avançadas e acessíveis.

## Metodologia Utilizada
Utilizamos um conjunto de dados que nós mesmos montamos com mais de 2500 imagens, que contém imagens subaquáticas rotuladas com diferentes tipos de resíduos sólidos.

## Processamento e Treinamento
*Pré-processamento: As imagens foram redimensionadas e normalizadas para facilitar o treinamento.
*Treinamento: Utilizamos o Roboflow para treinar um modelo de detecção de objetos, configurado para identificar resíduos sólidos específicos nas imagens.
*Validação: O modelo foi validado com um conjunto de dados de teste para avaliar a precisão e a robustez das detecções.
*Implementação: O modelo treinado foi exportado e integrado a uma API acessível via HTTP, permitindo a inferência em tempo real.

## Resultados Obtidos
O modelo alcançou uma precisão de 75% na detecção de resíduos sólidos nas imagens de teste. Os resultados indicam que o modelo é capaz de identificar corretamente diferentes tipos de lixo marinho, contribuindo significativamente para esforços de monitoramento e limpeza dos oceanos.

## Conclusões
A implementação do modelo de detecção de lixo marinho demonstrou que é possível usar tecnologias de visão computacional e aprendizado de máquina para enfrentar o desafio da poluição marinha. O uso dessa solução pode ser expandido para iniciativas de limpeza de oceanos, promovendo a sustentabilidade e preservação dos ecossistemas marinhos.
