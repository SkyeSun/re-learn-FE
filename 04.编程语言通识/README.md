# 编程语言通识

## 按【语法】分类

### 非形式语言

- 中文
- 英文

### 形式语言（乔姆斯基谱系）

- 0型 无限制文法

	- ?::=?

- 1型 上下文相关文法

	- ?<A>?::=?<B>?

- 2型 上下文无关文法

	- <A>::=?

- 3型 正则文法

	- <A>::=<A>?

## 按【图灵完备性】分类

### 命令式——图灵机

- goto（绝大多数现代语言都不建议使用）
- if 和 while（绝大多数的现代语言方案）

### 声明式——lambda

- 递归

## 按【动态与静态】分类
（非严谨划分）

### 动态

- 在用户的设备/在线服务器上
- 产品实际运行时
- Runtime

### 静态

- 在程序员的设备上
- 产品开发时
- Compiletime

## 按【类型系统】划分

### 动态类型系统与静态类型系统

### 强类型与弱类型

- String + Number
- String == Boolean

### 复合类型

- 结构体：(T1, T2) => T3
- 函数签名

### 子类型

- 逆变/协变

## 一般命令式编程语言所涵盖的概念

### Atom

- Identifier（标识符）
- Literal（直接量）

	- 例：1.2

### Expression

- Atom
- Operator（操作符）
- Punctuator（辅助运算符）

	- 例：（）

### Statement

- Expression
- Keyword（关键字）
- Punctuator

### Structure

- Function
- Class
- Process
- Namespace
- ......

### Program

- Program
- Module
- Package
- Library

*XMind - Trial Version*