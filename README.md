# Content-Aware Image Resizing

This is a group project for my Data Structures and Algorithms class where we implement an algorithm for content-aware image resizing based on [this](https://perso.crans.org/frenoy/matlab2012/seamcarving.pdf).

## How to Run

1. [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) this repository into your working machine.
2. Make sure that you have [Python](https://www.python.org/downloads/) installed in your machine. It is recommended to use Python 3.
3. Run the command line. Change your working directory into the directory where you cloned this repository. Once there, enter the following command:

```console
$ py gui.py
```
4. A window will open. You can now resize your images!

## How to Use

1. Click `Open Image` to choose an image that you want to resize.
2. Choose the seam that you want to remove. `Vertical` seam is for reducing the width of the image. `Horizontal` seam is for reducing the height of the image.
3. Click `Show seam` to see the seam to be removed in pink.
4. Click `Remove seam` to remove the seam that was shown.
5. You can repeat the process of removing a seam as many times as you want. Just enter your desired value on `Repeat` and click `Remove Seam`.
6. Finally, you can save the resized image by clicking `Save image`.


Enjoy!

## Credits

Thanks to my groupmates [James](https://github.com/kintengg) and [Aster](https://github.com/astermangabat25) for making this with me!