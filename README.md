# guestbook
Repositório para exercícios no Git. À medida em que testarmos mais coisas, elas aparecerão aqui.

## fluxo comum
Um repositório pode tanto ser criado com `git init` ou pode ser criado diretamente aqui no GitHub. Para os exercícios, vamos usar o ambiente do GitHub mesmo.

Daí, criamos o repositório e copiamo-lo para o computador usando `git clone https://github.com/wgnann/guestbook.git`. Tem um botão **Clone** que gera o link. Por ora, vamos usar **HTTPS** mesmo.

Uma vez feita a alteração, é necessário adicionar o conjunto de arquivos ao repositório. Isso é feito com `git add <seu arquivo>`. Depois de adicionado, é preciso consolidar as alterações com o `git commit`, usaremos commitar a partir de agora. Por fim, é preciso replicar as alterações para o repositório remoto com `git push`.

A ideia é que você pode fazer diversas alterações localmente sem precisar sincronizar com o remoto. Pode, inclusive, sequer usar o remoto e deixar só local todos os seus commits.

Para sincronizar seu repositório atual com o remoto, usar `git pull`.

Versão tl;dr:
 * `git pull`;
 * fazer suas alterações;
 * `git add`;
 * `git commmit`;
 * `git push`.
