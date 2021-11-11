# Modelo TCC EMAp

Escrever o Trabalho de Conclusão de Curso (TCC) é, em geral, um trabalho que exige
tempo e estudo. Esse trabalho, muitas vezes, é dificultado por regras que
devemos seguir, no caso segundo a Associação Brasileira de Normas Técnicas.
Essas regras são importantes para a padronização do formato do TCC.
Entretanto, este é uma facilitação que o
[LaTeX](https://www.latex-project.org/) nos permite: basta que o padrão
exista. Para nossa ajuda, o projeto [abnTeX2](https://www.abntex.net.br/) foi
elaborado para nos ajudar. Dentre um dos modelos, existe o [Trabalho
Acadêmico](https://github.com/abntex/abntex2/blob/master/doc/latex/abntex2/examples/abntex2-modelo-trabalho-academico.tex)
que se encaixa no que queremos desenvolver. 

Na Fundação Getulio Vargas, o modelo a ser seguido tem como base o [seguinte
manual](https://github.com/lucasmoschen/modelo-tcc-emap/tree/main/regras)
escrito por Amanda Maria Medeiros López Ares em colaboração com Andréa Guaranha Giannelli,
Márcia Nunes Bacha, Maria do Perpétuo Socorro
Almeida, Mercedes Ramos Silva Neta. Assim, os estudantes da Escola de
Matemática Aplicada (EMAp) devem seguir o mais próximo possível deste manual. Por
esse motivo, existe esse modelo de TCC para a EMAp. 

## Contribuidores 

[@FredsoNerd](https://github.com/FredsoNerd): See [#4](https://github.com/lucasmoschen/modelo-tcc-emap/issues/4).

## Como começar a usar? 

- [Por onde começar?](https://github.com/abntex/abntex2/wiki/PorOndeComecar)
  Vale a pena a leitura desta página. 
- [Instalação abnTeX](https://github.com/abntex/abntex2/wiki/Instalacao): se
  você tem uma das distribuições LaTeX como TeX Live ou MacTeX,já estar´a
- Download desse repositório. O seu ambiente de trabalho será o arquivo TeX
  `trabalho-academico.tex`. 

As partes do trabalho estão segmentadas, mas o arquivo principal contém todos
os ponteiros necessários. 

## O que preciso alterar para meu trabalho? 

- Título, autor, área de estudo, orientador e data de aprovação. 
- Se não houver subtítulo, exclua nos arquivos `capa_folha_rosto.tex` e `folha_aprovacao.tex`
  o comando `\imprimirsubtitulo`. 
- Para impressão considere alterar `oneside` para `twoside` na configuração do
 `\documentclass`. 

## Contribuições 

Sua ajuda é muito importante! Para contribuir, criar Issues ou Pull Requests
ajudam muito na manutenção do projeto. 

## Customizações do abnTeX 

Todas as instruções de customização podem ser encontradas em [Como
customizar](https://github.com/abntex/abntex2/wiki/ComoCustomizar). Os
[manuais de uso](https://www.ctan.org/pkg/abntex2) podem ser úteis. 
