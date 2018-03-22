<p align="center"><img src="http://fagoc.br/download/a/logo" alt="Fagoc"></p>
<h1 align="center">Ajuda do Professor</h1>
<p align="center">:smile: Material de ajuda para o app dos professores da Fagoc.</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/%24-free-%23a10000.svg" alt="Pay"></a> 
  <a href="/LICENSE.md"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="GitHub License"></a>
  <a href="/issues"><img src="https://img.shields.io/github/issues/fagocbr/ajuda-professor.svg" alt="GitHub Issues"></a>
</p>

## Como contribuir

1. Crie um fork;<br>
  1.1. Configure o GH Pages de modo a usar a pasta docs caso queira um preview final do que está sendo feito;<br>
  1.2. Não esqueça de configurar seu github para usar uma chave ssh gerada pelo seu PC;<br>

2. Faça seu clone local (usando ssh de preferência);<br>
  2.1. Caso prefira pode trabalhar diretamente pelo Github e atualizar o seu clone para poder fazer a publicação das suas mudanças através de PR para o repositório principal;<br>
  2.2. É importante lembrar que mudar os arquivos do diretório `manuscript` não atualiza a visualização do material publicado, para tal é necesário seguir a etapa 4;<br>

3. Execute o comando `npm run dev` na raiz da pasta de destino do clone;<br>
  3.1. Você pode usar o hot reload para ir visualizando o resultando das mudanças que está fazendo em http://localhost:4000;<br>

4. Para publicar as mudanças execute `npm run publish`, este comando irá fazer a geração dos arquivos na pasta docs e irá fazer um push na master;<br>
  4.1. Utilize o GH Pages do seu fork para verificar se está tudo ok;<br>
  4.2. Submeta um PR para este repositório;<br>

----

###### Powered by Gitbook | made with ♥ by [Fagoc](http://fagoc.br)

----
[Ajuda](https://toolchain.gitbook.com/syntax/markdown.html)
