## 🧪 ID: 001

### ✅ Nome do Teste:
Cadastro com dados válidos

### 🎯 Descrição:
Verificar se o sistema permite cadastrar um novo usuário com dados válidos.

### 🧰 Pré-requisitos:
- Usuário deve estar na tela de cadastro
- Banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de cadastro
2. Preencher os campos obrigatórios com dados válidos
3. Clicar no botão "Cadastrar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste        |
|------------------|------------------------|
| Nome             | João da Silva          |
| Email            | joao@email.com         |
| Senha            | Senha123               |
| Confirmar Senha  | Senha123               |

### 💡 Resultado Esperado:
Usuário deve ser cadastrado e redirecionado para a página do seu email para confirmar com um link do webSite com a confirmação inicial com a mensagem "Cadastro realizado com sucesso" logo após ao clicar no link do e-mail enviado. 

### 📌 Resultado Obtido:
Usuário foi cadastrado com sucesso e redirecionado de volta ao site corretamente.

### ✅ Status do Teste:
- [x] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 002

### ✅ Nome do Teste:
Cadastro com senha e confirmação diferentes

### 🎯 Descrição:
Verificar se o sistema impede o cadastro quando senha e confirmação de senha são diferentes.

### 🧰 Pré-requisitos:
- Usuário deve estar na tela de cadastro

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de cadastro
2. Preencher os campos obrigatórios com senhas diferentes
3. Clicar no botão "Cadastrar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste        |
|------------------|------------------------|
| Nome             | Maria Oliveira         |
| Email            | maria@email.com        |
| Senha            | Senha123               |
| Confirmar Senha  | Senha321               |

### 💡 Resultado Esperado:
Sistema deve exibir uma mensagem de erro informando que as senhas não coincidem.

### 📌 Resultado Obtido:
Sistema exibiu mensagem "As senhas não coincidem".

### ✅ Status do Teste:
- [ ] Aprovado
- [x] Reprovado

---


## 🧪 ID: 003

### ✅ Nome do Teste:
Tentativa de cadastro digitando o e-mail sem a senha

### 🎯 Descrição:
Usuário digita o e-mail completo e clica no botão de "Cadastrar"

### 🧰 Pré-requisitos:
- Usuário em processo de cadastro

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de login
2. Digitar o nome completo
3. clicar no botão "Cadastrar"

   
### 🧾 Dados de Entrada:
| Campo   | Valor de Teste        |
|---------|------------------------|
| Email   | joao@email.com         |
| Senha   |                        |

### 💡 Resultado Esperado:
É gerado uma tela de mensagem avisando da falta de informação no campo de "Senha" no momento do cadastro 


### 📌 Resultado Obtido:
Usuário é redirecionado para o campo de "Senha" para peenchimento correto da informação para concluir seu processo de cadastro.

### ✅ Status do Teste:
- [ ] Aprovado
- [x] Reprovado

---


## 🧪 ID: 004

### ✅ Nome do Teste:
Login com credenciais válidas

### 🎯 Descrição:
Verificar se o usuário consegue fazer login com email e senha válidos.

### 🧰 Pré-requisitos:
- Conta de usuário previamente cadastrada

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de login
2. Preencher os campos de email e senha com dados válidos
3. Clicar no botão "Entrar"

### 🧾 Dados de Entrada:
| Campo   | Valor de Teste        |
|---------|------------------------|
| Email   | joao@email.com         |
| Senha   | Senha123               |

### 💡 Resultado Esperado:
Usuário deve ser autenticado e redirecionado para a dashboard com a mensagem "Login realizado com sucesso".

### 📌 Resultado Obtido:
Usuário autenticado com sucesso e redirecionado.

### ✅ Status do Teste:
- [x] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 005

### ✅ Nome do Teste:
Login com senha incorreta

### 🎯 Descrição:
Verificar se o sistema bloqueia login com senha incorreta.

### 🧰 Pré-requisitos:
- Conta de usuário previamente cadastrada

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de login
2. Informar um email válido e uma senha incorreta
3. Clicar no botão "Entrar"

### 🧾 Dados de Entrada:
| Campo   | Valor de Teste        |
|---------|------------------------|
| Email   | joao@email.com         |
| Senha   | senhaErrada            |

### 💡 Resultado Esperado:
Sistema deve exibir mensagem "Email ou senha inválidos".

### 📌 Resultado Obtido:
Mensagem de erro apresentada corretamente.

