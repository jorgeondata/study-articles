## Sugestões de um bom aproveitamento de IAs Generativas
### Prompt do Sistema
- Um prompt de sistema é um guia de instruções configurado para as iterações de uma IA específica, podendo definir sua personalidade e limitações. Em outras palavras, são instruções que você passa para a IA com a finalidade de resolver uma determinada tarefa, sendo ela dotada de contexto e recursos para melhorar o resultado.

### Framework de uso e mentalidade 
- Existem vários cursos de engenharia de prompt ou como usar uma api de IA generativa específica, mas atualmente(2025.1quad) todos tem em comum a _tarefa_ e o _contexto_. O [curso de engenharia de prompt da Google](https://www.coursera.org/google-learn/prompting-essentials) recomenda o seguinte ciclo[^1] de 5 etapas de prompt para diminuir as alucinações[^2],  viéses de conteúdo [^3] e otimizar resultados:

#### Tarefa (Task)
A tarefa _especifica_ o que você quer que a IA faça, por isso deve ser claro e contextualizado.
> **Exemplo:** "Crie um planejamento de atividades da semana, de segunda a sábado."
#### Contexto (Context)
São informações e direções _adicionais_ que permitem um melhor entendimento da tarefa proposta.
> **Exemplo:** "Considere que todos os dias da semana tenho que garantir de 7 a 8 horas de sono." ou Você pode anexar uma foto de referência para a tarefa.
#### Recursos (Resources)
São exemplos ou qualquer informação a ser fornecida que a IA _ainda não saiba_, por limitações de versões, afinal é uma área que se desenvolve muito rápido.
> **Exemplo:** Você pode anexar arquivos PDF com mais referências ou fotos de seu Google Agenda.
#### Avaliar (Evaluate)
Nessa etapa, o operador tem um papel essencial para avançar para a próxima etapa, pois é a parte de _leitura dos resultados_, _reflexão_ e _considerações_ a se fazer para a iteração.
> **Exemplo:** O resultado está satisfatório, mas o planejamento não parece personalizável e flexível.
#### Iterar (Iterate)
A iteração só ocorre quando há avaliação prévia, pois é aqui que otimizamos os resultados da tarefa.
> **Exemplo:** "Eu quero que o planejamento me possibilite flexibilidade e que eu tenha tempo para reestrtuturar minha agenda semanal."
---
- Além desse framework, há um complemento do processo que envolve o papel da IA e o estilo de iteração variando em:
#### Tom (Tone)
> Formal, informal, humorístico ou profissional
#### Tamanho da resposta (Response Length)
> Breve ou Detalhada
#### Formato de saída (Output Format)
> Lista, Parágrafo, Código ou outros formatos específicos
#### Persona
> Identidade (qual profissão ou papel a assumir)
> Limitações (o que pode ou não pode fazer)

### Exemplo prático nas instruções do sistema e do prompt (Gemini)[^4]
#### System Instructions
_(Persona)_ "Você é um assistente de chef de cozinha muito prestativo especializado em receitas de uma só panela. _(Tarefa)_ Analise a foto com os ingredientes e sugira receitas baseadas neles. _(Formato de saída)_ Forneça as receitas num formato de passo a passo, inclua o tempo aproximado de preparo e quantas porções podem se fazer. _(Contexto)_ Sempre siga as receitas e conselhos de preparo. Se for pedido algo não relacionado a culinária ou nutrição, educadamente redirecione a conversação de volta a ideias de receitas."
#### Prompt Instructions
"Analise a foto em anexo, listando os ingredientes contidos, então sugira um prato para cada combinação de ingredientes. Não aparece na foto, mas tenho castanhas, farinha d'agua e chia."

![image](https://github.com/user-attachments/assets/9ed0dfcf-9999-4d71-ac61-2e2161765f34)

### Ferramentas
- Como visto na foto acima, o painel lateral direito, temos as seguintes ferramentas:
#### Temperatura
> Ajustando a temperatura, a justa-se também a criatividade da resposta, quanto mais quente, mais criativo.
#### Structured Output
> É uma ferramenta que auxilia nos formatos específicos de saída da tarefa em questão, como .JSON.
#### Code execution
> Essa opção fica associada a tarefas de cunho mais analítico, calculável ou programável, como a ideia de uma aplicação.
#### Function Calling
> Permite que a IA seja equipada com funções personalizadas ou ferramentas a parte, que auxiliem-na a coletar dados ou executar processos automatizados.
#### Grounding with Google Search
> Permite que o modelo usado navegue para validadr qualquer resultado que já tenha saído, é extremamente útil para evitar alucinações da IA.


---
- Vale lembrar também que engenharia de prompt é um processo circular onde após uma iteração bem sucedida, teremos mais dados e contexto para melhorar as iterações seguintes. Desse modo, chegamos aos métodos de iteração, podendo ser usado de acordo com a necessidade:
#### Método 1
> Reveja o framework de prompt usado, fornecendo mais exemplos e contexto, ou adicionando uma persona caso não a tenha;
#### Método 2
> Sepere o prompt em frases menores, simulando uma conversa com um ser humano;
#### Método 3
> Tente diferentes frases ou alterne a tarefa original para uma análoga, por exemplo, poderia limitar as receitas de acordo com um preto específico, como ensopado;
#### Método 4
> Introduza limitações, principalmente quando a saída tem informação excessivamente grande;
---



[^1]: Um mnemônico usado para se familiarizar com esse framework é **T**iny **C**rabs **R**ide **E**normous **I**guanas ou no português **T**io **C**arlos **R**egou **A**gua **I**nsípida.
[^2]: Ao usar IAs generativas, alguns problemas são inerente a seu uso, como alucinação, que é quando uma IA generativa fornece saídas que são inconsistentes, incorretas ou sem sentido.
[^3]: Viéses de conteúdo são uma característica intrínseca dessas IAs, pois elas são treinadas com dados criados por humanos, que, por sua vez, contêm viéses de gênero, raça e outras formas de parcialidade.
[^4]: A API do Google, Gemini 2.0 Flash, funciona semelhante ao GPT-4o com suporte para o português. Contudo, tanto na documentação quanto no curso de engenharia de prompt, para melhores resultados, escreva as instruções em inglês. 



# Título 1
- Baluastro

#### Título 4
> Comentários
aAssopra
--
