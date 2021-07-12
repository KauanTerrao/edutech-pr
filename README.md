# projeto_edutech_PR
Meu primeiro Projeto.


BackUp do JavaScript aula 1 e 2:

Aula 1:

<meta charset="utf-8">

<h1>Meu primeiro teste!</h1>

<br>
Ancoramento de HiperLinks é usado o (<.a href " o link"> a mensagem onde vai ancorar o link e "<./a>" para fechar o código).
igual o exemplo abaixo:

Seria isso um programa? Descubra visitando Alura <a href="http://www.alura.com.br">aqui</a>

<script>

    alert("Isso sim é um programa");

</script>

<br>

Pop-Up sem instruções, aspas somente com texto, vai dar o mesmo resultado(sem palavras no pop-up)

<br>

<br>

<script>

	alert();

</script>

<script>

	alert("");

</script>

<script>

	document.write("Se a vida te der um limão");
	document.write("Você faz um");
	document.write("<br>");
	document.write("limão");

</script>

Observação: pode escrever sem aspas, mas esta sujeito a posiveis erros!

<br>

OU menos bonita

<br><br>

<script>

	document.write("Se a vida te der um limão <br> Você faz um <br> Limão")

</script>

<br><br>

pular uma linha é <.br>(sem o ponto final dentro do códico)

<br>

pular mais de uma, tem duas formas, primeira <.br> em cada linha que vai pular e a segunda é, você escreva a quantidade de linha em código que vai pular em uma linha como <.br><.br>.

<br><br><br>

Retornando ao código do JavaScript document.write, agora com funções matemáticas sendo mais, menos ,vezes, divido, etc.(espaçamento entre digitos e fuções opcional).

<script>
	
	document.write(18 + 20);
	document.write(18 - 20);
	document.write(18*2);
	document.write(18/3);

</script>

Para fazer a media ter que ser essa formula assim com o proximo código a seguir

<script>

	document.write((30+30+60)/3);

</script>

<br><br>

contatenação

<script>

	document.write("18" + "20");


</script>

ocorrerá a junção desses dois textos, pois o JavaScript o reconhece como texto e não como número, por causa das aspas.

<br>

Contatenação de strings(palavras) e números e com media:

<script>

	document.write("O total das idades são" + (30 + 60 + 10));
	document.write("A media das idades é" + (30 + 60)/3);

</script>

Contatenação que breake line(pular linha)

<br>

<script>

	document.write("flavio nasceu em " + (2021 - 40) + "<br>");
	document.write("joaquim nasceu em " + (2021 - 60) + "<br>");
	document.write("Barney nasceu em " + (2021 - 35) + "<br>");

</script>

<br>

Para cotentação com porcentagem é:

<script>

	document.write("Eu acertei "+(15/50*100) +"%");

</script>

<br>

Variavel, forma de alteral tudo relacionado por um código(ano,més,data.etc)
Exemplo o "ano" é o modulo a ser pesquisado, tudo que tiver "ano" digitado vai ser alterado na variavel.

<br>

<script>

	var ano = 2021;
	document.write("Flávio tem " + (ano - 1977) + " anos" + ("<br>"));
	document.write("Joaquim tem " + (ano - 1996) + "anos" + ("<br>"));
	document.write("Barney tem " + (ano - 1976) + "anos" + ("<br>"));

</script>

Variavel: Excessões, A seguir os comandos vão estão programados pelos anos que você escolher no código anterior

<script>

var ano = 2021;
	document.write("Flávio tem " + (ano - 1977) + " anos" + ("<br>"));
	ano = 2022; 
	document.write("Joaquim tem " + (ano - 1996) + "anos" + ("<br>"));
	document.write("Barney tem " + (ano - 1976) + "anos" + ("<br>"));

</script>

Por exemplo a tabuada:

<script>
   var tabuada = 8
    document.write(tabuada + " vezes 1 é " + tabuada * 1+ "<br>");
    document.write(tabuada + " vezes 2 é " + tabuada * 2+ "<br>");
    document.write(tabuada + " vezes 3 é " + tabuada * 3+ "<br>");
    document.write(tabuada + " vezes 4 é " + tabuada * 4+ "<br>");
    document.write(tabuada + " vezes 5 é " + tabuada * 5+ "<br>");
    document.write(tabuada + " vezes 6 é " + tabuada * 6+ "<br>");
    document.write(tabuada + " vezes 7 é " + tabuada * 7+ "<br>");
    document.write(tabuada + " vezes 8 é " + tabuada * 8+ "<br>");
    document.write(tabuada + " vezes 9 é " + tabuada * 9+ "<br>");
    document.write(tabuada + " vezes 10 é " + tabuada * 10+ "<br>");

</script>

<script>

	var ano = 2021
	document.write("Flávio tem " + (ano - 1977) + " anos" + ("<br>"));
	ano = 2022
	document.write("Joaquim tem " + (ano - 1996) + " anos" + ("<br>"));
	document.write("Barney tem" + (ano - 1976) + " anos" + ("<br>"));
	var media = (44 + 26 + 46)/3;
	document.write(" A média das idades é " + media);

</script> 

E para arredondar o numero vamos usar o Math.round(), lembrando o Match sempre deve começar com maiúscula, ou mais legivel

<script>

	var ano = 2021
	document.write("Flávio tem " + (ano - 1977) + " anos" + ("<br>"));
	ano = 2022
	document.write("Joaquim tem " + (ano - 1996) + " anos" + ("<br>"));
	document.write("Barney tem" + (ano - 1976) + " anos" + ("<br>"));
	var media = (44 + 26 + 46)/3;
	document.write(" A média das idades é " + media + ("<br>"));
	document.write(' A média das idades é ' + Math.round (media) + ("<br>"));
    var idadeFlávio = 44
    var idadeJoaquim = 26
    var idadeBarney = 46
    var media = (idadeFlávio + idadeJoaquim + idadeBarney)/3
    document.write("A média das idades é " + Math.round(media) + ("<br>"));
    var nome = "Flávio";
    document.write("A idade de " + nome + " é " + idadeFlávio);

