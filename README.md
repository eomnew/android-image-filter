android-image-filter
====================

some android image filter example

in some filter, I use NDK to implement it

# Setup

- Get a clean clone of this project, in import the library in Ecliplse, click Project->Clean, then click Project->Build Project
to regenerate the library
- Then just add AndroidImageFilter as a dependency to your existing project, following this guild:

# How to Use it

- It is dead simple, you can see magic in the following code:

```Java
  Bitmap newBitmap = BitmapFilter.changeStyle(originBitmap, BitmapFilter.BLUR_STYLE);
  imageView.setImageBitmap(newBitmap);
```

it is very simple, right? And you can see all filters in file /src/cn/Ragnarok/BitmapFilter.java, it contains totally
14 kinds of filters now!

- Also, you can download the demo app from this [link][1]

[1]: http://s.yunio.com/lYlEKr

