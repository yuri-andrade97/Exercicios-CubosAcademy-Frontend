![](https://i.imgur.com/xG74tOh.png)

## Exercícios de classe 🏫

### Recriar layout sem todas as especificações

O objetivo desse exercício é recriar a tela encontrada na pasta "design-files" com no mínimo 6 divs da classe card, não podendo repetir os pratos.

As classes .esquerda, .meio e .direita devem estar presente em 2 divs da classe card, ou seja, você terá 2 cards com a classe esquerda, dois com a classe meio e dois com a classe direita, totalizando os 6 mínimos.

#### Especificações de estrutura
- h1 
- div.card e (.esquerda, .meio ou .direita)
  - img
  - div.conteudo
    - h2
      - span
    - p

#### Especificações de estilo (CSS separado)
- todos os elementos (`*`)
  - sem margin, sem padding, box-sizing border box e fonte 'Almond Nougat' com fallback para *cursive*
- body
  - background será a imagem 'background.jpg', cor branca (*white*), posicao initial no canto esquerdo do topo (*top left*), tamanho automatico (*auto*) e deverá se repetir
- h1
  - tamanho de fonte 60px, margem de 50px para baixo, background com cor #FCD9AF e borda em baixo de 2px, solida e preta (*black*)
- div.card
  - todas as divs da classe card devem conter uma cor de fundo diferente, essa cor de fundo deve vir de outra classe.
- .card
  - largura máxima (*max-width*) de 400px, bordas arredondadas em 15px e sombra 3px para baixo, 10px de blur, 0px de spread e cor preta (*black*)
  - img
    - largura máxima (*max-width*) de 400px e bordas do topo/esquerda e topo/direita arredondadas em 15px
  - h2
    - tamanho de fonte 30px, peso da fonte (*weight*) de 400 e borda em baixo de 1px, solida e preta (*black*)
  - span
    - tamanho de fonte 34px, peso da fonte (*weight*) de 800
  - p
    - tamanho de fonte 24px, justificado e margens horizontais de 15px e verticais de 5px
  - .conteudo
    - padding de 15px e margem em baixo de 15px
- .esquerda
  - margem na esquerda de 45px
- .meio
  - margem horizontal automatica
- .direita
  - margem na esquerda automatica e na direita de 45px

---

Preencha a checklist para finalizar o exercício:

- [ ] Resolver o exercício
- [ ] Adicionar as mudanças aos commits (`git add .` para adicionar todos os arquivos ou `git add nome_do_arquivo` para adicionar um arquivo específico)
- [ ] Commitar a cada mudança significativa ou na finalização do exercício (`git commit -m "Mensagem do commit"`)
- [ ] Pushar os commits na sua branch na origem (`git push origin nome-da-branch`)
- [ ] Realizar o pull request

###### tags: `front-end` `módulo 1` `exercício de classe` `HTML` `CSS`
