# O que é o R? E o RStudio? Qual a diferença?

O R é uma linguagem de programação utilizada para manipulação, análise e visualização de dados. 
O RStudio é um ambiente de desenvolvimento integrado (IDE) para o R.A diferença entre eles é que o R é uma linguagem de programação, já o RStudio é uma IDE para o R. Entendeu?

Sobre a escrita, meus professores me passaram algumas dicas e eu vou repassar pra você:

- Acostume-se a usar letras minúsculas, números e underline (_)
- Use nomes fáceis de lembrar
- Use espaço em ambos os lados de operadores matemáticos e em atribuições

## Diretório de trabalho

Um diretório nada mais é que o local onde os arquivos ficam armazenados no sistema.

```r
# verifica o seu diretório
getwd()
```

É muito importante manter um diretório organizado desde o princípio, para que você consiga localizar os seus projetos no R.

Dentro do R é possível criar quantos projetos quiser. Como criar um projeto? Eu poderia explicar aqui, mas vou deixar como desafio você descobrir essa parte, rs. 

> É importante lembrar que o R é sensível (não, ele não chora kkkk) mas se você escrever com letra maiúscula ele vai diferenciar.  
> Lembre-se sempre de conferir isso. Quando você começar a programar, vai perceber que muitas vezes os erros acontecem por falta de atenção a coisas básicas como essa.

No R, para escrever comentários é necessário colocar um "#" antes, pois sem a hashtag vai dar erro (dependendo do que você escreveu).

Uma dica: use o "help" no RStudio.

Se é a primeira vez que você está usando o R, vai ter que baixar vários pacotes. Para instalar pacotes, utilize:

```r
install.packages("nome do pacote")
```

> Install quer dizer instalar, package quer dizer pacote.

Depois, para carregar o pacote:

```r
library("nome do pacote")
```

> Library quer dizer biblioteca.

## Tá com mais dúvidas?

Vou deixar uma série de links de conteúdos que me ajudaram a aprender:

- https://r4ds.hadley.nz/
- https://rladies-sp.org/
Com o tempo eu vou adicionando mais, viu?!

## Atalhos de teclado do RStudio que uso regularmente

### Inserções

- "Ctrl+Shift+M": inserir %>%
- "Alt + -": inserir `<-`

### Editar linhas

- "Ctrl+Shift+C": alterna a linha entre código e comentário
- "Shift+Tab": desindentar linha
- "Ctrl+D": apagar tudo na linha atual
- "Ctrl+K": apagar tudo na linha atual após o cursor
- "Alt + ↑ / ↓": mover a linha atual
- "Ctrl+Alt+Shift+M": renomear todas as instâncias selecionadas
Eu peguei essas dicas no reddit (https://www.reddit.com/r/rstats/comments/jvdc4z/comment/gcj3idz/?tl=pt-br&utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)

### Navegação

- "Alt + O": colapsa todos os blocos
- "Alt + Shift + O": expande todos os blocos
- "Ctrl + Shift + O": mostra o painel de esboço

## Operações básicas

Para criar e atribuir nome a objetos, utilize "<-".  
Você pode fazer:

- Adição com +
- Subtração com -
- Multiplicação com *
- Divisão com /

Use "ls()" para listar os objetos criados.

## Sobre Inteligência Artificial

É costumeiro usar ferramentas de IA generativa para obter respostas — e está tudo bem!  
Ferramentas como ChatGPT, DeepSeek e outras são ótimas para te auxiliar no aprendizado de programação.  
Mas lembre-se: ajuda não é fazer por você!

É importante pedir ajuda, mas também tentar entender.  
Não tem problema pedir pro chat gerar um código, desde que você tente entender o que está sendo feito.

## Dica de inglês

O inglês é muito importante nos dias atuais, especialmente para quem estuda Estatística.  
Não me considero fluente, mas estou além do intermediário: leio, escrevo e me comunico bem.

Minha dica é: Explore!
O R utiliza muitos termos em inglês. Pesquise para entender.  
Como você vai usar com frequência, vai guardar aos poucos.

Até já!
