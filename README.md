
[![BasuiLogo](https://github.com/BasycOpenSource/Basui/blob/main/README-Files/BasuiLogo.png)](#) <br>
blazor component library for sending messages to bus

[![](https://github.com/BasycOpenSource/Basui/blob/main/README-Files/HeadingLeft.png)](#) Get Started
----
1. Install <code>Basyc.Basui</code> nuget package
2. Create a empty blazor wasm app <code>Program.cs</code>:
```c#
builder.Services.AddBlazorMessageBus()
    .AddBusClient<BasycInterfaceTypedBusClient>()
    .AddInterfaceTypedCQRSProvider(typeof(IQuery<>), typeof(ICommand), typeof(ICommand<>), typeof(CreateCustomerCommand).Assembly)                
    .AddDomainNameFormatter<TypedDDDDomainNameFormatter>();
```
[![](https://github.com/BasycOpenSource/Basui/blob/main/README-Files/HeadingLeft.png)](#) Extensibility
----
Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Mauris elementum mau

[![](https://github.com/BasycOpenSource/Basui/blob/main/README-Files/HeadingLeft.png)](#) Features
----
- [x] UI for sending messages to bus
- [x] Very high extensibility

[![](https://github.com/BasycOpenSource/Basui/blob/main/README-Files/HeadingLeft.png)](#) 3rd party support
----
- [x] MassTransit client
- [x] Basyc integration
- [ ] AzureServiceBus client



<mark>what is DataBase</mark>
    