</script> 

Dica interesante é:
Usar a variavel para pular as linhas e escolher a quantidade de quantas pular, sem modificar todos os códigos já escritos.

<script>
	var puloDeLinha = "<br>";
	document.write("Flávio tem 26 anos");
	document.write(puloDeLinha);
	document.write("Joaquim tem 40 anos");
	document.write(puloDeLinha);
	document.write("Barney tem 20 anos");
	document.write(puloDeLinha);
</script> 

Criação de funções, deve escrever dentro das chaves o que sua função criada deve exercer como o código de pular linha.
Nota tem que por parenteses para ser classificado como função e não variavel e os parenteses devem estar vazios porque conta como uma area reservada para um texto ou um calculo, igual o document.write, fazer sempre no inicio pois a função só é exercida em ordem de cima para baixo e não de baixo para cima.

<script>
	function pulaLinha(){

		document.write("<br>")
	}
	document.write("Flávio tem 26 anos");
	pulaLinha();
	document.write("Joaquim tem 40 anos");
	pulaLinha();
	document.write("Barney tem 20 anos");
</script>

Comentário, é uma forma didática de falar para o programa não o executá-lo para fins como observação, correção,etc. Ele é usado dentro do JavaScript nos document.write, ele é representado por //, como a seguir:

<script>
	// document.write("Barney tem 20 anos")
</script>

Dica para a criação de novas funções: Criar uma função que trabalhe com document.write, para ser mais rápido na digitação, mais resumido o comando e organizado.
<br><br>
Para fazer essa função tem que definir uma variavel identicadentro dos parenteses da função como o exemplo que usei "cleitin", pode escrever qualquer variavel o resultado será o mesmo.
<br><br>
<script>
	function mostrar(cleitin){
		document.write(cleitin);
	}

	function pulaLinha(){
		document.write("<br>");
	}
	mostrar("Olá esse é um programa Alpha");
	pulaLinha();
	mostrar("Usando o Java Script, consegui criar um novo código");
</script> 
<br><br>
Observação: Uma função pode ter como efeito charmar outra função para ser operada, basta incluir a outra função ñas chaves de outra função. Como o exemplo que eu mesmo fiz para mim mesmo. 
<br>
<script>
	function pulaLinha(){
		document.write("<br><br>");
	}
	function mostrar(cleitin){
		document.write(cleitin);
		pulaLinha();
	}
	mostrar("Olá");
	mostrar("Seja Bem Vindo!");
</script>
Fazendo uma função para calcula o IMC:
OBSERVAÇÃO IMPORTANTE: NO LUGAR DA VIRGULA DEVESSE SEMPRE USAR O PONTO FINAL E NÃO VIRGULA, SE NÃO O RESULTADO VAI SER ALTERADO.
<script>
	function mostra(frase){
		document.write(frase);
	}
	function calculaImc(peso, altura){
		var imc = peso / (altura * altura);
		mostra("O IMC calculado é " + imc);
	}
	calculaImc(60, 1.80);

</script> 
Para completar a função, sempre deve por uma função de imprimir o resultado ou ele só vai calcular e não vai aparecer nada e vai ser concluido como codogo em função correta.
Da para calcular o IMC de duas pessoas em uma função? Sim usasse o código a seguir:
Inves de só: "PESO, ALTURA" 
vai ser: "PESO1 , ALTURA1, PESO2, ALTURA2"
Observação: Para funcionar irá por no "calculaImc" assim "calculaImc(60, 1.80, 58, 1.90)"
<script>
	function pularAsLinha(){
		document.write("<br><br><br>")
	}
	function mostra(frase){
		document.write(frase);
	}
	function calculaImc1(peso1, altura1, peso2, altura2){
		pularAsLinha();
		var imc1 = peso1 / (altura1 * altura1);
		var imc2 = peso2 / (altura2 * altura2);
		var totalImc = (imc1 + imc2);
		mostra("O IMC calculado é " + totalImc);
	}
	calculaImc1(60, 1.80, 58, 1.90);

</script> 
<br><br>
Aprendendo a função "return":
Objetivo:Ao calcularmos o IMC dentro da função, e a variável IMC guardar o resultado, a palavra return deixa disponível à esquerda da variável o resultado que foi calculado pela função.
<br><br>
<script>
	function mostra(frase){
			document.write(frase + "<br>");
	}
	function calculaImc2(altura, peso) {

    var imc = peso / (altura * altura);
    return imc;

}

var imcFlavio = calculaImc2(1.71, 73);
var imcAmigo = calculaImc2(1.72, 68);

mostra(imcFlavio);
mostra(imcAmigo);
</script> 
Minha observação: Ao executar o calculo com uma variavel o resultado se torna a variavel, assim esperando ser chamado pelo resultado exato que foi processado, ai entra a fu~nção "return" ela disponibiliza o var em numero e não em função para processar.
<br>
Explicação do site: o valor de uma variável pode ser retornado por uma função. O problema é que a função por padrão não retorna, então, precisamos explicitar seu retorno através da instrução return. Uma outra forma tambem que irá dar o mesmo resultado é usa o "return" no lugar do "var", por exemplo:
<br><br>
<script>
	function pulaLinha(){
		document.write("<br><br>");
	}
	function mostra(frase){
			document.write(frase);
			pulaLinha()
	}
	function calculaImc2(altura, peso) {

    return = peso / (altura * altura);

}

