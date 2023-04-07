# DesafioBootcampDIOOrangeTechBackEnd
Um registro dos desafios de códigos do Bootcamp DIO Orange Tech BackEnd, minha resoluções dos desafios.

Primeiro desafio:

Desafio
Seu sobrinho começou a ganhar mesada dos pais. No auge dos seus 8 anos recebendo 50 reais por mês, ele quer saber quanto terá se juntar todo o dinheiro, sem gastar nada, durante alguns meses. E você, como um bom tio com habilidades de programação, vai criar um programa que com as entradas do seu sobrinho vai calcular automaticamente a quantidade de dinheiro que ele terá em X meses.

Entrada
A entrada será o número de meses que o sobrinho polpará o dinheiro.

Saída
A saída deve ser o valor que o sobrinho terá ao final dos meses. (sem as aspas)

MINHA RESOLUÇÃO:
import java.util.Scanner; 
    
public class Program {
    public static void main(String[] args) {
        Scanner leitor = new Scanner(System.in);
        int entrada = leitor.nextInt();
        int mesada = 50;
        int saida = entrada * mesada;
        
            System.out.println(saida);
           
Segundo Desafio:

Desafio
Você foi contratado para criar um gerenciador de pacotes. Porém, o que restou para você fazer foi o contador de porcentagem de download dos pacotes. Mas como o espaço para essa informação ficou pequeno, a empresa optou por fazer uma escala de 10 – 1. Então a escala será 1 = 10%, 2 = 20%, 3 = 30% e etc.
Para cada 10% de download, o programa deve printar, em sequência e sem espaços, uma barra “/”.

Entrada
A entrada será um número que representará a porcentagem

Saída
A saída serão as barras sem espaços entre elas. 

MINHA RESOLUÇÃO:

import java.util.Scanner; 
    
public class Program {
    public static void main(String[] args) {
        Scanner leitor = new Scanner(System.in);
        int tamanho = leitor.nextInt();
     
                // TODO: Crie a condição necessária para que, de acordo com o tamanho, seja printado no console barras representando o download
        switch(tamanho){
          case 1:
            System.out.println("/");
            break;
          case 2:
            System.out.println("//");
            break;
          case 3:
            System.out.println("///");
            break;
          case 4:
            System.out.println("////");
            break;
          case 5:
            System.out.println("/////");
            break;
          case 6:
            System.out.println("//////");
            break;
          case 7:
            System.out.println("////////");
            break;  
          case 8:
            System.out.println("/////////");
            break;
          case 9:
            System.out.println("/////////");
            break;
          case 10:
            System.out.println("///////////");
            default:
            
        }
        }
    }
