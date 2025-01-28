# Gradient image creation

When I was collecting gradient images, I realized that it was difficult to find images that I liked. So I wrote code that would draw a gradient for me every time I ran it. This process is based on a very simple algorithm. First, a single line is drawn randomly on the screen. This line is defined by a spline interpolation connecting several randomly placed points. According to this line, every position on the screen has information about the minimum distance from the line segment. This is used as the basis for determining the position between the two colors. Since the two colors of the gradient and this line are defined randomly, the gradient will be unpredictable each time it is output. There are several parameters that are strongly constrained to produce a pretty output image. Adjusting these constraints, you can create gradients to your liking.


![output1](https://github.com/user-attachments/assets/6864471c-a685-4ff9-985a-c786c8c599d4)
![output2](https://github.com/user-attachments/assets/88afd083-1e23-45fb-a147-e1a72a2d7738)
![output3](https://github.com/user-attachments/assets/1109cac1-6569-4dbf-9a00-6fd41f41a6fb)
![output4](https://github.com/user-attachments/assets/8404aac6-4809-444c-bb85-643b920efa2f)
