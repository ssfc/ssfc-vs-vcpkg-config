# Visual studio中配置vcpkg

https://github.com/microsoft/vcpkg

在vcpkg路径，命令行输入以下：

`.\vcpkg integrate install`

After this, you can now create a New non-CMake Project (or open an existing one). All installed libraries are immediately ready to be #include'd and used in your project without additional configuration. => 如果不用CMake，那就不需要额外的配置，直接就能用了。