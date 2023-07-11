# VSCode Configuration

## VSCode plug-in
- C/C++
- cpplint

## .vscode

### .vscode/settings.json

### .vscode/c_cpp_properties.json
```json
{
    "configurations": [
        {
            "name": "windows",
            "includePath": [
                "${workspaceFolder}/**",
                "${workspaceFolder}"
            ],
            "defines": [
                "_DEBUG",
                "UNICODE",
                "_UNICODE"
            ],
            "windowsSdkVersion": "10.0.22621.0",
            "compilerPath": "C:/Program Files/LLVM/bin/clang.exe",
            "cStandard": "c17",
            "cppStandard": "c++20",
            "intelliSenseMode": "windows-clang-x64"
        }
    ],
    "version": 4
}
```


### .vscode/launch.json

### .vscode/tasks.json