var imcFlavio = calculaImc2(1.71, 73);
var imcAmigo = calculaImc2(1.72, 68);
var totalImc = imcFlavio+ imcAmigo;
mostra(imcFlavio);
mostra(imcAmigo);
mostra(" a soma dos IMCs é " + totalImc);
</script> 
É uma forma mais resumida e facil de fazer.
Ou até mais resumida:
<script>
	function pulaLinha(){
		document.write("<br><br>");
	}
	function mostra(frase){
			document.write(frase);
			pulaLinha()
	}
	function calculaImc2(altura, peso) {

    return = peso / (altura * altura);

}
var totalImc = calculaImc2(1.71, 73);+ calculaImc2(1.72, 68);
mostra(" a soma dos IMCs é " + totalImc);
</script> 
Ambos da no mesmo, a escolha é do gosto do programador.
<br>
Variavel mutavel pelo usuario: adicione a função prompt no console do navegador e tambem no bloco de programação:
<script >

function mostra(frase) {

    document.write(frase);
}

function pularlinhas(){

    document.write("<br>");

}

function calculaImc (altura,peso){
    var imc=Math.round(peso/(altura*altura));
    return imc

} 
var nome= prompt("Informe seu nome");
var informeSuaAltura=prompt("Informe sua Altura");
var informeSeuPeso=prompt("Informe seu peso");
var resultadoimc=calculaImc(informeSuaAltura,informeSeuPeso);
mostra("<h1><big>O resultado do seu imc é:   </h1></big>"+resultadoimc)
</script>
~~Dica~~
Não cometa mais esse erro de esquecer de colocar o recebe depois da variavel e o antes do prompt;
Se ouver mais problemas consulte a pagina teste_de_prompt no Sublime mesmo.
<br><br><br>
Corvertendo texto em números: (Esse primeira formula é a qual eu descobri, recomendo pois é mais facil, a seguir ire por a formula do professor)
Nota: Ambas as formulas são funcionais.
====================================================================Eu:=====================================================================
<script>

function pulaLinha() {

    document.write("<br>");
    document.write("<br>");
}

function mostra(frase) {

    document.write(frase);
    pulaLinha();
}

var vitorias = prompt("Entre com o número de vitórias.");
var empates = prompt("Entre com o número de empates.");
var pontos = (vitorias * 3 + (empates * 1));

mostra("O total dos pontos é " + pontos);
</script>
 ===============================================================Professor:==================================================================
<script>
function pulaLinha() {

    document.write("<br>");
    document.write("<br>");
}

function mostra(frase) {

    document.write(frase);
    pulaLinha();
}

var vitorias = parseInt(prompt("Entre com o número de vitórias."));
var empate = parseInt(prompt("Entre com o número de empates."));
var pontos = (vitorias * 3) + empate;
mostra("O total dos pontos é " + pontos);
</script>
OBSERVAÇÃO: O função "parseInt" funciona somente para converter texto como "68768" em números, caso contrario se for uma palavra ele vai dar NaN, o meu código alternativo que fiz pode não funciionar em algumas ocassiões como a conversão de: "4"(ele será reconhecido como "quatro") para 4 ou qualquer outro numero.
===========================================================Formula==========================================================================
Formula:
var "o nome do item que será convertido" = parseInt("o item que será convertido");

Observação: o conceito vai ser o mesmo como os das variaveis.
============================================================FIM.============================================================================

Condições: Por exemplo quero fazer que o programa de uma mensagem para cada resultado que foi dado ou somente 1, sera usado "if"(se em inglês) a variante e superior(>), inferior(<) ou igual(==);
NOTA: Tomar cuidado com o "igual" pois deve ser comandado com 2 recebe(=), se não a função não funcionará.

