# Atv03

## Passos realizados

- [x] Configurar o JOptionPane para leitura de Dados
- [x] Ler as notas de cada prova e trabalho
- [x] Calcular a média das notas
- [x] Exibir a média

## Código

```java
import javax.swing.JOptionPane;

public class Atv03 {
    public static void main(String[] args) {
        double prova1 = Double.parseDouble(JOptionPane.showInputDialog("Digite a nota da primeira prova:"));
        double prova2 = Double.parseDouble(JOptionPane.showInputDialog("Digite a nota da segunda prova:"));
        double trabalho = Double.parseDouble(JOptionPane.showInputDialog("Digite a nota do trabalho:"));

        double media = (prova1 + prova2 + trabalho) / 3;

       JOptionPane.showMessageDialog(null, "A média é: " + media);
    }
}