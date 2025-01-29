# Gradient image creation

One day, when I was collecting gradient images, I realized it was difficult to find ones that matched my aesthetic preferences. So, I wrote a program that generates a unique gradient image each time I run it. The process is based on a simple algorithm: it starts by randomly defining several points on the screen, and then a line is drawn using spline interpolation to connect these points. Each position on the screen is then assigned a value based on its minimum distance from this line. This value serves as the basis for determining the gradient's transition between two colors. The unpredictability of the output lies in the fact that both the colors of the gradient and the line are defined randomly. There are several parameters constrained to ensure the output image looks aesthetically pleasing. By adjusting these constraints, you can create gradients that align with your preferences.


![output1](https://github.com/user-attachments/assets/6864471c-a685-4ff9-985a-c786c8c599d4)
![output2](https://github.com/user-attachments/assets/88afd083-1e23-45fb-a147-e1a72a2d7738)
![output3](https://github.com/user-attachments/assets/1109cac1-6569-4dbf-9a00-6fd41f41a6fb)
![output4](https://github.com/user-attachments/assets/8404aac6-4809-444c-bb85-643b920efa2f)
