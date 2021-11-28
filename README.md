A counter demo of [Elmish](https://github.com/fable-compiler/fable-elmish).
========

This is a port of Elm's counter implemented in F# and targeting Fable and React.


## Live sample
The sample is live and you can try it [here](https://fable-elmish.github.io/sample-react-counter).

## Building and running the sample
Pre-requisites:
* .NET Core [SDK 5.*](https://docs.microsoft.com/en-us/dotnet/core/install/sdk)
* `yarn` installed as a global `npm` or a platform package and available in the path 

To build locally and start the webpack-devserver:
* once: `dotnet tool restore`
* `dotnet fake build -t Watch`

open [localhost:8090](http://localhost:8090)