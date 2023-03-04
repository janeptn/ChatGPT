# Explorando a nova API ChatGPT da OpenAI

Nesta semana (01/03/2023), a OpenAI lançou a API ChatGPT (Chat completions Beta - https://lnkd.in/dT4PqCfF). Anteriormente, a principal API disponível era para o modelo GPT-3.5 (text-davinci-003), que faz parte da família de modelos de linguagem natural desenvolvidos pela OpenAI.

A nova API ChatGPT (modelo gpt-3.5-turbo), tem o foco em tarefas de conversação, com uma arquitetura adaptada para interações de diálogo. A API do ChatGPT permite por exemplo, o desenvolvimento de chatbots capazes de manter conversas com usuários, sendo possível configurar o comportamento do assistente por meio de mensagens de sistema e de usuário.

Algo que chama a atenção é o custo, $0,002 por 1.000 tokens, que é 10 vezes mais barato do que o modelo GPT-3.5.

** SobreTokens: Tratam-se de unidades de texto que os modelos de linguagem GPT e ChatGPT usam para processar informações. Um token pode ser uma única letra ou uma palavra completa, dependendo do contexto. Por exemplo, a frase "ChatGPT é incrível!" é dividida em seis tokens: ["Chat", "G", "PT", " é", " incrível", "!"]. A quantidade de tokens usados em uma chamada de API determina o custo e o tempo de processamento da chamada. (https://lnkd.in/dbuN6D7P).

Disponibilizei neste link um exemplo de uso da API ChatGPT (Google Colab - Python): https://lnkd.in/d-pNxbxD

