## Checkpoint 2: PAI - Assistente de Regras do Jogo Monopoly
## Integrantes:
Julia Johanson Peniche Dias Da Silva RM: 572220  
Lucas Bomfim Leite RM: 570420  
Eduardo Barcelos De Carvalho Braziliano RM: 573274  
## Justificativa:
O fator determinante na seleção do nosso domínio foi a convergência entre o interesse pessoal do grupo e a aplicabilidade prática no setor de jogos. Ao optarmos pelo desenvolvimento de um Assistente de Regras, buscamos unir a nossa afinidade com o universo lúdico à criação de uma ferramenta que resolva problemas reais de jogabilidade.

A proposta central é transformar a experiência do usuário, oferecendo um suporte consultivo que elimina a necessidade de pausas constantes para a leitura de manuais extensos, garantindo assim que a dinâmica e o fluxo das partidas sejam mantidos de forma fluida e intuitiva.

## Dataset:
O dataset foi construído a partir de 20 perguntas e respostas feitas para o olhama ter uma base de conhecimento sobre as regras e funcionalidades do jogo, assim se tornando capaz de ser um assistente de regras capaz de responder às perguntas de forma correta.

## System Prompt:
- Dataset: Serve para treinar o modelo e fornecer o contexto necessário sobre as regras e mecânicas dos jogos.

- Modelfile: Componente responsável por definir a "personalidade" do assistente, estabelecendo as regras de comportamento e o tom das respostas geradas (ex: amigável, instrutivo e direto).

- Preset: Para assegurar a reprodutibilidade e a eficiência, o Modelfile foi salvo como um preset, permitindo manter o padrão de desempenho e as configurações técnicas em diferentes sessões de uso.

## Comparação Base x Customizada::
| Característica | Modelo Base (Padrão) | Modelo Customizado (Assistente) |
| :--- | :--- | :--- |
| **Precisão** | Respostas genéricas sobre jogos. | Respostas precisas baseadas no dataset de Monopoly. |
| **Tom de Voz** | Informativo e neutro. | Consultivo e focado em suporte ao jogador. |
| **Agilidade** | Exige prompts mais detalhados. | Identifica a dúvida rapidamente pelo contexto prévio. |

## Aprendizados:
Eduardo Barcelos:  
Durante o desenvolvimento do projeto, compreendi como a estruturação de um Modelfile bem definido é crucial para transformar um modelo de linguagem genérico em um assistente especializado e funcional. O processo de integrar o Dataset de regras do Monopoly me permitiu entender, na prática, como o contexto fornecido influencia diretamente na precisão das respostas, garantindo que a IA não apenas reproduza informações, mas atue como um suporte dinâmico para o usuário. Além disso, a experiência de configurar e salvar os presets do sistema consolidou meu conhecimento sobre a importância da padronização técnica para manter a consistência e a personalidade da ferramenta em diferentes interações.
  
  
Lucas Bomfim:  

Julia Johanson:  
