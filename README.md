# DWM
dwm is a dynamic window manager for X. It manages windows in tiled, monocle and floating layouts. All of the layouts can be applied dynamically, optimising the environment for the application in use and the task performed.

# Preview
<p align="center">
    <img src="https://github.com/motolla/dwm/blob/vscode/img/dwm-preview%2301.png">
    <img src="https://github.com/motolla/dwm/blob/vscode/img/dwm-preview%2302.png">
</p>

# Quick Keybind
```
# Open Terminal (st)
Alt + Enter

# Close & Kill Program
Alt + q

# Switch Focus Window
Alt + j/k

# Move Stack
Alt + Shift + j/k

# Toggle Layout
Alt + Space

# Toggle Gaps
Alt + Shift + +

# Increase Gaps
Alt + +

# Decrease Gaps
Alt + -
```

# Patch Applied > [PATCH](https://github.com/motolla/dwm/tree/vscode/patch)

# Requirements
+ Void
```
xbps-install libXft-devel libX11-devel libXinerama-devel
```
```
Nerd Font JetBrains
```
# Build & Install
+ Clone the repo

```
git clone https://github.com/gillgrite/dwm.git
```

```
cd dwm
```

```
git checkout vscode
```

+ Build & Install dwm
```
./dwmclean
```
