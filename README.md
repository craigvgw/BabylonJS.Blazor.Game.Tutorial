## About

This project is from the BabylonJS Guided Learning Create a Game Tutorial Series, the different is that this project is built on top of Blazor Wasm using EventHorizon.Blazor.TypeScript.Interop.Generator to generate a C# proxy layer to the talk with the BabylonJS Framework. 

This show cases Blazor Wasm being used with a relativity complicated JavaScript Framework to create a functional Game.

## EventHorizon.Blazor.TypeScript.Interop.Generator

This is a project I, Cody Merritt Anhorn, personally created to help with the generation of the .NET/C# proxy layer. This proxy layer creates an interop layer to the underlying JavaScript having an almost exact API that would be used if the game was built in JavaScript/TypeScript.

## Commands 

~~~ bash
# Generated BabylonJS project interop with multiple sources.
ehz-generate -c Scene -c Engine -c DebugLayer -c HemisphericLight -c ArcRotateCamera -c MeshBuilder -a Blazor.BabylonJS.WASM -s https://raw.githubusercontent.com/BabylonJS/Babylon.js/master/dist/babylon.d.ts -s https://raw.githubusercontent.com/BabylonJS/Babylon.js/master/dist/gui/babylon.gui.d.ts
~~~