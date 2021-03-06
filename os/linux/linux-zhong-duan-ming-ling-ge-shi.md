# Linux 终端命令格式

## 1. 终端命令格式 <a href="01-zhong-duan-ming-ling-ge-shi" id="01-zhong-duan-ming-ling-ge-shi"></a>

```bash
command [-options] [parameter]
```

说明：

* `command`：命令名，相应功能的英文单词或单词的缩写
* `[-options]`：选项，可用来对命令进行控制，也可以省略
* `parameter`：传给命令的参数，可以是 **零个**、**一个** 或者 **多个**

> `[]` 代表可选

## 2. 查阅命令帮助信息（知道） <a href="02-cha-yue-ming-ling-bang-zhu-xin-xi-zhi-dao" id="02-cha-yue-ming-ling-bang-zhu-xin-xi-zhi-dao"></a>

> 提示
>
> * 现阶段只需要 **知道** 通过以下两种方式可以查询命令的帮助信息
> * 先学习**常用命令**及**常用选项**的使用即可，工作中如果遇到问题可以借助 **网络搜索**

### 2.1 `--help` <a href="21-help" id="21-help"></a>

```bash
command --help
```

说明：

* 显示 `command` 命令的帮助信息

### 2.2 man <a href="22-man" id="22-man"></a>

```bash
man command
```

说明：

* 查阅 `command` 命令的使用手册

> `man` 是 **manual** 的缩写，是 Linux 提供的一个 **手册**，包含了绝大部分的命令、函数的详细使用说明

使用 `man` 时的操作键：

| 操作键     | 功能              |
| ------- | --------------- |
| 空格键     | 显示手册页的下一屏       |
| Enter 键 | 一次滚动手册页的一行      |
| b       | 回滚一屏            |
| f       | 前滚一屏            |
| q       | 退出              |
| /word   | 搜索 **word** 字符串 |
