# [TERA]  -Aula Responsividade

### Repositório da Aula

https://github.com/ocesarmartins/responsividade-start

# Responsividade

Revisão de Responsividade

# Viewport

O viewport é a área visível de uma página da web em um dispositivo, ou seja, a parte da página que os usuários podem ver e interagir diretamente.

### Viewport Meta Tag

A meta tag viewport é uma linha de código inserida na seção **`<head>`** do código HTML de uma página da web. Ela permite controlar como o conteúdo da página é dimensionado e exibido nos dispositivos, ajudando a garantir uma experiência adequada e responsiva.

## Layout Fixo

`px` - Pixels

## Layout Fluído

`%` - Porcentagem

`auto` - Automático

`vh` - Viewport Height

`vw` - Viewport Width

### Textos Fixos

`1px` = 0.75pt

`16px` = 12pt

### Textos Fluídos

`em` - Multiplicado pelo pai

`rem` - multiplicado pelo Root (body) 

## Breakpoints

Breakpoints são pontos predefinidos nas dimensões da tela em que um design responsivo muda seu layout e comportamento para se adequar ao tamanho específico do dispositivo.

Usando o próprio Dev Tools do Chrome é possível verificar como o seu layout se comporta com os breakpoints de diferentes dispositivos.

Você também pode baixar a extensão [Window Resizer na Chrome Web Store](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh) 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/df9f6602-c684-4a9f-8c78-0ccceb82b7ef/Untitled.png)

**********************************************************Breakpoints mais comuns são:**********************************************************

1. **320px (ou menor):** Geralmente usado para smartphones em modo retrato.
2. **480px:** Outro tamanho comum para smartphones e dispositivos de menor tamanho.
3. **768px:** Muitas vezes usado para tablets em modo retrato.
4. **992px:** Ponto de mudança para dispositivos maiores, como tablets em modo paisagem e monitores menores.
5. **1200px:** Para monitores maiores e laptops.

### Media Queries

É um recurso do CSS que **permite aplicar diferentes estilos aos elementos** com base nas características do dispositivo, como tamanho da tela, **proporcionando uma experiência responsiva**.

```jsx
@media (max-width: 992px) {

}
```

### Grid de 12 Colunas

O conceito de **Grid de 12 Colunas** é uma estrutura de layout que **divide o espaço horizontal de uma página** da web **em 12 partes iguais**, oferecendo uma base organizacional flexível para o posicionamento de elementos.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8a4c51ad-8934-4b53-9c18-99a0fba02017/Untitled.png)

O Grid de 12 Colunas utiliza classes atribuídas a elementos HTML para definir larguras em porcentagens (como **.col-1** a **.col-12**), criando uma estrutura flexível onde a soma das larguras resulta em **100%**. Por exemplo, ao aplicar **.col-3**, o elemento ocupará **25%** da largura da página, permitindo layouts equilibrados e adaptáveis, essenciais para uma experiência responsiva em vários dispositivos.

```css
.col-1 {width: 8.33%;}
.col-2 {width: 16.66%;}
.col-3 {width: 25%;}
.col-4 {width: 33.33%;}
.col-5 {width: 41.66%;}
.col-6 {width: 50%;}
.col-7 {width: 58.33%;}
.col-8 {width: 66.66%;}
.col-9 {width: 75%;}
.col-10 {width: 83.33%;}
.col-11 {width: 91.66%;}
.col-12 {width: 100%;}
```

### Flexbox

Flexbox é um modelo de **layout CSS que simplifica a organização de elementos em um contêiner**, permitindo alinhamento e distribuição flexíveis em layouts responsivos, independentemente do tamanho da tela.