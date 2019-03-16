# i3idler

These simple scripts probably will be useful only for laptop users and more probably for laptop users who uses `i3-wm` as main WM.

`achecker` is a simple bin to start on system start. It ensures on battery state and setup initial condition.

`i3idler` is a simple listener to `ACPI` socket and handles incoming events. This structure done due to inability of `acpi service` to perform on «user» level (e.g. start any of `Xorg` apps).

`suspender` is just and alias for handler — `i3idler` redirecting events to this binary. `suspender` just acepts and handles events or simply skips them.

`i3lock2` another one simplest improvement for insane `i3lock` ¯\\_(ツ)_/¯

__NB:__ it's about [146%](https://gawker.com/5864945/putin-clings-to-victory-as-russias-voter-turnout-exceeds-146) that this repository will get updates once in a year