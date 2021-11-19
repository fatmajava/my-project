# my-project

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Vue Sequence
1- Create file at Veiws folder "Dummy.vue"
2- app.vue=>
    <b-nav-item>
    <router-link to ="/dummy">Dummy</router-link>
    </b-nav-item>
3- Router => index.js
3.1
    import Dummy from '../views/Dummy.vue
 , {
    path : "/yours-link",
    name : "dummy"
    Component: Dummy
 }
 4-Create component at component folder "DummyComp.vue"
 5- at Dummy.vue
 <template> 
 <Hello/>
 </template>

        import Hello from '@/components/DummyComp.vue'
        export default {
            components :
            Hello
        }


}