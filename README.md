# Workinprogress
I'm writing on this as I migrate my system to it's final form. So this stops in the middle and will have single words as a reminder. Thats okay. I'll fill in the blanks on my next travels.

## MyHomeAssistantSetup

### Preface
You want a setup that is resilient and practical? That leaves room for other shenanigans? You've come to the right place. The only two skills I think you need is fearlessness and dedication. All here isn't rocket science, its just boring tech. Which is good.

### Hardware, Part I: The Core System

I started with a raspberry pie, as I assume most home assistant users (haus) do. The mental sale pitch of a raspi is brilliant: Just this board, everything included. Excep the case, the sd-card, the harddrive and the power supply. And some extras you will need.

At some point in my personal evolution I looked at the power consumption of the system: It was around 2W, with 3 to 4 W peak. I also looked at the flexibility and durability of the data storage and ram. Which was meager to non existant. So when searching for alternatives I came across this website: https://www.tpcdb.com/ - the power consumption database.
The database showed me that there is plenty of NUCs that run around 4W idle, while being significantly more flexible and extendable. And they are x86/Amd64 which means first class support for drivers and gizmos.

So I bought a nuc. And another, as a reserve. Both cost me less than 60€ (in 2022). I upgraded them to the max: 16 gb ram and 1 TB internal ssd.
With that hardware, everything is a peace of cake (until it wasn't - but I've learned from my mistakes and you will avoid them too, with my notes)

- If you have no hardware yet for home assistant: Super! Go NUC and similar, skip the raspi phase. You'll thank me later.
- If you have raspi hardware: Great, you have a running system. It's time to get an upgrade you can migrate to.
- If you have x86 hardware: Congrats. Check https://www.tpcdb.com/ for power saving and compare flexibility.

(--- will continue to write later ---)
