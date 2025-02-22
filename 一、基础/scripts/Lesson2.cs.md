```c#
using System;  
  
namespace ConsoleApplication1  
{  
    internal class Program  
    {  
        public static void Main(string[] args)  
        {  
            #region 有符号类型  
            Console.WriteLine("有符号类型");  
            int sbyteSize = sizeof(sbyte);  
            int shortSize = sizeof(short);  
            int intSize = sizeof(int);  
            int longSize = sizeof(long);  
              
            Console.WriteLine($"sbyte 所占的字节数为: {sbyteSize}");  
            Console.WriteLine($"short 所占的字节数为: {shortSize}");  
            Console.WriteLine($"int 所占的字节数为: {intSize}");  
            Console.WriteLine($"long 所占的字节数为: {longSize}");  
            Console.WriteLine();  
              
            #endregion  
            #region 无符号类型  
            Console.WriteLine("无符号类型");  
            int byteSize = sizeof(byte);  
            int ushortSize = sizeof(ushort);  
            int uintSize = sizeof(uint);  
            int ulongSize = sizeof(ulong);  
              
            Console.WriteLine($"byte 所占的字节数为: {byteSize}");  
            Console.WriteLine($"short 所占的字节数为: {ushortSize}");  
            Console.WriteLine($"int 所占的字节数为: {uintSize}");  
            Console.WriteLine($"long 所占的字节数为: {ulongSize}");  
            Console.WriteLine();  
              
            #endregion  
  
            #region 浮点类型  
            Console.WriteLine("浮点类型");  
            int floatSize = sizeof(float);  
            int doubleSize = sizeof(double);  
            int decimalSize = sizeof(decimal);  
              
              
            Console.WriteLine($"float 所占的字节数为: {floatSize}");  
            Console.WriteLine($"double 所占的字节数为: {doubleSize}");  
            Console.WriteLine($"decimal 所占的字节数为: {decimalSize}");  
            Console.WriteLine();  
              
            #endregion  
  
            #region 特殊类型  
  
            Console.WriteLine("特殊类型");  
            int boolSize = sizeof(bool);  
            int charSize = sizeof(char);  
              
            Console.WriteLine($"bool 所占的字节数为: {boolSize}");  
            Console.WriteLine($"char 所占的字节数为: {charSize}");  
  
            #endregion  
        }  
    }  
}
```