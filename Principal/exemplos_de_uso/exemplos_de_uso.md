# Exemplos de Uso
A seguir, estão descritos exemplos de uso do sistema de ensalamento Rooms onde são descritas as possíves ações dos atores Convidado e Administrador.

## Cenário 1: Acessar o site como convidado e consultar os ensalamentos

### Descrição do fluxo de trabalho:
Um usuário acessa o site sem realizar login (convidado) e deseja visualizar os ensalamentos disponíveis. Ele pode navegar pelos dados dos ensalamentos, que incluem informações como professor, disciplina, sala, dia da semana e horário. O usuário também tem a opção de filtrar os ensalamentos por curso específico e baixar o arquivo PDF contendo as informações filtradas.

### Fluxo detalhado:

#### 1. Acesso ao site como convidado
- **Usuário**: João, estudante interessado em verificar os ensalamentos da próxima semana.
- **Ação**: João acessa o site da instituição sem realizar login.
- **Expectativa**: O sistema permite que ele navegue pelo conteúdo público, incluindo o acesso aos ensalamentos.

#### 2. Visualização dos ensalamentos
- **Usuário**: João deseja consultar os horários das disciplinas de Engenharia de Software.
- **Ação**: João clica na aba "Acessar como convidado" na página inicial.
- **Resultado**: O sistema exibe uma lista organizada com as seguintes colunas:
  - Professor
  - Disciplina
  - Sala
  - Dia da semana
  - Horário

#### 3. Filtro por curso
- **Usuário**: Para facilitar sua busca, João decide filtrar os ensalamentos pelo curso de "Engenharia de Software".
- **Ação**: João seleciona o curso "Engenharia de Software" no filtro de cursos.
- **Resultado**: O sistema atualiza a lista de ensalamentos, exibindo apenas as disciplinas e horários relacionados ao curso selecionado.

#### 4. Baixar os ensalamentos em PDF
- **Usuário**: João quer salvar o ensalamento em seu dispositivo para consulta offline.
- **Ação**: Ele clica no botão "Doanload" localizado acima da tabela de ensalamentos.
- **Resultado**: O sistema gera um arquivo PDF contendo os dados filtrados de acordo com o curso de "Engenharia de Software" e o download é iniciado automaticamente.

### Impacto da funcionalidade:
- **Acessibilidade**: Permitir que usuários convidados consultem os ensalamentos sem necessidade de login aumenta a acessibilidade e conveniência para estudantes e interessados externos.
- **Eficiência**: A funcionalidade de filtro por curso reduz o tempo necessário para encontrar informações específicas, melhorando a experiência de navegação.
- **Praticidade**: A opção de baixar o ensalamento em PDF permite ao usuário acessar as informações mesmo offline, oferecendo maior flexibilidade.

### Contribuição para o objetivo geral:
Essa funcionalidade contribui para o objetivo principal do sistema de fornecer informações acadêmicas de maneira fácil e acessível, facilitando o planejamento e organização dos alunos. Ao permitir que qualquer visitante consulte os ensalamentos, o sistema garante que as informações estejam amplamente disponíveis, e a opção de filtrar e baixar os dados em PDF melhora a usabilidade e conveniência.

## Cenário 2: Acessar o sistema como administrador e gerenciar alocações

### Descrição do fluxo de trabalho:
Um funcionário da UFAM responsável pelo sistema acessa o site como administrador e utiliza o painel administrativo para adicionar novas alocações de professores, disciplinas, espaços, dias da semana e horários. Após adicionar uma nova alocação, ele pode lançar essa mudança no ensalamento através de um botão específico.

### Fluxo detalhado:

#### 1. Acesso ao sistema como administrador
- **Usuário**: Maria, funcionária da UFAM responsável pelo gerenciamento do sistema.
- **Ação**: Maria acessa o site e clica no botão "Acessar como Administrador".
- **Resultado**: O sistema exibe a página de login para administradores.
- **Ação**: Maria insere suas credenciais de administrador (usuário e senha) e clica em "Entrar".
- **Resultado**: O sistema autentica Maria e redireciona para o painel administrativo.

