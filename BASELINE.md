## Baseline

I used color-mix() to blend colors within perceptually uniform color spaces such as oklab, creating consistent lighter tones and border shades for buttons and cards. Compared to hard-coded hexadecimal values, this approach produces more stable and tunable results across different themes and displays, while keeping color logic linked to design tokens instead of fixed values. The color-mix() API is a modern Baseline feature with strong support across major browsers.

