Checkpoint 2: PAI - Assistente de Regras do Jogo Monopoly
Integrantes:

Julia Johanson Peniche da Silva – RM: 572220

Lucas Bomfim Leite – RM: 570420

Eduardo Barcelos De Carvalho Brazilano – RM: 573274

1. Justificativa
O fator determinante na seleção do nosso domínio foi a convergência entre o interesse pessoal do grupo e a aplicabilidade prática no setor de jogos. Ao optarmos pelo desenvolvimento de um Assistente de Regras, buscamos unir a nossa afinidade com o universo lúdico à criação de uma ferramenta que resolva problemas reais de jogabilidade.

A proposta central é transformar a experiência do usuário, oferecendo um suporte consultivo que elimina a necessidade de pausas constantes para a leitura de manuais extensos, garantindo assim que a dinâmica e o fluxo das partidas sejam mantidos de forma fluida e intuitiva.

2. Dataset
O dataset foi construído criteriosamente a partir de 20 perguntas e respostas estruturadas para fornecer ao modelo (Ollama) uma base sólida de conhecimento sobre as regras e funcionalidades específicas do Monopoly. Essa base permite que o assistente responda de forma precisa, interpretando nuances que um modelo genérico poderia ignorar.

3. System Prompt e Arquitetura
O desenvolvimento do assistente baseia-se em três pilares fundamentais:

Dataset: Serve para treinar o modelo e fornecer o contexto necessário sobre as regras e mecânicas dos jogos.

Modelfile: Componente responsável por definir a "personalidade" do assistente, estabelecendo as regras de comportamento e o tom das respostas geradas.

Preset: Para assegurar a reprodutibilidade e a eficiência, o Modelfile foi salvo como um preset, permitindo manter o padrão de desempenho e as configurações técnicas em diferentes sessões de uso.
