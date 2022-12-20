<div id="animation">
  <div class="frame">Frame 1</div>
  <div class="frame">Frame 2</div>
  <div class="frame">Frame 3</div>
</div>
```css
<style>
#animation {
  position: relative;
  width: 100%;
  height: 100%;
}

.frame {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
  transition: opacity 1s;
}

.frame.visible {
  opacity: 1;
}
</style>
```
<script>
const animation = document.getElementById('animation');
const frames = Array.from(animation.children);
let currentFrame = 0;

function showFrame() {
  frames.forEach(frame => frame.classList.remove('visible'));
  frames[currentFrame].classList.add('visible');
  currentFrame = (currentFrame + 1) % frames.length;
}

setInterval(showFrame, 1000);
</script>
