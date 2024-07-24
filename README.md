## GPT in Elixir using Nx/Axon

This is a follow-along of Andrej Karpathy's [Let's build GPT: from scratch, in
code, spelled out.](https://www.youtube.com/watch?v=kCc8FmEb1nY) Jupyter
Notebook using Elixir/Livebook/Axon/Nx.

This is still a work in progress and I've done my best to label the sections in
accordance with the Youtube video.

### Usage

1. Drop into a Nix shell (requires `flakes` enabled)
```console
nix develop
```
2. Install `livebook`
```console
mix escript.install hex liveserver
```
3. Run `livebook` and open the file `gpt.livemd` within the repo
```
livebook server
```
