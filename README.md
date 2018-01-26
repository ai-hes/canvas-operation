Usage
------------
```
    <html>
    <body>
        <div> <!-- set desired position and size to that div -->
            <canvas id="mycanvas" style="width: 100%; height: 100%"></canvas>
        </div>

        <script src="img-touch-canvas.js"></script>
        <script>
              var gesturableImg = new ImgTouchCanvas({
                        canvas: canvas,
                        path: "trollface.png",
                        desktop: true,
                        // destination: "./",
                        // compositionType: 'source-over'
                        compositionType: 'destination-over'
                    });
        </script>
    </body>
    </html>

```