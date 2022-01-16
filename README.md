# example repo to see that the poprs are not showing in the suggestions

### intall the package
First install the library using your prefered package manager
```bash
yarn add @yaman3bd/vue-vite-example
```
### usage
then you can import the available component like so
```vue
import {MButton} from '@yaman3bd/vue-vite-example'
```
add styles
```vue
import '@yaman3bd/vue-vite-example/dist/style.css'
```
MButton availbe props:
```
label,
title,
type,
disabled
```
they all not showing in the props suggestions like so:

![m-button](https://user-images.githubusercontent.com/58285821/149418924-586b1ec6-e2ed-4d1e-a3e4-b8714767f7df.png)

and the props are in the dist build files but idk why not showing when using the component:
![build](https://user-images.githubusercontent.com/58285821/149419086-76f63984-7b50-4611-a8aa-34b0454124a3.png)

used code editor:

![php](https://user-images.githubusercontent.com/58285821/149419416-18e4a5c3-47ca-4df1-9ec6-f33ac9ac5c35.png)


my package managers version
```
node version
v14.17.1
npm vesrion
6.14.13
yarn version
1.22.10
```

setup env:
```
windows10 pro core i7
```
also tried using:
```
macbook pro M1 Pro
macbook pro core i7
```
and the problem still the same


## Note
try to build the lib using vite version:
```
"vite": "2.4.3"
```
and you will see the dist build files are different (the built code is different)
