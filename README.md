# vuetify-electron

Initial codes for `Electron` & `Vue` & `Vuetify`

<br>

## Project setup in Windows

### Install git

```
> choco install git
```

### Install Node JS

```
https://nodejs.org/en/
```

### Install Yarn

```
https://classic.yarnpkg.com/en/docs/install#windows-stable
```

### Install Vue 3

```
> yarn global add @vue/cli
> vue --version
@vue/cli 4.5.10
```

### Create project

```
> vue create vuetify-electron
? preset: Manual
? features: Babel, Router, Vuex, Linter
? Vue.js: 2.x
? linter / formatter: Standard
? lint features: Lint on save
? config: dedicated config files
? future projects: No

> cd vuetify-electron
```

### Install Vuetify

```
> vue add vuetify
? preset: Configure (advanced)
? pre-made template: No
? custom theme: No
? custom properties: No
? icon font: Material Design Icons
? fonts as a dependency: Yes
? a-la-carte components: Yes
? locale: English
```

### Install Electron-Builder

```
> vue add electron-builder
? Electron Version: 9.0.0
```

<br>

## Project Build

### Compile/Build for production

```
> yarn electron:build
```

<br>

## Project Test

### Test project in local

```
> yarn electron:serve
```

<br>

## Etc

### Customize vue configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
