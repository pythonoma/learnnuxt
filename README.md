# Learn Nuxtjs v3

#### Create a new Nuxt app: 
```npx nuxi init <project-id>```

#### Serve local port 3001 to LAN IP
```
devServer:{
    host: '0.0.0.0',
    port: 3001
  }
```
---
### Add NuxtTailwind 
#### Install and add the module to current project
```npx nuxi@latest module add tailwindcss```

#### Add to ``nuxt.config.ts``:
```
export default defineNuxtConfig({
  modules: ['@nuxtjs/tailwindcss'],
  tailwindcss: {
    exposeConfig: true,
    viewer: true,
    // and more...
  }
})
```
