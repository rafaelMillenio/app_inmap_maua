# V5 -> V6 Log

## V5.1
- apontamento de armazenamento de arquivos para o storage no 253 (retrabalhando todo o codigo)
- função global para sanitizar nome de arquivos
- user ID do botão visitante na variavel de sessão da tela de login mudada de "28" para "5" para concertar problema de visitante adm

## V5.2
- apontamento arquivos_outros corrigido
- se o campo inscrição estiver vazio, configura que esta sem quadra

## V5.3
- corrigindo apontamento de todas as telas
- corrigindo apontamento storage todas as telas
- corrigindo update que procura osasco em matricula

## V5.4
- corringindo a sequence de arquivos

# InMap Maua V4 -> V5 Log

## V4.1
- Telas Sistema(fileman), GeoServer(web), PgAdmin e Portainer redirecionando corretamente

## V4.2
- CRUD da tabela t_depart_tabela na admin_cadastros
- padronização da tabela admin_cadastros

## V4.3
- conectar o crud da tabela grupo cadastro com todas as outras tabelas respectivas para preenchimento
- apontamento o webgis corrigido
- list concatenado no grupo x cadastro (agora o campo link aparece com o _list.php ao lado)
- fuid depart cadastro corrigido (agora esse campo é coletado e inserido na tabela)

## V4.4
- tabela depart cadastro com crud no cadastro
- replanejamento de organização de tabelas para a tela cadastro

## V4.5
- view depart_cadastro removida
- edit corrigida para salvar id (depart_cadastro) e bloquear usuario de alterar esse dado (depart_cadastro e grupo cadastro)

# TODO
- detectar tabelas existentes no projeto para adicionar num dropdown automaticamente
- corrigir envio de varios arquivos de uma vez (só coloca contador caso varios arquivos sejam enviados de uma vez)
- corrigir responsividade das telas 
