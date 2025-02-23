

Clone this repo to its own directory, such as:

```
git clone https://github.com/JohnJFarrow/ClangFormatFile d:\work\ClangFormatFile
```

In other repositories which need to use this file:

#### Linux

```
ln -s ~/configs/.clang-format /path/to/project/.clang-format
```

#### Windows

```
cd Source
mklink .clang-format d:\work\ClangFormatFile\.clang-format
```
