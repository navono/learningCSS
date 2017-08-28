This is sample CSS code for learning.

# Cascade and inheritance
哪个selector最终会起作用，根据以下三个因素来判断，优先级从高到低：
- Importance
- Specificity
- Source order

# Fundamental text and font styling

## web safe fonts

name | Generiac type
---- | ---
Arial | sans-serif
Courier New |   monospace
Georgia | serif
Times New Roman | serif
Trebuchet MS | sans-serif
Verdana | sans-serif

## Font size
- px
- em
- rem

## Font sytle, font weight, text transform, text decoration
- font-style
  - normal
  - italic
  - oblique
- font-weight
  - normal, bold
  - lighter, bolder
  - 100-900
- text-transform
  - none
  - uppercase
  - lowercase
  - capitalize
  - full-width
- text-decoration
  - none
  - uderline
  - overline
  - line-through

其他的Font styles还有：
- font-variant
- font-kerning
- font-feature-settings
- font-variant-alternates
- font-variant-caps
- font-variant-east-asian
- font-variant-ligatures
- font-variant-numeric
- font-variant-position
- font-size-adjust
- font-stretch
- text-underline-position
- text-rendering

Text布局风格还有：
- text-indent
- text-overflow
- white-space
- word-break
- direction
- hyphens
- line-break
- text-align-last
- text-orientation
- word-wrap
- writing-mode


# text shadows
```css
text-shadow: 4px 4px 5px red;
```
四个参数：
1. 水平偏移
2. 垂直偏移
3. 模糊半径（blur radius）
4. 基色（base color）
