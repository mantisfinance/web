<template>
  <div id="mantis-3d-wrapper" style="position: relative;">
    <div id="mantis-3d-lines"></div>
    <div id="mantis-3d" style="position: absolute; top: 0;"></div>
    <script type="application/javascript" src="/mantis-bundle.js"></script>
    <script type="application/javascript">
      window.addEventListener('load', () => {
        var mantis3d = createMantisViewer({
          width: 0.4,
          height: 0.4,
          followMouse: true,
          followMotion: true,
          fill: true,
          lines: false,
        });
        var mantis3dLines = createMantisViewer({
          width: 0.4,
          height: 0.4,
          followMouse: true,
          followMotion: true,
          fill: false,
          lines: true,
        });
        document.getElementById("mantis-3d").appendChild(mantis3d.container);
        document.getElementById("mantis-3d-lines").appendChild(mantis3dLines.container);
      });
    </script>
  </div>
</template>

<script>
export default {
  name: 'Mantis3d',
  setup() {
    return {
    };
  }
};
</script>
