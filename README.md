# fast-latex-with-espanso
Personal [Espanso](https://espanso.org) matches to speed up latex editing on Overleaf. Inspired by [Gilles Castel](https://castel.dev/post/lecture-notes-1/).

To use this script for Overleaf, git clone the repository under your `match` directory (Run `espanso path` to check your match and config directory) and then add the following line to an `.yml` file under your config directory, e.g. `config/default.yml`.
```
filter_title: "Overleaf"

extra_includes:
  - "../match/fast-latex-with-espanso/_latex.yml"
```

If you want to use the script for other apps, edit the `filter_title` line to match where you want the script to be activated. See https://espanso.org/docs/configuration/app-specific-configurations/ for more information on how to match your specific app.
