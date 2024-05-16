# Visual studio中配置vcpkg

https://github.com/microsoft/vcpkg

在vcpkg路径，命令行输入以下：

`.\vcpkg integrate install`

After this, you can now create a New non-CMake Project (or open an existing one). All installed libraries are immediately ready to be #include'd and used in your project without additional configuration. => 如果不用CMake，那就不需要额外的配置，直接就能用了。

果然，还是要复制fmtd.dll的（因为在C:\gitcloud\visual-studio-vcpkg-config\x64\Debug找到了fmtd.dll文件），只不过visual studio把这个过程自动化了。(2024年5月17日) => 但是在cmake版本的vcpkg中，复制fmtd.dll无法自动进行，就变成了需要手动完成的工作。(2024年5月17日)