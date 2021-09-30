# Flycatcher
Flycatcher is a general purpose, multi-paradigm, statically typed systems programming language.  It is designed to be as easy to learn as possible, with a zero performance cost.

```flycatcher
@func main() {
    console.log("Hello, world!");
}
```

> **note** Flycatcher is not yet in alpha, meaning it is not even functional right now.  Flycatcher is constantly changing, which makes it unstable and unrecommended to use for any serious projects.  Feel free to play around with it!

## Goals
- Prevent the need of any manual memory management.  For example, in the C language, many calls to `malloc` and `free` are common, and they often lead to memory leaks.  One of Flycatcher's main goals is to prevent this, by automatically allocating, deallocating and freeing memory.
- It should be easily learnable for newer programmers, to give new programmers easy access to high-efficiency systems programming.
- It should be safe.  A Flycatcher program's validity should be strictly enforced, to ensure that it will run the way it is expected.  This is implemented with strict static typing and automatic memory management.