===========================================================FORMULAS=========================================================================
FORMULA:
if(Exemplo) > 28){
	(MENSAGEM, CALCULO, ALERTA, ETC.)
}                                                  (Maior que 28).
if(Exemplo < 28){
	(MENSAGEM, CALCULO, ALERTA, ETC.)              (Menor que 28).
}
if(Exemplo) ==28){
	(MENSAGEM, CALCULO, ALERTA, ETC.)
}                                                  (Igual que 28).
if(Exemplo >=28){
	if(Exemplo <= 38){

	}
}                                                  (Entre 28 e 38)
Versão simplificado do "entre" para ficar mais intuitivo
:
if(Exemplo >=28 && <=38){
	mostra("MENSAGEM DE AVISO")                     (Entre 28 e 38)
	ESSA FORMA É MAIS FACIL E ORGANIZADA.
	

============================================================FIM.============================================================================

Exemplo funcional: o 28 é o total de pontos que o time consigui ano passado.
<script>
function pulaLinha() {

    document.write("<br>");
    document.write("<br>");
}

function mostra(frase) {

    document.write(frase);
    pulaLinha();
}

var vitorias = parseInt(prompt("Entre com o número de vitórias."));
var empate = parseInt(prompt("Entre com o número de empates."));
var pontos = (vitorias * 3) + empate;
mostra("O total dos pontos é " + pontos);

if(pontos > 28)
	mostra("Seu time foi melhor do que ano passado.");
if(pontos < 28)
	mostra("Seu time foi pior que o ano passado.");
if(pontos == 28)
	mostra("Seu time teve o mesmo resultado no ano passado.");
</script>   
Entre um valor e outro no "if". Por exemplo o programa do IMC:
NOTA: a variavel esta localizada na ultimo código
<script>
	function pulaLinha(){
		document.write("<br>");
	}
	function mostra(frase){
		document.write(frase);
	}
	function calculaImc(altura,peso){
		return Math.round(peso/ (altura*altura));
	}
	var nome= prompt("Informe seu nome");
	var InformeSuaAltura = prompt(nome + ", informe sua altura (Use ponto final como virgula!)");
	var InformeSeuPeso = prompt(nome + ", informe seu peso");
	var imc = calculaImc(InformeSuaAltura,InformeSeuPeso);
	mostra(nome + ",o resultado do seu IMC é " + imc);
	pulaLinha()
if(imc < 18.5){
	mostra("Seu indice esta abaixo do recomendado, cuidado!");
	pulaLinha();
	mostra("Possiveis casos, má-nutrição ou algumas doenças <br> Procure uma médico com urgência!")
}
if(imc > 35){
	mostra("Seu indice está acima do recomendado, cuidado!");
	pulaLinha();
	mostra("Possiveis casos, nutrição acima do normal, falta de exercícios fisícos, sedentárismos,etc. <br> Procure um médico ou um nutricionista com urgência!");
}
if(imc >= 18.5){
	if(imc <= 35){
		mostra("Muito bem, seu indice esta normal do recomendado, continue assim com: Pratica de exercícios e boa alimentação, e não se esqueça de consultar um médico regularmente!");
	}
	}
</script>
<br><br>
Jogo do adivinha: Nesse próximo programa irei usar todos os conhecimentos adquiridos como: var, if e function.
<br>
<script>
	function pulaLinha(){
			document.write("<br>");
		}
	function mostra(frase){
			document.write(frase);
			pulaLinha();
	}

	var numeroPensado = 5;
	var chute = parseInt(prompt("Digite o o seu núnero!"))
	if(chute == numeroPensado){
		mostra("Boa, você acertou!");
		}
	if(chute != numeroPensado){
		mostra("Não foi dessa vez, palhaço!")
	}
</script> 
<br>
Outra forma mais simplificada: Usando o código "else", no lugar do segundo "if".
<script>
	function pulaLinha(){
			document.write("<br>");
		}
	function mostra(frase){
			document.write(frase);
			pulaLinha();
	}

	var numeroPensado = 5;
	var chute = parseInt(prompt("Digite o o seu núnero!"))
	if(chute == numeroPensado){
		mostra("Boa, você acertou!");
		} else {
			mostra("Não foi dessa vez, palhaço!")
		}
</script> 
E outro código interessante o "Math.random" ele se encaixa pefeitamente no jogo adivinha pois ele gera um número aleatório contantemente a cada momento que recarregar a pagina.
OUTROS CÓDIGOS MOSTRADOS NA AULA:

1  "console.log(variavel)" = serve para consultar o programa selecionado no console;

2  "else" = servirá para diminuir a escrita do código como no "se for um numero destinado do programa" resultará em true ou verdadeiro caso contrário usaremos o "else".

3  "Math.random" = gera um número aleatório no código, se não for multiplicado por 1 ele sera com 0,694984549... e por um 6,94984549, por 10 será 6,94...  .Para se tornar um numero inteiro use "Math.round", e será assim: var "nome da variavel" Math.round(Math.random() * 10);
===========================================================================================================================================
var "nome da variavel" Math.round(Math.random() * 10);
==============================================Conteúdos adicionais=========================================================================
Criação de senha: Se for de numero deve por o "parseInt" antes do "prompt", para a converção de texto para número.
############################################################DICA############################################################################
LEMBRANDO: A função prompt ela sempre vai por o que o usuário escrever como texto, até mesmo número, a função "parseInt" serve para destinar o texto como número, ELE NÃO FUNCIONARÁ SE TIVER PALAVRAS NO LUGAR DOS NÚMEROS.
<script>
var senha = prompt("Insira a senha.");
if(senha == "cleitonfodastico"){

	alert("Acesso liberado");
}

	else { 

	alert("Acesso negado.");
}
</script>
============================================================================================================================================
Repetição de funçoes iguais infinitamente, com quantia indefinida:
EXEMPLO:
<script>
	function pulaLinha(){
		document.write("<br>");
	}
	function mostra(frase){
		document.write(frase);
	}
	function titulo(palavras){
		document.write("<h3>" + palavras + "</h3>");
		pulaLinha();
		pulaLinha();
		pulaLinha();
	}
	var anoCopa = 1930;
	while(true) {
		alert("Teve copa em " + anoCopa);
		anoCopa = anoCopa + 4;
	}
	alert("FIM.")
</script> 
CURIOSIDADE:Esse programa acima nunca vai imprimir o "alert(FIM.)" pois o código vai ficar mandando resultados de 4 em 4 anos para sempre, se não colocar um limite.


Para limitar esse código infinito  deverá fazer assim a seguir:
<script>
	function pulaLinha(){
		document.write("<br>");
	}
	function mostra(frase){
		document.write(frase);
	}
	function titulo(palavras){
		document.write("<h3>" + palavras + "</h3>");
		pulaLinha();
		pulaLinha();
		pulaLinha();
	}
	var anoCopa = 1930;
	while(anoCopa <= 2016) {
		alert("Teve copa em " + anoCopa);
		anoCopa = anoCopa + 4;
	}
	alert("FIM.");
</script> 
DEVE SE APLICAR AS FUNÇÕES MENOR(<) E IGUAL(=) NO CÓDIGO "while", PARA SERVIR COMO LIMITADOR;
OUTRAS CURIOSIDADES DO "while": 
1# ELE DEVE TER "while(true);{"outras funções ou códigos"}" PARA UMA FUNÇÃO DE REPRODUZIR O CÓDIGO INFINITAMENTE E SE FOR "false"? ELE NÃO IMPRIME NENHUM CÓDIGO OU FUNÇÃO, POIS MESMO SE O CÓDIGO ESTIVER CORRETO O FALSE É A DEFINIÇÃO DE INVALIDEZ.
2# O "while" ELE LÊ A  PRIMEIRA LINHA DEPOIS DA CHAVE("{ }") ATÉ A ULTIMA E DEPOIS RETORNA COM O RESULTADO DA PRIMEIRA LEITURA DANDO O CÓDIGO A FORMA DE SER INFINITO NAQUELA FUNÇÃO, CLARO SEM DELIMITAR UM LIMITE. 

Pode se fazer tambem sem o "alert", como o "mostra", a diferença que o programa não irá ficar tão cansativo com tantos Poup-Ups:
<script>
	function pulaLinha(){
		document.write("<br>");
	}
	function mostra(frase){
		document.write(frase);
	}
	function titulo(palavras){
		document.write("<h3>" + palavras + "</h3>");
		pulaLinha();
		pulaLinha();
		pulaLinha();
	}
	var anoCopa = 1930;
	while(anoCopa <= 2016) {
		mostra("Teve copa em " + anoCopa);
		anoCopa = anoCopa = 4;
	}
	mostra("FIM.");
</script> 
NOTA: Se a variavel do anoCopa for maior que a limitação do "while", ele simplesmente irá pula diretamento para o FIM, independente se for Poup-Ups ou imprimido no programa!
CUIDADO: Como a função "mostra" se você tirar o limitador do "while" e por "true" ele poderá travar o navegador ou o computador:

Não se deve fazer:
<.script>
	function pulaLinha(){
		document.write("<br>");
	}
	function mostra(frase){
		document.write(frase);
	}
	var anoCopa = 1930;
	while(true) {
		mostra("Teve copa em " + anoCopa);
		anoCopa = anoCopa = 4;
	}
	mostra("FIM.");
<./script>

Ou podemos fazer o usuário do programa escolher o ano limite, como a seguir:
<script>
	function pulaLinha(){
		document.write("<br>");
	}
	function mostra(frase){
		document.write(frase);
	}
	var limite = parseInt(prompt("Entre com o ano limite."));
	var anoCopa = 1930;
	while(anoCopa <= limite) {
		mostra("Teve copa em " + anoCopa);
		anoCopa = anoCopa = 4;
	}
	mostra("FIM.");
</script> 
Excessão de alguns numeros, exemplo de 30 para 40 sem o 33 e o 37.

NOTA: Não usar o ponto e virgula no "if", caso contrario o problema vai ser sempre relatado como erro de syntax do "else" e não será facil encontrar o problema.
<script>
	function pulaLinha(){
		document.write("<br>");
	}
	function mostra(frase){
		document.write(frase);
	}
	var numero = 30;
	
	while(numero <= 40){
		
		if(numero == 33) {
			numero = numero + 1;
		}
		if(numero == 37) {
			numero = numero + 1;
		}
		else {
		mostra(numero + "<br>");
		numero = numero + 1;
		}
	}

	
	mostra("FIM.");
</script> 
Pagina com senha. Esse modelo tem uma quantidade limitada de tentativas, que é 3, caso necessite usar só mude os códigos que tem 3 para a quantidade desejada.

<script>
    var loginCadastrado = "alura";
    var senhaCadastrada = "alura321";

    var maximoDeTentativas = 3;
    var tentativaAtual = 1;

    while(tentativaAtual <= maximoDeTentativas){
            
        var loginInformado = prompt("Informe seu login");
        var senhaInformada = prompt("Informe sua senha");
        
        if( loginCadastrado == loginInformado && senhaCadastrada == senhaInformada ) {
    		alert("Bem-vindo ao sistema " + loginInformado);
            tentativaAtual = maximoDeTentativas; // Aqui não tem nenhum número pois se não iria repetir o login, como se tivesse errado.
              
        } else {
                   
            	if(tentativaAtual == 3){
                alert("Número de tentaqtivas permitido ultrapassado.");
            } else {
                alert("Login inválido. Tente novamente.")
           	}
        }
    tentativaAtual = tentativaAtual + 1
}    
</script>
============================================================================================================================================
Conteúdos que podemos usar o "while":
por exemplo se um usuário por a idade escrita com dez no "prompt", a página dirá que o resultado será "NaN", para isso iremos usar uma função para saber se um valor é NaN precisamos usar uma função específica, a isNaN. Essa função recebe um parâmetro e retorna true ou false caso o valor seja NaN ou não.
======================================================Tabuada com "while"===================================================================
<script>
	function pulaLinha(){
		document.write("<br>");
	}
	function mostra(frase){
		document.write(frase);
		pulaLinha();
	}
	var multiplicador = 1;
	var valorInformado = parseInt(prompt("Digite o número de qual tabuada deseja."));
	while(multiplicador <= 10){
	multiplicador = multiplicador + 1;
	}
	mostra("FIM.")
</script> 
********************************************************************************************************************************************
OUTRA FORMA DE REPETIR É USANDO O "for" POR EXEMPLO:
Nota: mais abaixo está a forma teórica de formação do código!
<script>
	function pulaLinha(){
		document.write("<br>");
	}
	function mostra(frase){
		document.write(frase);
		pulaLinha();
	}
	for(var valorInformado = parseInt(prompt("Digite o número de qual tabuada deseja.")); multiplicador <= 10; multiplicador = multiplicador + 1){
		mostra(valorInformado * multiplicador);// Nesse caso usei o parseInt para ser mais dinâmico, onde o usuário escolhe o valor!
	}
	mostra("FIM.")
</script> 
EXPLICAÇÃO DO CÓDIGO:
	
	for(valor a ser multiplicado = parseInt(prompt("Digite o número de qual tabuada deseja."));limitador, nesse caso foi usado menor igual a 10(<=); "a sequência da ser contado, nesse caso foi de 1 em 1, pode ser maior é só mudar o ultimo parametro que é o 1 no exemplo"){
		mostra("o valor a ser multiplicado "* "o limitador");
		NOTA:Lembre-se se não por o mostra() ele irá calcular mas não irá imprimi-lo.
	}
Fim
conclussão: É um código mais resumido e mais simples de se usar ele pode substituir o "while" até um ponto mas se for em regra de excessão deve se usar o "while".
**********************************************-***********************************-*********************************************************

ATALHO
Em caso de fazer por exemplo:
var total = 0;
total = total + 1 //  será 1 o resultado final e se usar...
total++;  

ele terá o mesmo resultado que o anterior, so que de forma mais abreviada, assim como os exemplos de "for" dá para usar essa abreviação assim.
<script>
	function mostra(frase){
		document.write(frase + "<br>");
	}
	for(var valorInformado = parseInt(prompt("Digite o número de qual tabuada deseja.")); multiplicador <= 10; multiplicador++){
		mostra(valorInformado * multiplicador);// Percebe-se que o multiplicador invés de "multiplicador = multiplicador + 1";, dá para abreviar com multiplicador++; , para poupar mais a escrita e gastar menos tempo.
	}
	mostra("FIM.")
</script> 
--------------------------------------------------------------------------------------------------------------------------------------------
 ATIVIDADE

 for( var i = 0; i < 10; i++ ) {
    alert( "O resultado é " + (2 * i) );
}
Converta-o para usar a instrução while. Lembre-se: o resultado do programa tem que ser o mesmo!
<script>
	function mostra(palavra){
		document.write(palavra);
	}
    var i = 0;
while( i < 11) {
    mostra( "O resultado é " + (1 * i) + "<br>");
    i++;    
}
    mostra("FIM")
</script>
--------------------------------------------------------------------------------------------------------------------------------------------============================================================================================================================================
ACUMULANDO VALORES:

<script>
	function mostra(palavra){
		document.write(palavra);
	}
    var totalFamiliares = parseInt(prompt("Informe a quantidade de familiares."));
    var numero = 1;
    var totalIdades = 0;
    while(numero <= totalFamiliares){
    	var idade = parseInt(prompt("Informe a idade do familiar."));
    	totalIdades = totalIdades + idade;
    	numero++;
    }
    var mediaDasIdades= totalIdades/totalFamiliares;
    mostra("A média das idades é " + mediaDasIdades);
    mostra("FIM");
</script>
------------------------------------------------***************************************-----------------------------------------------------
                                                 Jogo do Adivinha, código novo: "break"

Nota: O código "break" tem como função anular o looping que o "while" fornece, como um jogo de adivinha se você acertar sem o "break" ele ainda vai continuar perguntando, para resolver isso o "break" se encaixa nesse programa teste abaixo:
<script>
    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }
    var numeroPensado = Math.round(Math.random() * 10);
    var tentativas = 1
    while(tentativas <= 3){
        var numeroChute = parseInt(prompt("Qual número estou pensando"));
    
        if(numeroChute == numeroPensado){
            mostra("Você acertou!");
            break; // Ele vai mandar reeler o código de baixo para cima onde ele se encontra e anulará o "while" e pulará nesse programa para o "FIM" , tambem se encaixaria se por "tentativas = 4" excedendo o limite e finalizando o "while" ou usar o "for no lugar do "while".
        } else {
            mostra("Você errou.");
        }
        tentativas++;
    }

