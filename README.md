
# ImageToast

[![Release]( https://jitpack.io/v/doomers/imagetoast.svg?style=flat )]( https://jitpack.io/#doomers/imagetoast )


## Prerequisites

Add this in your root `build.gradle` file (**not** your module `build.gradle` file):

```gradle
allprojects {
	repositories {
		...
		maven { url "https://jitpack.io" }
	}
}
```

## Dependency

Add this to your module's `build.gradle` file (make sure the version matches the JitPack badge above):

```gradle
dependencies {
	...
	        compile 'com.github.doomers:imagetoast:2.1.1'
}
```

You have successfully integrated ImageToast in your android application

## How to display ImageToast

 prototypes of function makeText()
 
 ```
makeText(Context context,Bitmap bitmap,int duration);

```
          

```
makeText(Context context,Bitmap bitmap,int duration,int size);

```

bitmap - bitmap is the bitmap of the image you want to display.  
duration - Use ImageToast.LENGTH_LONG or ImageToast.LENGTH_SHORT.   
size - value should be between 5 - 100, it will alter the size of the image bitmap.  

## for quick usage consider this

### First create the bitmap of image resource you wan't to display

```
 Bitmap bitmap = BitmapFactory.decodeResource(getResources(),R.drawable.your_drawable_resource_name);
```

### Now to display the Toast


```
  ImageToast.getInstance().makeText(context,bitmap,ImageToast.LENGTH_LONG,50);
```


## Demos


<img src="https://github.com/doomers/ImageToast/blob/master/GIFs/goku.gif" width="350" height="600" /> <img src="https://github.com/doomers/ImageToast/blob/master/GIFs/heart.gif" width="350" height="600" /> <img src="https://github.com/doomers/ImageToast/blob/master/GIFs/mouse.gif" width="350" height="600" />






## Contributing

Please fork this repository and contribute back using
[pull requests](https://github.com/doomers/ImageToast/pulls).

Any contributions, large or small, major features, bug fixes, are welcomed and appreciated
but will be thoroughly reviewed.

### Contact - Let's become friend 
- [Twitter](https://twitter.com/rahul40800)
- [Github](https://github.com/doomers)
- [Linkedin](https://www.linkedin.com/in/rahul-tuteja-20353a114/)
- [Facebook](https://www.facebook.com/rahul.tuteja.984)




       



