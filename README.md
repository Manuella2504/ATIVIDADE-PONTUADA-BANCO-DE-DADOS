# 🛩️ Sistema de Aeronaves - MySQL

## 📋 Descrição
Sistema de banco de dados para gerenciar aeronaves, tripulação, missões e escalas operacionais.

---

## 🎯 Objetivo
- Criar banco para armazenar dados de aeronaves
- Demonstrar conhecimentos em DDL/DML
- Implementar relacionamentos entre tabelas

---

## 🗄️ Estrutura

### Tabelas Principais
| Tabela | Função |
|--------|---------|
| **POSTO** | Patentes militares |
| **MISSAO** | Missões operacionais |
| **STATUS_MISSAO** | Status das operações |
| **FUNCAO** | Funções na escala |
| **TIPO_AERONAVE** | Tipos de aeronaves |
| **TRIPULACAO** | Dados dos tripulantes |
| **AERONAVE** | Dados das aeronaves |
| **ESCALA** | Escalas operacionais |

### Relacionamentos
```
TRIPULACAO → POSTO
AERONAVE → STATUS_MISSAO
AERONAVE → TIPO_AERONAVE  
ESCALA → AERONAVE/MISSAO/FUNCAO
```

---

## ⚙️ Operações Implementadas

### DDL
- ✅ CREATE DATABASE/TABLE
- ✅ ALTER TABLE (modificar colunas)
- ✅ RENAME TABLE
- ✅ Foreign Keys

### DML
- ✅ INSERT (dados em todas tabelas)
- ✅ UPDATE (modificações)
- ✅ DELETE (remoções)
- ✅ SELECT (consultas)

---

## 🚀 Como Usar

1. **Criar estrutura:**
```sql
CREATE DATABASE AERONAVES;
USE AERONAVES;
```

2. **Executar DDL** → Criar todas as tabelas

3. **Executar DML** → Inserir/modificar dados

4. **Testar consultas** → Verificar funcionamento

---

## 📊 Dados Armazenados

| Entidade | Principais Campos |
|----------|-------------------|
| **Tripulantes** | Nome, posto, tipo sanguíneo, contatos |
| **Aeronaves** | Prefixo, apelido, cor, capacidade |
| **Escalas** | Data, função, missão |

---

## 🏆 Competências
- Modelagem relacional
- Chaves primárias/estrangeiras  
- CRUD completo
- Modificações de estrutura
- Consultas com filtros

---

*Atividade pontuada - Sistema aeronáutico em MySQL*