</script>
--------------------------------------------------------------------------------------------------------------------------------------------
REPETIÇÕES ANINHADAS:
Nesse conteúdo vai aprender a repetir palavras, mas não as agrupadas tipo "oi", e sim imprimir "o" varias vezes na mesma linha dando o resultado de "ooooooooooo".

Nota: o objetivo é fazer 3 linha com 10 ásteriscos somente com 1.

<script>
    function pulaLinha() {

        document.write("<br>");
        document.write("<br>");
    }

    function mostra(frase){

        document.write(frase);
        pulaLinha();
    }

    for(var linha = 1; linha <= 3; linha++) {
    	for(var coluna = 1; coluna <=10; coluna++){
    		document.write("*");// document.write porque se for mostra ele pula linha como esta informado na função, pode ser o mostra tambem so usou pois não pula linha.
    	}
		pulaLinha();
    }
</script>

--------------------------------------------------------------------------------------------------------------------------------------------
Código "parseFloat"

Aprendemos a utilizar parseInt() para converter um texto em número. Certo? Contudo, ele converte um texto para um número inteiro e nem sempre queremos abdicar dos números decimais. Vejamos um exemplo:

var numero = parseInt("12.13");

O valor de numero será 12. Para que as casas decimais sejam mantidas, usamos o parseFloat():

