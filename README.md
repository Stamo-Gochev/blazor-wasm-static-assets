# blazor-wasm-static-assets

## Description
Static assets are not loaded even with the call to [app.UseStaticFiles()](https://github.com/Stamo-Gochev/blazor-wasm-static-assets/blob/3daa028e1c473be4fbf4b582ffba7399ec6d21e7/blazor-wasm-static-assets.Server/Startup.cs#L30)

## Steps to reproduce
1. Run the project 
2. Look for the [script.js](https://github.com/Stamo-Gochev/blazor-wasm-static-assets/blob/master/razor-class-lib/wwwroot/script.js) file in the Network tab in DevTools.
