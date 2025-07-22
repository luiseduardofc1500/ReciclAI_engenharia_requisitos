## Requisito Funcional: RF-011 - Registro de Descarte

### Descrição

O sistema deve registrar o descarte de resíduo de um usuário identificado quando a verificação do descarte for concluída com sucesso.

- **Autor do Requisito:** Anderson Neto
- **Status:** Aprovado
- **Origem/Fonte:** Stakeholder principal

### Justificativa

Este requisito é fundamental para a operação do sistema, pois vincula a ação de descarte do usuário ao sistema de recompensas e à coleta de dados. O registro preciso é essencial para garantir a credibilidade do programa, motivar a participação contínua através da pontuação e gerar dados confiáveis para a gestão de resíduos e relatórios de impacto ambiental.

### Critérios de Aceitação

- O sistema deve iniciar o processo de registro de descarte somente após a identificação válida de um usuário através do seu QR Code em um ponto de coleta inteligente.
- O sistema deve receber e processar a confirmação dos sensores do ponto de coleta, validando o tipo de material (papel, plástico, orgânico, metal, vidro) e a quantidade (e.g., peso ou volume) do resíduo depositado.
- Após a verificação bem-sucedida, um novo registro de descarte deve ser criado e permanentemente armazenado no banco de dados, associado ao perfil do usuário.
- O registro de descarte deve conter, no mínimo, as seguintes informações: ID do Usuário, ID do Ponto de Coleta, Data e Hora do Descarte, Tipo de Material e Quantidade de Material.
- O sistema deve, em seguida, acionar a regra de negócio para creditar os pontos correspondentes ao descarte na conta do usuário.
- Uma notificação de confirmação do descarte e dos pontos adquiridos deve ser exibida ao usuário na interface do aplicativo.
- Caso a verificação do descarte falhe (e.g., o sensor não detecta o material após a identificação do usuário), o sistema não deve registrar o descarte e deve informar ao usuário sobre a falha através de uma mensagem clara no ponto de coleta ou no aplicativo.


- **Prioridade:** Essencial
