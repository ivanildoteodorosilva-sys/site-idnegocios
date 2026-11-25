# Site institucional — ID. Realidade e Negócios

Páginas estáticas (sem banco, sem cookies) publicadas pelo GitHub Pages.

| Endereço | Arquivo |
|---|---|
| / | index.html |
| /privacidade/ | privacidade/index.html |
| /kitlcdpr/ | kitlcdpr/index.html (página do Kit: planos, beta, perguntas) |
| /kitlcdpr/demonstracao/ | kitlcdpr/demonstracao/index.html (versão de demonstração, abre no navegador) |
| /kitlcdpr/termos/ | kitlcdpr/termos/index.html (versão vigente) |
| /kitlcdpr/termos/v1/ | kitlcdpr/termos/v1/index.html (arquivo da versão 1.0) |

Domínio principal: idnegocios.com.br (idrealidade.com.br redireciona para ele).
E-mails: contato@idnegocios.com.br (geral e privacidade) e kitlcdpr@idnegocios.com.br (suporte do Kit).
O domínio é ligado em Settings › Pages › Custom domain (o GitHub cria o arquivo CNAME sozinho).

Nova versão dos termos: copie a vigente para `kitlcdpr/termos/vN/`, depois edite a vigente.
Não coloque aqui o app nem código-fonte: este repositório é público.

Botões "Comprar" da página do Kit: hoje abrem um e-mail para kitlcdpr@. Quando os produtos existirem na Hotmart, troque o href de cada botão (marcados com data-plano="produtor", "contador10" e "ilimitado") pelo link de pagamento.
Nova demonstração: gere com `python build.py --demo` e substitua kitlcdpr/demonstracao/index.html.
