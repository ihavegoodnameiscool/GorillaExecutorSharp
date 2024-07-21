# Miscellanious functions
Functions to interact with gorilla tag.

---

## loadstring

```csharp
function loadstring(string code);
```

Loads a string of code. Like the lua function!

---

## game.httpget

```csharp
async function game.httpget(string url);
```

Gets the value of an URL that can then be used in loadstring or other stuff.

---

## messagebox

```csharp
function messagebox(string text, string caption uint options);
```

Dispatch a messagebox in Gorilla Tag

---

## setclipboard

```csharp
function setclipboard(string text);
```

Set the value of the Windows clipboard.

---

## setfpscap

```csharp
function setfpscap(int cap);
```

Set the targetted FPS for the game.