#### 2. Acessar o menu de alocações
- **Usuário**: Maria precisa adicionar novas alocações de disciplinas para o próximo semestre.
- **Ação**: No painel administrativo, Maria clica na seção "Alocações" no menu lateral.
- **Resultado**: O sistema exibe a tela "Lista de Alocações", onde são exibidas todas as alocações atuais com informações como professor, disciplina, espaço, dia da semana e horário.

#### 3. Adicionar nova alocação
- **Usuário**: Maria quer adicionar uma nova alocação de disciplina para o professor Carlos no curso de Matemática.
- **Ação**: Ela clica no botão "Adicionar Nova Alocação" localizado na parte superior da tela.
- **Resultado**: O sistema exibe um formulário para adicionar uma nova alocação com os seguintes campos:
  - Professor
  - Disciplina
  - Espaço (sala/laboratório)
  - Dia da semana
  - Horário

- **Ação**: Maria preenche o formulário com as seguintes informações:
  - **Professor**: Carlos Silva
  - **Disciplina**: Cálculo II
  - **Espaço**: Sala 104
  - **Dia da semana**: Segunda-feira
  - **Horário**: 08:00 - 10:00

- **Ação**: Maria clica no botão "Adicionar" para confirmar a nova alocação.
- **Resultado**: O sistema salva a nova alocação e redireciona Maria de volta para a "Lista de Alocações", agora com a nova alocação incluída na tabela.

#### 4. Lançar a nova alocação
- **Usuário**: Maria quer garantir que a nova alocação de Cálculo II seja incluída nos ensalamentos visíveis aos estudantes.
- **Ação**: Na tela "Lista de Alocações", ela localiza a nova alocação e clica no botão "Gerar Ensalamento".
- **Resultado**: O sistema atualiza o ensalamento oficial, incorporando as novas alocações adicionadas, e a mudança fica disponível para consulta pública.

### Impacto da funcionalidade:
- **Controle e Organização**: A funcionalidade oferece aos administradores total controle sobre a alocação de professores e disciplinas, garantindo que as informações estejam sempre atualizadas.
- **Facilidade de Gerenciamento**: O fluxo de adicionar alocações de forma centralizada e poder lançá-las diretamente no ensalamento reduz a complexidade e o tempo gasto no gerenciamento.
- **Precisão e Agilidade**: O botão "Gerar Ensalamento" assegura que qualquer alteração feita no sistema seja rapidamente refletida para os usuários, promovendo transparência e atualização em tempo real.

### Contribuição para o objetivo geral:
Essa funcionalidade facilita o processo administrativo, permitindo que funcionários da UFAM gerenciem alocações de maneira ágil e eficiente. Ao centralizar esse controle, o sistema garante que os ensalamentos estejam sempre atualizados, evitando conflitos de horários e garantindo uma distribuição eficiente de disciplinas e espaços.

## Cenário 3: Adicionar uma nova disciplina

### Descrição do fluxo de trabalho:
O administrador acessa o painel administrativo e deseja adicionar uma nova disciplina ao sistema. Ele pode navegar até a tela de "Lista de Disciplinas" e adicionar uma nova disciplina com base em seu nome, código, curso e modo de ensino.

### Fluxo detalhado:

#### 1. Acesso à lista de disciplinas
- **Usuário**: Maria, funcionária da UFAM responsável por adicionar disciplinas.
- **Ação**: No painel administrativo, Maria clica no botão "Disciplinas" no menu principal.
- **Resultado**: O sistema exibe a "Lista de Disciplinas" com as disciplinas já cadastradas e um botão "Adicionar Nova Disciplina" no topo da página.

#### 2. Adicionar nova disciplina
- **Usuário**: Maria quer adicionar uma nova disciplina chamada "Engenharia de Software II".
- **Ação**: Ela clica no botão "Adicionar Nova Disciplina".
- **Resultado**: O sistema exibe um formulário com os seguintes campos:
  - Nome da Disciplina
  - Código da Disciplina
  - Curso
  - Modo de Ensino (Teórico ou Teórico/Prático)

- **Ação**: Maria preenche o formulário com as seguintes informações:
  - **Nome da Disciplina**: Engenharia de Software II
  - **Código da Disciplina**: ES302
  - **Curso**: Engenharia de Software
  - **Modo de Ensino**: Teórico/Prático

