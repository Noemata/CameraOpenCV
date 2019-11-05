## Sample

Adjusted to use OpenCV v4.1.1 and VS2019, this is Microsoft's CameraOpenCV sample located here:

https://github.com/microsoft/Windows-universal-samples/tree/master/Samples/CameraOpenCV

### Build the sample

1. Use vcpkg to get OpenCV for uwp (you may wish to get the triplet x64, x86, ARM)

.\vcpkg install opencv[contrib]:x64-uwp --recurse

2. Adjust project settings to reference where things land on your system

### Linker Settings Screenshot
![Screenshot](https://github.com/Noemata/CameraOpenCV/raw/master/LinkerSettingsScreenshot.png)

