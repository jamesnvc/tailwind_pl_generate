# Tailwind_pl_generate

`Tailwind_pl_generate` is the internal library for [tailwind_pl](https://github.com/jamesnvc/tailwind_pl) that does the actual CSS generation. It's been split off into a separate library, so it can be used independently of the watcher, which requires `inotify` and hence only runs on Linux; this library is pure Prolog and should run anywhere SWI-Prolog does.
