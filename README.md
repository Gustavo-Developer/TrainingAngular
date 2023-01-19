<h1 align="center">
  <img src="./.github/logo.png" alt="Angular" width="100px"/>
</h1>

<p align="center">
  Curso <strong> Angular </strong>
</p>

Repositorio destinado ao estudo do framework Angular, aqui voce encontrara anotações, projetos e testes.

## :dart: Diretivas

<strong>Atributo:</strong> Alteram a aparenciua ou comportamento de um elemento, componente ou diretiva.

[NgClass]
[NgStyle]
[NgModel]

<strong>Estruturais:</strong> Modam ou Remodelam a estrutura do DOM

[NgIf]
[NgFor]
[NgSwitch]

## :dart: Ciclo de vida Angular

<strong>ngOnInit:</strong> é executado uma vez quando o componente é inicializado;

<strong>ngOnChanges:</strong> executado também uma vez na criação do componente e toda vez que ele sofrer alguma mudança;

<strong>ngDoCheck:</strong> executado a cada mudança que o ngOnChange não detecta;

<strong>ngOnDestroy:</strong> executado na destruição do componente.

Além desses existem outros quatros hooks dentro do ngDoCheck:

<strong>ngAfterContentInit:</strong> sempre que um conteúdo vindo de uma fonte externa do componente é inserido;

<strong>ngAfterContentChecked:</strong> quando o conteúdo externo é verificado;

<strong>ngAfterViewInit:</strong> executado logo após os dados dos filhos e do próprio componente ser inicializado;

<strong>ngAfterViewChecked:</strong> sempre que é detectado uma alteração do conteúdo é chamado esse cara.

## :dart: Databiding

<strong>Interpolation</strong> Permite inserir textos dinamicos

```bash
  <h1> {{title}} </h1>

  public title: string = "Bem vindo";
```

<strong>Property Binding</strong> Permiter definir valores para propriedades de elementos ou diretivas HTML

```bash
  <button [disabled]="disabledButton"> Button </button>
  <img [src]="itemImageUrl">
  ou
  <img src="{{itemImageUrl}}">
```

<strong>Event Binding</strong> Permite escutar ou responder eventos do usuario

```bash
  <button [click]="calc()"> Button </button>
```

<strong>Two-way Binding</strong> Uniao entre propert-binding e event-binding. Usado para ouvir eventros e atualizar valores simultaneamente

```bash
  <input [(ngModel)]="nome">
  <span> {{nome}} </span>

  public nome = "Gustavo"
```

<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/gustavo-mendes-00661318b/">
        <img src="https://avatars.githubusercontent.com/u/71361227?v=4" width="100px;" alt="Gustavo Mendes"/><br>
        <sub>
          <b>Gustavo Mendes</b>
        </sub>
      </a>
    </td>
  </tr>

</table>
