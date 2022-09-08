## Entendendo Atenticação com Devise

- links Uteis - Documentações

[rubygems.org devise](https://rubygems.org/gems/devise/versions/4.2.0?locale=pt-BR)
[github devise](https://github.com/heartcombo/devise)

- Adicione ao Gemfile

```
gem 'devise'

```

- Rode o bundle

```
bundle install
```

- Gerar o devise

```
rails generate devise:install

```
- Configurar a URL padrão do action mailer no ambiente de desenvolvimento
  - acesse config/environments/development.rb

```
  config.action_mailer.default_url_options = { host: 'localhost', port: 3000 }
```

- Gerar as configurações do devise para a empresa

```
  rails generate devise Company
  rails db:migrate 
```

- Gerar as views

```
  rails g devise:views
```

Start a aplicação
Faça um layout separado para o devise na tela de login

