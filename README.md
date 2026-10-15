# daedalus
A game about a labyrinth in x86 assembly.

Made for CSE1400 Computer Organization, won the "assembly game contest" on the 2022 edition.

Learn more about how it was built by reading the short [spec](./spec.md).

## Demo video

Here's a demo recording (spoilers! technically).

https://github.com/user-attachments/assets/a3597e08-89fd-4d94-8868-c634adf8101d



I recorded this 4 years after finishing the project, so this is a genuine run because didn't remember the maze layout :)

## Running

This only runs on x86-64 Linux. 

If you're on Linux, you just need `gcc`, `make` and run

```bash
make
```

### Other platforms

**Windows**: 
1. Install [WSL](https://learn.microsoft.com/en-us/windows/wsl/install)
2. Run `sudo apt-get gcc` and `sudo apt-get make`
3. Run `make` on the directory

**MacOS**: Apple silicon can't execute x86 natively, so some virtualization layer is needed. I used Lima, but Docker could work too. Once on Linux, follow the above instructions.

