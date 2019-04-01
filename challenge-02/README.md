// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.

function soma(x, y) {
    return x + y;
    }
    
    soma(20, 20);
    
    // Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
    var z = 0;
    z = soma(20, 40);
    z += 5;
    
    // Qual o valor atualizado dessa variável?
    65
    
    // Declare uma nova variável, sem valor.
    var indefinido;
    
    /*
    Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
    Onde VALOR é o novo valor da variável.
    */
    function adicionarValor() {
    indefinido = 100;
    return indefinido = 'O valor da variável agora é :' + indefinido;
    }
    
    adicionarValor();
    
    // Invoque a função criada acima.
    adicionarValor();
    
    // Qual o retorno da função? (Use comentários de bloco).
    
    /*
    indefinido;
    >'O valor da variável agora é VALOR'
    */
    
    /*
    Crie uma função com as seguintes características:
    1. A função deve receber 3 argumentos;
    2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
    3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
    */
    function valores(a, b, c) {
    if (a == undefined || b == undefined || c == undefined) {
    return 'Preencha todos os valores corretamente!';
    }
    return (a * b * c) + 2;
    }
    
    
    // Invoque a função criada acima, passando só dois números como argumento.
    valores(20, 10);
    
    // Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
    
    // R: 'Preencha todos os valores corretamente!'
    
    // Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
    valores(2, 2, 2);
    
    // Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
    
    // R: 10
    
    /*
    Crie uma função com as seguintes características:
    1. A função deve receber 3 argumentos.
    2. Se somente um argumento for passado, retorne o valor do argumento.
    3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
    4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
    5. Se nenhum argumento for passado, retorne o valor booleano `false`.
    6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
    */
    function valoresCondicional(d, e, f) {
    if (d !== undefined && e == undefined && f == undefined) {
    return d;
    }
    else if (d !== undefined && e !== undefined && f == undefined) {
    return d + e;
    }
    else if (d !== undefined && e !== undefined && f !== undefined) {
    return (d + e) / f;
    }
    else if (d == undefined && e == undefined && f == undefined) {
    return false;
    } else {
    return num;
    }
    }
    
    // Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.
    
    valoresCondicional();//false
    valoresCondicional(10, 20);//30
    valoresCondicional(10, 20, 30);//1