# 使用
```html
<div class="main-con">
  <div class="main" id="svgMain">
    <svg>
      ....
    </svg>
  </div>
</div>
```
```css
.main-con {
  position: relative;
  width: 100%;
  height: 100%;
}

.main {
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  overflow: hidden;
}

.main svg {
  width: 100%;
  height: 100%;
}
```
```javascript
  import ZoomSvg from 'gy-zoom-svg'

  let svgMain = document.getElementById('svgMain');
  new ZoomSvg(svgMain.querySelector('svg'), svgMain)
```