- **Ação**: Maria clica no botão "Adicionar" para salvar a nova disciplina.
- **Resultado**: O sistema salva a nova disciplina e a adiciona à "Lista de Disciplinas". Maria pode clicar no botão "Voltar" para retornar ao painel administrativo.

---

## Cenário 4: Adicionar um novo espaço físico (Salas/Laboratórios)

### Descrição do fluxo de trabalho:
O administrador deseja adicionar uma nova sala ou laboratório ao sistema. Ele pode acessar a "Lista de Espaços Físicos" e adicionar um novo espaço com base no andar, número, bloco e tipo de espaço.

### Fluxo detalhado:

#### 1. Acesso à lista de espaços físicos
- **Usuário**: Maria precisa cadastrar um novo laboratório.
- **Ação**: No painel administrativo, Maria clica no botão "Salas/Labs" no menu principal.
- **Resultado**: O sistema exibe a "Lista de Espaços Físicos" com as salas e laboratórios já cadastrados, junto com um botão "Adicionar Novo Espaço" no topo da página.

#### 2. Adicionar novo espaço físico
- **Usuário**: Maria quer cadastrar um novo laboratório no bloco D.
- **Ação**: Ela clica no botão "Adicionar Novo Espaço".
- **Resultado**: O sistema exibe um formulário com os seguintes campos:
  - Andar
  - Número
  - Bloco
  - Tipo de Espaço (Sala ou Laboratório)

- **Ação**: Maria preenche o formulário com as seguintes informações:
  - **Andar**: 2
  - **Número**: 305
  - **Bloco**: D
  - **Tipo de Espaço**: Laboratório

- **Ação**: Ela clica no botão "Adicionar" para salvar o novo espaço.
- **Resultado**: O sistema salva o novo espaço e o adiciona à "Lista de Espaços Físicos". Maria pode clicar no botão "Voltar" para retornar ao painel administrativo.

---

## Cenário 5: Adicionar um novo professor

### Descrição do fluxo de trabalho:
O administrador deseja cadastrar um novo professor no sistema. Ele pode acessar a "Lista de Professores" e adicionar um novo professor usando o SIAPE, nome e sobrenome.

### Fluxo detalhado:

#### 1. Acesso à lista de professores
- **Usuário**: Maria precisa cadastrar um novo professor para o curso de Matemática.
- **Ação**: No painel administrativo, Maria clica no botão "Professores" no menu principal.
- **Resultado**: O sistema exibe a "Lista de Professores" com os professores já cadastrados e um botão "Adicionar Novo Professor" no topo da página.

#### 2. Adicionar novo professor
- **Usuário**: Maria quer cadastrar o professor Carlos Souza.
- **Ação**: Ela clica no botão "Adicionar Novo Professor".
- **Resultado**: O sistema exibe um formulário com os seguintes campos:
  - SIAPE
  - Nome
  - Sobrenome

- **Ação**: Maria preenche o formulário com as seguintes informações:
  - **SIAPE**: 123456
  - **Nome**: Carlos
  - **Sobrenome**: Souza

- **Ação**: Ela clica no botão "Adicionar" para salvar o novo professor.
- **Resultado**: O sistema salva o novo professor e o adiciona à "Lista de Professores". Maria pode clicar no botão "Voltar" para retornar ao painel administrativo.

---

## Cenário 6: Registrar um novo usuário

### Descrição do fluxo de trabalho:
O administrador deseja registrar um novo usuário no sistema. Ele acessa diretamente a tela de registro, onde pode inserir as informações de nome de usuário, e-mail, senha e confirmação de senha.

### Fluxo detalhado:

#### 1. Acesso à tela de registro de usuários
- **Usuário**: Maria precisa registrar um novo usuário no sistema.
- **Ação**: No painel administrativo, Maria clica no botão "Adicionar Usuário" no menu principal.
- **Resultado**: O sistema redireciona Maria diretamente para a tela de registro de usuário.

#### 2. Registrar um novo usuário
- **Usuário**: Maria quer registrar um novo usuário com nome "João".
- **Ação**: Ela preenche o formulário de registro com as seguintes informações:
  - **Nome de usuário**: João
  - **E-mail**: joao@ufam.edu.br
  - **Senha**: ********
  - **Confirmar senha**: ********

- **Ação**: Maria clica no botão "Registrar" para concluir o cadastro.
- **Resultado**: O sistema cria o novo usuário e confirma o registro. Maria pode clicar no botão "Voltar" para retornar ao painel administrativo.

