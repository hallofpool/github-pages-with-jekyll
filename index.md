<!DOCTYPE html>
<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Unity WebGL Player | RollaBall2</title>
  </head>
  <body style="text-align: center">
    <canvas id="unity-canvas" style="width: 960px; height: 600px; background: #231F20"></canvas>
    <script src="Build/WebGL.loader.js"></script>
    <script>
      createUnityInstance(document.querySelector("#unity-canvas"), {
        dataUrl: "Build/WebGL.data.gz",
        frameworkUrl: "Build/WebGL.framework.js.gz",
        codeUrl: "Build/WebGL.wasm.gz",
        streamingAssetsUrl: "StreamingAssets",
        companyName: "HallofPool",
        productName: "RollaBall2",
        productVersion: "0.1",
      });
    </script>
  </body>
</html>
