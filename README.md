### CUSTOM SIDEBAR



*Custom sidebar using the plugin [Simplebar](https://github.com/Grsmto/simplebar)*

---
![bandicam-2020-06-24-15-03-40-380](https://user-images.githubusercontent.com/16353858/85553067-49ba8c00-b62c-11ea-9d4c-5ac458334327.gif)

#### Installation <br>
npm `npm install simplebar --save` <br>
yarn `yarn add simplebar`

##### file path in the gulp <br>
`./node_modules/simplebar/dist/simplebar.js` <br>
`./node_modules/simplebar/dist/simplebar.css`

##### adding atribute `data-simplebar`<br>
```html
<ul data-simplebar>
  <li></li>
  ...
</ul>                   
```

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

