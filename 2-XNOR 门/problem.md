---
id: 2
logic_id: 2
name: XNOR 门
level: 1
tags:
points: 1
---

# XNOR 门

## 题目描述
同或(XNOR)门

同或门的逻辑特点是

- 当两个输入端一个为`0`，另一个为`1`时，输出为`0`
- 当两个输入端均为`1`或均为`0`时，输出为`1`

## 输入格式
输入为 `a` 和 `b`，均为 1-bit wire。

## 输出格式
输出`out`，为 `a` 和 `b` 进行同或运算的结果，位宽为 1。

## 代码
```verilog
module Xnor( 
    input a, 
    input b, 
    output out
);
    // 在这里输入你的代码 请不要修改模块和信号名称
endmodule
```
