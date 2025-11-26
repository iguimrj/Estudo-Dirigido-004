# Estudo-Dirigido-004
App de Garantia de Equipamentos

# App de Garantia de Equipamentos

Sistema para controle de garantias de equipamentos eletrônicos.

## Estrutura do Banco de Dados

### Tabelas:
- **loja**: Cadastro das lojas onde os equipamentos foram comprados
- **equipamento**: Registro dos equipamentos adquiridos
- **garantia**: Controle dos prazos de garantia

### Consultas SQL Implementadas:

1. **Equipamentos e Lojas**: Lista todos os equipamentos com informações das lojas
2. **Garantias e Dias Restantes**: Mostra o status das garantias ativas
3. **Garantias Vencidas**: Identifica garantias que já expiraram

## Como Executar

1. Execute `schema.sql` no PostgreSQL para criar o banco
2. Execute `inserts.sql` para popular com dados de teste
3. Configure a conexão no arquivo `src/main.py`
4. Execute `python src/main.py`

## Tecnologias Utilizadas

- PostgreSQL
- Python 3.x
- Psycopg2 (driver PostgreSQL para Python)
- Programação Orientada a Objetos
