# even-or-odd-game
This is my first project in JavaScript 

function make(){
    let start= prompt("escolha par ou impar: ")

if (start=== 'p'){
    alert("eu escolho impar \n")
   let r= prompt("digite um numero de 0 a 10\n:")
   const meunum = parseInt(r)
   const num = Math.floor(Math.random() * 11)
   alert("eu escolho " + num)
   let soma = meunum + num
   alert("a soma é " + soma)
   if(soma===0){alert("indefinido, reiniciando...") + make()}
   else if(soma%2=== 0){alert("Parabéns,vc ganhou!")}
   if (soma%2 > 0){alert("vc perdeu!")} 
   }

    else if (start=== 'i'){
    alert("eu escolho par \n")
   let r= prompt("digite um numero de 0 a 10\n:")
   const meunum = parseInt(r)
   const num = Math.floor(Math.random() * 11);
   alert("eu escolho " + num)
   let soma = meunum + num
   alert("a soma é " + soma)
   if(soma===0){alert("indefinido, reiniciando...") + make()}
   else if(soma%2 > 0){alert("Parabéns,vc ganhou!")}
   if (soma%2 === 0){alert("vc perdeu!")} 
}}


let start= prompt("escolha par ou impar: ")

 if (start=== 'i'){
    alert("eu escolho par \n");
   let r= prompt("digite um numero de 0 a 10\n:")
   const meunum = parseInt(r)
   const num = Math.floor(Math.random() * 11)
   alert("eu escolho " + num)
   let soma = meunum + num
   alert("a soma é " + soma)
   if(soma===0){alert("indefinido, reiniciando...") + make()}
   else if(soma%2 > 0){alert("Parabéns,vc ganhou!")}
   if (soma%2 === 0){alert("vc perdeu!")} 
}

else if (start=== 'p'){
    alert("eu escolho impar \n");
   let r= prompt("digite um numero de 0 a 10\n:")
   const meunum = parseInt(r)
   const num = Math.floor(Math.random() * 11)
   alert("eu escolho " + num)
   let soma = meunum + num
   alert("a soma é " + soma)
   if(soma===0){alert("indefinido, reiniciando...") + make()}
   else if(soma%2=== 0){alert("Parabéns,vc ganhou!")}
   if (soma%2 > 0){alert("vc perdeu!")} 
   
}
