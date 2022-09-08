## Use Active Storage variant

- Adicione a gem

> gem 'image_processing', '~> 1.2'

- Criar configuração do AS dentro do propeto

> rails active_storage:intall

- Execute a migration

> rails db:migrate 

- Faça o relacionamento no model

> has_one_attached 
