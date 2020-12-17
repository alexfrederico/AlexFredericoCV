# Alex Frederico CV
## Currículo produzido no LaTeX utilizando a ferramenta Overleaf


# LaTeX

LaTeX, é um sistema de preparação de documentos para uma composição tipográfica de alta qualidade. É mais frequentemente usado para documentos técnicos ou científicos de médio a grande porte, mas pode ser usado para quase qualquer forma de publicação.

LaTeX não é um processador de texto! Em vez disso, o LaTeX encoraja os autores a não se preocupar muito com a aparência de seus documentos, mas a se concentrar em obter o conteúdo correto.

O LaTeX é baseado na ideia de que é melhor deixar o design do documento para os designers do documento e permitir que os autores continuem escrevendo os documentos.

## Recursos do LaTeX
* Composição de artigos de periódicos, relatórios técnicos, livros e apresentações de slides.
* Controle sobre grandes documentos contendo secções, referências cruzadas, tabelas e figuras.
* Composição de fórmulas matemáticas complexas.
* Composição tipográfica avançada de matemática com AMS-LaTeX.
* Geração automática de bibliografias e índices.
* Editoração multilíngue.
* Inclusão de arte e processo ou cor especial.
* Usando fontes PostScript ou Metafont.

https://www.latex-project.org/

# Overleaf

Startup e empresa social que desenvolve ferramentas de autoria colaborativas modernas para cientistas. O seu produto principal é um editor colaborativo online em tempo real para artigos, teses, relatórios técnicos e outros documentos escritos na linguagem de marcação LaTeX.

## Requisitos e compilação
### (Caso não utilize o Overleaf)

* pdflatex + biber + pdflatex
* AltaCV usa fontes [`impressionantes`](http://www.ctan.org/pkg/fontawesome) e [`acadêmicas`](http://www.ctan.org/pkg/academicons); eles estão incluídos no TeX Live 2016 e no MikTeX 2.9;
* O carregamento de `academicons` é opcional: habilite-o adicionando a opção `academicons` a `\documentclass`;
* Use a opção foto normal para obter uma foto normal (ou seja, não circular);
* Use a opção `ragged2d` para ativar as hifenizações enquanto mantém o texto justificado à esquerda; terminações de linha serão, portanto, menos irregulares e mais esteticamente agradáveis;
* Agora pode ser compilado com pdflatex, XeLaTeX and LuaLaTeX!;
* No entanto, se estiver usando `academicons`, você _deve_ usar XeLaTeX ou LuaLaTeX. Se o documento compilar, mas os ícones não aparecerem no PDF de saída, tente compilar com LuaLaTeX;
* Os exemplos aqui usam a fonte [Lato](http://www.latofonts.com/lato-free-fonts/).

v1.1.5 (1 December 2018), by LianTze Lim (liantze@gmail.com),
[AltaCV](https://www.overleaf.com/latex/templates/altacv-template/trgqjpwnmtgv)