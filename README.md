# Hashbrowns
I'm hungry, and yet oddly motivated

```csharp
using Hashbrowns;

public class Program
{
    static void Main(string[] args)
    {
        string rawInput = "Hello World!";
        Hashing hashbrown = new Hashing(rawInput);
        
        string md5 = hashbrown.MD5Hash();
        Console.WriteLine(md5);
        // ED076287532E86365E841E92BFC50D8C
        
        string sha1 = hashbrown.SHA1Hash();
        Console.WriteLine(sha1);
        // 2EF7BDE608CE5404E97D5F042F95F89F1C232871
        
        string sha256 = hashbrown.SHA256();
        Console.WriteLine(sha256);
        
    }
}
