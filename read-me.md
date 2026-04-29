# 🚀 Engenharia de Prompts com Groq API

Repositório de estudos da Udemy focado em técnicas avançadas de engenharia de prompts utilizando a API Groq.

## ⚙️ Configuração do Ambiente

### Instalação
```bash
# Instalar o ambiente virtual
python -m venv .venv

# Ativar o ambiente virtual (Windows)
.venv\Scripts\activate

# Instalar as dependências
pip install -r requirements.txt

# Executar o Jupyter Lab
jupyter lab
```

## 📚 Dependências

As seguintes bibliotecas são necessárias:
- **python-dotenv**: Para carregar variáveis de ambiente (.env)
- **jupyterlab**: Para executar os notebooks interativos
- **groq**: SDK para interagir com a API Groq

## 🔑 Configuração da API Groq

1. Acesse [Groq Console](https://console.groq.com/keys)
2. Gere sua chave de API
3. Crie um arquivo `.env` na raiz do projeto com:
   ```
   GROQ_API=sua_chave_aqui
   ```

## 📓 Estrutura dos Notebooks

### 01-roles.ipynb - Compreendendo os Roles
Introdução aos três papéis fundamentais na comunicação com LLMs:
- **User**: Mensagens do usuário
- **Assistant**: Respostas do modelo
- **System**: Instruções de comportamento para o modelo

### 02-params.ipynb - Parâmetros Importantes
Exploração dos parâmetros principais que controlam o comportamento do modelo:
- **temperature**: Controla a aleatoriedade (0.0 = determinístico, 1.0 = máxima criatividade)
- **max_completion_tokens**: Define o número máximo de tokens na resposta
- **top_p**: Controla a diversidade via "nucleus sampling"

### 03-boas_praticas.ipynb - Boas Práticas em Prompts
Técnicas essenciais para escrever prompts eficazes:
- Use prompts específicos e detalhados
- Instruções precisas
- Controle o formato da resposta
- Use separadores para organizar informações

### 04-output_estruturado.ipynb - Saída em Formato Estruturado
Como estruturar respostas em formatos específicos:
- Tabelas markdown
- Listas estruturadas
- JSON
- Outros formatos customizados

### 05-condicoes.ipynb - Usando Condicionais Básicos
Implementação de lógica condicional nos prompts:
- Respostas baseadas em tipo de pergunta (básica, avançada, ambígua)
- Adaptação dinâmica do comportamento do modelo
- Casos de uso específicos

### 06-few_shot.ipynb - Técnicas Few Shot Prompting
Estratégias de aprendizado por exemplos:
- **Zero Shot**: Sem exemplos, apenas instruções
- **One Shot**: Um exemplo para instruir o modelo
- **Few Shot**: Múltiplos exemplos para melhor compreensão

### 07-steps.ipynb - Resolução de Problemas por Etapas
Decomposição de tarefas complexas em passos sequenciais para melhor qualidade de resposta

### 08-cot.ipynb - Cadeia de Pensamento (Chain of Thought)
Técnica para melhorar a qualidade do raciocínio do modelo:
- Raciocínio estruturado e explícito
- Explicação transparente do processo
- Clareza na tomada de decisão

### 09-sumarizacao.ipynb - Sumarização de Textos
Técnicas para resumir textos mantendo informações essenciais:
- Redução de tamanho mantendo contexto
- Preservação de pontos centrais
- Adaptação de tom e estilo

### 10-texto_complemento.ipynb - Complementação de Textos
Técnicas para completar e expandir textos:
- Continuação natural de conteúdo
- Preenchimento de lacunas informacionais
- Geração de conteúdo contextualizado

### 11-transformacao_texto.ipynb - Transformação de Textos
Conversão e reformulação de textos:
- Mudança de tons e estilos
- Paráfrase
- Tradução contextual
- Reformulação para diferentes públicos

### 12-analise_textual.ipynb - Análise Textual
Técnicas para extrair insights de textos:
- Identificação de sentimentos
- Extração de entidades
- Análise de estrutura e padrões
- Classificação de conteúdo

## 💡 Referências Externas

- **Groq API**: https://groq.com/
- **Groq Console**: https://console.groq.com/keys
- **Documentação Groq**: https://console.groq.com/docs
