### For google colab
This code creates an HTML canvas element and a submit button, along with JavaScript that allows a user to draw on the canvas using their mouse. When the submit button is clicked, the drawing is converted to a PNG image and the data URL of the image is returned. The data URL is then decoded and written to a file with the specified filename. The function also accepts parameters for the canvas dimensions and the width of the line to be drawn. This code will not work in Jupyter notebook as it's using Colab-specific functionality.

```
    !git clone https://github.com/MuhammadAshiqAmeer/draw_ui.git

    %run /content/8409b3feec20f159d8a50b0a811d3bca/draw.py

    draw(filename = "your_name_here.png", w=400, h=400, line_width=15)
```
