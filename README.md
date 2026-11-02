# Routers All the Way Down

A top-down factory game on an infinite grid, written as one HTML file.
Everything (blocks, items, deposits, research costs, even the music)
is generated from a single world seed.

**Play:** <your GitHub Pages link>

## Features
- Six block types: conveyors (plus a router), bridges, extractors,
  factories, generators (plus batteries) and labs
- Block stats, research costs and recipes come from the seed and the
  block's ID, with no upper limit on IDs. Block size grows
  logarithmically with ID.
- Raw items appear as deposits that get rarer and farther from the
  origin as the ID rises. Some items can only be made in factories.
- Some factories are upgraded versions of lower-ID factories
- Items travel along conveyors, with queues and real travel time
- Power flows through any touching blocks, with batteries per network
- Research by feeding items to labs, then spending them on new blocks
- Seeded music: each world gets its own set of short melodies
  (leitmotifs), assembled into pieces. Some pieces are
  orchestral "battle" themes.
- A hidden boss fight if you chain five routers together
- Save and load as a JSON file, "New world" with a custom seed,
  and a developer mode

## Controls
| Input | Action |
|---|---|
| W A S D | Move camera (hold Shift for 2×) |
| Scroll | Zoom |
| Left click | Place the selected block (hold and drag to place a line) |
| R | Rotate conveyors and bridges |
| Right click | Exit placing mode; with nothing selected, delete (drag to delete a line) |
| Menu button / Esc | Pause: continue, save, load, new world, music, developer mode, exit |

## Running locally
Open `index.html` in a browser. No install is needed. Audio starts
after your first click or key press.

## License
GPLv3
