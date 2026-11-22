# Amigos da Sogra / StwpTV — Android + Android TV

Projeto Android com duas variantes, ambas ligadas ao mesmo NETV Player2.

- Amigos da Sogra: https://player2.amigosdasogra.pt/login
- StwpTV: https://stwp.amigosdasogra.pt/login

## Compilar no GitHub
Abra **Actions > Compilar APKs Android e Android TV > Run workflow**.
Após a conclusão, descarregue o artifact **AmigosDaSogra-e-StwpTV-APKs-teste**.
Contém dois APKs de teste assinados com a chave de debug (não usar como lançamento de produção).

## Logótipos
As imagens incluídas são provisórias. Antes de distribuir, substitua os ficheiros
`app/src/main/res/drawable/app_icon.png` e `tv_banner.png` por recursos adequados.
Para ícones diferentes por marca, use `app/src/amigos/res/drawable/` e
`app/src/stwp/res/drawable/` com os mesmos nomes de ficheiro.

## Limitações da versão de teste
A aplicação abre o WebPlayer numa WebView e não altera o NETV. Navegação por comando,
DRM, codecs, fullscreen e reprodução de streaming precisam de testes nos dispositivos.
A WebView pode não suportar todos os formatos de vídeo usados pelo NETV.
Não incluir credenciais de clientes ou fornecedores no repositório.