var numero = parseFloat("12.13");
O valor de numero será 12.13.



------------------------------------------------------------------------------------------------------------------------------------------

Campo de texto e botão:


Códigos:
*Gerar uma barra de texto para o usuário escrever é: <input/>

*Gerar um botão com texto para o usuário acessar é: <button>Compare com meu segredos</button>
Nota: Esse código não precisa por aspas para por as palavras, somente por dentro do código.

Mas esses códgos estão no mundo HTML então não funcionarão diretamente no mundo JavaScript, para isso usarremos um código que "puxa" a função <.input/> para o mundo JavaScript ele necessita dessa formula:
Formula para transferir função do mundo HTML para o JavaScript=

	var NOME1 = document.querySelector("input");

Explicação: *

*O NOME1 pode ser o nome da função para ficar mais facil de lembrar;

*Deve-se seguir exatamente a nomenclatura do querySelector, isso inclui o "S" maíusculo tambem;

*Lembrando deve ser dentro do mundo JavaScript para o código funcionar.


###########################################################################################################################################

EXEMPLO:
1) Faça um jogo de adivinha com que apareça uma barra de texto e um botão de pesquisar ou enviar:
 
 <input/> 
<button>Verificar resposta</button> 
<script>
    var segredo = 5;
    var input = document.querySelector("input");
   
    function verifica(){
            
            if(input.value == segredo){
        
        document.write("Você acertou!" + "<br>");
    } else {
        document.write("Você errou." + "<br>");
    }
    }
   
    var button = document.querySelector("button");

    button.onclick = verifica;// onclick("no clicar" em português) FAZ COM QUE AO CLICAR EXECUTE ALGO, no programa ele recebe a função "verifica" que se destina aos códigos acima, não deve ter parentesses de parâmetros pois ele executa antes da hora de clicar no botão. 

