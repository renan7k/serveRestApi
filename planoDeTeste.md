# Plano de testes da API ServerRest

Este documento lista os principais cenários de testes da API serverRest, afim de relembrar e colocar em prática os conhecimentos em automação de testes via postman.  

## Cenários

## Fluxo Completo
### Usuários
CT01 - Consultar usuários cadastrados
CT02 - Cadatrar usuário com sucesso
CTXX - Verificar mensagem de erro ao tentar cadastrar sem parâmetro obrigatório
CT03 - Verificar mensagem de erro ao utilizar email já cadastrado
CT04 - Consultar usuário por ID
CT05 - Consultar usuário não cadastrado
CT06 - Alterar usuário com sucesso
CT07 - Verificar mensagem de erro ao alterar para email já cadastrado
CT08 - Deletar usuário com sucesso
CT09 - Verificar mensagem de erro ao deletar usuário com carrinho cadastrado      PENDENTE
CTXX - Verificar mensagem após tentativa de exclusão de usuário não cadastrado

### Login
CT10 - Realizar login com sucesso
CT11 - Verificar mensagem de erro quando email/senha estiverem incorretas

### Produtos
CT13 - Consultar produtos cadastrados
CTXX - Consultar carrinhos por filtros
CT14 - Cadastrar produto com sucesso
CT15 - Verificar erro ao tentar inserir produto com nome já cadastrado
CT16 - Verificar erro ao tentar cadastrar sem enviar o token
CT17 - Verificar erro ao tentar cadastrar com token inválido/expirado
CT18 - Verificar erro ao tentar cadastrar produto com usuário que não é administrador
CT19 - Consultar produto por ID com sucesso
CT20 - Cadastrar produto não cadastrado
CT21 - Alterar produto com sucesso
CT22 - Verificar que caso o produto não exista, o PUT vai funcionar como um cadastro
CT23 - Verificar erro ao tentar alterar produto com nome já cadastrado
CT24 - Verificar erro ao tentar alterar produto sem enviar o token
CT25 - Verificar erro ao tentar alterar produto com token inválido/expirado
CT26 - Verificar erro ao tentar alterar produto com usuário que não é administrador
CT27 - Deletar produto com sucesso
CT28 - Verificar erro ao deletar produto que esteja dentro do carrinho
CT29 - Verificar erro ao tentar deletar produto sem enviar o token
CT30 - Verificar erro ao tentar deletar produto com token inválido/expirado
CT31 - Verificar erro ao tentar deletar produto com usuário que não é administrador

### Carrinhos
CT32 - Consultar carrinhos cadastrados
CTXX - Consultar carrinhos por filtros
CT33 - Cadastrar carrinho com sucesso
CT34 - Verificar mensagem de erro ao tentar adicionar produto duplicado no carrinho
CT35 - Verificar mensagem de erro ao tentar adicionar mais de 1 carrinho por cliente
CT36 - Verificar mensagem de erro ao tentar cadastrar carrinho com produto não cadastrado
CT37 - Verificar mensagem de erro ao tentar cadastrar carrinho com produto sem estoque
CT38 - Verificar mensagem de erro ao tentar cadastrar carrinho sem envio do token
CT39 - Verificar mensagem de erro ao tentar cadastrar carrinho com token expirado
CT40 - Consultar carrinho por ID com sucesso
CT41 - Cadastrar carrinho por ID não cadastrado
CT42 - Concluir compra com sucesso
CT43 - Verificar mensagem de erro ao tentar concluir compra de usuário sem carrinho
CT44 - Verificar mensagem de erro ao tentar concluir compra sem envio do token
CT45 - Verificar mensagem de erro ao tentar concluir compra com token expirado
CT46 - Deletar carrinho com sucesso
CT47 - Verificar mensagem de erro ao tentar excluir compra de usuário sem carrinho
CT48 - Verificar mensagem de erro ao tentar excluir compra sem envio do token
CT49 - Verificar mensagem de erro ao tentar excluir compra com token expirado


C2abcDefgHlMNo1PQ