---
title: rust learnning record
date: 2025-02-27 22:15:16
tags:
---
# Struct

## Unit-like Struct

没有任何字段的结构体。如：

    struct UnitLikeStruct;

## Struct Update Syntax

可以利用已有结构体创建新的结构体。如：

    struct Point {
        x: i32,
        y: i32,
        z: i31,
    }

    let p1 = Point { x: 0, y: 0, z: 0 };
    let p2 = Point { x: 1, ..p1 };

# String

# trait

特征定义了一组可以被共享的行为，实现了特征，就可以使用这组行为。
