# iaconstruart-auth

Página de retorno da autorização (OAuth) do Mercado Livre para o painel da Construart,
publicada em `https://auth.iaconstruart.com/ml/retorno/`.

A página é estática e não guarda segredo. Ela mostra o código de autorização para ser colado no
painel e então o apaga da barra de endereço. Ela não envia nada a nenhum servidor e não carrega
conteúdo de terceiros. O fluxo usa PKCE, então o código sozinho não serve para obter acesso.

O código do painel fica em outro repositório, privado.
