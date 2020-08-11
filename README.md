# Parcel+Vue template

Simple boilerplate using Parcel + Vue + Vuex + Vue-Router.

### How to:

1. `git clone https://github.com/ClimenteA/parcel-vue-template.git`
3.  Rename `parcel-vue-template` folder with `your-project-name` 
4.  Rename from package.json file field: `"name": "parcel-vue-vuex-vue-router-template"` to `"name": "your-project-name"` 
5. `cd your-project-name`
6. `npm run dev` (this will install dependencies also)


### Install other modules

Production: `npm install buefy`

Development: `npm install typescript --save-dev`


### Build

By default when you run `npm run build` it will remove `dev` folder.

If you are running windows rename `prebuild` to `prebuild_if_linux` and `prebuild_if_windows` to `prebuild`.

```
...
  "prebuild": "rm -rf dist",
  "prebuild_if_windows": "rmdir dist /s /q"
...

```

Parcel `prebuild` assures that there are no duplicate files in dist folder when running npm build.





