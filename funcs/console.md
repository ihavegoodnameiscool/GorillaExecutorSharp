# Console functions
Functions to interact with the **Console** on gorilla tag.

---

## gconsolesettitle

```csharp
function gconsolesettitle(string title);
```

Allows the modification of the title of the console.

---

## gconsolecreate

```csharp
function gconsolecreate();
```

Allocates a console into the Gorilla Tag application.

---

## gconsoleprint

```csharp
function gconsoleprint(string text);
```

Display a string of text onto the created Console in the game.

---

## gconsoledestroy

```csharp
function gconsoledestroy();
```

Free the console from Gorilla Tags memory, making in dissapear. (May also crash the game)

---

## gconsoleinput

```csharp
function gconsoleinput();
```

Pauses the game to allow input through the previously allocated console.
