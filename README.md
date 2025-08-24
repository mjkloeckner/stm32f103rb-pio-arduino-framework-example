# Nucleo board Arduino framework example

This is a simple [platformio](https://platformio.org/) example using Arduino
framework. The code blinks the board's builtin LED

## Compiling and uploading

To compile and upload the code [platformio](https://platformio.org/) is used,
this is a great tool which is available as an IDE or as a set of tools for the
command line. To compile the code from the command line on any Linux
distribution run:

```console
$ pio run
```

And with the board connected, compile and upload the code by running the upload
target of platformio:

```console
$ pio run -t upload
```

## Related info

[https://github.com/platformio/platform-ststm32](https://github.com/platformio/platform-ststm32)  
[https://docs.platformio.org/en/latest/platforms/ststm32.html#platform-ststm32](https://docs.platformio.org/en/latest/platforms/ststm32.html#platform-ststm32)
