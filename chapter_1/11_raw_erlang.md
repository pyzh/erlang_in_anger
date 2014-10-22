# Raw Erlang

1.1 Raw Erlang
1.1 原始的Erlang Code(Raw Erlang)
<p></p>
If you encounter a raw Erlang code base, you’re pretty much on your own. These rarely follow any specific standard, and you have to dive in the old way to fi gure out whatever happens in there.
<p></p>
<font color="green">
如果你遇到的是未加工过(不成熟)的Erlang代码库，那么你就只能靠自己了，这些代码几乎不会遵守任何具体的标准，你不得不深入代码当中去查看到底发生了什么。
</font>
<p></p>
This means hoping for a README.md file or something similar that can point to an entry point in the application, and going from there, or hoping for some contact information that can be used to ask questions to the author(s) of the library.
<p></p>
<font color="green">
或许一个类似于README.md文件会指明应用(application)的切入点，到了那里面后，或许会发现一些可以问作者相关问题的联系信息。
</font>
<p></p>
Fortunately, you should rarely encounter raw Erlang in the wild, and they are often beginner projects, or awesome projects that were once built by Erlang beginners and now need a serious rewrite. In general, the advent of tools such as rebar<sup>1</sup> made it so most people use OTP Applications.
<p></p>
<font color="green">
很庆幸，你几乎不会遇到这种Raw Erlang 代码，这种代码基本上都是项目最初阶段创建的，或由Erlang初学者创建的需要重写的代码。
通常，Rebar<sup>1</sup>的工具的出现，使得绝大多数的人都使用OTP Applications。
</font>
<p></p>
[1] [https://github.com/rebar/rebar/](https://github.com/rebar/rebar/) — a build tool briefly introduced in Chapter 2
<font color="green" >
[注1]：https://github.com/rebar/rebar/ 会在chapter 2中介绍]
</font>