---

### Impacto das funcionalidades:
- **Escalabilidade**: A possibilidade de adicionar disciplinas, espaços físicos, professores e usuários de maneira direta e organizada permite que o sistema se expanda conforme necessário.
- **Facilidade de Uso**: O acesso centralizado e a interface simplificada para o gerenciamento de informações críticas (disciplinas, espaços, professores e usuários) melhoram a eficiência do trabalho administrativo.
- **Atualização em Tempo Real**: Ao garantir que as mudanças sejam refletidas imediatamente nas listas correspondentes, o sistema mantém os dados atualizados e evita inconsistências.

### Contribuição para o objetivo geral:
Essas funcionalidades reforçam o controle administrativo do sistema, permitindo que a UFAM mantenha um registro organizado e atualizado das disciplinas, espaços, professores e usuários. A interface intuitiva e o fluxo de trabalho eficiente garantem uma operação administrativa ágil, crucial para o gerenciamento das informações acadêmicas da instituição.

## Cenário 7: Excluir, editar e visualizar detalhes de uma alocação

### Descrição do fluxo de trabalho:
O administrador deseja gerenciar as alocações, acessando uma lista de alocações. Neste cenário, ele decide visualizar os detalhes de uma alocação, editar outra e excluir uma terceira. Essas mesmas ações podem ser realizadas nas listas de disciplinas, salas ou professores.

### Fluxo detalhado:

#### 1. Acesso à lista de alocações
- **Usuário**: Maria, funcionária da UFAM responsável pelas alocações.
- **Ação**: No painel administrativo, Maria clica no botão "Alocações" no menu principal.
- **Resultado**: O sistema exibe a "Lista de Alocações", onde cada linha da lista contém informações como: 
  - Professor: José Campos
  - Disciplina: Inglês I
  - Bloco: A
  - Sala: 10
  - Dia: Segunda-feira
  - Horário: 08:00 - 09:00
  
  Ao lado de cada linha, há três botões: "Detalhes", "Editar" e "Excluir".

---

#### 2. Visualizar detalhes de uma alocação
- **Usuário**: Maria deseja ver os detalhes da alocação de José Campos.
- **Ação**: Ela clica no botão "Detalhes" ao lado da alocação.
- **Resultado**: O sistema exibe a tela "Detalhes da Alocação", mostrando as seguintes informações:
  - Professor: José Campos
  - Disciplina: Inglês I
  - Bloco: A
  - Sala: 10
  - Dia: Segunda-feira
  - Horário: 08:00 - 09:00
  
  Na parte inferior da tela, há dois botões: "Editar" e "Excluir".

- **Ação**: Maria decide não realizar nenhuma ação e clica no botão "Voltar" para retornar à lista de alocações.

---

#### 3. Editar uma alocação
- **Usuário**: Maria decide editar a alocação de José Campos.
- **Ação**: Na "Lista de Alocações", ela clica no botão "Editar" ao lado da alocação.
- **Resultado**: O sistema exibe um formulário de edição com os seguintes campos:
  - Professor
  - Disciplina
  - Bloco
  - Sala
  - Dia da Semana
  - Horário

- **Ação**: Maria altera o horário da alocação de 08:00 - 09:00 para 09:00 - 10:00.
- **Ação**: Ela clica no botão "Salvar" para confirmar as alterações.
- **Resultado**: O sistema salva as alterações e redireciona Maria de volta à "Lista de Alocações", agora com a alocação atualizada.

---

#### 4. Excluir uma alocação
- **Usuário**: Maria deseja excluir uma alocação.
- **Ação**: Na "Lista de Alocações", ela clica no botão "Excluir" ao lado de uma alocação.
- **Resultado**: O sistema exibe a tela "Confirmação de Exclusão", com o seguinte aviso:

Você tem certeza que deseja excluir a alocação de: José Campos - Inglês I - A - 10 - Segunda-feira - 08:00 - 09:00? Esta ação não é reversível!  

Abaixo do aviso, dois botões são exibidos: "Confirmar Exclusão" e "Cancelar e Voltar para a Lista de Alocações".

