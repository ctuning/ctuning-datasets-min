Converted from ctuning-datasets-min:dataset.features:image-jpeg-dnn-cropped-panda as follows:
```
$ ck cp \
    ctuning-datasets-min:dataset.features:image-jpeg-dnn-cropped-panda \
    ctuning-datasets-min:dataset.features:image-ppm-dnn-cropped-panda
$ cd `ck find ctuning-datasets-min:dataset.features:image-ppm-dnn-cropped-panda`
$ convert cropped_panda.jpg -resize 227x227 cropped_panda.ppm
$ rm cropped_panda.jpg
```
