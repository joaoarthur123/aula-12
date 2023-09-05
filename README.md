# aula-12
joaoarthur-17
/ this is a js file
// joao arthur

//1 sera impresso 10, 50,e na b na nada pois a foncao so foi declarada.

//2 ela deixa todas as letras minusculas e se a palavra cenoura esta na frase. b. eu gosto de cenoura,true, cenoura e bom pra vista , true,cenouras crescem na terra.
//3.
//a. 
function exercicio () {
    const linhas = "Eu sou Caio, tenho 23 anos, moro em São Paulo e sou estudante.";
    console.log(linhas);
}

//b 
function retornaTextoComParamatros(nome, idade, cidade, profissao) {
    return `eu sou ${nome}, tenho ${idade} anos, moro em ${cidade} e sou ${profissao}`;
}
console.log(retornaTextoComParamatros("arthur", 16, "portao", "estudante"));

//4,
function soma(valor, valor2){
    return valor + valor2;
}
console.log(soma(5 + 10));

function somar(valores, valores2){
    const somar2 = valores + valores2;
    console.log(somar2);
}
function dividir(valores, valores2){
    const dividir2 = valores / valores2;
    console.log(dividir2);
}
function subtrair(valores, valores2){
    const subtrair2 = valores - valores2;
    console.log(subtrair2);}

    function multiplicar(valores, valores2){
        const multiplicar2 = valores * valores2;
        console.log(multiplicar2);
    }
multiplicar(15,10);
dividir(15,10);
somar(15,10);
subtrair(15,10);
