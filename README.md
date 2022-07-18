# Maior-de-tr-s-valores
Exercício de logica de programação


 
Moodle - IFRS

Programador Web - Turma 2022A
Painel Meus cursos  PW2022A  3 Lógica de Programação  3.20 Praticando um pouco...
 
3.20 Praticando um pouco...
Neste curso, você faz seu próprio tempo de estudos. Seu progresso será aferido pelos questionários denominados "Teste seu conhecimento". Entretanto, sabemos da importância em praticar, pois só assim você aperfeiçoar sua aprendizagem. Para isso, elaboramos esse livro, com algumas questões desafiadoras e seu gabarito. Utilize o menu de navegação para acessar os enunciados. Quando finalizar sua resposta, confira com o gabarito localizado logo abaixo.



 

Exercício 5: Maior de três valores
Gabarito do Exercício 5
programa

{

   funcao inicio(){

      inteiro valor1, valor2, valor3

      escreva ("Informe o valor 1: ")

      leia(valor1)

      escreva ("Informe o valor 2: ")

      leia(valor2)

      escreva ("Informe o valor 3: ")

      leia(valor3)

      se(valor1 > valor2 E valor1 > valor3) {

         escreva ("O valor 1 é o maior")

      }

      senao{

         se(valor2 > valor1 E valor2 > valor3) {

            escreva ("O valor 2 é o maior")

         }

         senao{

            escreva ("O valor 3 é o maior")

         }

      }

   }

}
