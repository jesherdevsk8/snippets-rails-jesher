## Adicionar o bootstrap

### adicionar com yarn bootstrap versões: 
├─ @popperjs/core@2.11.6
└─ bootstrap@5.2.1 

```
  yarn add bootstrap@5.2.1 @popperjs/core@2.11.6
  yarn add @fortawesome/fontawesome-free
```

- Acesse /app/assets/stylesheets e renomeie aplication.css para aplication.scss
  - Deixe o arquivo em branco e adicione

```
  @import "bootstrap/scss/bootstrap";
  @import "@fortawesome/fontawesome-free/css/all.min.css";
```
quando instalado com yarn add, os arquivos são encontrados em node_modules

Faça um layout separado para o devise na tela de login
em /app/views/layouts

---

- Usar paginação com kaminari

```
gem 'kaminari'
```

- Gerar views

```
rails g kaminari:views bootstrap4
``` 
