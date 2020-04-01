# An overview of my thoughts about a cross-platform 2D rendering pipeline

## API

  - plotter
  - canvas
  - graphics2D
  - path
      - line
      - polygon
      - curve
      - ellipse
  - text and fonts
  - masks
  - clipping
  - alpha compositing and blending
  - coordinate system

## Backends

  - Linux/BSD
      - OpenGL
      - Vulkan
      - X11
      - pixman
      - cairo/pango
      - DRM/KMS
      - GPU driver
          - i915
          - nouveau
          - radeon
  - Windows
      - OpenGL
      - Vulkan
      - Direct2D
      - GDI
      - DX11
  - Macos
      - Core 2D
      - Metal
  - Haiku
      - ???
  - Redox
      - Orbital
  - Plan9
      - libdraw
  - Web
      - WebGPU
      - WebGL
      - HTML/CSS/JS
      - Canvas
  - SoCs
      - Raspi
          - ???
      - Pine64
          - ???
  - Android
      - ???
  - iOS
      - ???
