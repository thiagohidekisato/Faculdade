# Atividade 4: Seção Crítica por espera ocupada

Implemente, usando linguagem C com PThreads ou JavaThreads, o algoritmo de Manna-Pnueli que implementa entrada em SC por algoritmo Cliente-Servidor. Demonstre o funcionamento do código para 2 e 4 threads como processos clientes, realizando o correto incremento em uma determinada variável global.

> _OBSERVAÇÃO:_ Para provar que a seção crítica no código implementado de fato funciona, pode-se fazer um teste em dois códigos, onde o primeiro não implementa controle de seção crítica nos processos clientes (comentar o pré-protocolo, por exemplo) e o segundo faz a correta implementação da seção crítica nos processos clientes, e comparar o valor final esperado para a variável global envolvida. Nestes testes faça com que a seção crítica seja executada inúmeras vezes pelos processos clientes (normalmente da ordem de bilhão de vezes).
