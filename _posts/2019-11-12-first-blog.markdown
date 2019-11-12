---
layout: post
title:  "Qt, C++ & Rust"
date:   2019-11-12 14:34:00 +0800
categories: Misc
tags: Misc
description: Qt, C++ and Rust
---

```c++
#include <QCoreApplication>

int main(int argc, char *argv[]) {
    QCoreApplication app(argc, argv);
    app.exec();
}
```

```c++
#include <iostream>

using namespace std;

int main() {
    cout << "Hello!" << endl;
    return 0;
}
```

```rust
fn main() {
    println!("Hello!");
}
```