</script> 

FIM.
------------------------------------------------------------------------------------------------------------------------------------------

Melhorando a usabilidade do programa: 
	
A próxima melhoria que faremos em nosso programa implica em fazermos com que o campo de texto seja esvaziado quando o usuário errar uma tentativa. Para isso, após a função verifica(), declararemos que o input.value receberá uma string em branco:

<input/>
<button>Compare com o meu segredo</button>

<script>
    var segredo = 5;

    var input = document.querySelector("input");

    function verifica() {

        if(input.value == segredo) {

        alert("Você ACERTOU!");
        } else {

        alert("Você ERROU!!!!!!!!");
        }

                input.value = "";// com essa string vazia ela irá esvaziar a barra de texto assim que apertar "ok" no Poup Up.

    }

    var button = document.querySelector("button");

    button.onclick = verifica;

</script>

Seria bom se quando errassemos o jogo o programa já entrasse na barra de texto sem nós clicarmos com o mouse, esse código é assim:

<input/>
<button>Compare com o meu segredo</button>

<script>
    var segredo = 5;

    var input = document.querySelector("input");

    function verifica() {

        if(input.value == segredo) {

        alert("Você ACERTOU!");
        } else {

        alert("Você ERROU!!!!!!!!");
        }

                input.value = "";
                input.focus();// com o "focus" formará o programa mais dinâmico, pois não precisará clicar novamente para o usuario possa responder com mais rapidez.

    }

    var button = document.querySelector("button");

    button.onclick = verifica;

</script>

Mas entrar no programa e ter que ir clicar na barra para responder é chato. Teria alguma forma de fazer isso automatico sem precisar clicar? Sim e seria o seguinte:


<input/>
<button>Compare com o meu segredo</button>

<script>
    var segredo = Math.round(Math.random() * 10);

    var input = document.querySelector("input");
        input.focus();// pondo o "focus" aqui fará com que ele forme um looping para que não precise clicar na barra.

    function verifica() {

        if(input.value == segredo) {

        alert("Você ACERTOU!");
        } else {

        alert("Você ERROU!!!!!!!!");
        }

                input.value = "";
                input.focus();

    }

    var button = document.querySelector("button");

    button.onclick = verifica;

</script>
FIM

##############################################################################################################################################################################################################################################################################################################################################################################################################################

ARMAZENANDO DADOS:

Para se tornar mais prático o aumento de informação, tipo o jogo de adivinha se quiser por 2,3,4,5... ou muito mais números necessitará de muitos "if", e ai onde o colchetes("[]") nos ajudará a formar um arrey, vejá o código a seguir:

NOTA: O JavaScript tem sua contagem iniciada do 0, como se tiver três números e quiser selecionar o primeiro deverá começa com o 0.


<input/>
<button>Compare com o meu segredo</button>
<script>
    var segredos = [5,6,7,8,9,10];// com os "if" teria muitos poup-ups avisando que você não acertou

    var input = document.querySelector("input");
        input.focus();

    function verifica() {
        for(var posicao = 0; posicao < 4; posicao++){//Por que 4? Menor que quatro significa que ele irá parar no 3 que na ordem do JavaScript conta como 4 pois ele lê 0,1,2,3...

            if(input.value == segredos[posicao]) {

                alert("Você ACERTOU!");
                break;
            } else {

                alert("Você ERROU!!!!!!!!");
            }
        }
        input.value = "";
                input.focus();
        
    }

    var button = document.querySelector("button");

    button.onclick = verifica;

</script>
Pronto tá feito, mas ficar mandando varios avisos de "ERROU" mesmo acertando alguma fica esquisito, para tirar isso é só remover o "else" assim:
<input/>
<button>Compare com o meu segredo</button>
<script>
    var segredos = [5,6,7,8,9,10];// com os "if" teria muitos poup-ups avisando que você não acertou

    var input = document.querySelector("input");
        input.focus();

    function verifica() {
        for(var posicao = 0; posicao < 4; posicao++) {//Por que 4? Menor que quatro significa que ele irá parar no 3 que na ordem do JavaScript conta como 4 pois ele lê 0,1,2,3

            if(input.value == segredos[posicao]) {

                alert("Você ACERTOU!");
                break;
            } 
        }
        input.value = "";
        input.focus();
        
    }

    var button = document.querySelector("button");

    button.onclick = verifica;

</script>

Mas e se mudar o numero de "segredos" você normalmente não lembrará de mudar o numero do limite, mas o arrey é camarada ele pode ser usado com o código aseguir:

<input/>
<button>Compare com o meu segredo</button>
<script>
    var segredos = [5,6,7,8,9,10,1];// Agora pûs o 1, para não mudar o limitador basta fazer no lugar dele "segredos.length"

    var input = document.querySelector("input");
        input.focus();

    function verifica() {
        for(var posicao = 0; posicao < segredos.length; posicao++) {// o "length" retorna o valor de valores que a variavel "segredos" contem
            if(input.value == segredos[posicao]) {

                alert("Você ACERTOU!");
                break;
            } 
        }
        input.value = "";
        input.focus();
        
    }
    alert("VOCÊ ERROU!!!!"); // sobre o problema de não aparecer o "errou" quando errasse, necessitava fazer igual esta no exemplo de agora.
    var button = document.querySelector("button");

    button.onclick = verifica;

</script>

*******-----------------------********************====RESOLUÇÃO DE ERROS====*************-----------------****************----------------
 Com o "length" facilita pois ele automatiza o programa sem que haja a necessidade de que você faça manuntenção no código, e por fim o problema apresentado que não dava a mensagem que havia errado necessita por uma "alert" no fim do "for". como mostra acima.

 Mas olha o que acontece depois de acertar ainda manda o aviso que "ERROU", para isso necessitaremos fazer um "var" com "achou" de exemplo com "false" dando o resultado assim:"var achou = false"

 NOTA: Para ficar mais compreensivel farei o programa abaixo:

<input/>
<button>Compare com o meu segredo</button>

<script>

    var segredos = [5,7,10,2,3];

    var input = document.querySelector("input");
        input.focus();

    function verifica() {

    var achou = false;// COMO SABEMOS "false" NO JavaScript ELE INVÁLIDA O CÓDIGO QUE O APRESENTA, ENTÃO SUMIRÁ A MENSAGEM DE "ERROU".

    for(var posicao = 0; posicao < segredos.length; posicao++) {

        if(input.value == segredos[posicao]) {

            alert("Você ACERTOU!");
            achou = true;
            break;
        }
    }

    if(achou == false) {
        alert("Você ERROU!");// AQUI USAREMOS O "if" COMO CÓDIGO COMPARATIVO, "achou == false" PONDO JUNTO O "alert" COM A MENSAGEM DE "ERROU".
    }

    input.value = "";
    input.focus();

    }

    var button = document.querySelector("button");

    button.onclick = verifica;

</script>
==========================================================================================================================================
Há tambem outras formas de incrementar numeros no arrey, com o "push" que empura o dado para ele, assim como no exemplo abaixo:

<script>
	//5,7,10,2,3; esses são os mesmos numeros do exemplo anterior, não tem ligação alguma com o código.
	var segredos = []
	segredos.push(5);
	segredos.push(7);
	segredos.push(10);
	segredos.push(2);
	segredos.push(3);
</script> 

Mas isso seria um trabalho desnecessario para por números "fixos" por isso essa forma anterior dá para trabalhar com números "livres" como o exemplo a seguir que usarei "(Math.round(Math.random() * 10);".

<script>
	var segredos = []
	segredos.push(Math.round(Math.random() * 10));
	segredos.push(Math.round(Math.random() * 10));
	segredos.push(Math.round(Math.random() * 10));
	segredos.push(Math.round(Math.random() * 10));
	segredos.push(Math.round(Math.random() * 10));
</script> 

Outra forma mais resumida e mais simples seria criar uma "function", assim:

<script>
	
	function sorteia(){
		return Math.round(Math.random() * 10);
	}
	function sorteiaNumeros(quantidade){
		var segredos = []; // esse segredo não irá interferir com o segredo externo pois ele faz parte da function.
	}
	var segredos = []
	segredos.push(sorteia());
	segredos.push(sorteia());
	segredos.push(sorteia());
	segredos.push(sorteia());
	segredos.push(sorteia());
</script> 

Esse código irá gerar todos os números aleatóriamente, mas por ser muita informação podemos simplificalá com uma function e caso haver que esses números iram se duplicar, isso será um problema para o programa por isso temos que fazer o seguinte:

<script>
	
	function sorteia(){
		return Math.round(Math.random() * 10);
	}
	function sorteiaNumeros(quantidade){
		var segredos = [];
		var numero = 1;
		while(numero <= quantidade){
			segredos.punsh(sorteia());
			numero++;
		}
		return segredos;
	}
	var achou = false;

    for(var posicao = 0; posicao < segredos.length; posicao++) {

        if(input.value == segredos[posicao]) {

            alert("Você ACERTOU!");
            achou = true;
            break;
        }
    }

    if(achou == false) {
        alert("Você ERROU!");
    }

    input.value = "";
    input.focus();

    
    var button = document.querySelector("button");

    button.onclick = verifica;

</script>
 
 Mas ainda repete os numeros e ainda aparece o 0, então deverá formar assim:


<input/>
<button>Compare com o meu segredo</button>

<script>
    function sorteia() {

       return Math.round(Math.random() * 10);

    }

    function sorteiaNumeros(quantidade) {

        var segredos = [];

        var numero = 1;

        while(numero <= quantidade) {

              var numeroAleatorio = sorteia();
              var achou = false;

              if (numeroAleatorio !== 0) {
                     for(var posicao = 0; posicao < segredos.length; posicao++) {

                           if(segredos[posicao] == numeroAleatorio){
                                achou = true;
                                break;
                           }

                     }

                     if (achou == false) {
                           segredos.push(numeroAleatorio);
                           numero++;
                     }
              }

        }

        return segredos;

    }

    var segredos = sorteiaNumeros(3);

    console.log(segredos);

    var input = document.querySelector("input");
    input.focus();

    function verifica() {

       var achou = false;

       for(var posicao = 0; posicao < segredos.length; posicao++) {

              if(input.value == segredos[posicao]) {

                     alert("Você ACERTOU!");
                     achou = true;
                     break;
              } 
       }

       if(achou == false) {

              alert("Você ERROU!");
       }

       input.value = "";
       input.focus();

    }

    var button = document.querySelector("button");

    button.onclick = verifica;

</script>