### ✅ Status do Teste:
- [ ] Aprovado
- [x] Reprovado

---

## 🧪 ID: 006

### ✅ Nome do Teste:
Criar plano de gastos com dados válidos

### 🎯 Descrição:
Verificar se o usuário pode criar um novo plano de gastos informando nome, descrição e período.

### 🧰 Pré-requisitos:
- Usuário logado
- Acesso à tela de planos

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de planos de gastos
2. Clicar em "Novo Plano"
3. Preencher os campos obrigatórios
4. Clicar em "Salvar"

### 🧾 Dados de Entrada:
| Campo      | Valor de Teste         |
|------------|-------------------------|
| Nome       | Plano Mensal Junho      |
| Descrição  | Controle de gastos mensais |
| Período    | 01/06/2025 - 30/06/2025 |

### 💡 Resultado Esperado:
Plano deve ser criado com sucesso e exibido na lista de planos.

### 📌 Resultado Obtido:
Plano criado e listado corretamente.

### ✅ Status do Teste:
- [x] Aprovado
- [ ] Reprovado

---
## 🧪 ID: 007

### ✅ Nome do Teste:
Editar plano de gastos com dados válidos

### 🎯 Descrição:
Verificar se o usuário pode editar um plano de gastos informando nome, descrição e período.

### 🧰 Pré-requisitos:
- Usuário logado
- Acesso à tela de planos
- O plano estar selecionado

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de planos de gastos
2. Clicar no plano requirido
3. Cliclar em editar plano
4. Preencher os campos obrigatórios
5. Clicar em "Salvar"

### 🧾 Dados de Entrada:
| Campo      | Valor de Teste         |
|------------|-------------------------|
| Nome       | Plano Mensal Junho      |
| Descrição  | Controle de gastos mensais |
| Período    | 01/06/2025 - 30/06/2025 |

### 💡 Resultado Esperado:
O plano deve ser atualizado com sucesso, mostrando uma mensagem de sucesso ao usuario. Depois o plano deve ser reajustado a lista.

### 📌 Resultado Obtido:
Plano editado e listado corretamente.

### ✅ Status do Teste:
- [x] Aprovado
- [ ] Reprovado

---
## 🧪 ID: 008

### ✅ Nome do Teste:
Deletar plano de gastos

### 🎯 Descrição:
Verificar se o usuário pode deletar um plano de gastos.
obs: todas as despesas relaciocionadas serão deletadas juntas

### 🧰 Pré-requisitos:
- Usuário logado
- Acesso à tela de planos
- O plano estar selecionado

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de planos de gastos
2. Selecionar plano requirido
3. Clicar em "Deletar"

### 🧾 Dados de Entrada:
| Campo      | Valor de Teste         |
|------------|-------------------------|
| Nome       | Plano Mensal Junho      |
| Descrição  | Controle de gastos mensais |
| Período    | 01/06/2025 - 30/06/2025 |

### 💡 Resultado Esperado:
Plano deve ser criado com sucesso e exibido na lista de planos.

### 📌 Resultado Obtido:
Plano criado e listado corretamente.

### ✅ Status do Teste:
- [x] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 009

### ✅ Nome do Teste:
Criar categoria personalizada em plano existente

### 🎯 Descrição:
Verificar se o usuário pode criar uma nova categoria de despesa dentro de um plano de gastos.

### 🧰 Pré-requisitos:
- Usuário logado
- Plano de gastos criado

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar o plano de gastos existente
2. Selecionar “Adicionar Categoria”
3. Preencher os campos obrigatórios
4. Clicar em "Salvar"

### 🧾 Dados de Entrada:
| Campo    | Valor de Teste        |
|----------|------------------------|
| Nome     | Alimentação            |
| Descrição | Despesas com comida    |

### 💡 Resultado Esperado:
Categoria deve ser adicionada ao plano com sucesso.

### 📌 Resultado Obtido:
Categoria adicionada corretamente.

### ✅ Status do Teste:
- [x] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 010

### ✅ Nome do Teste:
Editar categoria personalizada em plano existente

### 🎯 Descrição:
Verificar se o usuário pode editar uma categoria de despesa já cadastrada em um plano de gastos.

### 🧰 Pré-requisitos:
- Usuário logado
- Plano de gastos criado
- Categoria existente

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar o plano de gastos existente
2. Selecionar a categoria a ser editada
3. Clicar em "Editar Categoria"
4. Alterar os dados desejados
5. Clicar em "Salvar"

