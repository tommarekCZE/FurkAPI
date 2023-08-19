# FurkAPI
- What is furk API?
 Furk API is API dll for creating your own WPF executor applications for roblox. Running on furk.

- Is this safe?
  This .dll is safe, antiviruses may false report application as virus because its injector

- How I can use?
  1. Download furkAPI.dll
  2. Right click on Denepndecies>Add Project Refference>Browse and select FurkAPI.dll
  3. Include FurkAPI.dll to add `using FurkAPI;` to top of your code
  4. Add `FurkAPI.Module module = new FurkAPI.Module();` to your code.
  5. Use our two functions where you want
    <br /> -> `await module.Init();` - Inject the Furk to the roblox
    <br /> -> `module.ExecuteScript("Add your script here");` - Execute script.
    <br /> -> These two functions returns int varriable
    <br />    >>> 0 = Succes
    <br />    >>> 1 = Error

  
