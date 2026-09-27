# 🌱 Branch da Academia

> Projeto colaborativo desenvolvido pelos alunos da **Academia do Programador**.

## 🐦 Twitter da Academia

Plataforma inspirada no Twitter/X, desenvolvida de forma colaborativa para colocar em prática os conhecimentos adquiridos durante a formação.

### ATENCAO ⚠️
Os padrões descritos abaixo devem ser rigorosamente seguidos para garantir
o desenvolvimento mais harmônico possível entre a equipe.
O projeto é grande, são muitas pessoas trabalhando, se não tivermos um padrão, tornará o desenvolvimento mais difícil do que ele originalmente já é.

### 🚧 Status

**Em desenvolvimento**

Neste primeiro momento, o projeto será desenvolvido exclusivamente como **Backend / API**, utilizando o **Swagger** para testes e validação dos endpoints.

Com o avanço das aulas de **Angular**, o Frontend será desenvolvido e integrado à aplicação.

---

## 🛠️ Tecnologias

- C#
- .NET
- ASP.NET Core
- Entity Framework Core
- MediatR
- FluentResults
- Swagger
- SQLite
- PostgreSQL _(futuro)_

---

# 📋 Padrões de Desenvolvimento

Como o projeto possui diversos colaboradores, seguir um padrão é essencial para manter o código organizado e facilitar a integração entre as equipes.

## 🌿 Branches

As alterações devem ser desenvolvidas em branches próprias e integradas à `main` através de **Pull Requests**.

### Padrão de nomenclatura

| Tipo     | Padrão                       | Exemplo                    |
| -------- | ---------------------------- | -------------------------- |
| Feature  | `ModuloXX/Feature`           | `Modulo01/CadastroUsuario` |
| Fix      | `Fix/NomeDoBug`              | `Fix/ErroAutenticacao`     |
| Refactor | `Refactor/NomeDaRefatoracao` | `Refactor/RepositorioBase` |
| Test     | `Test/NomeDaFeatureTestada`  | `Test/CadastroUsuario`     |
| Docs     | `Docs/OqueFoiDocumentado`    | `Docs/Readme`              |

### ⚠️ Alterações fora do escopo

Se durante o desenvolvimento de uma feature ou correção for identificada uma alteração necessária em **outros arquivos ou partes do projeto**, deve-se:

1. Sinalizar a alteração no grupo;
2. Criar uma **nova branch** exclusivamente para essa alteração;
3. Realizar o Pull Request separadamente.

Isso reduz conflitos e permite que outros desenvolvedores aproveitem a correção sem depender da sua feature.

---

# 🧪 Testes

Todo código desenvolvido deve possuir testes que garantam seu comportamento.

Sempre que aplicável, devem ser testados:

- Entidades;
- Métodos;
- Handlers;
- Regras de negócio;
- Repositórios;
- Endpoints.

Os testes devem seguir o padrão **AAA**:

```text
Arrange → Act → Assert
```
