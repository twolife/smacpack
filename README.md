# smacpack - _Sid Meier's Alpha Centauri Planetary Pack_ launcher

A long time ago [...], in August 2000, [Loki Entertainment](https://en.wikipedia.org/wiki/Loki_Entertainment)
released a native Linux version of _[Sid Meier's Alpha Centauri Planetary Pack](https://en.wikipedia.org/wiki/Sid_Meier%27s_Alpha_Centauri)_.

Surprisingly, it is still possible to enjoy this game (among others)
on modern Linux based systems, thanks to efforts of
[some](https://github.com/ZeroPointEnergy/lokishim)
[people](https://github.com/twolife/lokishim).

This Linux version came with a small launcher that allowed the player to choose
between the original game or the _Alien Crossfire_ expansion.
That launcher was provided as a statically linked binary, that didn't age well
and is virtually unusable today; due to changes in how alpha-transparency
is handled between X protocol / server versions.

This is a rewrite of that `smacpack` launcher, in python3. 

![Obligatory screenshot](https://raw.githubusercontent.com/twolife/smacpack/main/screenshot.png)
