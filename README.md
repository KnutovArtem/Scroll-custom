### CUSTOM SIDEBAR



*Custom sidebar using the plugin [Simplebar](https://github.com/Grsmto/simplebar)*

---

![Simplebar](https://user-images.githubusercontent.com/16353858/85533930-9d6faa00-b619-11ea-919b-a54a5b137630.png)

#### Installation <br>
npm `npm install simplebar --save` <br>
yarn `yarn add simplebar`

##### file path in the gulp <br>
`./node_modules/simplebar/dist/simplebar.js` <br>
`./node_modules/simplebar/dist/simplebar.css`

##### style css <br>
```css
/*hover*/
.simplebar-visible:before{
  display: block !important;
  opacity: 5 !important;
}
/*style scroll*/
.simplebar-scrollbar:before {
  position: absolute;
  content: '';
  background: red;
  border-radius: 7px;
  left: 2px;
  right: 2px;
  opacity: 5;
  -webkit-transition: opacity .2s linear;
  -o-transition: opacity .2s linear;
  transition: opacity .2s linear;
}
```

