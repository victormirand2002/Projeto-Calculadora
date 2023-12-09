function calcularIMC(){
    let peso = document.querySelector("#peso").value
    
    let altura = document.querySelector("#altura").value
    altura= altura/100

    let imc = peso / altura** 2;

    console.log(imc)
    return imc  
}

function exibirIMC(){
    
    let imc = calcularIMC()

    if (imc < 18.5) {
        text="Você está abaixo da faixa de IMC esperado"
      } else if (imc < 24.9) {
        text="Você está na faixa de IMC esperado"
      } else if (imc < 29.9) {
        text="Você está na faixa de IMC classificada  como sobrepeso"
      } else if (imc < 39.9) {
        text="Você está na faixa de IMC classificada  como obesidade"
      } else if (imc > 39.9) {
        text="Você está na faixa de IMC classificada  como obesidade mórbida"
      }

    document.querySelector("#resultado_imc").innerHTML = `<p> ${text} <\p>` 
}
