# GorillaExecutorSharp API
Allows the use of GorillaExecutorSharp with your own UIs.
must be used in a .NET CORE 6.0 project.

---

## Initialising the API.
to initialize the API, first put ```using GorillaExecutorAPI;``` at the top of your code.
to then get access to the ```Inject``` and ```Execute``` functions, please put the code ```API api = new API();``` inside it.

## Injecting.

To inject into Gorilla Tag, after following the initialization steps, but the code ```await api.Inject();``` in your Inject button.

## Executing.

To then execute scripts provided, you may use the ```await api.Execute(string code);``` function. This takes 1 argument, the code you want to execute. you can set this to the textboxes text or so on.
