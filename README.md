Scuffed Linux Loader 🍆

Read this and make your own mind up, stay on 12.xx or update to 13.60 :)
https://x.com/sonic_iso/status/2113252409782755428?s=46

A working Linux loader for PS5 firmware 12.00, 12.02 (not had a isolated test yet, but I’ve uploaded), 12.20, 12.40, 12.60 and 12.70

It needs a PS5 Linux image on USB or SSD, and it arms once per boot — power-cycle to arm again.

## Get the pieces 

I recommended this image as it patches WiFi, add 1440p etc
- **PS5 Bazzite Deck** https://github.com/VivaLaVent/ps5-bazzite-deck/releases
  
- **The AIO .elf Loader** — check loader releases here
  
- More images you can test yourselves here - https://github.com/ps5-linux/ps5-linux-image/releases/tag/latest

## To test/use
I seriously recommend using a SSD in a enclosure, USB flash drives are just way too slow for use
1. Flash the image using Rufus and plug the drive into a rear USB-A port or the bottom front USB-C port.
2. On a freshly jailbroken (relaspe) console, run the loader. Don't use autoloader, manually send it after a relaspe jailbreak.
4. It arms and drops to rest mode — wait for the orange light to stop blinking, then press power.
5. Linux boots. One arm per boot, so power-cycle before trying again, first boot can take a while.

## Credits

- **rmux** — the 12.40 CFI check address, taken from his developer build
- **ps5-linux** — the loader source and the Ubuntu image this build boots
- **soniciso1** — the loader fork this build is based on, and the image archive
- **Ouroboroshen** — his 13.00 / 13.20 tables, used to cross-check our own 12.40 console
- **gzimbric** — his 11.60 port, the reference we checked the wake path against
- **PS5Dev** — Byepervisor and its HV escape, which our kernel read/write work builds on
- **j4lenj** — the original MT7921 module port that one is built from

  
 Discord 12.xx Bros POGGERS
 All below gave me their dumps, verified and booted into Linux
- **Ben3Coder** 12.70 (confirmed)
- **Shortykun** 12.20 (confirmed)
- **MagmaEye** 12.60 (confirmed)
- **4killerbeast** 12.00 (confirmed)
- **Darks** 12.02 (still awaiting confirmation of boot)
