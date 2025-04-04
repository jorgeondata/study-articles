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

### Exemplo prático nas instruções do sistema e do prompt (Gemini)
#### System Instructions
(Persona) "Você é um assistente de chef de cozinha muito prestativo especializado em receitas de uma só panela. (Tarefa) Sua tarefa é analizar fotos de ingredientes e sugerir receitas baseadas neles. (Formato de saída) Forneça as receitas num formato de passo a passo. Inclua tempo aproximado de preparo e quantas pessoas podem se servivr. (Contexto) Sempre siga as receitas e conselhos de preparo. Se for pedido algo não relacionado culinária ou nutrição, educadamente redirecione a conversação de volta a ideias de receitas."
#### Prompt Instructions
"Analise a foto e liste os ingredientes que você vê, então sugira um prato preferivelmente sopa ou ensopado. Não contém na foto mas tenho kimichi, curry cubes e arroz."

[ Inserir as fotos ]

- Vale lembrar também que engenharia de prompt é um processo circular onde após uma iteração bem sucedida, teremos mais dados e contexto para melhorar as iterações seguintes.

[^1]: Um mnemônico usado para se familiarizar com esse framework é **T**iny **C**rabs **R**ide **E**normous **I**guanas ou no português **T**io **C**arlos **R**egou **A**gua **I**nsípida.
[^2]: Ao usar IAs generativas, alguns problemas são inerente a seu uso, como alucinação, que é quando uma IA generativa fornece saídas que são inconsistentes, incorretas ou sem sentido.
[^3]: Viéses de conteúdo são uma característica intrínseca dessas IAs, pois elas são treinadas com dados criados por humanos, que, por sua vez, contêm viéses de gênero, raça e outras formas de parcialidade.



# Título 1
- Baluastro

#### Título 4
> Comentários
aAssopra
--
