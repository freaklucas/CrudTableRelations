# CRUD de Entidades

## Entidade Pessoa
### Campos
* id
* no_pessoa
* no_email
* endereco
* sexo (char M/F)
* ic_ativo (boolean)

## Entidade Animal
### Campos
* id
* fk_id_pessoa
* id_fazenda
* no_animal
* no_raca
* sexo (char M/F)
* vr_peso
* dt_nascimento

## Entidade Animal Lote
### Campos
* id
* no_lote
* ds_lote

## Entidade Animal X Lote
### Campos
* id
* fk_id_animal
* fk_id_lote
* dt_entrada
* dt_saida
* dt_ultima_movimentacao
* ic_bezerro
