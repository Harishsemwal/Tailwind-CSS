# Tailwind CSS

Tailwind CSS is a utility-first CSS framework for rapid UI development. It provides a set of highly customizable utility classes that you can use directly in your HTML to build responsive, modern designs without writing any CSS.

## Installation

You can install Tailwind CSS via npm:

```bash
npm install tailwindcss
```

``` Once installed, you can include Tailwind CSS in your project by importing it in your CSS file:

@import 'tailwindcss/base';
@import 'tailwindcss/components';
@import 'tailwindcss/utilities';

```
## Usage
``` Tailwind CSS operates on a utility-first approach. Instead of writing custom CSS, you can apply utility classes directly in your HTML markup. For example:

html
Copy code
<div class=""bg-blue-500 text-white font-bold py-2 px-4 rounded"">
  Button
</div>
```

This will create a button with a blue background, white text, bold font, padding, and rounded corners.



## My Importent Notes :
```
create two folder: dist, src.
dist: index.html
src : input.css

input.css :-

@tailwind base;
@tailwind components;
@tailwind utilities;

tailwind.config:
content: ["./dist/index.html"]

npx tailwindcss -i ./src/input.css -o ./dist/style.css

npx tailwindcss -i ./src/input.css -o ./dist/style.css --watch


Terminal:
npx tailwindcss init

```
