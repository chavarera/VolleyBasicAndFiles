# VolleyBasicAndFiles
How to integrate volley into android studio

Step 1:
Open build.gradle and add volley support by adding'

compile 'com.mcxiaoke.volley:library-aar:1.0.0'

under dependencies section.

Step 2:
Now copy both file AppController and LruBitmapCache into java folder

Step 3:
now go to manifest file and add following line in <application> section
        android:name=".AppController"
