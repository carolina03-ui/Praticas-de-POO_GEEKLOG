Conceitos de POO utilizados no projeto Geeklog

Este documento descreve onde e como os conceitos de Programação Orientada a Objetos (POO) são aplicados no projeto Geeklog.

✅ Arquivos que utilizam POO

1. games/apps.py

Classe: GamesConfig

Conceito: Herança

Descrição: A classe GamesConfig herda de AppConfig, que é usada para configurar a aplicação Django chamada games.

2. games/models.py

Classe: Review

Conceitos:

Herança (herda de models.Model)

Encapsulamento (uso de atributos e métodos)

Representação (_str_)

Descrição: A classe Review representa um modelo de dados (ORM) para armazenar avaliações de jogos feitas pelos usuários. Ela define atributos como user, game_id, texto e created_at, e um método especial _str_ para exibir representações textuais da instância.

3. games/migrations/0001_initial.py

Classe: Migration

Conceitos:

Herança (de migrations.Migration)

Descrição: Script gerado automaticamente pelo Django. Define uma classe que representa a primeira migração do banco de dados com a criação da tabela Review.

📁 Localização dos arquivos

Caminho Relativo

Arquivo

Geeklog-main/games/apps.py

Configuração da app

Geeklog-main/games/models.py

Modelo de dados POO

Geeklog-main/games/migrations/0001_initial.py

Migração Django

Se você quiser expandir o uso de POO no projeto (por exemplo, adicionando serviços, classes de domínio ou lógica de negócio separada), posso te ajudar com isso também!
