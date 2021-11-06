
<br><br>
[![BasuiLogo](https://github.com/BasycOpenSource/Basui/blob/main/README-Files/BasuiLogo.png)](#)

<br>

[![](https://github.com/BasycOpenSource/Basui/blob/main/README-Files/HeadingPoint.png)](#) Get Started
----
1. Install <code>Basyc.Basui</code> nuget package
2. Create a empty blazor wasm app <code>Program.cs</code>:
```c#
builder.Services.AddBlazorMessageBus()
    .AddBusClient<BasycInterfaceTypedBusClient>()
    .AddInterfaceTypedProvider(typeof(IRequest), typeof(IRequest<>), typeof(MyRequest).Assembly);
```
<br><br>
[![](https://github.com/BasycOpenSource/Basui/blob/main/README-Files/HeadingPoint.png)](#) Extensibility
----
Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Mauris elementum mau
<br><br>

[![](https://github.com/BasycOpenSource/Basui/blob/main/README-Files/HeadingPoint.png)](#) Features
----
- [x] UI for sending messages to bus
- [x] Very high extensibility
<br><br>

[![](https://github.com/BasycOpenSource/Basui/blob/main/README-Files/HeadingPoint.png)](#) 3rd party support
----
- [x] MassTransit client
- [x] Basyc integration
- [ ] AzureServiceBus client
<br><br>