- **Ação**: Maria decide confirmar a exclusão e clica no botão "Confirmar Exclusão".
- **Resultado**: O sistema exclui a alocação e retorna Maria à "Lista de Alocações", agora sem a alocação de José Campos.

---

### Impacto das funcionalidades:
- **Gestão Eficiente**: A possibilidade de visualizar, editar e excluir alocações diretamente da lista permite um gerenciamento mais ágil e preciso das informações.
- **Confirmação de Exclusão**: O sistema garante segurança nas operações, solicitando uma confirmação antes de excluir qualquer alocação, evitando exclusões acidentais.
- **Atualização Imediata**: As alterações feitas no sistema são refletidas em tempo real, garantindo que os dados estejam sempre atualizados para os administradores e usuários.

### Contribuição para o objetivo geral:
Essas funcionalidades são essenciais para o controle e manutenção das alocações no sistema, permitindo que a UFAM organize eficientemente o uso de espaços e horários de professores e disciplinas. A confirmação de exclusão protege contra erros, enquanto a edição direta facilita ajustes rápidos nas alocações.

## Cenário 8: Excluir, editar e visualizar detalhes de uma disciplina

### Descrição do fluxo de trabalho:
O administrador deseja gerenciar as disciplinas cadastradas no sistema. Ele decide visualizar os detalhes de uma disciplina, editar outra e excluir uma terceira, seguindo o mesmo fluxo de navegação descrito anteriormente.

### Fluxo detalhado:

#### 1. Acesso à lista de disciplinas
- **Usuário**: Maria, administradora do sistema.
- **Ação**: No painel administrativo, Maria clica no botão "Disciplinas" no menu principal.
- **Resultado**: O sistema exibe a "Lista de Disciplinas", onde cada linha contém informações como:
  - Nome: Inglês I
  - Código: ING101
  - Curso: Letras
  - Modo de Ensino: Teórico
  
  Ao lado de cada linha, há três botões: "Detalhes", "Editar" e "Excluir".

---

#### 2. Visualizar detalhes de uma disciplina
- **Ação**: Maria clica no botão "Detalhes" ao lado da disciplina "Inglês I".
- **Resultado**: O sistema exibe a tela "Detalhes da Disciplina", mostrando:
  - Nome: Inglês I
  - Código: ING101
  - Curso: Letras
  - Modo de Ensino: Teórico
  
  Na parte inferior da tela, há dois botões: "Editar" e "Excluir".
- **Ação**: Maria retorna à "Lista de Disciplinas" clicando no botão "Voltar".

---

#### 3. Editar uma disciplina
- **Ação**: Maria clica no botão "Editar" ao lado da disciplina "Inglês I".
- **Resultado**: O sistema exibe um formulário de edição com os seguintes campos:
  - Nome
  - Código
  - Curso
  - Modo de Ensino

- **Ação**: Maria altera o código da disciplina para "ING102" e clica em "Salvar".
- **Resultado**: O sistema salva a alteração e redireciona Maria à "Lista de Disciplinas", atualizando a disciplina com o novo código.

---

#### 4. Excluir uma disciplina
- **Ação**: Maria clica no botão "Excluir" ao lado da disciplina "Inglês I".
- **Resultado**: O sistema exibe a tela "Confirmação de Exclusão" com o seguinte aviso:

Você tem certeza que deseja excluir a disciplina: Inglês I - ING101? Esta ação não é reversível!

Abaixo do aviso, dois botões: "Confirmar Exclusão" e "Cancelar e Voltar para a Lista de Disciplinas".

- **Ação**: Maria confirma a exclusão clicando em "Confirmar Exclusão".
- **Resultado**: A disciplina é excluída, e Maria é redirecionada à "Lista de Disciplinas", agora sem a disciplina "Inglês I".

---

## Cenário 9: Excluir, editar e visualizar detalhes de uma sala/laboratório

### Descrição do fluxo de trabalho:
O administrador deseja gerenciar as salas e laboratórios cadastrados no sistema. Ele decide visualizar os detalhes de uma sala, editar outra e excluir uma terceira.

### Fluxo detalhado:

#### 1. Acesso à lista de salas/laboratórios
- **Usuário**: João, administrador do sistema.
- **Ação**: No painel administrativo, João clica no botão "Salas/Labs" no menu principal.
- **Resultado**: O sistema exibe a "Lista de Espaços Físicos", com as seguintes informações:
- Bloco: A
- Andar: 1
- Número: 101
- Tipo: Sala de Aula

