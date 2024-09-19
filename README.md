public class BancoTerminal {
    public static void main(String[] args) {
        // Variáveis
        double saldo = 25.0;
        double valorSolicitado = 18.0;

        // Verificar se o saldo é suficiente
        if (saldo >= valorSolicitado) {
            // Realizar saque
            saldo -= valorSolicitado;
            System.out.println("Saque realizado com sucesso!");
        } else {
            System.out.println("Saldo insuficiente");
        }

        // Imprimir saldo
        System.out.println("Saldo atual: " + saldo);

        // Executar novamente com novos valores
        saldo = 15.0;
        valorSolicitado = 22.0;

        // Verificar se o saldo é suficiente
        if (saldo >= valorSolicitado) {
            // Realizar saque
            saldo -= valorSolicitado;
            System.out.println("Saque realizado com sucesso!");
        } else {
            System.out.println("Saldo insuficiente");
        }

        // Imprimir saldo
        System.out.println("Saldo atual: " + saldo);
    }
}# saque
aulas de java saque
