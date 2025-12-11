# VGA-Pattern-Generator

VGA timing contains visible area + porches + sync:

For 640×480@60Hz:

Horizontal visible pixels = 640

Horizontal front porch = 16

Horizontal sync pulse = 96

Horizontal back porch = 48

Horizontal total = 800 (counts 0..799)

Vertical visible lines = 480

Vertical front porch = 10

Vertical sync pulse = 2

Vertical back porch = 33

Vertical total = 525 (counts 0..524)

HSYNC and VSYNC are typically active low for this mode.
