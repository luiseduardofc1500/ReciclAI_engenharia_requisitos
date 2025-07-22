## Requisito Não Funcional: RNF-021 - Otimização para alto volume de dados

- **Categoria:** Eficiência de Uso > Performance do Sistema
- **Autor do Requisito:** Luis Eduardo
- **Status:** Aprovado
- **Origem/Fonte:** Catálogo
- **Prioridade:** Alta

### Justificativa

Garantir que a performance não degrade à medida que a base de usuários e o volume de registros aumentam, mantendo a qualidade do serviço a longo prazo.

### Critérios de Aceitação

- A consulta ao histórico de descartes do usuário, mesmo com mais de 1000 registros, deve carregar em menos de 3 segundos.
- A geração de relatórios administrativos com dados de um mês não deve exceder 10 segundos.

### Descrição

O tempo de resposta do sistema deve ser otimizado para alto volume de dados.