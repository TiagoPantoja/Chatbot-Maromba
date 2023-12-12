# Chatbot Maromba

Este é o repositório do Chatbot Maromba, um assistente virtual para fornecer informações sobre a Academia YouFit. O chatbot é desenvolvido em Python e utiliza a biblioteca `fuzzywuzzy` para processar perguntas dos usuários de forma mais flexível.

## Instalação

Antes de começar, certifique-se de ter o Python e o gerenciador de pacotes `pip` instalados. Em seguida, instale as dependências executando o seguinte comando:
```
pip install fuzzywuzzy
```

## Uso

Clone este repositório para o seu ambiente local e execute o script Python `academia_chatbot.py`. O chatbot oferecerá um menu interativo para responder a perguntas relacionadas à Academia YouFit.
```
python academia_chatbot.py
```

## Funcionalidades

O Chatbot Maromba pode responder a diversas perguntas relacionadas à academia, como localização, professores disponíveis, aulas oferecidas, exercícios recomendados e informações sobre dieta. Além disso, utiliza correspondência difusa (`fuzzy matching`) para lidar com perguntas que não coincidem exatamente com as regras predefinidas.

## Personalização

O chatbot permite a adição de novas regras e variáveis para expandir sua base de conhecimento. As regras são configuradas no método `__init__` da classe `AcademiaChatbot` no script Python.

# Exemplo de adição de regra
chatbot.adicionar_regra("Qual sua política de cancelamento?", "Você pode cancelar sua assinatura a qualquer momento entrando em contato com nosso suporte.")
