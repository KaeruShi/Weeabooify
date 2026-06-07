# Special Lockscreen (Deprecated)

The **Special Lockscreen** is an advanced lockscreen overlay that reimagines the Android lockscreen with an **iOS-inspired aesthetic** — full-screen widgets, repositionable elements, and precise layout control.
::: warning Deprecated
Only for version 5.6 below, latest version already includes this feature.
:::

## Clock

- **Custom clock size** — scale up or down
- **Custom font** — apply any font
- **Adjust clock position** — move freely on the screen

## Date

- **Custom date format**
- **Adjust date position**
- **Custom date color**

## Widgets

- **Add widgets** — weather, battery, steps, media, and more
- **Show/Hide widget background** — toggle the widget card background
- **Adjust widget position** — place widgets wherever you want
- **Custom widget color**

## Always-On Display (AOD)

- **Show/Hide on AOD** — control whether the special lockscreen layout is shown on Always-On Display

## System Bar

- **Show/Hide system bar** (status bar on the lockscreen)
- **Adjust system bar position** — vertical and horizontal
- **Adjust system bar size**
- **Custom system bar color**

## Wallpaper

- **Custom wallpaper** — set a dedicated lockscreen wallpaper
- **Adjust wallpaper blur** — frosted glass effect
- **Adjust wallpaper dim** — darken the background
- **Adjust wallpaper opacity**

::: info
The Special Lockscreen injects a full Compose-based overlay into `keyguard_root_view` at runtime, with its own `LifecycleOwner` and `ViewTreeOwner` chain. Constraints are re-applied on every rotation and AOD transition.
:::
