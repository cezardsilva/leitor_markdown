# SSL

Para ajustar o **SSL** você deve utilizar o **cPanel** de cada conta,

Siga este passo a passo:

- Primeiro remova qualquer instalação antiga.
- Acesse no menu <u>"Segurança" -> "SSL/TLS"
Chaves privadas (KEY)</u> -> Gere, exiba, carregue ou exclua as chaves privadas.
- Se tiver qualquer chave nesta tela vá em **"Ações"** e **"Excluir"**
- Volte nesta mesma tela e escolha:
- Instalar e gerenciar SSL para seu site (HTTPS) -> Gerencie sites SSL.
- Se tiver qualquer certificado nesta tela vá em **"Ações"** e **"Desinstalar"**
- Agora acesse no menu **"Segurança"** <u>-> "SSL/TLS Status</u>"
Aqui deve aparecer tudo com o "cadeado vermelho" indicando que não há nenhum certificado instalado.
Marque a "caixa de seleção" Dominio e clique no botão "Run Auto-SSL" e aguarde...

**Para **"forçar"** um site a sempre abrir com *https://* use o <u>menu "Domínios"</u> ícone <u>"Domínios"</u> e selecione o domínio na coluna **"Force HTTPS Redirect"**

**Importante:** Vale ainda enfatizar que sistemas como o *WordPress, Joomla* e outros **CMS** devem ter a URL ajustada para *"https://"* dento do "admin" do site para funcionarem corretamente.

Se um site carregar com *https://* mas mesmo assim exibir a mensagem de *"Não Seguro"* será preciso revisar o código fonte pois possivelmente devem existir links internos apontando para endereços com *HTTP://* sem o **"s"** e o navegador considera isto como conteúdo misto e não exibe o cadeado.