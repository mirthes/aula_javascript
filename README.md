# aula_javascript
# introdução ao javaScript

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Minha página</title>
    <script type="text/javascript" src="js/main.js"><</script>
</head>
    <body>
        <h1>Minha página</h1>
    </body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Minha página</title>
    <script type="text/javascript" src="js/main.js"><</script>
</head>
<body onload="load()">
    <button type="button" onclick="clicked">Clique Aqui</button>
    <p id="acknowledgmant" onclick="redirect()"></p>
    <p id="mousemover" onmouseover="exchange(this)" onmouseout="comeback(this)">mouse over here</p>
    <p id="mousemover2" onmouseover="exchange(this)" onmouseout="comeback(this)">mouse over here</p>
    <p id="mousemover3" onmouseover="exchange(this)" onmouseout="comeback(this)">mouse over here</p>
    <select onchange="functionchange(this)">
        <option value="1">value 1</option>
        <option value="2">value 2</option>
        <option value="3">value 3</option>
    </select>
</body>
</html>

/*var name = "Mirthes";
var idade = 30;
var peso = 115;
var humano = true;
var humano = false;
var alunos =  ["LavYnia", "Vanessa"];
var alunos = {
   nome: "Mirthes",
   idade: 30,
   peso: 115,
   humano: true
  };
console.log(alunos);
*/

/*
var x = 10;
 var y = 5;
 var resultado = x + y;
   console.log(resultado);
   */

/*function clicked(){
    document.getElementById("acknowledgmant").innerHTML = "thanks for clicking";
    //console.log(document.getElementById("agradecimento"));
    //alert("thanks for clicking!");
}

function redirect() {
    window.open("https://enem.inep.gov.br/");
    window.location.href = "https://enem.inep.gov.br/";

}

function trocar() {
    elemento.innerHTML = "tkanks for hovering";
    //document.getElementById("elemento").innerHTML = "tkanks for hovering";
    //alert("trocar texto");
}

function voltar(element) {
    elemento.innerHTML = "mouse over here";
    //document.getElementById("elemento").innerHTML = "mouse over here";
}

function load(element) {
    alert("page loaded");
}

function functionchange(element){
    console.log(element.value);
}
*/

/*function soma(n, n1) {
    return n - n1;
}

function validaIdade(idade) {
    var validor;
    if (idade >= 18){
        validor = true;
    }else{
        validor = false
    }
    return validor;
}

var idade = prompt("qual sua idade?");
console.log(validaIdade(idade));
*/

/*function soma(n, n1) {
    return n - n1;
}

function setReplace(frase, nome, novo_nome){
    return frase.replace(nome, novo_nome)
}
alert (soma(5, 10));
alert(setReplace("vai japão", "japão", "brasil"));
*/

/*
var count;
for(count = 0; count <= 5; count++){
    alert(count);
};
*/

/*var count = 0;
while (count < 5) {
    console.log(count);
    alert(count);
    count++;
};
*/

/*
var idade = prompt("Qual sua idade");
//var idade = 18;
if (idade >= 18){
    alert("maior de idade");
}else{
    alert("menor de idade");
};
*/

/*
var frutas = [{name:"maça", cor:"vermelha"}, {name:"uva", cor: "roxo"}]
console.log(frutas);
alert(frutas[1].name);
*/

/*
var fruta = {name:"maça", cor:"vermelha"};
console.log(fruta.name);
alert(fruta.cor);
*/

/*
var liste = ["Maça", "pêra", "laranja"];
console.log(liste[0]);
console.log(liste.toString()[0]);
console.log(liste.join(" - "));
//console.log(liste.reverse());
//liste.pop();
//liste.push("uva");
//console.log(liste.length);
//console.log(liste[2]);
//alert(liste[1]);
*/

/*
var name = "Mhipereyre";
var n = 3;
var n2 = 5;
var frase = "Barcelona é o melhor time do mundo";
//alert( name + "tem" + idade + "anos");
//alert(idade + idade2)
console.log(name);
console.log(n * n2);
console.log(frase.toLowerCase());
//alert(frase.replace("Barcelona", "Real"));
*/