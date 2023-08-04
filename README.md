<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->

<h1 align="center">Árvore de dependências do curso de Bacharelado em Engenharia da Computação</h1>

<p align="center">
  <img src="images/uefs.png" alt="MarineGEO circle logo" style="height: 150px; margin: 0 auto"/>
</p>

<h2 align="center">Universidade Estadual de feira de Santana - UEFS</h2>

## Introdução

Olá! Seja bem-vindo à Árvore de Dependências do Curso de Bacharelado em Engenharia da Computação (ECOMP) da Universidade Estadual de Feira de Santana (UEFS). Essa árvore representa a relação entre as 55 matérias necessárias para concluir a formação como bacharel em Engenharia da Computação.

> Caso você seja calouro e ainda não saiba a importância da correlação entre as matérias, clique [aqui](./docs/materias.md) para entender mais.

## Aproveitamento do Curso

A árvore de dependências foi criada para auxiliar os alunos a obter um melhor aproveitamento das matérias durante o curso. Ela ajuda a entender quais matérias têm pré-requisitos e como as disciplinas se relacionam, permitindo um planejamento mais eficiente para uma trajetória acadêmica bem-sucedida.

> Ou seja... vai te ajudar a sair da caverna do dragão `;)`

## Versões Disponíveis

- Resolução CONSEPE 073/2023 `(Novo)` [aqui](/src/CONSEPE%20073_2023/)

- Resolução CONSEPE 124/2020 [aqui](/src/CONSEPE%20124_2020/)

## Resolução 073/2023

![Diagrama](/images/dependency_tree.jpg)

## Como ler a árvore

### Matérias

<img align="right" width=50% src="images/etica.png" alt="MarineGEO circle logo"/>

A árvore é composta pelas matérias da grade curricular de ECOMP. Cada matéria é representada por um card de bordas arredondadas com informações detalhadas, como:

- Carga horária da matéria (ex.: 60h)
- Código da matéria (ex.: EXA615)
- Nome da matéria (ex.: Ética em Computação)
- Código de cor do semestre (explicação [aqui](README.md/#esquema-de-cores-dos-semestres))
- Score da matéria (explicação [aqui](README.md/#pontuação-das-matérias))

### Regras da árvore

- Os componentes no topo, sem nenhuma seta apontando para eles, não têm pré-requisitos.

- Uma matéria com algum requisito tem a matéria que é requisito apontando uma seta para ela (ex.: A matéria de `Cálculo D e I 1` tem como dependência `Introdução ao Cálculo`, por isso `Introdução ao Cálculo` → `Cálculo D e I 1`).

- As setas vermelhas são usadas só para melhor visualização quando há cruzamento de setas.

- Algumas matérias especiais precisam de uma porcentagem da grade concluída para estar disponível. Essas matérias estão indicadas no canto superior direito da árvore com uma nota vermelha e as instruções necessárias para desbloqueá-las.

- As matérias optativas estão em branco, permitindo que quem imprima utilize o espaço como quiser.

### Esquema de cores dos semestres

O esquema de cores, mostrado no canto superior esquerdo de cada card, demonstra o semestre de acordo com o fluxograma regular do curso.

![Diagrama](/images/semestres.png)

### Pontuação das matérias

Cada matéria apresenta um score no canto superior direito, indicando o impacto que ela tem nas matérias futuras. Uma matéria que não tem nenhuma outra dependente dela tem um score de 1.

<img width=50% src="images/etica.png" alt="MarineGEO circle logo"/>

Já uma matéria que tenha quem dependa dela vai constar como a somatória de quantas matérias ela vai impactar + 1 que seria da própria matéria

![Diagrama](/images/so.png)

> Uma matéria de pontuação 1 não necessariamente significa que não é importante. Lembre-se de que todas as matérias são necessárias para a formação completa.

## Como contribuir nesse projeto

- Faça um fork do repositório
- Crie uma branch contendo a modificação que você quer fazer

### Contribuindo na árvore

- Abra o projeto na pasta `src/dependency_tree.drawio` no site [Draw.io](https://app.diagrams.net/) com o o seu fork do projeto na pasta. Você precisa logar com sua conta do github no site e clicar em "Abrir diagrama existente"
- Faça as modificações e commite
- Faça um pull request

### Contribuindo na documentação

- Clone o repositório em sua máquina, faça suas modificações e peça um pull request

> Você também pode abrir uma issue relatando um erro ou dando alguma sugestão

## Como fazer a impressão da árvore

Você pode abrir o projeto no draw.io e fazer a impressão por lá

Também está sendo disponibilizada o pdf da árvore na pasta `src/dependency_tree.pdf`

## Como fazer modificações personalizadas

- Siga os passos para contribuição na árvore
- Seja criativo e ajuste como quiser 😉

## Contribuidores

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/AlanaSampaio"><img src="https://avatars.githubusercontent.com/u/71518539?v=4?s=100" width="100px;" alt="Alana Sampaio"/><br /><sub><b>Alana Sampaio</b></sub></a><br /><a href="#maintenance-AlanaSampaio" title="Maintenance">🚧</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/johnnyqdp"><img src="https://avatars.githubusercontent.com/u/32348002?v=4?s=100" width="100px;" alt="Johnny Quest"/><br /><sub><b>Johnny Quest</b></sub></a><br /><a href="#maintenance-johnnyqdp" title="Maintenance">🚧</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
