# Switch-Case
Switch case ile dört işlem 

namespace switchcase
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Lütfen 1. sayıyı giriniz");
            int sayi1 = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Lütfen 2. sayıyı giriniz");
            int sayi2 = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Lütfen işlem türünü giriniz");
            Console.WriteLine("toplama=1, çıkarma=2, çarpma=3, bölme=4");
            int islem = Convert.ToInt32(Console.ReadLine());

            switch (islem)
            {
                case 1: Console.WriteLine(sayi1 + sayi2); break;
                case 2: Console.WriteLine(sayi1 - sayi2); break;
                case 3: Console.WriteLine(sayi1 * sayi2); break;
                case 4: Console.WriteLine(sayi1 / sayi2); break;

                default: Console.WriteLine("Hata böyle bir işlem bulunamadı"); break;
            }

            Console.ReadKey();
        }

        [Patika Dev Sayfam](https://app.patika.dev/sevaalnuur)