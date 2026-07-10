# hey, i'm AnonNeo77

```
   ___                 _   _            
  / _ | ___  ___  ___ | \ | | ___  ___  
 / / | |/ __|/ _ \/ _ \|  \| |/ _ \/ _ \ 
/ /__| |\__ \ (_) | (_) | |\  | (_) | (_) |
\____/_||___/\___/ \___/|_| \_|\___/ \___/
                                           
a security researcher. sometimes i reverse things.
other times things reverse me.

currently: digging into kernel-level chaos
status: always learning | never stopping

```

---

## who am i?

i spend my time staring at assembly code, finding rootkits that shouldn't exist, and breaking things open to understand them. linux kernel modules, android firmware, binary reversing—it's all just puzzles waiting to be solved.

the kind of person who reads disassembly for fun. no judgment if you do too.

---

## what i actually do

- **reverse engineering** → decompile, analyze, understand
- **malware research** → find the bad stuff, figure out how it works
- **kernel security** → look for suspicious module behavior
- **firmware hacking** → android, bootloaders, partitions—it all falls apart eventually
- **ctf grinding** → crackmes, hackthebox, just for the sake of it

essentially: i take things apart, see how they're built, and document what i find.

---

## the projects

### [koaudit](https://github.com/AnonNeo77/koaudit) — kernel module auditor
static analysis tool for finding suspicious behavior in linux kernel modules. if your kernel module looks like a rootkit, this will probably catch it. or at least make you paranoid enough to check twice.

**why it exists:** because understanding what's actually running in your kernel matters.

```
python | kernel-modules | static-analysis | linux-security | rootkit-detection
```

---

### [MTK-SuperBuilder](https://github.com/AnonNeo77/MTK-SuperBuilder) — android partition tool
build and unpack android dynamic partition images. mediatek devices mostly. the kind of tool you need when you want to actually understand your phone's firmware.

**why it exists:** dynamic partitions are a mess. this makes it slightly less of a mess.

```
android | firmware | partition-manipulation | mediatek | python
```

---

### [Realme C55 Root Guide](https://github.com/AnonNeo77/realme-c55-root-guide) — technical documentation
deep dive into bootloader unlocking, avb verification, recovery flashing. basically "how to completely own your phone and why it's harder than it should be."

**why it exists:** because detailed technical documentation on this stuff is hard to find, and i learned it the hard way.

```
android-rooting | bootloader | avb | firmware-analysis | mediatek
```

---

### [Reverse Engineering Writeups](https://github.com/AnonNeo77/reverse-engineering-writeups) — ctf solutions & crackmes
hackthebox, tryhackme, random crackmes. solutions to problems. my notes on how i broke things open.

**why it exists:** documenting the process helps me learn. maybe it helps you too.

```
reverse-engineering | binary-analysis | ctf | ghidra | radare2 | malware-analysis
```

---

## how i work

| tool | language | what i use it for |
|------|----------|-------------------|
| **Ghidra** | — | decompilation, when you need to actually understand code |
| **Radare2** | — | lightweight analysis, scripting automation |
| **GDB** | — | debugging, dynamic analysis, watching things execute |
| **x64dbg** | — | windows reversing, when you have to go there |
| **Python** | — | everything else. tools, scripts, automation |
| **Assembly** | x64/ARM | when you're reading the real stuff |

---

## what i'm into

- kernel-level threats and security
- firmware engineering and analysis
- binary exploitation concepts
- cryptanalysis and protocol breaking
- understanding how things actually work (not just what they're supposed to do)

basically: the lower the level, the more interesting it gets.

---

## current state

```
learning: [████████████░░░░░░░░░░░░░░░░░░░░░░░░░░] 30%
obsessed: [████████████████████████████████████████] 100%
sleep schedule: [░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░] 2%
```

always looking for:
- interesting malware samples
- kernel-level security challenges
- firmware engineering problems
- people doing real security research

---

## if you want to talk

- found something weird in your kernel? 
- got a firmware you need reversed?
- interested in collaborating on security research?
- want to discuss why certain rootkits are actually impressive?

hit me up. or don't. i'll probably be staring at ghidra anyway.

---

## disclaimer

everything here is for education and research. use it responsibly. understand the laws in your country. don't do illegal stuff. i'm serious.

the code is here. the knowledge is here. what you do with it is on you.

---

```
stay curious
stay safe
stay weird

— AnonNeo77
```
