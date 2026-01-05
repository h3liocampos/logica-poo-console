package application;

import entities.Employee;

import java.util.Locale;
import java.util.Scanner;

public class Funcionarios {
    public static void main(String[] args) {
        Locale.setDefault(Locale.US);
        Scanner sc = new Scanner(System.in);
        Employee emp = new Employee();

        System.out.print("Nome: ");
        emp.name = sc.nextLine();

        System.out.print("Salário bruto: ");
        emp.grossSalary = sc.nextDouble();

        System.out.print("Imposto: ");
        emp.tax = sc.nextDouble();

        System.out.printf("Funcionário: %s, $ %.2f\n", emp.name, emp.netSalary());

        System.out.print("Qual a porcentagem para aumentar o salário? ");
        double percentage = sc.nextDouble();
        emp.increaseSalary(percentage);

        System.out.print("Dados atualizados: " + emp);
    }
}