Ao lado de cada linha, há três botões: "Detalhes", "Editar" e "Excluir".

---

#### 2. Visualizar detalhes de uma sala
- **Ação**: João clica no botão "Detalhes" ao lado da sala "Bloco A - 101".
- **Resultado**: O sistema exibe a tela "Detalhes do Espaço Físico", mostrando:
- Bloco: A
- Andar: 1
- Número: 101
- Tipo: Sala de Aula

Dois botões aparecem na parte inferior da tela: "Editar" e "Excluir".
- **Ação**: João retorna à "Lista de Espaços Físicos" clicando em "Voltar".

---

#### 3. Editar uma sala
- **Ação**: João clica no botão "Editar" ao lado da sala "Bloco A - 101".
- **Resultado**: O sistema exibe um formulário de edição com os seguintes campos:
- Bloco
- Andar
- Número
- Tipo (Sala de Aula, Laboratório, etc.)

- **Ação**: João altera o número da sala de "101" para "102" e clica em "Salvar".
- **Resultado**: O sistema salva a alteração e redireciona João à "Lista de Espaços Físicos", atualizando a sala com o novo número.

---

#### 4. Excluir uma sala
- **Ação**: João clica no botão "Excluir" ao lado da sala "Bloco A - 101".
- **Resultado**: O sistema exibe a tela "Confirmação de Exclusão" com o seguinte aviso:

Você tem certeza que deseja excluir a sala: Bloco A - 101? Esta ação não é reversível!

Abaixo do aviso, dois botões: "Confirmar Exclusão" e "Cancelar e Voltar para a Lista de Espaços Físicos".

- **Ação**: João confirma a exclusão clicando em "Confirmar Exclusão".
- **Resultado**: A sala é excluída, e João é redirecionado à "Lista de Espaços Físicos", agora sem a sala "Bloco A - 101".

---

## Cenário 10: Excluir, editar e visualizar detalhes de um professor

### Descrição do fluxo de trabalho:
O administrador deseja gerenciar os professores cadastrados no sistema. Ele decide visualizar os detalhes de um professor, editar outro e excluir um terceiro.

### Fluxo detalhado:

#### 1. Acesso à lista de professores
- **Usuário**: Ana, administradora do sistema.
- **Ação**: No painel administrativo, Ana clica no botão "Professores" no menu principal.
- **Resultado**: O sistema exibe a "Lista de Professores", com as seguintes informações:
- Nome: José Campos
- SIAPE: 1234567

Ao lado de cada linha, há três botões: "Detalhes", "Editar" e "Excluir".

---

#### 2. Visualizar detalhes de um professor
- **Ação**: Ana clica no botão "Detalhes" ao lado do professor "José Campos".
- **Resultado**: O sistema exibe a tela "Detalhes do Professor", mostrando:
- Nome: José Campos
- SIAPE: 1234567

Dois botões aparecem na parte inferior da tela: "Editar" e "Excluir".
- **Ação**: Ana retorna à "Lista de Professores" clicando em "Voltar".

---

#### 3. Editar um professor
- **Ação**: Ana clica no botão "Editar" ao lado do professor "José Campos".
- **Resultado**: O sistema exibe um formulário de edição com os seguintes campos:
- Nome
- SIAPE

- **Ação**: Ana altera o nome do professor de "José Campos" para "José Silva" e clica em "Salvar".
- **Resultado**: O sistema salva a alteração e redireciona Ana à "Lista de Professores", atualizando o nome do professor.

---

#### 4. Excluir um professor
- **Ação**: Ana clica no botão "Excluir" ao lado do professor "José Campos".
- **Resultado**: O sistema exibe a tela "Confirmação de Exclusão" com o seguinte aviso:

Você tem certeza que deseja excluir o professor: José Campos - SIAPE 1234567? Esta ação não é reversível!

Abaixo do aviso, dois botões: "Confirmar Exclusão" e "Cancelar e Voltar para a Lista de Professores".

- **Ação**: Ana confirma a exclusão clicando em "Confirmar Exclusão".
- **Resultado**: O professor é excluído, e Ana é redirecionada à "Lista de Professores", agora sem o professor "José Campos".
