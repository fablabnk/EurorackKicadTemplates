This repo contains KiCad templates for Eurorack synthesiser modules, for use in the KiCad PCB Editor. Each template is for both the main PCB and it's associated front panel, so that they can be designed and manufactured in tandem.

# Things to know

- Currently only a 6HP example is present in the repo
- The front panel template is full height 128.5
- The main board template is much shorter 106, so that it can fit past the Eurorack screw rails
- The main board template is positioned in the vertical centre of the front panel
- The surrounding dimension markers are just for reference and removing them can help with grid placement
- The front panel elements and main board elements are grouped together separately and locked. Be careful when moving them to maintain the spacing between them

# Workflow

Currently I work as if we are looking down on the front panel and looking at the PCB from the opposite side. This means the components must be flipped when placing them on the PCB template.

My current workflow goes like this:

1. place our key components (pots, jack sockets, switches, led etc) on the front panel and use the centre holes to create a layout
2. move these components over to the main board, then select them all and flip them (where needed)
3. flip each component back and place it in the same position as it was through rotation etc
4. add the other elecronic components

Note that silk screening on the PCB will be as if you are looking at the board from the back. This is because the legs of pots, jacks etc will stick out from this side. For other components it is unclear if mounting on the back or front best. Probably this needs more consideration for future builds...
