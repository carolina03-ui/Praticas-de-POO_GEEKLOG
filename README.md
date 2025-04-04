# 🕹️ Geeklog - Projeto Django com POO

Este documento descreve onde e como os conceitos de **Programação Orientada a Objetos (POO)** são aplicados no projeto **Geeklog**, uma aplicação Django que integra com a API do IGDB para buscar e exibir informações de jogos.

---

## ✅ Conceitos de POO utilizados no projeto

### 1. `games/apps.py`
- **Classe:** `GamesConfig`
- **Conceito:** Herança
- **Descrição:**  
  A classe `GamesConfig` herda de `AppConfig`, sendo usada para configurar a aplicação Django chamada `games`.

---

### 2. `games/models.py`
- **Classe:** `Review`
- **Conceitos Utilizados:**
  - **Herança:** herda de `models.Model`
  - **Encapsulamento:** uso de atributos e métodos
  - **Representação:** método especial `__str__`
- **Descrição:**  
  Representa um modelo de dados (ORM) para armazenar avaliações de jogos feitas pelos usuários.  
  Define atributos como:
  - `user`
  - `game_id`
  - `texto`
  - `created_at`  
  Além disso, implementa o método `__str__` para facilitar a leitura da instância.

---

### 3. `games/migrations/0001_initial.py`
- **Classe:** `Migration`
- **Conceito:** Herança (de `migrations.Migration`)
- **Descrição:**  
  Script gerado automaticamente pelo Django. Define a primeira migração do banco de dados, criando a tabela `Review`.

---

## 📁 Localização dos Arquivos

| Caminho Relativo                                | Descrição                         |
|--------------------------------------------------|-----------------------------------|
| `Geeklog-main/games/apps.py`                    | Configuração da aplicação         |
| `Geeklog-main/games/models.py`                  | Modelo de dados com POO           |
| `Geeklog-main/games/migrations/0001_initial.py` | Script de migração Django         |

---

Se você quiser expandir o uso de POO no projeto (por exemplo, criando serviços, classes de domínio ou lógica de negócio separada), posso te ajudar com isso também! 🚀
