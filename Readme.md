# C# Disposable Email Checker

Disposable Email Checker is a C# library for checking the disposable email.

## Installation

Use Nuget to install this library


## Usage

```c#
using System;
using EmailValidator;

namespace App
{
    class Program
    {
        static void Main(string[] args)
        {
            bool Checker = DisposableMails.IsDisposableEmail("test@Getnada.com"); //true
            Console.WriteLine(Checker);
        }
    }
}

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. 

+ We need to add MX Record Checking to make sure we are validating other domains too.

Please make sure to update the tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)