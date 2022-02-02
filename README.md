# HelloReact

## Goal

This project is used for the demonstration only. It leverages React and ThreeJS to show a rotating 3D cube. It shows a way to integrate three into react directly, not by other libraries. It's fun! Enjoy!

## Prerequisite

* Codepen.io (just use it as a simple IDE, you don't need to signup, otherwise, you want to have an account.)
* react 17
* react-dom 17
* threejs 0.137

> If you want to run it locally, please install them via npm or yarn. Of course, don't forget your Babel :)
> On codepen, you need to use these libraries via skypack.

## Steps

1. Visit Codepen and press the button,**Start Coding** to launch the editor directly.
2. tap "Setting" from JS tab and set the preprocessor as Babel for JS.
3. Ctrl+C or copy the content of example.js
4. Ctrl+V or paste the content into **JS** tab.
5. type the following content into **HTML** tab.
```html
<html>
  <body>
    <div id="root"></div> 
  </body>
</html>
```
6. Now, you should see the rotating cube from the below window.

## Notes
1. The demonstrated codes of rotating cube is from [Getting Started](https://threejs.org/docs/index.html#manual/en/introduction/Creating-a-scene) on threejs.org. Of course, there are lots of interesting [examples](https://threejs.org/examples/#webgl_animation_keyframes) from that websites.
2. Of course, you could install the related libraries on the local site and develop all the things from your preferred IDE. You will need to setup your webpack to compile your codes. We will introduce all of them in the later course. :)