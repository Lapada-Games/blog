# Como postar no blog

## Passo 1. Clone o repositorio
```bash
git clone https://github.com/Lapada-Games/blog
```

## Passo 2. Instale as dependencias
```bash
npm install
```

## Passo 3. Instale o hexo-cli
```bash
npm install hexo-cli -g
```

## Passo 4. Crie um post usando o comando do hexo
```
hexo new <nome do post>
```

Ele vai criar um arquivo markdown e uma pasta para colocar imagens somente para aquele post na pasta source/_posts. 

Por exemplo, rodei um
```
hexo new Seila
```

Ele gera:
- Seila/
- Seila.md

## Passo 5. Escreva o post
Escrever o post usando markdown. Conferir a [documentação do Hexo](https://hexo.io/docs/) pra saber como escrever e adicionar imagens.

## Passo 6. Publique apenas dando um push no github
Basta fazer o commit e push normalmente que já tem um github actions setado bonitinho pra fazer o trabalho sujo.