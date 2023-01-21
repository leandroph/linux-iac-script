# linux-iac-script

Script de criação de estrutura de usuários, diretórios e permissões, contento a seguinte estrutura:

## Diretórios:
```bash
/publico
/adm
/ven
/sec
```

## Grupos:
```bash
GRP_ADM
GRP_VEN
GRP_SEC
```

## Usuários:
```bash
carlos      debora          josefina
maria       sebastiana      amanda
joao        roberto         rogerio
```

## Definições do Script:
- O dono de todos os diretórios criados será o usuário root;
- Todos os usuários terão permissão total dentro do diretório publico;
- Os usuários de cada grupo terão permissão total dentro de seu respectivo diretório;
- Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertencem.


