# Agent_Analise_Dados

**Agent_Analise_Dados** é um projeto que permite ao usuário interagir com um agente analista de dados utilizando comandos de voz. O agente transcreve áudio para texto, processa esse texto com um modelo de linguagem (LLM), trata a resposta gerada e a converte novamente para áudio para responder ao usuário.

### Funcionalidade Principal

- **Transcrição de Áudio para Texto**: O sistema é capaz de transcrever áudio para texto utilizando uma classe presente no arquivo `talking_llm.py`.
- **Processamento de Texto com LLM**: A entrada de texto é processada por um modelo de linguagem (LLM) que gera respostas relevantes.
- **Reprodução de Áudio**: A resposta gerada pelo modelo de linguagem é convertida de volta para áudio, permitindo que o usuário ouça a resposta.

### Estrutura do Projeto

- **`talking_llm.py`**: Contém a classe que estrutura a lógica de transcrição de áudio para texto, ingestão do texto em uma LLM, tratamento da resposta e redecodificação em áudio.
- **`df_agent.py`**: Provavelmente relacionado ao agente de análise de dados e como ele interage com os dados.
- **`.env`**: Arquivo de configuração de variáveis de ambiente, provavelmente utilizado para armazenar chaves de API ou outras informações sensíveis.
- **`LICENSE`**: Arquivo que contém a licença do projeto.
  
### Requisitos

Antes de começar, certifique-se de ter as seguintes dependências instaladas:

- Python 3.x
- Bibliotecas necessárias (como `speech_recognition`, `pyaudio`, `openai`, etc., dependendo do seu código)

Você pode instalar as dependências executando:

```bash
pip install -r requirements.txt
```

```bash
git clone https://github.com/Caiojosue/Agent_Analise_Dados
cd Agent_Analise_Dados
```
E logo após execute o arquivo 

```bash
python talking_llm.py
```


Você pode copiar esse conteúdo e colá-lo diretamente no arquivo `README.md` do seu repositório no GitHub.
Se precisar de mais alguma coisa, é só avisar!
