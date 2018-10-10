# O que é React?

Ele inicialmente foi desenvolvido pelo Instagram, mas depois que o Facebook comprou o Instagram eles começaram a desenvolver e eles que lançaram o React no mercado.

O React é uma biblioteca para criação de UI. Ela te ajuda criar interfaces melhores e de uma maneira bem simples. Com o React você vai conseguir criar as `Views` para cada `state` da sua aplicação.

# O que faz ele ser tão especial? 

## Composição

O React te permite criar multiplos componentes e componentes pequenos. depois é só juntos eles para criar a sua UI.

```
<Container>
  <NavBar />
  <DatePicker>
    <Calendar />
  </DatePicker>
</Container>
```

Em ve de pensar em uma página inteira, você vai pensando em cada elemento, contexto.

* [Material UI](https://material-ui.com/)
* [Bootstrap](https://react-bootstrap.github.io/)
* [ReactDates](https://github.com/airbnb/react-dates)
* [BigCalendar](https://github.com/intljusticemission/react-big-calendar)

Praticar a identificação de componentes e como quebrar em componentes genéricos

## Data flow

Cada componentes PODE possuir um estado e ele pode ser alterado.
Quando você utiliza JQuery e altera uma parte da tela, ele está atualizando todo o DOM, enquanto com o React ele irá atualizar só o componente.

Essa atualizão é feita unidirecionalmente (sei la se essa palabra existe), isso que dizer que um evento será acionado, ele irá alterar o estado e ai a interface será atualizada, mas nunca o contrário.

Essa mutação de estado no React é feita através do `this.setState(...)`. 

* [Virtual DOM](https://reactjs.org/docs/faq-internals.html)
* [Redux](https://redux.js.org/)
* [Immutable JS](https://facebook.github.io/immutable-js/)

## JavaScript

Para programar em React praticamente a mesma coisa que JavaScript, inserindo HTML no meio. A única coisa que muda é que são algumas funcões e estruturas da API do React.

## Programar para vários lugares

Com o React você pode programar para celular, VR, TV e sei la mais o que

* [React Native](https://facebook.github.io/react-native/)
* [React TV](https://github.com/raphamorim/react-tv)
* [React VR](https://facebook.github.io/react-360/)

# React e ReactDOM

Antes tinha só uma biblioteca, a de React que funcionava só para a Web. Mas depois as pessoas começam a criar o React para vários outros dispositivos. Com isso eles decidiram separar as coisas.
Hoje a biblioteca React tem as coisas que são em comum para todos os dispositivos. E a ReactDOM tem as coisas para renderizar no navegador.

# Babel

O Babel é o cara que transpila o JSX em JS.

* [Babel](https://babeljs.io/)