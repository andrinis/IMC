# IMC
Programa simples para calculo de IMC.

<meta charset="UTF-8">
<script>

    function pulaLinha() {
        document.write("<br>");
        document.write("<br>");
    }
function mostra(frase) {
    document.write(frase);
    pulaLinha();
}
    function calculaImc(altura, peso){
        return peso / (altura * altura);
        //retornara o calculo.


    }
    var nome = prompt("Informe seu Nome");
    var alturaInformada = prompt(nome + ", Informe sua altura");
    var pesoInformado = prompt(nome + ", Informe seu peso");

    var imc = calculaImc(alturaInformada, pesoInformado);

    document.write( nome + " , O  seu imc calculado É " + imc);
</script>
