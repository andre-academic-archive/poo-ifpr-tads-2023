# Atv01

## Passos realizados

- [x] Importar o Java Scanner
- [x] Ler cada entrada do usuário, somando as válidas
- [x] Exibir a soma total de entradas válidas

## Código

```java
import java.util.Scanner;

public class Atv01 {
    public static void main(String[] args) {
        double total = 0;
        Scanner input = new Scanner(System.in);
        System.out.println("Digite os números que deseja somar. Para calcular a soma total, basta deixar uma linha em branco:");

        while (input.hasNextLine()) {
            String line = input.nextLine();

            if (line.length() == 0) {
                System.out.println("Total: " + total);
                break;
            }

            try {
                double number = Double.parseDouble(line);
                total += number;
                System.out.println("Soma parcial: " + total);
            } catch (NumberFormatException e) {
                System.out.println("Entrada inválida. Tente novamente.");
            }
        }
    }
}
```
