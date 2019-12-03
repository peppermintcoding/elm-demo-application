# elm-demo-application
A small application built with elm to learn elm.

Starting with the official Elm Guide -- https://guide.elm-lang.org/

### Project Setup
 + Create an Elm project with `elm init`, creates a .json and src directory
 + Start an Elm Server on localhost:8000, run `elm reactor` in the root of the Elm project

### Compiling
 + Compiling to HTML with Elm: `elm make Main.elm` --> index.html
 + Compiling to Javascript with Elm: `elm make Main.elm --optimize -- output=elm.js`

### Installing packages
 + To use Elm packages as imports they need to be installed in your project, which adds them to the .json
 + `elm install elm/http`
 + `elm install elm/json`



Following the video series of Jack Franklin -- https://www.youtube.com/watch?v=r44D650szpg
