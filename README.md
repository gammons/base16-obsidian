# Base16 colors for obsidian

This is the [Base16][b16] CSS theme for the [Obsidian notes application][o].

It includes 131 variations of the base16 theme.

## Installation

1. Clone this repo.
2. Copy all of the .css files from the root of this repo to `<vault>/.obsidian/themes` folder.

## Using your own font
This project doesn't make any assumptions about your font choice.  Each of these themes assumes there is a `--font-family-editor` and `--font-family-preview` variables.  You can add a CSS snippet that defines the font you want to use, smiliar to something below:

```css
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono&display=swap');

body {
  --font-family-editor: Roboto Mono, monospace;
  --font-family-preview: Roboto Mono, monospace;
}
```

## How to use in Obsidian

1. In obsidian, go to Settings -> Appearance
2. Set your color scheme to dark
3. Choose one of the 131 base16 themes to use.

## Development

There is a `build/` directory that allows you to make changes en masse to all of the themes.  Make changes to `base16-obsidian.css`, and then run `rake`.  It will then populate all of the themes in the parent directory with the new changes.

[o]: https://obsidian.md
[b16]: https://github.com/chriskempson/base16
[themes]: https://github.com/gammons/base16-obsidian/tree/main/base16-themes


## Some examples:

#### ia-dark

![image](https://user-images.githubusercontent.com/38560/123446102-8bb34080-d5a6-11eb-9ba8-6cb283abf850.png)

#### Nord

![image](https://user-images.githubusercontent.com/38560/123446243-b0a7b380-d5a6-11eb-8195-b366ebde02bb.png)

#### Solarized-dark

![image](https://user-images.githubusercontent.com/38560/123446442-e3ea4280-d5a6-11eb-8fc2-913a2723a443.png)

#### Solarized-light

![image](https://user-images.githubusercontent.com/38560/123446520-f6647c00-d5a6-11eb-99be-55520a55df6e.png)

#### Eighties

![image](https://user-images.githubusercontent.com/38560/123446709-214ed000-d5a7-11eb-97e9-e367b14faa1e.png)

Over 130 themes are included!
