# SharpVG

A .NET Core library for F# to generate vector graphics in SVG format.

## Why SharpVG?

 - Allows you to emit SVG using simple F# commands so that you can create graphics and animations that are easy to distribute
 - Ability to render dynamically using [Fable](http://fable.io) to create interactive web pages
 - All basic SVG elements are supported: line, circle, ellipse, rect, text, polygon, polyline, path, image, and groups
 - No understanding of SVG is required and its as easy as using seq, list, or array
 - No external dependencies other than SharpVG are required
 - .NET Core cross platform support on Windows, Linux, and OSX
 - Limited support for SVG animations
 - Limited support for cartesian plotting
 - Reusable styles

## Example

```F#
  Coming soon!
```

## Building SharpVG

Clone the repository:
```
  $ git clone https://github.com/ChrisNikkel/SharpVG.git
  $ cd SharpVG
```

Restore the dependancies:
```
  $ dotnet restore
```

Start the build:
```
  $ dotnet build
```

Run the tests:
```
  $ dotnet test Tests
```

Run the examples:
```
  $ dotnet run Examples\Triangle\Triangle.fsproj
  $ dotnet run Examples\Life\Life.fsproj
  $ dotnet run Examples\Graph\Graph.fsproj
  $ dotnet run Examples\Animate\Animate.fsproj
```

## Support

 - Please submit bugs and feature requests [here](https://github.com/ChrisNikkel/SharpVG/issues)

## Library License

The library is available under the MIT license. For more information see the [License file](https://github.com/ChrisNikkel/SharpVG/blob/master/LICENSE.md).

## Maintainer(s)

- [@ChrisNikkel](https://github.com/ChrisNikkel)
