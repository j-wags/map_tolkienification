# map_tolkienification

It's not clear to me that a CNN/GAN framework is the right tool for this job. 

Update 2018_05_04: I've made it so generator only gets the land mask as input, but discriminator gets both the prediction and the land mask. This way, the discriminator can see where the land/water *should* be when picking the real map. The result is that discriminator is now pretty much perfect, so I need to figure out how to beef up the generator.

Middle earth map from https://www.wallpapervortex.com/wallpaper-51689_the_lord_of_the_rings_map_map_of_middle_earth.html

GAN adapted from https://github.com/yashk2810/DCGAN-Keras
