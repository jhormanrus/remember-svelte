<script>
  let m = { x: 0, y: 0 }

  function handleMouseMove(e) {
    m.x = e.clientX
    m.y = e.clientY
  }
</script>

<div on:mousemove={handleMouseMove}>
  the mouse position is x:{m.x} y:{m.y}
</div>