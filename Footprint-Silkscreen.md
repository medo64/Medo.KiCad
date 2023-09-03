# Footprint Design

## Silkscreen

Dot should be outside of component outline and with a 0.15 mm radius. Location
is as follows:

| Direction | X Formula                               | Y Formula                                |
|-----------|-----------------------------------------|------------------------------------------|
| Top       | Component.X                             | Component.Y - Component.Height / 2 - 0.3 |
| Left      | Component.X - Component.Width / 2 - 0.3 | Component.Y                              |
| Bottom    | Component.X                             | Component.Y + Component.Height / 2 + 0.3 |
| Right     | Component.X + Component.Width / 2 + 0.3 | Component.Y                              |
