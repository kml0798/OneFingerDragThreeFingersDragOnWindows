[![Release](https://img.shields.io/github/v/release/kml0798/ThreeFingersDragOnWindows?label=Download%20version)](https://github.com/kml0798/ThreeFingersDragOnWindows/releases/latest)
[![TotalDownloads](https://img.shields.io/github/downloads/kml0798/ThreeFingersDragOnWindows/total)](https://github.com/kml0798/ThreeFingersDragOnWindows/releases/latest)
[![LatestDownloads](https://img.shields.io/github/downloads/kml0798/ThreeFingersDragOnWindows/latest/total)](https://github.com/kml0798/ThreeFingersDragOnWindows/releases/latest)

# OneFingerDrag/ThreeFingersDragOnWindows
Windows手势识别应用，支持三指转单指激活，单指拖拽功能（兼容windows默认手势）或Macos的三指拖动

A windows app that allows one finger drag( Windows original gesture compatible) or the macos three fingers drag(windows threefingers' gesture need to be closed ), using the Raw Inputs of precision touchpad.

- [kamektx/TouchpadGestures_Advanced][1]
- [mfakane/rawinput-sharp][2]
- [emoacht/RawInput.Touchpad][3]

## Preview
![1669353513623](https://user-images.githubusercontent.com/108204013/203906588-7ba5f10c-200c-4a81-add4-fa73f8584460.jpg)

## Requirements

- .NET 6.0

## Build and Execute
```
cd /path/to/ThreeFingersDragOnWindows/directory/
dotnet build ./ThreeFingersDragOnWindows.csproj
dotnet exec ./bin/Debug/net6.0-windows/ThreeFingersDragOnWindows.dll
```

## How to open configuration pane
DoubleClick the ThreeFingersDragOnWindows icon on the Windows task bar.

## License

- MIT License

[1]: https://github.com/kamektx/TouchpadGestures_Advanced

[2]: https://github.com/mfakane/rawinput-sharp

[3]: https://github.com/emoacht/RawInput.Touchpad
