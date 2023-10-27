# Teste de PSI 1 - Turno 1 - Versão 1

## Informação do aluno

    Nome: ...filipe sousa

Teste termina às 10:45.

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### P1. Indica o que é impresso pelo seguinte código. Justifica a tua resposta

    int i = 5 / 2;
    
    Console.WriteLine($"*\t{i}");

P1 - Resposta

    ...o codigo ira imprimir"* 2. isso acontece porque a expressão "5/2"resulta em 2.5, mascomoa variavel i édotipoint, a parte decimal é truncada, resultandoem2. o comando console.writelineiraexibir o asterisco seguindo de um tab (\t) e o de i, que é 2.

### P2. Considera o seguinte código com um *bug*

    string s = "2.5";
    int i = Convert.ToInt32(s);

    Console.WriteLine(i);

### Indica uma possível correção para que o código não apresente erros. Explica porque foi necessário fazer essa correção

P2 - Resposta

    ...Você pode usar Converter quando tiver uma cadeia de caracteres que deseja converter em int . int i = Convert.ToInt32("1234"); A conversão e a transmissão lançarão uma exceção se falharem. ou seja, isso ainda lançará uma exceção, não retornará 0: Convert.ToInt32("1234NonNumber");

### P3. Escreve um programa que solicite ao utilizador dois números inteiros e apresente a sua soma. Caso o resultado seja um número divisível por 3, deve também ser impressa a mensagem "Múltiplo de 3!"

P3 - Resposta

    ...csharp
    using system

    classprogram
    {
    static void main()
    {
    console.writeline("2")
    int num1 = 2;
    convert.ToInt32(console.readline())

    console.writeline("4");
    int num 2 = 4;
    converet.ToInt32(console.readline());

    int soma = num1 +num2;
    console.writeline("a soma é : "+ soma);
    if( soma %3 ==0)
    {
    console.writeline("multipo de 3!");
    }}}

### P4. Tens um repositório git criado localmente, onde estás no ramo 'master'. Queres associá-lo ao repositório remoto contido no url 'https://github.com/PSI/OMeuRepositorioRemoto'. Queres também alterar o nome do ramo atual para 'main'. Deverás enviar os *commits* já feitos localmente para o repositório remoto. Indica os comandos necessários

P4 - Resposta

    ...git remote add origin https://github.com/filssboy/filipe.git
git branch -M main
git push -u origin main
