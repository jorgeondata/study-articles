## Otimizando um modelo no Google Gemini
- Essa parte requer planejamento, o Fine-Tuned LLM; se você quiser aumentar a performance do modelo para uma tarefa muito específica, você fornece um modelo de treinamento com um dataset que contém muitos exemplos daquela tarefa.
	O modelo de treinamento recomenda que tenham entre 100 a 500 exemplos e criar um prompt estruturado, podendo ser escrito manualmente ou importanto um arquivo .CSV. 
- Considere que:
**1.** Essa API é indicada para coleta de informações mais atuais em relação a outras;
**2.** É indicada para pesquisar produtos, pois tem suporte do mecanismo de busca da Google;
**3.** Indicado para combinar dados, mas deve ser feito com cuidado;
**4*.** As respostas tem uma formato de saída editável de acordo com a necessidade: respostas curtas, longas, simples, casuais ou profissionais;
**5.** Os modelos disponíveis para uso são o Ultra (mais recente), Pro e Nano, respectivamente em ordem de disponibilidade;
**6.** A engenharia de prompt sempre será aplicada no uso de APIs de IA;
**7.** O uso de certas extensões disponíveis na API (como integração com o Gmail ou Youtube) otimizam o contexto e refinam as pesquisas/resultados;
**8.** Ao usar extensões, use o _EN-US_, pois as versões atuais não tem um suporte muito bom para _PT-BR_;
**9.** As extensões só funcionam se você estiver logado na sua conta pessoal Google, integração com o _Workspace_ aind não está disponível;
**10.** O ícone `Double-Check Response`, que compara os resultados encontrados com o que há na internet, só está disponível para usos em inglês. Em português, esse ícone se torna `Google It`, que simplesmente pesquisa no google o que foi digitado.

### Configurando o Fine-Tuned LLM
- c
