# Projeto Aluno Online

## Descrição
Projeto desenvolvido em Java com Spring Boot para gerenciamento de alunos, professores, disciplinas e matrículas.

O sistema permite realizar operações CRUD completas e gerenciamento de matrícula de alunos.

---

## Tecnologias Utilizadas

- Java
- Spring Boot
- Maven
- PostgreSQL
- Insomnia
- DBeaver
- Lambok

---

## Estrutura do Projeto

O projeto segue arquitetura em camadas:

- Controller → recebe as requisições
- Service → regras de negócio
- Repository → acesso ao banco de dados
- Entity → entidades/tabelas

---

## Funcionalidades

### CRUD de Aluno
- Criar aluno
- Listar alunos
- Atualizar aluno
- Deletar aluno

### CRUD de Professor
- Criar professor
- Listar professores
- Atualizar professor
- Deletar professor

### CRUD de Disciplina
- Criar disciplina
- Listar disciplinas
- Atualizar disciplina
- Deletar disciplina

### Matrícula de Aluno
- Matricular aluno
- Listar matrículas
- Outras funcionalidades implementadas

---


## Endpoints Testados no Insomnia

### Aluno
- POST /alunos
- GET /alunos
- PUT /alunos/{id}
- DELETE /alunos/{id}

### Professor
- POST /professores
- GET /professores
- PUT /professores/{id}
- DELETE /professores/{id}

### Disciplina
- POST /disciplinas
- GET /disciplinas
- PUT /disciplinas/{id}
- DELETE /disciplinas/{id}

---

## Testes do Insomnia

ALUN0(POST)
<img width="736" height="344" alt="image" src="https://github.com/user-attachments/assets/803a58e9-fa90-4aaf-b65d-13a153ed478c" />

LISTAR(GET)
<img width="747" height="701" alt="image" src="https://github.com/user-attachments/assets/4acfc9ba-4318-4aad-b2a3-6fc4aae74a83" />

EDITAR(PUT)
<img width="766" height="296" alt="image" src="https://github.com/user-attachments/assets/0533740b-9bcd-4077-b264-87c429d83ce8" />

BUSCAR ALUNO POR ID(GET)
<img width="753" height="324" alt="image" src="https://github.com/user-attachments/assets/f72f0185-ac3d-4ac0-becf-a12819605b9a" />


## Testes do DBeaver

TABELA ALUNO
<img width="666" height="358" alt="image" src="https://github.com/user-attachments/assets/645a6ae6-faee-4188-8582-1b7eee826256" />

TABELA PROFESSOR
<img width="674" height="367" alt="image" src="https://github.com/user-attachments/assets/412f36ae-00a3-42f4-bec0-e4fbde74cdc7" />


---

## Como Executar o Projeto

1. Clonar o repositório
2. Abrir no IntelliJ
3. Configurar banco PostgreSQL
4. Executar a aplicação
5. Testar endpoints no Insomnia

---

## Autor

José Maria Ferreira de Araújo
