# Michalis Zabaras

Athens. Keyboards of every kind. I go by [mikezaby](https://github.com/mikezaby) when I write code and [Miza Kiro](https://www.youtube.com/@mizakiro) when I make music, and the line between the two gets blurrier every year.

I build instruments. Some of them are songs, most of them are code.

---

The thing I keep coming back to is **[Blibliki](https://github.com/mikezaby/blibliki)**. It started in 2022 as a little experiment on top of Tone.js: a few modules, some cables, a grid in the browser to patch them together like a hardware modular. That first version is still around at [blibliki-js/engine](https://github.com/blibliki-js/engine). In 2024 I tore it down and rebuilt it straight on the Web Audio API, no library in between, and pulled everything into one monorepo so I could own the whole stack down to the AudioWorklet.

Now it wants to be an instrument rather than a patchbay. Tracks, sequencer blocks, pages, a Novation Launch Control XL3 mapped onto all of it, and the same session running in a browser tab, on a phone, or on a Raspberry Pi with its own little screen. It is a solo thing, it is not finished, and it moves at the pace of evenings and weekends.

If you want the long version, there is a four-part series on how the engine works at [mikezaby.com](https://mikezaby.com/), and a [GreeceJS talk](https://www.youtube.com/watch?v=cgrb_Li3bWU&t=6324s) where I explain it out loud.
