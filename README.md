# Reconhecimento de linguagem de sinais usando CNN
Esse artigo foi escrito para a disciplina de Aprendizado Profundo (IMD1104), do curso de Bacharelado em Tecnologia da Informação (BTI) da Universidade Federal do Rio Grande do Norte (UFRN), possuindo [Ivanovitch Silva](https://github.com/ivanovitchm) como professor.

Trabalho realizado por:
- <a href="https://github.com/alvarofpp">Álvaro Ferreira Pires de Paiva</a>
  - Matrícula: 2016039162
  - E-mail: alvarofepipa@gmail.com

Artigos escritos no Medium:
- [Reconhecimento de linguagem de sinais usando CNN](https://alvarofpp.medium.com/reconhecimento-de-linguagem-de-sinais-usando-cnn-75bb9a703fe3).

# Contexto
Atualmente mais de 10 milhões de cidadãos brasileiros sofrem com algum tipo de surdez e a previsão é que nos próximos anos essa quantidade de pessoas surdas aumente cada vez mais. Com isso em mente, se faz cada vez mais necessário o desenvolvimento de aplicações que auxiliem no dia a dia de pessoas com deficiência auditiva.

A aplicação em questão que irei desenvolver nesse artigo é uma inteligência artificial que deve ser capaz de classificar corretamente sinais com as mãos que representam números de 0 a 5. A partir desse modelo, podemos expandir ele para os demais números, letras e outros símbolos, podendo, por exemplo, implementar isso como funcionalidade em aplicativos de chamada por vídeo, no qual o usuário faz os símbolos com as mãos e o aplicativo transcreve eles para texto.
