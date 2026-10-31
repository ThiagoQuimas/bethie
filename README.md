# Bethiê

Aplicação web estática conectada ao Supabase.

## Publicação no GitHub Pages
1. Crie um repositório público chamado `bethie`.
2. Envie `index.html` para a raiz do repositório.
3. Em Settings → Pages, escolha Deploy from a branch.
4. Selecione a branch `main` e a pasta `/ (root)`, depois salve.
5. Aguarde a publicação e abra a URL exibida nessa tela.

## Segurança
O HTML usa a chave publishable do Supabase. Nunca adicione `service_role`, secret keys, senhas ou dados de clientes ao repositório. As políticas RLS atuais permitem acesso aos dados por qualquer usuário autenticado no projeto Supabase; mantenha o cadastro público desativado e crie usuários somente para pessoas autorizadas.
