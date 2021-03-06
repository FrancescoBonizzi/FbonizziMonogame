# ![Logo](https://raw.githubusercontent.com/FrancescoBonizzi/FbonizziMonoGame/master/logo-64x64.png) FbonizziMonoGame

These are some libraries that I built over `MonoGame` Framework to make my games. You can find them on `Windows Store` and `Android Play Store` by searching for **Francesco Bonizzi**. 

All my games are **totally free** and **open source**, you can find them in my other repositories. Actually, my games are:
- [Rellow](https://github.com/FrancescoBonizzi/Rellow): the most colorful concentration game!
- [Starfall](https://github.com/FrancescoBonizzi/StarfallGame): you are a fallen star, catch the glows and avoid black holes to run back home!
- [INFART](https://github.com/FrancescoBonizzi/InfartGame): avoid hamburgers and holes, and don't forget to bring a towel!
- ...

---

### What these libraries can do

Work in progress / talk about the gallery solution with some image

##### FbonizziMonoGame
FbonizziMonoGame is a simple set of libraries I made to code my games (they'r in my repos too). This library has some abstractions that are implemented in my platform specific libraries.

It contains, in particular:
- A `Sprite` abstraction with a `SpriteAnimation` class in order to make animations from a spritesheet
- A `SplashScreenLoader` abstraction in order to manage the loading of all assets while showing a splashscreen.
- A `Camera2D` to show game worlds that are larger than the screen size
- A `DynamicScalingMatrixProvider` that manages screen resizing and scaling for different resolutions
- Some useful extensions to many XNA's classes
- Input abstractions (interely copied from [craftworkgames MonoGame.Extended](https://github.com/craftworkgames/MonoGame.Extended))
- A particle generator to render some effects (you can see it at work in the `FbonizziMonoGameGallery` project)
- Some `TransformationObjects`(s) with little logic to change color over time, fade in/out, popup, change scale over time on drawable objects
- A full MonoGame `RateMe` abstraction (implemented for every platform)
- Some UI implementation (they are very very drafty) to show some dialog and some buttons
- `PlatformAbstractions`: they are simple interfaces to make this library compatible with `UWP`, `Windows Desktop`, `Android`, and potentially every .NET compiling project:
  - `ISettingsRepository`: abstracts "write data" / "read data" to each platform storage
  - `ITextFileLoader`: abstracts "read a text file" on the platform storage
  - `IFbonizziGame`: abstracts some basic game logic of my games: pause, resume
  - `IWebPageOpener`: nothing to explain :-)

---

### Getting started
The first thing you could do is to download one of my games to see what these libraries can do. Secondly you could just install one of them via `Nuget` and play a little with it :-)

### FbonizziMonoGameGallery

I started a little WPF application (thanks to [MarcStan/MonoGame.Framework.WpfInterop](https://github.com/MarcStan/MonoGame.Framework.WpfInterop) for the library) with some examples of what the library can do:

![FbonizziMonoGameGallery home image](images/FbonizziMonoGameGallery-Home.png)

---

### How to contribute

- Report any issues
- Propose new features / improvements
- Asking for a pull request
- Playing my games ;-)
- Just telling your opinion
- [Offer me an espresso!](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=DTT7P8N3TV7N6&currency_code=EUR&source=url) ;-)

---

## Infrastructure status

### Nuget

| Package | Version |
| ------- | ------- |
| FbonizziMonoGame | [![NuGet](https://img.shields.io/nuget/v/FbonizziMonoGame.svg)](https://www.nuget.org/packages/FbonizziMonoGame/) |


