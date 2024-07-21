# FileSystem functions
Functions to interact with the **FileSystem** outside of the gorilla tag environment. All of these functions are redirected to the 'workspace' directory inside the executors folder.

---

## readfile

```csharp
function readfile(string path);
```

Read the contents of a file.

---

## listfiles

```csharp
function listfiles();
```

List all files in a folder, including directories.

---

## writefile

```csharp
function writefile(string path, string text);
```

Write text to a file in the workspace folder. If the file is not found, the file will be created.

---

## makefolder

```csharp
function makefolder(string name);
```

Create a folder inside the workspace folder.

---

## appendfile

```csharp
function appendfile(string path, string text);
```

Add content onto the end of a previously existing file

---

## isfile

```csharp
function isfile(string path);
```

Check if a file already exists.

---

## isfolder

```csharp
function isfolder(string path);
```

Check if a folder already exists.

---

## delfile

```csharp
function delfile(string path);
```

Delete a file in the workspace folder.

---

## delfolder

```csharp
function delfolder(string path);
```

Delete a folder in the workspace folder and all of its subdirectories.

---

## loadfile

```csharp
function loadfile(string path);
```

Executes the content of a file. dofile() also does same thing.
