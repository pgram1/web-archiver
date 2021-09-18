# web-archiver
A simple bulk web archiver

## Execution

(You will need to `chmod +x save.sh spn.sh`)

```
./save.sh "initial URL"
```

This will request a save of all files within one level of subdirectories to the original URL.

## Acknowledgements

Special thanks go to [overcast07](https://github.com/overcast07) for their [wayback-machine-spn-scripts](https://github.com/overcast07/wayback-machine-spn-scripts), which is used to perform the saves.

## Notice

The process is **slow**, especially for websites with a lot of content. It nonetheless is a method to reliably archive more content than the "save outlinks" option of [archive.org](https://web.archive.org/save) (which also requires a registered account).
