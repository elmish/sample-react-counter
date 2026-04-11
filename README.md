A counter demo of [Elmish](https://github.com/fable-compiler/fable-elmish).
========

This is a port of Elm's counter implemented in F# and targeting Fable and React.


## Live sample
The sample is live and you can try it [here](https://fable-elmish.github.io/sample-react-counter).

## Building and running the sample
Pre-requisites:
* .NET [SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0)
* `npm` (comes with Node.js)

To build locally and start the webpack-devserver:
* once: `dotnet tool restore && npm install`
* `dotnet fsi build.fsx -- -t Watch`

open [localhost:8090](http://localhost:8090)