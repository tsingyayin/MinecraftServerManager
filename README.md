# MinecraftServerManager
Minecraft服务器增强管理器

众所周知，Minecraft服务器页面要么是个命令行，要么是个信息寥寥无几的UI页面。本程序即为解决这种信息过少的程序UI的服务器增强程序。

在程序内可以像一般启动器一样在可视化页面下操作服务器启动，不必操心于启动参数问题，并且有多种快速命令调用与其他增强功能。

程序同时提供多种管理策略，例如定时重启服务器（可选在重启时刷新指定世界），在服务器进程崩溃时自动重启服务器。后期在完成对于数据安全的保证测试后会同时推出远控子程序，可以从本地个人计算机远程直控Minecraft服务器进程。

与此同时，管理器支持多服务器实例的设定同步。例如可以仅执行一次封禁命令，同时对链入管理器并运行的全部服务器实例生效。

不选用Java开发这个东西有个很显而易见的理由，那就是作为管理器程序，不应当和被管理应用程序使用同一套平台，这样有利于增强管理器的鲁棒性。


