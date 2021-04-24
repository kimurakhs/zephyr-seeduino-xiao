# Example project for Seeeduino XIAO

Very simple project that prints "Hello, world!" to the console, based on Zephyr OS v2.5.

This works on Seeeduino XIAO board.

## Build

Please set up Zephyr OS development environment fiest.

Then,

```
$ cd projects/hello-world/
$ west build -b seeeduino_xiao
```

Generated firmware can be found in `build/zephyr/zephyr.bin`.

## Note

This project is almost the same to the Zephyr OS's sample project.

Please refer to `samples/hello-world` in Zephyr OS source tree.

