## Bazel 的demo
- 这里是一个简单的 Bazel 编译demo.
- 安装 Bazel
  - Arch: 
    ```c++
      pacman -S bazel
    ```
  - Ubuntu:
    详见 [ubuntu install bazel](https://bazel.build/install/ubuntu).
- 步骤
  ```bash
    git clone git@github.com:fansehep/bazel_demo.git
    cd bazel_demo
    # 编译全部.
    bazel build "..."
    ./bazel-bin/src/module_2/hello_bazel
  ```

- 好的, 勇者, 在欣赏完了简单的demo, 让我们进阶一点点吧
  ```bash
    git checkout advanced
    bazel build "..."
  ```
