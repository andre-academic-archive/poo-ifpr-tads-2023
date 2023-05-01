# Atv04

## Passos realizados

- [x] Declarar as variáveis gastosJaneiro, gastosFevereiro e gastosMarco
- [x] Inicializar as variáveis com os respectivos gastos
- [x] Declarar a variável gastosTrimestre
- [x] Inicializar a variável gastosTrimestre com a soma das outras variáveis
- [x] Exibir a variável gastosTrimestre

## Código

```java
public class Atv04 {
    public static void main(String[] args) {
        double gastosJaneiro = 567.89;
        double gastosFevereiro = 876.54;
        double gastosMarco = 934.21;

        double gastosTrimestre = gastosJaneiro + gastosFevereiro + gastosMarco;

        System.out.println("Gastos do trimestre: " + gastosTrimestre);
    }
}
```