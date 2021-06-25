//ANOTAÇÕES IMPORTANTES, DICAS E APRENDIZADOS//

1# NO HTML -> Sempre que utilizar <input>, utilizar também a tag <label></label> = Para facilitar a localização dos motores de busca (google) e também por questões de acessibilidade.

2# NO HTML -> NUNCA esqueça de colocar alt="#descrição da imagem" dentro da tag <img>! 

3# ZERAR CSS PADRÃO DO NAVEGADOR:
*{
    margin: 0;
    padding: 0;
    border: none;
    text-decoration: none;
    box-sizing: border-box;
}

>> DICA DE RESPONSIVIDADE E CÁLCULO DE TAMANHO <<

<1rem = 16px>

16px - 100% 
1px  - x

16x = 100
x = 100/16 = 6.25% = 1px

COLOCAR no HTML <font-size: 6.25%> então... 1rem = 1px)

>> VARIÁVEIS NO CSS <<

--nome-da-variavel: #cor;

chamar a var => var(--nome-da-variavel);

>> DICA VALIOSA <<

Experimente usar a tecla ALT+TAB para alternar facilmente entre suas telas durante a criação!

------------------------------------------------------------

NO CSS:
> :nth-child(#)  <= SELECIONA APENAS OS "FILHOS" ESPECIFICADOS POR NÚMEROS (1, 2, 3...). 
Assim, podemos estilizar apenas as tags filhas que queremos, sem afetar outras que não queremos.


>>DICA ATALHOS VS CODE <<

<TAB> PARA ARRUMAR A IDENTAÇÃO DO SEU CÓDIGO (MOVER PARA A DIREITA), PARA MOVER PARA A ESQUERDA = <SHIFT+TAB>