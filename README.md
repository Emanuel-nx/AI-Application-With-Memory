# Gerenciamento de Memória com LangChain e GROQ

## Introdução
Este projeto demonstra o uso da API da GROQ com LangChain para criar um chatbot com gerenciamento de memória. Ele permite armazenar e recuperar históricos de conversação e otimizar respostas.

## Configuração do Projeto

### Clonar o repositório
```sh
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### Criar e ativar ambiente virtual
```sh
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate  # Windows
```

### Instalar dependências
```sh
pip install -r requirements.txt
```

## Execução
```sh
python main.py
```

## Estrutura do Código
- **Importação de Bibliotecas**: Carrega dependências.
- **Configuração da API**: Obtém credenciais do arquivo `.env`.
- **Gerenciamento de Histórico**: Armazena conversas por ID de sessão.
- **Execução do Chatbot**: Processa e otimiza mensagens.

Esse projeto possibilita interações otimizadas com IA, mantendo o contexto das conversas. 🚀
