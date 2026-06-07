# Depth Wallpaper

The **Depth Wallpaper** effect creates a parallax-style layered look by splitting your wallpaper into a background and a foreground subject layer — giving the lockscreen a 3D depth appearance with your wallpaper's subject rendered in front of the clock.

## How It Works

Weeabooify extracts the subject from your wallpaper using a background processing pipeline (via WorkManager), then renders two independent layers:

```
┌─────────────────────────┐
│   Foreground (subject)  │  ← rendered above clock
│        Clock / UI       │
│   Background (scene)    │  ← rendered behind everything
└─────────────────────────┘
```

Changes are processed automatically whenever your wallpaper changes.


## Scale Foreground Image

**Match to native device wallpaper** — scales the extracted foreground subject to match the dimensions and positioning of your device's native wallpaper, so the subject aligns naturally without manual adjustments.

## Custom Images

Override either layer with your own image instead of using the auto-extracted wallpaper:

- **Custom background image** — replace the background layer with any image of your choice
- **Custom foreground image** — replace the extracted subject layer with your own image

::: tip
Using a custom foreground with a transparent PNG gives you full control over what appears in front of the clock, independent of your wallpaper.
:::

## Background Adjustments

Fine-tune the background layer's appearance:

- **Dim** — darken the background to reduce visual noise behind the clock
- **Blur** — apply a frosted glass blur to the background layer

## Foreground Adjustments

Fine-tune the foreground subject layer's appearance:

- **Dim** — add a darkening overlay over the foreground subject
- **Blur** — soften the foreground subject edges for a depth-of-field effect

::: info
Depth Wallpaper processing runs via **WorkManager** and a broadcast, so extraction happens even when the Weeabooify app is not in the foreground.
:::
