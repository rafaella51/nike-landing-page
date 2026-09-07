# Landing Page - Nike Air Jordan 1 Mid Feminino

Site gerado a partir do seu design no Canva (13 páginas -> 11 seções, removendo 2 páginas duplicadas).
Estrutura:

```
nike-landing/
├── index.html
└── images/
    ├── section-01.jpg  (topo, com botão "Comprar Agora")
    ├── section-02.jpg  ... até section-10.jpg
    └── section-11.jpg  (CTA final, com botão "Comprar Agora")
```

## Link de checkout

Já configurado: todos os botões "Comprar Agora" (seção 1, seção 6, seção 11 e a barra fixa) apontam para `https://link.mercadopago.com.br/nikejordan`.

Se um dia precisar trocar, abra o `index.html` num editor de texto (Bloco de Notas, VS Code) e use "Substituir tudo" nesse link.

## Testar localmente

Basta dar duplo clique no `index.html` — ele abre no navegador. Ou, se preferir ver como ficaria num celular, use a extensão "Live Server" no VS Code.

## Publicar no GitHub

1. Crie uma conta em github.com (se ainda não tiver).
2. No canto superior direito, clique em "+" > "New repository". Dê um nome, ex: `nike-landing-page`. Deixe como "Public". Não marque nenhuma opção extra. Clique em "Create repository".
3. Na página do repositório recém-criado, clique em "uploading an existing file".
4. Arraste a pasta inteira (`index.html` + pasta `images`) para a área de upload.
5. Role para baixo e clique em "Commit changes".

Pronto, seu código está no GitHub.

## Publicar na Vercel

1. Acesse vercel.com e crie uma conta gratuita (pode entrar direto com sua conta do GitHub).
2. Clique em "Add New..." > "Project".
3. Selecione o repositório `nike-landing-page` que você acabou de criar no GitHub (a Vercel pede permissão para acessar seus repositórios — autorize).
4. Não precisa mudar nenhuma configuração de build (é um site estático). Clique em "Deploy".
5. Em menos de um minuto a Vercel te dá um link tipo `nike-landing-page.vercel.app` — sua página já está no ar.

Qualquer atualização que você fizer no GitHub depois (editar o `index.html`, trocar uma imagem) publica automaticamente de novo na Vercel.

## Observação

Essa página usa a marca e as imagens da Nike/Air Jordan para divulgar um produto de terceiro (fora do fabricante). Isso é comum em páginas de afiliado/dropshipping, mas vale ter em mente que usar a marca sem autorização tem risco de notificação por uso indevido de marca — principalmente se o produto anunciado não for original. Se quiser, dá pra suavizar isso (ex: tirar o logo oficial da Nike e deixar só "Estilo Air Jordan Mid") — me avisa se quiser que eu ajuste.
