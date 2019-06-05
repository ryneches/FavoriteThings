# FavoriteThings

When I find something awesome and useful on the internets, I often find
that I don't want to close the browser tab for fear of forgetting that
my new discovery exists. This repo exists mostly to help me address my
browser-tab-anxiety, but everything on this list really is pretty awesome.

## Software

### [`sshuttle`](https://sshuttle.readthedocs.io/en/stable/index.html)

If you have ssh access to a machine with a trusted network connection, 
`sshuttle` lets you use it as a VPN exit gateway for your local machine.
As long as the remote machine has a python interpreter, you don't need
to install or configure anything on it.

### [`gzipstream`](https://github.com/commoncrawl/gzipstream)

Streaming I/O from gzipped data sources. Comes in handy when working with
huge text-like data files.

### [The Knowledge Repo](https://airbnb.io/projects/knowledge-repo/)

A tool for organizing Jupyter notebooks and MarkDown documents into a
bare-bones peer reviewed journal.

### [Jupyter Renderers](https://github.com/jupyterlab/jupyter-renderers)

Renderers to display various types of output in Jupyter notebooks. My 
particular favorite is the FASTA viewer, which serves as a pretty-OK
viewer for DNA, RNA and protein alignments.

### [Jupyter Themes](https://github.com/dunovank/jupyter-themes)

I spend a lot of time in Jupyter notebooks. Themes are fun, but they are
also an effective way to avoid eyestrain and address other ergonomic
issues.

### [notify.run](https://github.com/paulgb/notify.run)

This tool makes it super easy to push notifications to a mobile device
from python or shell code that may be running anywhere. This is really
handy when you've got a long job running on a remote machine, and you'd
like to track its status in some customized way.

### [nbdiff](https://github.com/tarmstrong/nbdiff)

Jupyter notebooks aren't flat files, so they can be kind of annoying to
track with git. `nbdiff` solves most of the major pain points, particularly
merging and resolving conflicts.

### [mathpix](https://mathpix.com/)

An OCR tool specifically for mathematics with sophisticated integration with
various desktop environments (Windows, OS X, Gnome) and LaTeX-based writing
platforms. Highlight some math, and it will magically poof into LaTeX math
mode.

### [Magic Wormhole](https://github.com/warner/magic-wormhole)

A pure python utility that lets you move a file from one computer to another
using human-readable, human-pronounceable authentication tokens across the 
internet.

### [PyPrind](https://github.com/rasbt/pyprind)

A python module for adding text-based progress bars to your code. I also like
[`tqdm`](https://github.com/tqdm/tqdm), which does pretty much the same thing
but has more features. I find that I run into fewer issues with PyPrind's
text-only design, though.

### [hat-trie](https://github.com/pytries/hat-trie)

A [trie](https://en.wikipedia.org/wiki/Trie), or prefix tree, is a data structure
for compactly storing and searching ordered, sequence-like data (usually strings).
The twist is that tries search for a match starting at the first element, and
stops as soon as a unique prefix is identified. If you've ever used tab
completion, it's just like that. `hat-trie` is an extremely high performance
unicode trie that implements the Python `dictionary` interface. It's not a tool
I reach for often, but when a job calls for a prefix tree, it's *scary* how much
faster `hat-trie` is than a basic dictionary or set.

## Data

### [WorldClim](http://worldclim.org/)

A map dataset of several bioclimactic variables at about 1km resolution.

## Hardware

### [OTTO](https://github.com/topisani/OTTO)

An open source synth, sampler, sequencer, effects processor and audio looper,
inspired by the [Teenage Engineering OP-1](https://teenage.engineering/products/op-1).

## Assorted

### [Swear Trek](https://sweartrek.tumblr.com/)

Hilarious memes and GIFs derived from Star Trek. It's the best thing.
