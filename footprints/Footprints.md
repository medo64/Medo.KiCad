# IPC 7351

- Courtyard [rectangle]:
  - Line width: 0.01
  - Line style: Dashed
  - Layer:      X.Courtyard

- Courtyard (connectors) [rectangle]:
  - Line width: 0.01
  - Line style: Dashed
  - Layer:      X.Courtyard
  - Distance:   0.5 (from furthest side component)

- Component [rectangle]:
  - Line width: 0.01
  - Line style: Dash-Dot
  - Layer:      X.Fab

- Silkscreen [rectangle]:
  - Line width: 0.1
  - Line style: Normal
  - Layer:      X.Silkscreen

- Silkscreen (pin 1, outer) [circle]:
  - Center X:   (same as pin 1)  -or-  0.25 from edge of pin 1  -or-  (same distance as pin 0 would be)
  - Center Y:   (same as pin 1)  -or-  0.25 from edge of pin 1  -or-  (same distance as pin 0 would be)
  - Radius:     0.1
  - Filled:     Yes
  - Line width: 0.1

- Silkscreen (pin 1, inner) [circle]:
  - Center X:   Component.Left - 0.5
  - Center Y:   Component.Top + 0.5
  - Radius:     0.2
  - Filled:     Yes
  - Line width: 0.1

- Ref [text]:
  - Pivot:      Bottom-Center
  - Width:      0.6
  - Height:     0.7
  - Thickness:  0.1
  - Layer:      X.Silkscreen
  - Position X: 0
  - Position Y: Courtyard.Top + 0.1

- Value [text]:
  - Pivot:      Middle-Center
  - Width:      0.6
  - Height:     0.7
  - Thickness:  0.1
  - Layer:      X.Silkscreen
  - Position X: 0
  - Position Y: 0  -or-  Courtyard.Bottom + 0.2

- Pin function [text]:
  - Pivot:      Middle-Left -or- Middle-Right
  - Width:      0.07
  - Height:     0.13
  - Thickness:  0.01 -or Bold (voltage or ICSP)
  - Layer:      User.7
  - Position X: 0
  - Position Y: Silkscreen.Left - 0.1  -or- Silkscreen.Right - 0.1 

