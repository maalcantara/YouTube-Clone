<div align='center'>
  <h1 >YouTube Clone ▶️</h1>
  <h3>(In progress)</h3>
</div>

![YouTube Clone](src\assets\devtube-print.png)

## Overview 📹

This project is a responsive clone of the YouTube homepage interface, built using TypeScript, React, and YouTube data. Also, the project includes a responsive navbar, which adapts to different screen sizes and devices.

## Technologies 🎞️

- Vite
- React.js
- TypeScript
- Tailwind

## Installation ▶️

To run this project on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/maalcantara/youtube-clone.git
   cd youtube-clone
   ```

2. Install dependencies and start the development server:
   ```bash
   npm install
   npm install autoprefixer
   npm i class-variance-authority tailwind-merge
   npm install lucide-react
   npm run dev
   ```
3. Open your web browser and navigate to http://localhost:xxxx to see the project in action.

## Notes 📌

- This project utilizes Vite for a fast and efficient development setup. You can learn more about Vite at https://vitejs.dev/.

- Tailwind CSS is used for styling and is a highly configurable utility-first CSS framework. For more information about Tailwind CSS, visit https://tailwindcss.com/.

## Credits 📹

- **YouTube:** [video tutorial](https://www.youtube.com/watch?v=ymGB1lqP1CM) by WebDevSimplified.
- **React:** The JavaScript library used for building the user interface.
- **Lucide React:** Implementation of the lucide icon library for react applications.

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
