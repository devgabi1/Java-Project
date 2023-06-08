public class Calculadora {
boolean Erro;
String Mensagem;
public double Somar(double N1, double N2)
{ double R;
R= N1 + N2;
Erro = false;
Mensagem = " Soma executada com sucesso !!";
return (R);
}
//------------------------------------------------
public double Subtrair(double N1, double N2)
{ double R;
R= N1 - N2;
Erro = false;
Mensagem = " Subtração executada com sucesso !!";
return (R);
}
//------------------------------------------------
public double Multiplicar(double N1, double N2)
{ double R;
R= N1 * N2;
Erro = false;
Mensagem = " Multiplicação executada com sucesso !!";
return (R);
}
//------------------------------------------------
public double Dividir(double N1, double N2)
{ double R;
Erro = false;
Mensagem = " Divisão executada com sucesso !!";
if (N2 == 0)
{
R = 0;
Erro = true;
Mensagem = " Não é possível dividir por ZERO !!";
}
else
R = N1 / N2;
return (R);
}
