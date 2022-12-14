# vue-wordpress

> A vue plugin that facilitates use of the WordPress REST API as a back-end Content Management System (CMS) with a Vue front-end

# Design overview


# Example:

Check out the example in src/example/example.vue

You can run the example by running npm run dev (see below)

You can see the components used 'in the wild'

## Getting Started

### Vue installation

```
vue add vue-wordpress

```

### How to use vue-wordpress in your Vue app

Anywhere you wish to pull in content from WordPress, simply do the following:
```

<div v-for="(post,index) of postLoader.pages[0].content" :key="index">
    <post-summary imgSize="thumbnail" :post="post" class="post-summary"></post-summary>
    </br>
</div>

```

#### &#x1F537; Note: You may experience a babel-preset-env error when running 'npm run dev'
-- to fix this, please execute 'npm install --save-dev babel-preset-env'. See Babel issue 186 for more information <https://github.com/babel/babel-preset-env/issues/186>

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
