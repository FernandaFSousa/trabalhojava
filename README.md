# trabalhojava
trabalho java

Questão 01  // Algoritmo "Escadas"
 Var
 p, x1, x, lin, col, degr: inteiro
Inicio
 escreva ("Quantidade de degraus: ")
 leia (degr)
 x:=degr
x1:=1
 para lin de 1 até degr passo 1 faça
   para col de 1 até x passo 1 faça
   escreva(" ")
    fimpara
 x:=x-1
 para p de 1 até x1 passo 1 faça
      escreva("#")
 fimpara
 x1:=x1+1
escreval("")
 fimpara
 fimalgoritmo 

02 QUESTÃO 
public static boolean validaSenha(String senha) {

        String regex = "^(?=.*[0-9])"
                + "(?=.*[a-z])(?=.*[A-Z])"
                + "(?=.*[!@#$%^&*()-+])"
                + "(?=\\S+$).{6}$";
       ///senhas
        Pattern p = Pattern.compile(regex);
       

        if (senha == null) {
            return false;
        }
      /// senha return
     

        Matcher m = p.matcher(senha);

        return m.matches();
    }   
public static void main(String[] args) {
   ///
        Locale.setDefault(Locale.US);
        Scanner scanner = new Scanner(System.in);

        System.out.println("n");
        double n = scanner.nextDouble();

        if ( n == 1) {
            System.out.println("     *");
        }
      /// imprime senha 
03 QUESTÃO 
 

   

// java 
piblic class programa {

public static void main (String[] args)
String s1= "roma";
String s2="roma";

if(isAnagroma(s1,s2))
System.out.println("É anograma!");
/// imprime anograma 
else

System .out.println("É anograma!");

}

private static boolean isAnograma(String s1,String s2) { 

int r = 0;

for(int i = 0; i <s1.length(); i++)
r = r ^ s1.charAT(i);
/// sequencia de sequencia de bits
for(int i = 0; i <s2.length(); i++)
r = r ^ s2.charAT(i);
//operador exclusivo
return (r == 0);

}
///todos bits serão zerados 


