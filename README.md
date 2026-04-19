# Greedy Piggies — Widget Switcher API Docs

API documentation for the Widget Switcher system I built for Greedy Piggies. It's the part of the game that handles all the menu UI — opening pause menus, navigating between options screens, and making sure gamepad controls actually work properly with widgets.

The whole thing runs through a Player Controller called `PC_MainInstance` and uses an enum (`E_MenuState`) to keep track of which menu is currently showing.

**Live site:** [https://yourusername.github.io/greedy-piggies-api/](https://yourusername.github.io/greedy-piggies-api/)

## What's in the docs

- How the Widget Switcher works and how it manages menu states
- The main Blueprint methods — `ApplyMenuState`, `RefreshMenuInput`, and `SetInitialWidgetFocus` — with all their inputs, outputs, and what happens when things go wrong
- How gamepad/controller support works (detecting mouse vs. gamepad and handling D-pad focus)
- A call flow walkthrough with actual Blueprint screenshots from the project
- Known issues, mainly that Steam Input doesn't play nicely with it yet

## Built with

- Unreal Engine 5.6.1
- Enhanced Input system (`IMC_GamePad` mapping context)
- Hosted as a static page on GitHub Pages

## Files

```
GreedyPiggiesAPI.html    ← the docs page (everything's in this one file, images included)
README.md                ← you're reading it
```

## Running locally

Just open `GreedyPiggiesAPI.html` in your browser. No setup needed.
