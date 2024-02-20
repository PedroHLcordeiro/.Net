# .Net
using System;

namespace PedroHelloWorld.Models
{
    public class HelloModel
    {
        public string Mensagem { get; set; } = "Ola Model C#";
    }
}

namespace PedroHelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Models.HelloModel model = new Models.HelloModel();
            Console.WriteLine(model.Mensagem);
            Console.Read();
        }
    }
}
