

# Easy Password Encrypt

Simplify password encryption and verification in your .NET applications with EasyPasswordEncrypt.NET. This lightweight library allows you to effortlessly integrate robust password security with just one line of code.

## Features

- **Seamless Integration:** Implement password security with minimal code.
- **Encryption Made Simple:** Encrypt passwords with a single line of code.
- **Effortless Verification:** Verify passwords with a straightforward function call.
- **Strong Security:** Utilizes industry-standard encryption techniques for enhanced security.

## Quick Start

```csharp
using EasyPasswordEncrypt;

// Encrypt a password
string encryptedPassword = PasswordManager.Encrypt("user_password");

// Verify a password
bool isVerified = PasswordManager.Verify("user_password", encryptedPassword);

if (isVerified)
{
    Console.WriteLine("Password verified successfully!");
}
else
{
    Console.WriteLine("Incorrect password. Please try again.");
}
```

## Installation

```bash
dotnet add package EasyPasswordEncrypt
```

Explore advanced features and customization options in our [documentation](docs/).
