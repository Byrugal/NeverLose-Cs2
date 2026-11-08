
1. Fixed the autowall and multipoints functions in rage mode: removed an erroneous limit of 64 traces per tick, which previously caused the cheat to malfunction and fail to penetrate walls when scanning multiple points.
2. Fixed autowall and multipoints in rage mode (removed a flawed 64-trace-per-tick limit that caused the cheat to occasionally malfunction and fail to penetrate walls when scanning multiple points).
3. Instant yaw switching (the 15-tick delay and smoothing have been removed; calculations have been moved to a multithreaded process)
4. Fixed local model pitch (the head in third-person view no longer looks straight ahead when firing while using anti-aims)
5.Animfix for mid-air movement and sub-tick bunny hopping (the character model no longer jitters during jumps; leg animations upon landing have been fixed).

The loader has been removed; it’s now just a DLL, as some users were experiencing issues with the injection process.
