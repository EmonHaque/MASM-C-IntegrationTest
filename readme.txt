Inline __asm{ ... } doesn't work on x64!

1) right click the project, go to Build Dependencies -> Build Customisations
2) check masm(.targets, .props)
3) add/create .asm files and write your procs
4) declare the protos and call
5) build and run
