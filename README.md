```sh
┌──(sarthak㉿tty1)-[/home/sarthak]
└─$ whoami
15 y/o wannabe low-level enthusiast  
studying *nix internals, OS design, and the Linux abyss  
no IDEs, no GUIs, just TTYs and man pages  
init systems > social systems

> "If you don’t know how it works, you don’t own it."
```

---

```sh
┌──(sarthak㉿tty1)-[/home/sarthak]
└─$ dmesg | grep contact
[+][email]   → sarthak.brnw@proton.me  
[+][discord] → sarthakbrnw  
[+][x.com]   → @sarthakbrnw
```

---

```sh
┌──(sarthak㉿tty1)-[/home/sarthak]
└─$ uname -a
Linux void-machine 6.8.0-custom x86_64 GNU/Linux  
bootloader: GRUB  
shell: /bin/sh  
X11: only when summoned  
desktop: dwm (patched like a madman)  
status: writing dotfiles like gospel  
mood: breaking, learning, repeating
```

---

```sh
┌──(sarthak㉿tty1)-[/home/sarthak]
└─$ pstree -A

init
├─ login
│  └─ shell
│     ├─ vim
│     ├─ less
│     ├─ man
│     ├─ htop
│     └─ startx --> dwm
└─ X: inactive (until summoned)
```

---

```sh
┌──(sarthak㉿tty1)-[/home/sarthak]
└─$ echo "goodbye world" > /dev/null
```
