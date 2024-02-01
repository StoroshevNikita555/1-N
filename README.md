internal class Program
{
    private static void Main(string[] args)
    {
        {
            Console.Write("Введи число от 1 до N" +
                "\nN = ");
            int number = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("----------");
            for (int i = 1; i <= number; i++)
            {
                Console.WriteLine("{0} + 1 = {1}", i - 1, i);
                if (i % 1 == 0)
                {
                    Console.WriteLine("----------");
                }
                else
                {
                    Console.WriteLine(i);
                }
            }
            Console.Write("Последнее число: {0}", number);
        }
        Console.ReadKey();
    }
}
