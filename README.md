Pergunta 1 - Resposta: O valor será 91.

Pergunta 2 - Linguagem escolhida: Javascript.
Código:

	let a = 0;
        let b = 1;
        let c = 0;
        let arrayfibonacci = [];
    
        let numerotestado = 33

        while (c <= numerotestado){
            c = a + b;
            a = b;
            b = c;
            arrayfibonacci.push(c)
        };

        if(arrayfibonacci.includes(numerotestado)){
            console.log('O número pertence a sequência de Fibonacci!');
        } else {
            console.log('O número não pertence a sequência de Fibonacci!')
        }


Pergunta 3 - a) 9, b) 128, c) 49, d) 100, e) 13, f) 200

Pergunta 4 - Foi definido apenas que não posso ver a lampada apenas da sala onde estou atualmente, então existe a possibilidade de conferir quais são as lampadas acesas das outras salas onde não estou. Nesse caso, não seria nem necessário sair da sala, apenas virando os interruptores duas vezes ja seria o suficiente para descobrir a qual sala todos estão associados.

Pergunta 5 - Linaguem escolhida: Javascript.
Código:

        let texto = "texto";
        let textoInvertido = '';

        for (let i = texto.length - 1; i >= 0; i--) {
            textoInvertido += texto[i];
        }

        console.log(textoInvertido);
