# Backlog
Como na documentação original não havia user stories, foi elaborado este documento com as devidas adições.

# User Stories
## User Stories para Usuário Convidado
**User Story 1:** *Como usuário convidado*, quero poder salvar o ensalamento em forma de arquivo para visualizar offline.  
**Critérios de Seleção:**
* O arquivo deve conter todas as informações do ensalamento selecionado.
* O sistema deve gerar e disponibilizar o download do arquivo após a seleção.
* O arquivo deve estar disponível para visualização offline após ser baixado.


**User Story 2:** *Como usuário convidado*, quero poder filtrar os ensalamentos por curso para poder visualizar/salvar apenas o ensalamento do meu curso.  
**Critérios de Seleção:**
* O usuário deve visualizar uma lista de cursos disponíveis para filtro.  
* Ao selecionar um curso, o ensalamento exibido deve ser atualizado para mostrar apenas as turmas relacionadas ao curso escolhido.  
* O sistema deve permitir que o usuário salve o ensalamento filtrado em formato de arquivo.  


**User Story 3:** *Como usuário convidado*, quero poder visualizar o ensalamento na página inicial do site, a fim de facilitar consultas rápidas.
**Critérios de Seleção:**
* O ensalamento deve ser exibido de forma clara e organizada na página inicial.  
* O usuário deve poder visualizar o ensalamento sem a necessidade de realizar login.  
* O sistema deve atualizar automaticamente o ensalamento na página inicial conforme alterações ou novas alocações.  


## User Stories para Administrador - Gestão de Professores
  
**User Story 4:** *Como administrador*, desejo adicionar novos professores ao sistema, para garantir que todos os profissionais estejam registrados e possam ser alocados às disciplinas.  
**Critérios de Seleção:**
* O sistema deve permitir o cadastro de todos os campos obrigatórios (nome, especialidade, disponibilidade).  
* Após o cadastro, o novo professor deve aparecer na lista de professores.  
* O sistema deve validar a entrada para evitar cadastros duplicados.



**User Story 5:** *Como administrador*, desejo visualizar a lista completa de professores cadastrados para ter um controle sobre o corpo docente e suas respectivas disciplinas. 
**Critérios de Seleção:**
* A lista de professores deve exibir todos os registros de forma paginada, caso exceda uma quantidade definida.
* O administrador deve poder realizar buscas e aplicar filtros por nome, especialidade, e status (ativo/inativo).
* A lista deve mostrar informações resumidas, como nome, disciplinas associadas, e status.



**User Story 6:** *Como administrador*, desejo editar os dados de um professor existente, como especialidade ou disponibilidade, para garantir que as informações estejam sempre corretas.  
**Critérios de Seleção:**
* O administrador deve poder acessar uma interface de edição a partir da lista de professores.
* O sistema deve permitir a atualização de campos como especialidade e disponibilidade.
* O sistema deve exibir uma confirmação antes de salvar as alterações.
* As alterações devem refletir imediatamente na lista de professores e nas alocações relacionadas.



**User Story 7:** *Como administrador*, desejo excluir registros de professores que não fazem mais parte da instituição, para manter o sistema atualizado e organizado.  
**Critérios de Seleção:**
* O sistema deve solicitar uma confirmação antes de excluir um professor.
* O professor não pode ser excluído caso esteja alocado a uma disciplina ativa.
* Após a exclusão, o registro deve ser removido da lista de professores.



**User Story 8:** *Como administrador*, desejo visualizar os detalhes de um professor específico, como qualificações, disciplinas que leciona e histórico de alocações, para melhor planejar a gestão acadêmica.
**Critérios de Seleção:**
* O sistema deve exibir uma página com informações detalhadas, como qualificações, disciplinas associadas, e histórico de alocações.
* O administrador deve ter a opção de retornar à lista de professores ou editar os dados a partir desta visualização.



## User Stories para Administrador - Gestão de Disciplinas

**User Story 9:** *Como administrador*, desejo adicionar novas disciplinas ao sistema para garantir que todos os cursos e áreas de estudo estejam corretamente cadastrados e disponíveis para consulta.  
**Critérios de Seleção:**
* O sistema deve permitir o cadastro de todas as informações necessárias (nome, ementa, pré-requisitos).
Após o cadastro, a disciplina deve aparecer na lista de disciplinas.
* O sistema deve validar para evitar a criação de disciplinas duplicadas.



**User Story 10:** *Como administrador*, desejo visualizar a lista completa de disciplinas para ter um controle centralizado de todas as matérias oferecidas, permitindo uma fácil gestão.  
**Critérios de Seleção:**
* A lista deve exibir todas as disciplinas com informações básicas, como nome e carga horária.
* O administrador deve poder aplicar filtros por curso, carga horária e outros critérios.
* A lista deve ser paginada para melhorar a usabilidade.



**User Story 11:** *Como administrador*, desejo editar as informações das disciplinas existentes, para ajustar o conteúdo ou alterar detalhes conforme necessário, mantendo os dados atualizados. 
**Critérios de Seleção:**
* O sistema deve permitir a edição de campos como ementa, pré-requisitos, e carga horária.
* As atualizações devem refletir em todas as consultas e exibições da disciplina.
* O sistema deve exibir uma confirmação antes de salvar as alterações.


 
**User Story 12:** *Como administrador*, desejo excluir disciplinas que não são mais oferecidas, para manter o sistema limpo e relevante.  
**Critérios de Seleção:**
* O sistema deve solicitar uma confirmação antes de excluir uma disciplina.
* Disciplinas com alunos matriculados ou alocações ativas não devem ser excluídas.
* Após a exclusão, a disciplina deve ser removida da lista de disciplinas.




