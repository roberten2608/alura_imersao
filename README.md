# Sistema de Criação de Atividades Educativas

Este projeto utiliza o Google ADK para criar agentes que ajudam professores do ensino infantil a buscar ideias de atividades, planejar e criar matrizes para suas aulas.

## Visão Geral

O sistema consiste em dois agentes principais:

- **Agente Buscador de Atividades**: Pesquisa na internet por ideias de atividades criativas para crianças, priorizando aqueles que incluem diagramas visuais ou imagens.
- **Agente Planejador de Atividades**: Organiza as atividades encontradas em categorias e sugere métodos de aplicação em sala de aula.

## Como Usar

1. **Instale as Dependências**: Certifique-se de ter o `google-adk` instalado no seu ambiente.

   ```bash
   !pip install -q google-adk

   Execute o Sistema no Google Colab:

Importe as bibliotecas necessárias.
Defina funções auxiliares e agentes.
Insira o tópico desejado e observe as atividades e planos sugeridos.
Exemplo de Uso
O usuário insere um tópico, por exemplo, "númeral 2".
O sistema busca e apresenta uma lista de atividades relevantes.
As atividades são então organizadas e um plano de aula é sugerido.
Estrutura do Código
agent_buscador: Pesquisa por atividades baseadas em um tópico.
agent_planejador: Organiza as ideias em um plano estruturado.
