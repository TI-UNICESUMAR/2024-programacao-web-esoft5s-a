### Combinadores

> Combinadores de filhos

Representado pelo sinal `>`, é colocado entre dois seletores. O estilo será aplicado apenas aos elementos que são filhos diretos do primeiro seletor.

```css
/* Aplica estilo apenas aos elementos <span> que são 
  filhos diretos de <p> */
p > span {
  color: red;
}
```

---

> Combinadores de irmãos

Representado pelo sinal `+`, é colocado entre dois seletores. O estilo será aplicado apenas aos elementos que são irmãos imediatos do primeiro seletor.

```css
/* Aplica estilo apenas aos elementos <span> que são 
  irmãos imediatos de <p> */
p + span {
  background-color: lightgrey;
}
```

---

> Combinadores de irmãos gerais

Representado pelo sinal `~`, é colocado entre dois seletores. O estilo será aplicado a todos os elementos que são irmãos do primeiro seletor.

```css
/* Aplica estilo a todos os elementos <span> que são 
  irmãos de <p> */

p ~ span {
  color: blue;
}
```

---

É possível utilizar todos os combinadores em conjunto.

```css
/* Aplica estilo a todos os elementos <span> que são 
  irmãos de <p> e filhos diretos de <div> */

div > p ~ span {
  color: blue;
}
```

[Documentação MDN sobre Combinadores css](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Combinators)

---

> Algumas das principais unidades de medidas css

| Unidade | Descrição                                            |
| ------- | ---------------------------------------------------- |
| `px`    | Pixels                                               |
| `em`    | Relativo ao tamanho da fonte do elemento pai         |
| `rem`   | Relativo ao tamanho da fonte do elemento raiz (root) |
| `vw`    | Relativo à largura da viewport (1vw = 1% view width) |
| `vh`    | Relativo à altura da viewport (1vh = 1% view height) |
| `%`     | Percentual                                           |
| `ch`    | Largura do "0" no tipo de letra                      |

<!-- _footer: pedro.mateus@unicesumar.edu.br -->
