
Test
----

```php
<?php
var_dump(face_count('party.jpeg', 'data/haarcascades/haarcascade_frontalface_alt.xml'));
var_dump(face_detect('party.jpeg', 'data/haarcascades/haarcascade_frontalface_alt.xml'));
?>
```

You can test on the command line: 
LD_PRELOAD=../opencv/lib/libopencv_objdetect.so:./.libs/facedetect.so php5 -c opencv.ini test.php

See Also
--------

http://www.makebetterthings.com/php/face-detection-in-php-using-open-cv/
http://www.xarg.org/project/php-facedetect/