### 🧾 Dados de Entrada:
| Campo     | Valor de Teste              |
|-----------|------------------------------|
| Nome      | Alimentação e Bebidas        |
| Descrição | Despesas com comida e drinks |

### 💡 Resultado Esperado:
Categoria deve ser atualizada no plano com sucesso.

### 📌 Resultado Obtido:
Categoria editada corretamente.

### ✅ Status do Teste:
- [x] Aprovado
- [ ] Reprovado


## 🧪 ID: 011

### ✅ Nome do Teste:
Deletar categoria personalizada de plano existente

### 🎯 Descrição:
Verificar se o usuário pode excluir uma categoria de despesa de um plano de gastos.

### 🧰 Pré-requisitos:
- Usuário logado
- Plano de gastos criado
- Categoria existente

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar o plano de gastos existente
2. Selecionar a categoria a ser removida
3. Clicar em "Excluir Categoria"
4. Confirmar a exclusão

### 🧾 Dados de Entrada:
| Campo | Valor de Teste |
|-------|-----------------|
| Nome  | Alimentação     |

### 💡 Resultado Esperado:
Categoria deve ser removida do plano com sucesso.

### 📌 Resultado Obtido:
Categoria excluída corretamente.

### ✅ Status do Teste:
- [x] Aprovado
- [ ] Reprovado



## 🧪 ID: 012

### ✅ Nome do Teste:
Cadastrar despesa associada a plano

### 🎯 Descrição:
Verificar se o usuário consegue cadastrar uma despesa vinculada a um plano de gastos e categoria.

### 🧰 Pré-requisitos:
- Usuário logado
- Plano de gastos e categoria existentes

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar o plano de gastos
2. Selecionar uma categoria
3. Clicar em "Adicionar Despesa"
4. Preencher os dados da despesa
5. Clicar em "Salvar"

### 🧾 Dados de Entrada:
| Campo        | Valor de Teste        |
|--------------|------------------------|
| Nome         | Supermercado           |
| Valor        | 150.00                 |
| Data         | 05/06/2025             |
| Categoria    | Alimentação            |

### 💡 Resultado Esperado:
Despesa deve ser cadastrada corretamente e listada na categoria.

### 📌 Resultado Obtido:
Despesa registrada e exibida corretamente.

### ✅ Status do Teste:
- [x] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 013

### ✅ Nome do Teste:
Editar despesa associada a plano

### 🎯 Descrição:
Verificar se o usuário consegue editar uma despesa já cadastrada em um plano de gastos e categoria.

### 🧰 Pré-requisitos:
- Usuário logado
- Plano de gastos, categoria e despesa existentes

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar o plano de gastos
2. Selecionar uma categoria
3. Localizar e selecionar a despesa desejada
4. Clicar em "Editar Despesa"
5. Alterar os dados da despesa
6. Clicar em "Salvar"

### 🧾 Dados de Entrada:
| Campo        | Valor de Teste        |
|--------------|------------------------|
| Nome         | Supermercado Atacado   |
| Valor        | 200.00                 |
| Data         | 06/06/2025             |
| Categoria    | Alimentação            |

### 💡 Resultado Esperado:
Despesa deve ser atualizada corretamente e refletida na categoria correspondente.

### 📌 Resultado Obtido:
Despesa editada e exibida corretamente.

### ✅ Status do Teste:
- [x] Aprovado
- [ ] Reprovado

## 🧪 ID: 014

### ✅ Nome do Teste:
Deletar despesa associada a plano

### 🎯 Descrição:
Verificar se o usuário consegue deletar uma despesa vinculada a um plano de gastos e categoria.

### 🧰 Pré-requisitos:
- Usuário logado
- Plano de gastos, categoria e despesa existentes

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar o plano de gastos
2. Selecionar uma categoria
3. Localizar a despesa
4. Clicar em "Excluir Despesa"
5. Confirmar a exclusão

### 🧾 Dados de Entrada:
| Campo        | Valor de Teste   |
|--------------|-------------------|
| Nome         | Supermercado      |
| Categoria    | Alimentação       |

### 💡 Resultado Esperado:
Despesa deve ser removida corretamente da categoria.

### 📌 Resultado Obtido:
Despesa excluída corretamente.

### ✅ Status do Teste:
- [x] Aprovado
- [ ] Reprovado

