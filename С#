using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Введіть перше число:");
        string input1 = Console.ReadLine();
        int number1;

        // Перевіряємо, чи введено коректне число
        while (!int.TryParse(input1, out number1))
        {
            Console.WriteLine("Некоректне значення. Введіть ціле число:");
            input1 = Console.ReadLine();
        }

        Console.WriteLine("Введіть друге число:");
        string input2 = Console.ReadLine();
        int number2;

        // Перевіряємо, чи введено коректне число
        while (!int.TryParse(input2, out number2))
        {
            Console.WriteLine("Некоректне значення. Введіть ціле число:");
            input2 = Console.ReadLine();
        }

        // Рахуємо суму двох чисел
        int sum = number1 + number2;

        // Виводимо результат на екран
        Console.WriteLine($"Сума чисел {number1} та {number2} дорівнює {sum}.");
    }
}
