# Fluxo de trabalho

Guia prático de como colaborar

### Criando um novo repositório

Crie uma nova pasta, abra-a e execute o comando
```
git init
```
### Obtendo um repositório existente

Crie uma cópia de trabalho em um repositório local executando o comando
```
git clone /caminho/para/o/repositório
```

### Adicionando e confirmando mudanças

Você pode propor mudanças usando
```
git add <nome do arquivo>
```
ou
```
git add .
```

Para realmente confirmar estas mudanças, use
```
git commit -m "descrição das alterações"
```
Agora o arquivo é enviado para o HEAD, mas ainda não para o repositório remoto.

### Atualizando e mesclando

Para atualizar seu repositório local com a mais nova versão do repositório remoto, execute
```
git pull
```
na sua pasta de trabalho para obter e mesclar (merge) as alterações remotas.

### Enviando alterações

Suas alterações agora estão no HEAD da sua cópia de trabalho local. Para enviar estas alterações ao repositório remoto, execute
```
git push origin master
```

___

## Resumo de comandos git

![](resume_git.png)


___

## Referências

[GIT - guia prático](https://rogerdudler.github.io/git-guide/index.pt_BR.html)

[GIT - documentação](https://git-scm.com/doc)

[curso prático GIT e GITHUB](https://www.youtube.com/playlist?list=PLbEOwbQR9lqzK14I7OOeREEIE4k6rjgIj)

