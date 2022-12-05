# Gulp with TailwindCSS Starter Kit

Gulp with TailwindCSS v3 Starter Kit.
A repo which makes your development easier with predefined gulp tasks that help you to use [tailwindcss](https://github.com/tailwindcss/tailwindcss) with simple commands.

## Included Tailwind Plugins

- @tailwindcss/forms
- @tailwindcss/line-clamp
- @tailwindcss/typography

## Usage

1. Install Dev Depedencies

```sh
npm install
```

2. To start development and server for live preview

```sh
npm run dev
```

3. To generate minifed files for production server

```sh
npm run prod
```

# Configuration

To change the path of files and destination/build folder, edit options in **config.js** file

```sh
{
  config: {
      ...
      port: 9050 // browser preview port
  },
  paths: {
     root: "./",
     src: {
        base: "./src",
        css: "./src/assets/css",
        js: "./src/assets/js",
        img: "./src/assets/img"
     },
     dist: {
         base: "./dist",
         css: "./dist/assets/css",
         js: "./dist/assets/js",
         img: "./dist/assets/img"
     },
     build: {
         base: "./build",
         css: "./build/assets/css",
         js: "./build/assets/js",
         img: "./build/assets/img"
     }
  }
  ...
}
```