**User Story 13:** *Como administrador*, desejo visualizar os detalhes de uma disciplina específica, como ementa, pré-requisitos e carga horária, para garantir que as informações estejam corretas e completas.
**Critérios de Seleção:**
* O sistema deve exibir uma página com todas as informações da disciplina, incluindo ementa, pré-requisitos e carga horária.
* O administrador deve ter a opção de editar a disciplina ou voltar à lista de disciplinas.



## User Stories para Administrador - Gestão de Salas

**User Story 14:** *Como administrador*, desejo adicionar novas salas ao sistema para garantir que todas as instalações estejam disponíveis para alocação e uso.  
**Critérios de Seleção:**
* O sistema deve permitir o cadastro de todas as informações necessárias (nome, capacidade, localização).
* A nova sala deve aparecer na lista de salas após o cadastro.
* O sistema deve validar para evitar a criação de salas com nomes duplicados.



**User Story 15:** *Como administrador*, desejo visualizar a lista completa de salas disponíveis, a fim de facilitar a gestão e o planejamento do uso do espaço.  
**Critérios de Seleção:**
* A lista deve exibir todas as salas cadastradas com informações básicas.
* O administrador deve poder aplicar filtros por capacidade e localização.
* A lista deve ser paginada se o número de registros for grande.



**User Story 16:** *Como administrador*, desejo editar as informações de uma sala existente, como capacidade ou localização, para refletir quaisquer mudanças nas instalações.  
**Critérios de Seleção:**
* O administrador deve poder editar campos como capacidade e localização.
* As alterações devem ser refletidas em todas as consultas e exibições de salas.
* O sistema deve exibir uma confirmação antes de salvar as alterações.



**User Story 17:** *Como administrador*, desejo excluir salas que não estão mais em uso, para evitar confusões e garantir que apenas os espaços disponíveis estejam cadastrados.  
**Critérios de Seleção:**

* O sistema deve solicitar uma confirmação antes de excluir uma sala.
* Salas com alocações ativas não devem ser excluídas.
* Após a exclusão, a sala deve ser removida da lista de salas.



**User Story 18:** *Como administrador*, desejo visualizar os detalhes de uma sala específica, como a capacidade e os recursos disponíveis, para facilitar o processo de alocação.
**Critérios de Seleção:**
* O sistema deve exibir uma página com todas as informações da sala, como capacidade e recursos disponíveis.
* O administrador deve poder editar a sala a partir desta visualização ou voltar à lista de salas.



## User Stories para Administrador - Gestão de Alocações
  
**User Story 19:** *Como administrador*, desejo adicionar novas alocações para organizar a distribuição de recursos e horários de forma eficiente, a fim de garantir o cumprimento das atividades programadas.  
**Critérios de Seleção:**
* O sistema deve permitir o cadastro de todas as informações necessárias (sala, professor, disciplina, horário).
* A nova alocação deve aparecer na lista de alocações após o cadastro.
* O sistema deve validar para evitar conflitos de horário e sobreposição de alocações.



**User Story 20:** *Como administrador*, desejo visualizar todas as alocações disponíveis para monitorar e gerenciar a ocupação de recursos e horários de forma clara.  
**Critérios de Seleção:**
* A lista de alocações deve exibir informações resumidas, como sala, disciplina, e horário.
* O administrador deve poder filtrar por sala, professor, disciplina e horário.
* A lista deve ser paginada se o número de registros for grande.



**User Story 21:** *Como administrador*, desejo editar as alocações já existentes para realizar ajustes quando necessário, garantindo que a distribuição de recursos continue eficiente.  
**Critérios de Seleção:**
* O sistema deve permitir a edição de campos como sala, horário, ou professor.
* As alterações devem ser refletidas em todas as consultas e exibições de alocações.
* O sistema deve exibir uma confirmação antes de salvar as alterações.



**User Story 22:** *Como administrador*, desejo excluir alocações que não sejam mais necessárias, para manter o sistema organizado e evitar confusões com dados obsoletos.  
**Critérios de Seleção:**
* O sistema deve solicitar uma confirmação antes de excluir uma alocação.
* Após a exclusão, a alocação deve ser removida da lista de alocações.
* A exclusão deve atualizar automaticamente as listas de alocações disponíveis.



**User Story 23:** *Como administrador*, desejo visualizar os detalhes de uma alocação específica para compreender melhor como os recursos e horários foram distribuídos e tomar decisões baseadas nessa análise.  
**Critérios de Seleção:**
* O sistema deve exibir uma página com informações detalhadas sobre a alocação, como professor, disciplina, sala e horário.
* O administrador deve poder editar a alocação a partir desta visualização ou voltar à lista de alocações.



**User Story 24:** *Como administrador*, desejo poder gerar o ensalamento através da lista de alocações.
**Critérios de Seleção:**
* O sistema deve compilar as alocações em um ensalamento organizado.
* O ensalamento gerado deve ser disponibilizado em formato de arquivo para download (PDF).
* O sistema deve permitir que o administrador visualize uma prévia antes de confirmar a geração do ensalamento.
* O ensalamento deve ser atualizado automaticamente sempre que houver uma mudança nas alocações.
