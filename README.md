# 📌 Sistema de Gerenciamento de Tarefas Ágil

## 📖 Descrição do Projeto

Este projeto consiste no desenvolvimento de um sistema simples de gerenciamento de tarefas, com o objetivo de aplicar conceitos de Engenharia de Software e metodologias ágeis utilizando o GitHub.

O sistema permite que usuários criem, visualizem, atualizem e removam tarefas, além de acompanhar o progresso das atividades por meio de um fluxo organizado.

---

## 🚀 Funcionalidades

* Criar tarefas
* Listar tarefas
* Atualizar status (pendente/concluída)
* Remover tarefas
* Organização das tarefas em fluxo ágil (Kanban)

---

## 🛠️ Tecnologias Utilizadas

* Python
* GitHub
* GitHub Actions (Integração Contínua)
* PyTest (Testes automatizados)

---

## 📂 Estrutura do Projeto

```
/src
  └── main.py
/tests
  └── test_tarefas.py
/docs
README.md
.github/
  └── workflows/
        └── test.yml
```

---

## ⚙️ Pré-requisitos

Antes de executar o projeto, você precisa ter instalado:

* Python 3.x
* Git
* Conta no GitHub

---

## ▶️ Como Executar o Projeto

1. Clone o repositório:

```
git clone https://github.com/seu-usuario/sistema-tarefas-agil.git
```

2. Acesse a pasta do projeto:

```
cd sistema-tarefas-agil
```

3. Execute o sistema:

```
python src/main.py
```

---

## 🧪 Testes Automatizados

Os testes foram implementados utilizando **PyTest**, com o objetivo de garantir que as funcionalidades principais funcionem corretamente.

Para executar os testes manualmente:

```
pytest
```

Os testes validam:

* Criação de tarefas
* Estrutura de dados
* Funcionamento básico do sistema

---

## 🔄 GitHub Actions (Integração Contínua)

O projeto utiliza o GitHub Actions para automatizar a execução dos testes a cada alteração no repositório.

Funcionalidades do pipeline:

* Executa automaticamente ao realizar um *push*
* Instala dependências
* Roda os testes com PyTest
* Garante a qualidade do código

Arquivo de configuração:

```
.github/workflows/test.yml
```

---

## 🔁 Metodologia Ágil Utilizada

Foi utilizada a metodologia **Kanban**, organizada em colunas:

* A Fazer
* Em Progresso
* Concluído

Isso permite acompanhar o fluxo de desenvolvimento e melhorar a produtividade.

---

## 🔄 Gestão de Mudanças

Durante o desenvolvimento, foi adicionada a funcionalidade de **marcar tarefas como concluídas**, com o objetivo de melhorar o controle do progresso das atividades.

Essa alteração foi registrada:

* No quadro Kanban
* No histórico de commits
* Neste documento

---

## 📌 Considerações Finais

Este projeto demonstra a aplicação prática de conceitos de Engenharia de Software, incluindo versionamento, desenvolvimento ágil, testes automatizados e integração contínua, utilizando ferramentas amplamente empregadas no mercado.

