
# Sistema de Gestão de Chamados de Suporte Técnico

Este sistema foi desenvolvido para gerenciar chamados de suporte técnico em diferentes níveis de permissão. Ele contempla funcionalidades específicas para usuários comuns, técnicos de suporte, gestores e administradores, além de um modelo de dados bem estruturado.

---

## 📌 Diagrama de Casos de Uso

O sistema possui funcionalidades distribuídas de acordo com o nível de acesso:

### Níveis de Usuário:
- **Usuário Comum**: pode registrar chamados, acompanhar o status e cancelar quando necessário.
- **Técnico de Suporte**: pode visualizar chamados atribuídos, iniciar atendimento, registrar soluções e encerrar chamados.
- **Gestor de Suporte**: visualiza todos os chamados, pode reatribuir tarefas e acompanhar indicadores.
- **Administrador do Sistema**: realiza o controle de usuários, permissões e configurações gerais.

![Casos de Uso](./001-%20Diagrama%20de%20Casos%20de%20Uso%20por%20N%C3%ADvel%20de%20Usu%C3%A1rio.png)

---

## 🔁 Fluxos de Uso

### 1. Usuário Comum

- Abertura de chamado
- Acompanhamento do status
- Cancelamento do chamado

![Fluxo Usuário Comum](./002-%20Fluxo%20Usu%C3%A1rio%20Comum.png)

### 2. Técnico de Suporte

- Visualização de chamados pendentes
- Aceitação e execução do chamado
- Registro de atendimento e encerramento

![Fluxo Técnico](./003-%20Fluxo%20T%C3%A9cnico%20de%20Suporte.png)

### 3. Gestor de Suporte

- Acompanhamento geral dos chamados
- Reatribuição de chamados
- Monitoramento de desempenho da equipe

![Fluxo Gestor](./004-%20Fluxo%20Gestor%20de%20Suporte.png)

### 4. Administrador do Sistema

- Gerenciamento de usuários e permissões
- Controle de parâmetros do sistema

![Fluxo Administrador](./005-%20Fluxo%20Administrador%20do%20Sistema.png)

---

## 🧩 Modelo Conceitual

O modelo conceitual detalhado representa as principais entidades do sistema e seus relacionamentos. Ele foi desenvolvido para garantir integridade e escalabilidade.

![Modelo Conceitual](./006-%20Modelo%20conceitual%20detalhado.png)

---

## 📁 Estrutura do Projeto

```
📦 projeto-suporte
├── 📄 README.md
├── 📁 imagens/
│   ├── 001- Diagrama de Casos de Uso por Nível de Usuário.png
│   ├── 002- Fluxo Usuário Comum.png
│   ├── 003- Fluxo Técnico de Suporte.png
│   ├── 004- Fluxo Gestor de Suporte.png
│   ├── 005- Fluxo Administrador do Sistema.png
│   └── 006- Modelo conceitual detalhado.png
```

---

## 🛠 Tecnologias Sugeridas

- **Back-end**: Python (Flask) ou Node.js
- **Banco de Dados**: SQLite ou MySQL
- **Front-end**: HTML, CSS, JavaScript (pode ser usado Bootstrap)
- **Controle de Acesso**: Baseado em níveis de permissão

---

## 📈 Possíveis Melhorias Futuras

- Dashboard com gráficos de chamados por setor ou técnico
- Notificações por e-mail ou sistema interno
- Integração com autenticação corporativa (ex: Microsoft ou Google)

---

## 📃 Licença

Este projeto pode ser utilizado, modificado e distribuído livremente para fins educacionais e institucionais.
