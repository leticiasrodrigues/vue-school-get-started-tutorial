# VueSchool - Vue.js Fundamentals
Tutorial do curso *Vue.js Fundamentals* de VueSchool.
Disponível em [https://vueschool.io/courses/vuejs-fundamentals](https://vueschool.io/courses/vuejs-fundamentals).

Os atributos data do componente podem ser diretamente modificados no console, com efeito direto na view (responsivo).
Exemplos:

```shoppingList.$data.items.push('Forth Item')```

Com Vue Dev Tools

```$vm0.$data.items.pop()```

Da mesma maneira é possivel ver a mudança no valor do atributo quando mudamos o input (o bind ocorre nos dois sentidos)

`@keyup.enter` é uma forma de escrever `v-on:keyup.enter`

`:disabled` é uma forma de escreve `v-bind:disabled`

**Quando usar *methods* e *computed*?**

*Methods* para mudar valores de propriedades.

*Computed* para apresentá-los de maneira diferente que estão guardados (não modifica o dado).