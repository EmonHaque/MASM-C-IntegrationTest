Inline __asm{ ... } doesn't work on x64!

1) right click the project, go to Build Dependencies -> Build Customisations
2) check masm(.targets, .props)
3) create a separate .asm and add your procs
4) build and run