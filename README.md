# component-library-drafts
thoughts & ideas that i may use if i ever get the crazy idea that i want to make an open source (svelte) component library

## Inspiration:
- https://www.radix-ui.com/
- https://jetbrains.github.io/ring-ui/master/index.html
- https://element-plus.org/

## Ideas & thoughts:

### Must-haves
- Light/dark theme
- Configurable color system
- Interactive docs
- SSR support
- Plug & play (other configs needed)
- TypeScript support
- Fast & clean animations (remember @prefers-reduced-motion)
- Figma

### Color palette
Multiple color palettes could be nice, should be really easy to change if i've designed the system correctly.

Should use https://tailwindcss.com/docs/customizing-colors#default-color-palette as default color palette.
Think i want to use Tailwind for developing, but it should not be a dependency for using the library.

### Icons
Don't really wanna be the one to tell others what icons they should use. 
Using https://github.com/antfu/unplugin-icons, or maybe just designing the API
so that icons should come from somewhere else, sounds appealing.

### Uncluttered doc-page
The documentation page must be stupid simple and fast.
Also need to find out what should be shown in the API documentation for every component.

### Enabled and disabled styling sheet
Not sure about this yet... idk if there are components that only need classes to be used, e.g. button or badge. 
But if this is the case, then two types of styling sheets could be provided:
- enabled (all button elements will automatically be styled)
- disabled (you need to apply button class to style elements)

### Start simple
Begin with components that are most commonly used. Also maybe wait with a11y, because that's a big rabbit hole.
My opinionated list of components to start with (in order):

- button
- input (text, textarea)
- select
- checkbox
- dropdown
- switch
- tabs
- dialog
- popover
- tooltip
- toast
- avatar
- label
- radio group
- datepicker
- slider
- menu bar
- navigation menu


### Name
Future (UI)
