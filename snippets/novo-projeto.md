## Ininicar um novo projeto com rails

- Web app para modelagem de dados

[dbdiagram.io](https://dbdiagram.io/home)

- Iniciando projeto na versão 6.1

```
  rails _6.1_ new app_rails --database=mysql
```

- Gerando os scaffolds (create, update e delete)

```
  rails g scaffold Company name:string description:text --no-stylesheets
  rails g scaffold Vacancy title location description:text requirements salary available:boolean company:references --noe-stylesheets
  rails g scaffold Applicant name vacancy:references --no-stylesheets
```

- Com o scaffold já gerado, vamos migrar as tabelas para o banco de dados

```
  rails db:migrate
```
