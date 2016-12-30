# leccion18

ciclo for:
//retorna la suma partiendo de 0

function forLoop(limit) {
    var suma=0;
    for(var i=0;i<=limit;i++)
    {
            suma=suma+i;
     }
return suma;
}

Numeros Pares del 1 al 100:

function sumaPares(n) {
    var suma = 0
    for (var i=0 ; i<=n; i+=2)
    {
         suma=suma+i ;
     }
    return suma ;

}

Factorial de un Número:

function factorial(n) {
var fact=1;
    if(n<0 || n==0)
        return null;            
    else {
        for(var i=1; i<=n;i++)
            {
                fact=fact*i;
            }
    }
    return fact;
}

Multiplicar:

function stringMultiplicar(n) {
var r1=0;
var resultado="";
    for(var i=1; i<=10 ;i++)
        {
            r1=n*i;
            resultado +=n+"x"+i+"="+r1;
            if((i+1)<=10)
                {
                   resultado +="/";
                }
        }
    return resultado;

}

Palidrome:

function casiPalindrome(palabra) {
    var tam = palabra.length;
    var palindrome;
    var conta = 0;
     for (i=0, j=tam-1; i<tam/2, j>tam/2; i++, j--){
         if(palabra[i] !=palabra[j]){
             conta++;
         }
      }
         if(conta<=2){
            palindrome=true;
         }else{
             palindrome=false;
         }
     return palindrome;
}




