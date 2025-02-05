### C++

##### 推荐使用 cmake-tools 插件

- [《例子》](https://github.com/feixiao/cmake-catch-vsc-template)
- [《Get started with CMake Tools on Linux》](https://code.visualstudio.com/docs/cpp/cmake-linux)

- [《CMake: Debug and launch》](https://github.com/microsoft/vscode-cmake-tools/blob/main/docs/debug-launch.md)

##### ToDo

- [ ] 支持静态库
- [ ] 支持单元测试

##### CoreDump

###### OSX

```shell
sudo sysctl kern.coredump=1

sudo mkdir /cores
sudo chown root:admin /cores
sudo chmod 1775 /cores
sudo chmod o+w /cores

# example cpp/coredump_test.cpp
```

##### 参考资料

- [《Visual Studio Code 远程调试》](https://www.cnblogs.com/mightycode/p/10876119.html) WSL、SSH、Containers）
- [《把你的 VS Code 打造成 C++ 开发利器》](https://mp.weixin.qq.com/s/zA3HWWq-R0PT40CuLIbGsQ)
- [《VS Code 与 CMake》](https://www.cnblogs.com/iwiniwin/p/13705456.html)
- [《VS Code 搭建 C++ 开发环境(OSX 系统)》](https://xie.infoq.cn/article/1dd3fe369ec9f3db5661570fa)
- [《CPP ON MAC M1》](https://www.geeksforgeeks.org/c-installation-on-macbook-m1-for-vs-code/)
- [brew 同时支持 arm64 和 x86_64](https://benobi.one/posts/running_brew_on_m1_for_x86/)
