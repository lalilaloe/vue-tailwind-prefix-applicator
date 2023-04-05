# Tailwind.CSS Prefix Applicator

## Project setup
```
yarn install
```
### Compiles and hot-reloads for development
```
yarn serve
```

## Extract custom tailwind classes (*php)
For example use `npx tailwindcss build -o custom.css` to output your projects classes. Don't forget to remove your `prefix: "tw-",` to output clean tailwind classes.
```
yarn run extract custom.css 
## or any other file/path
```

### Advanced
You can output all possible classes using the (safelist feature)[https://tailwindcss.com/docs/content-configuration#using-regular-expressions] in Tailwind.

You can also trick it into outputting all classes. This is not recommended as it takes a long time and outputs a large file but suits a real purpose in this case ;).
```
  safelist: [
    {
      pattern: /.*/,
    }
  ],
```


### Demo
https://github.vue.tailwind-prefix.cbass.dev
