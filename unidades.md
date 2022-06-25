# Unidades

## Unidade fixas ou absolutas: px, cm, mm;

    - cm e mm: O css tem suporte porém quase não são usadas para web design;
    - px: É uma unidade fixa "normalizada", ela se adapta a densidade de pixels do device em questão;
    
## Unidades de viewport: vw, vh, vmin, vmax;
    - vw: porcentagem da largura da tela;
    - vh: porcentagem da altura da tela;
    - vmin: porcentagem do menor lado da tela;
    - vmax: porcentagem do maior lado da tela;

## Unidades de fonte: rem, em;
    - rem: Trabalhará com um fonte relativa ao elemento HTML raiz (body);
    - em: Trabalhará com um fonte relativa ao elemento pai (div, ou qualquer elemento que esteja englobando o filho em questão);

## Caso especial: % (porcentagem);
    - %: É semelhante as unidades de viewport (vw, vh, ...) porém não considera como relativo o elemento pai mais próximo, ao inves do tamanho da tela;
