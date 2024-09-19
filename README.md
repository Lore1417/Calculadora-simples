# Calculadora-simples

<!doctype html>
<html lang="pt-BR"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Calculadora Simples</title> 
 </head> 
 <body> 
  <h1>Calculadora Simples</h1> 
  <script>
        let n1 = Number(prompt("digite um número: "));
        let n2 = Number(prompt("digite um segundo número "));
        const resultado = n1 + n2
        let resultado2 = n1 * n2
        let resultado3 = n1/ n2
        let resultado4 = n1 - n2
        console.log(`${n1} + ${n2} = ${resultado} `);
        console.log(`${n1} × ${n2} = ${resultado2}`);
        console.log(`${n1} ÷ ${n2} = ${resultado3}`);
        console.log(`${n1} - ${n2} = ${resultado4}`);
        </script> 
