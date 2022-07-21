# Alura - Solução do Desafio 7DaysOfCode

Minha solução de codificação do desafio #7DaysOfCode proposto pela Instituição Alura na formação de HTML e CSS.

## Indíce

**Visão Geral**
>[Desafio](#desafio) |
>[Screenshot](#screenshot) |
>[Links](#links)

**Meu Processo**
>[Construído com](#construído-com) | 
>[O que eu aprendi](#o-que-eu-aprendi) | 
>[Recursos úteis](#recursos-úteis)

**Considerações Finais** 
>[Autor](#autor) |
>[Agradecimentos](#agradecimentos)

## Visão Geral

### Desafio

O desafio foi codificar do zero um projeto disponibilizado pela instituição e fazê-lo parecer o mais próximo possível do design. Os usuários devem ser capazes de:

- Visualizar o layout ideal tanto para dispositivos mobiles quanto para desktops.

### Screenshot

![Print 7DaysOfCode](https://user-images.githubusercontent.com/105252003/180119456-cf6cb4ae-d292-420d-acea-d1331a59170e.jpg)

### Links

- URL da solução: [Index](https://github.com/beatrizslan/Projeto-Desafio-7DaysOfCode/blob/main/docs/index.html)
- URL do site: [Site](https://beatrizslan.github.io/Projeto-Desafio-7DaysOfCode/)

## Meu processo

### Construído com

- HTML5 com tags semânticas;
- Propriedades personalizadas de CSS;
- Flexbox;
- Grid Layout;
- Media Queries.

### O que eu aprendi

- Trabalhar com o CSS Grid Layout;
- Importar fontes externas;
- Utilizar variáveis no CSS;
- Adicionar a tag form com o input do tipo email;
- Trabalhar com o Flexbox;
- Desenvolver uma página responsiva, com media queries.

```HTML
<form class="rodape__contato">
    <input type="email" name="email" id="email" class="rodape__contato__email" placeholder="Seu e-mail">
    <input type="button" value="Cadastrar" class="rodape__contato__botao">
</form>
```

```CSS
.resultados {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    justify-content: center;
    gap: 2rem;
    padding: 0 3rem;
}
```

### Recursos úteis

- [Guia Completo do CSS Grid Layout](https://css-tricks.com/snippets/css/complete-guide-grid/) - Este é um artigo incrível que me ajudou a entender melhor de como funciona o Grid Layout e quais são suas propriedades. 
- [Media Queries](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/) - Este é um outro artigo do mesmo autor que também foi muito importante para eu ter uma melhor noção sobre as dimensões de telas dos dispositivos móveis.
  

## Considerações Finais

### Autor

- Codificação - [Beatriz Slan](https://beatrizslan.github.io/Projeto-Product-Preview-Card/)
- Design do Projeto - [Alura](https://www.alura.com.br/escola-programacao)
- Linkedin - [in/beatriz-slan](https://www.linkedin.com/in/beatriz-slan-2324a4173/)


### Agradecimentos

Gostaria de agradecer a Giovanna Moeller pelo desafio do #7DaysOfCode e a toda equipe envolvida da Instituição Alura, pela excelente didática, plataforma de ensino e por disponibilizar projetos reais e profissionais que me ajudam muito a praticar e aprimorar todo meu conhecimento deste mundo incrível do Front-end.
