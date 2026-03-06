# gif

import imageio.v3 as iio

filenames = ['image-pic0.png', 'image-pic1.png']
images = []

for filename in filenames:
    images.append(iio.imread(filename))

iio.imwrite('pic-pic1.gif', images, duration=500, loop=0)
