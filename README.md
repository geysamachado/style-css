@import url('https://fonts.googleapis.com/css2?family=Krona+One&family=Montserrat:wght@400;600&display=swap');

:root {
    --cor-primaria: #000000;
    --cor-secundaria: #F6F6F6;
    --cor-terciaria: #22D4FD;
    --cor-hover: #272727;

    --fonte-primaria: 'Krona One', sans-serif;
    --fonte-secundaria: 'Montserrat', sans-serif;
}
*{
    margin: 0;
    padding: 0;
}

body{
    box-sizing: border-box;
    background-color: var(--cor-primaria);
    color: var(--cor-secundaria);
}
.cabecalho{
    padding: 2% 0% 0% 15%;
}
.cabecalho__menu{
    display: flex;
    gap: 80px;
}
.cabecalho__menu__link{
    font-family: var(--fonte-secundaria);
    font-size: 1.5rem;
    font-weight: 600;
    color: var(--cor-terciaria);
    text-decoration: none;
}
.apresentacao{
    padding: 5% 15%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
}
.apresentacao__conteudo{
    width: 50%;
    display: flex;
    flex-direction: column;
    gap: 40px;
}

.apresentacao__conteudo__titulo{
    font-size: 2.25rem;
    font-family: var(--fonte-primaria);
}
.titulo-destaque{
    color: var(--cor-terciaria);
}
.apresentacao__conteudo__texto{
    font-size: 1.5rem;
    font-family: var(--fonte-secundaria);
}

.apresentacao__links{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    gap: 32px;
}
.apresentacao__links__subtitulo{
    font-family: var(--fonte-primaria);
    font-weight: 400;
    font-size: 1.5rem;
}
.apresentacao__links__link{
    display: flex;
    justify-content: center;
    gap: 16px;
    border: 2px solid var(--cor-terciaria);
    width: 50%;
    text-align: center;
    border-radius: 8px;
    font-size: 1.5rem;
    font-weight: 600;
    padding: 21.5px 0;
    text-decoration: none;
    color: var(--cor-secundaria);
    font-family: var(--fonte-secundaria);
}
.apresentacao__links__link:hover{
    background-color: var(--cor-hover);
}

.apresentacao__imagem {
    width: 50%;
}

.rodape{
    color: var(--cor-primaria);
    background-color: var(--cor-terciaria);
    padding: 24px;
    text-align: center;
    font-family: var(--fonte-secundaria);
    font-size: 1.5rem;
    font-weight: 400;
}

@media (max-width: 1200px) {
    
}
        .cabecalho {
            padding: 10%;

        }


        .apresentacao {
            flex-direction: column-reverse; 
                   padding: 5% 
        }

        .apresentacao__conteudo {
            width: auto;
        }
