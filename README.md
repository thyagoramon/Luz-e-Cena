# Luz & Cena

Home page de uma rede de cinemas fictícia, desenvolvida ao longo da formação em front-end "CSS avançado: implementando designs com Grid, Flexbox e Sass" da Alura. A página contém um menu de navegação no cabeçalho, banner, vitrine com os filmes em cartaz, seção de cadastro para a newsletter e rodapé com links.

![luz   cena](https://github.com/user-attachments/assets/df2d7e13-3ceb-4a62-8724-4e047d302c27)

[Clique aqui para visualizar a página](https://thyagoramon.github.io/Luz-e-Cena/)

## Funcionalidades da página
- Responsividade em diferentes tamanhos de tela: desktop, tablet e smartphone.
- Header com links de navegação, campo para pesquisa e menu suspenso na versão mobile.
- Vitrine de exposição dos filmes em cartaz.
- Campo de cadastro para newsletter.
- Rodapé completo com diferentes informações e links úteis.
- Efeitos decorativos ao posicionar o cursos (hover).

## Técnicas e tecnologias utilizadas
- **`HTML`**: Linguagem de marcação utilizada para estruturar o conteúdo das páginas web.
- **`CSS`**: Utilizado para estilizar a apresentação da página web.
  - **`CSS Flexbox`**: Utilizado para organizar elementos de forma flexível e responsiva, garantindo um layout moderno e adaptável. Abaixo estão os principais atributos utilizados do Flexbox:
    - **`display: flex`**: Define um elemento como um container flexível, ativando as propriedades Flexbox para os elementos filhos.
    - **`flex-direction`**: Define a direção principal do layout dos itens flexíveis.
    - **`justify-content`**: Alinha os itens ao longo do eixo principal (horizontal por padrão).
    - **`align-items`**: Alinha os itens ao longo do eixo transversal (vertical por padrão).
    - **`align-content`**: Alinha várias linhas de itens flexíveis quando há espaço extra no eixo transversal. Funciona quando há múltiplas linhas (com `flex-wrap`).
    - **`flex-wrap`**: Define se os itens devem ou não quebrar para a próxima linha.
    - **`flex-flow`**: Combina `flex-direction` e `flex-wrap` em uma única propriedade.
    - **`order`**: Define a ordem dos itens dentro do container flexível.
    - **`flex-grow`**: Define a capacidade de um item flexível de crescer, ocupando o espaço disponível.
    - **`flex-shrink`**: Define a capacidade de um item de encolher caso necessário.
    - **`flex-basis`**: Define o tamanho inicial do item antes de o espaço disponível ser distribuído.
    - **`flex`**: Combina `flex-grow`, `flex-shrink` e `flex-basis` em uma única propriedade para maior simplicidade.
    - **`align-self`**: Permite modificar o alinhamento de um item específico, substituindo o valor definido em `align-items` para aquele item.
