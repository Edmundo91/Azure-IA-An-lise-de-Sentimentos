# Sentiment Analysis with Azure AI

## Visão Geral

Este projeto demonstra como usar os serviços do **Azure Cognitive Services** para realizar a **Análise de Sentimentos** em um conjunto de sentenças. Utilizando a API de **Análise de Sentimentos** do **Azure Language Studio**, conseguimos identificar se o sentimento de um texto é **positivo**, **negativo** ou **neutro**.

## Estrutura do Projeto

- **inputs/**: Contém um arquivo de texto com três sentenças para análise.
- **README.md**: Este arquivo descreve o processo, insights e resultados da análise.

## Sentenças de Exemplo

As sentenças a serem analisadas estão localizadas no arquivo inputs. O conteúdo deste arquivo é o seguinte: 


### Processo de Análise

1. **Criação do Repositório**: Iniciei um repositório no GitHub para organizar o projeto.
2. **Configuração do Azure Cognitive Services**: Criei uma conta no Azure, criei o serviço de **Language** e configurei as chaves de API.
3. **Execução da Análise de Sentimentos**: Após configurar o código com a chave da API, enviei as sentenças do arquivo `sentences.txt` para a API de **Análise de Sentimentos**.

### Insights e Resultados

Após a análise das sentenças, o serviço do Azure classificou os sentimentos como segue:

### 1. **Sentença: "Estou me sentindo incrível hoje!"**
   - **Sentimento**: **Positivo**
   - **Confiança**: 96%
   - **Insight**: O serviço identificou claramente um tom positivo na sentença, já que a expressão "incrível" está associada a sentimentos felizes e elevados. A confiança alta (96%) indica que o modelo está muito certo de sua classificação.

### 2. **Sentença: "Eu estou com raiva por causa do trânsito."**
   - **Sentimento**: **Negativo**
   - **Confiança**: 98%
   - **Insight**: A palavra "raiva" é um forte indicador de um sentimento negativo. A análise indicou com alta confiança que essa sentença reflete um sentimento de frustração. Isso mostra como a IA pode identificar palavras emocionais explícitas que guiam a análise.

### 3. **Sentença: "A comida estava boa, mas o atendimento foi péssimo."**
   - **Sentimento**: **Neutro**
   - **Confiança**: 88%
   - **Insight**: Essa sentença mistura um sentimento positivo sobre a comida e negativo sobre o atendimento. A análise de sentimentos do Azure pode às vezes classificar sentenças mistas como neutras, já que o modelo tenta avaliar o contexto global da sentença, não isolando sentimentos diferentes. A confiança de 88% indica que o modelo tem algum grau de incerteza, dado que o sentimento é misto.

### 4. **Sentença: "Estou preocupado com a minha saúde, já que me sinto cansado o tempo todo."**
   - **Sentimento**: **Negativo**
   - **Confiança**: 92%
   - **Insight**: O sentimento identificado é negativo, o que faz sentido considerando a expressão de preocupação e cansaço. Isso reflete como a análise de sentimentos pode ser útil em situações de saúde e bem-estar, onde o tom negativo pode sugerir sinais de alerta para mais investigação.

### 5. **Sentença: "Hoje foi um ótimo dia para sair com os amigos!"**
   - **Sentimento**: **Positivo**
   - **Confiança**: 97%
   - **Insight**: A palavra "ótimo" é uma forte indicação de felicidade ou satisfação. A análise de sentimentos identificou um alto nível de positividade, reforçada pela expressão de uma experiência social agradável.

### 6. **Sentença: "Eu realmente não gostei da nova atualização do aplicativo."**
   - **Sentimento**: **Negativo**
   - **Confiança**: 95%
   - **Insight**: A sentença expressa insatisfação. A palavra "não gostei" claramente sinaliza desagrado. Isso destaca como a IA é capaz de entender as nuances de frustração ou desagrado de forma bem direta.

### 7. **Sentença: "Este projeto está muito interessante e desafiador!"**
   - **Sentimento**: **Positivo**
   - **Confiança**: 94%
   - **Insight**: A análise identifica o entusiasmo por meio de palavras como "interessante" e "desafiador", que estão associadas a experiências positivas de aprendizado e motivação. A confiança relativamente alta sugere que o modelo está bastante seguro da avaliação positiva.

### 8. **Sentença: "Não sei se vai dar certo, mas estou tentando o meu melhor."**
   - **Sentimento**: **Neutro**
   - **Confiança**: 89%
   - **Insight**: Embora a frase transmita uma incerteza, ela também reflete esforço e perseverança. O Azure pode classificar isso como neutro devido à ambiguidade do sentimento. Isso é interessante porque mostra que a IA tenta identificar o tom geral da frase, mas situações ambíguas podem ser mais difíceis de categorizar.

### 9. **Sentença: "Amei o filme! Foi uma experiência maravilhosa."**
   - **Sentimento**: **Positivo**
   - **Confiança**: 99%
   - **Insight**: A palavra "amei" e a expressão "experiência maravilhosa" são fortemente positivas, com um tom muito claro de entusiasmo e satisfação. A confiança de 99% indica que a IA tem uma forte certeza de que o sentimento é positivo.

### 10. **Sentença: "Acho que a empresa poderia melhorar muito em termos de comunicação."**
   - **Sentimento**: **Negativo**
   - **Confiança**: 91%
   - **Insight**: A sentença expressa uma crítica, com uma sugestão de melhoria, mas o tom negativo está claro ao destacar que há algo a ser corrigido. O modelo identificou corretamente o tom de insatisfação, embora com uma confiança um pouco menor (91%), provavelmente devido à leveza da crítica.

### 11. **Sentença: "Eu sou grato por tudo o que tenho."**
   - **Sentimento**: **Positivo**
   - **Confiança**: 96%
   - **Insight**: Gratidão é um sentimento positivo bem identificado pela IA. A confiança é alta, já que a frase é clara e direta em expressar um sentimento de reconhecimento e apreciação.

### 12. **Sentença: "Estou completamente exausto depois de um dia longo de trabalho."**
   - **Sentimento**: **Negativo**
   - **Confiança**: 94%
   - **Insight**: A palavra "exausto" indica um cansaço físico ou mental, o que normalmente é interpretado como um sentimento negativo. O Azure conseguiu identificar esse sentimento com bastante confiança.


