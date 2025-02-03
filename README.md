# Azure Open Ai DIO
No conteúdo aprendi muita coisa sobre o Azure Open AI, desde as ferramentas utilizadas até o como a AI utiliza para realizar a tokenização, tendo atenção a qual língua irá utilizar, pois se fizer uma comparação do inglês para o português-BR temos um certo quantitativo de tokens a mais no português.

Sempre estar atendo ao System Message, pois ele é quem define de fato como a AI irá funcionar, quanto mais específico e detalhado for ela terá um melhor desempenho para o trabalho/projeto específico.

Ajustar a temperatura e/ou o Top-P. A temperatura controla as respostas da nossa AI, sendo que quanto menor estiver mais previsível, determinísticas serão e quanto maior a temperatura, mais imprevisíveis, sem sentido serão as resposta. O Top-P controla quais palavras podem ser usadas, sendo quanto menor há uma menor probabilidade de palavras que serão utilizadas e quanto maior o Top-P há uma maior probabilidade de palavras para usar.

Temos também no Azure uma multimodalidade de AI's sendo desde insere texto e devolve texto, quanto inserir texto e devolver imagem ou até então a AI que recebe em áudio e devolve em texto.
