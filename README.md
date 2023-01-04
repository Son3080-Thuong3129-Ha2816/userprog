~/pintos-anon/src/userprog/build
pintos-mkdisk filesys.dsk --filesys-size=2
pintos -f -q
pintos run 'echo' -q
