body{/* corpo */
  width: 100%; /* largura*/
  height: 100vh; /* altura */
  margin:0; /* margem baixa */
  background-color: #B0E0E6; /* coloração do fundo */
  font-family: Tahoma; /* fonte familia */
  font-size: 16px; /* tamanho da fonte */
}

h1, p{
  margin: 1em auto; /* Margem para o Cabeçario */ 
  text-align: center ; /* alinhamento do texto */

}

form{
  width: 60vw; /* altura de todo seu codigo viewport, sendo a primeira para altura e a segunda para largura */
  max-width: 500px;
  min-width: 300px;
  margin: 0 auto; /* a confirmaçao do meu min e max width AUTO*/
  padding-bottom: 2em; /* largura do espaço da minha margem baixa*/
}

fieldset{ /* barra de conjutos  */
  border: none;/*  */
  padding: 2rem 0; /* altura e largura */
  border-bottom: 3px solid #F0FFF0; /* tamanho e coloração */
}

fieldset:last-of-type { /* isola o ultimo fieldset */ 
  border-bottom: none;
}

label { /* organiza seu conjunto de input */
  display: block;
  margin: 0.5rem 0;
}

option{
  background-color: #F0FFF0;
}

input,
textarea,
select {/*acerta sua caixa  de imput textarea select */
  margin: 10px 0 0 0;
  width: 100%;
  min-height: 2em;
}

input, textarea {
  background-color: #F0FFF0;/* cor da barra */
  border: 1px solid #B0E0E6;/*cor das bordas */
  color: black; /*cor do texto do input */
}

.inline { /* acerta o formato da minha classe inline */
  width: unset;
  margin: 0 0.5em 0 0;
  vertical-align: middle;
}

input[type="submit"] { /*design do botão submit */
  display: block;
  width: 60%;
  margin: 1em auto;
  height: 2em;
  font-size: 1.1rem;
  background-color: #F0FFF0;
  border-color:#B0E0E6;
  min-width: 300px;
}
input[type="file"] {  /* ??????? */
  padding: 1px 2px;
}





