# DesignOverlay

Run this from a Chrome Snippet:

```javascript
window.xxx = xxx = document.getElementById('xxx')
if (xxx) xxx.parentNode.removeChild(xxx)
xxx = document.createElement('img')

xxx.style.position = 'fixed'
xxx.style.zIndex = 10000
xxx.style.top = '-180px'
xxx.style.left = '0'
xxx.style.width = '375px'
xxx.src = 'http://localhost:3000/joker.jpg'
xxx.id = 'xxx'

document.querySelector('body').appendChild(xxx)
```