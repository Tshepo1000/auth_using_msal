# Azure Authentication with MSAL (.NET)

A minimal .NET 8 console application that signs a user in interactively with the Microsoft Authentication Library (MSAL) and acquires an access token from Microsoft Entra ID (Azure AD). It was written while studying for the AZ-204 Azure developer exam.

## What it demonstrates

- Registering a public client application with `Microsoft.Identity.Client`
- Acquiring a token interactively through the browser sign-in prompt
- Displaying the acquired access token in the console

## Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download)
- An app registration in Microsoft Entra ID with a redirect URI for a public/native client

## Getting started

```bash
git clone https://github.com/Tshepo1000/auth_using_msal.git
cd auth_using_msal
```

1. Open `Program.cs` and set your own **client ID** and **tenant ID** from your app registration.
2. Run the app:

   ```bash
   dotnet run
   ```

3. Sign in when the browser window opens. The token is printed to the console.

> Treat access tokens like passwords. Do not share or commit them.

## Tech stack

C#, .NET 8, Microsoft.Identity.Client (MSAL.NET).

## Author

Tshepo Sekete, [GitHub](https://github.com/Tshepo1000)
