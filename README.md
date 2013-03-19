CircularImageView
=================

This is an extended version of the Android ImageView that creates an ImageView in a circular shape with a border.

Example of Use 
==============

Simply add the class to your existing project. There are no images or other files required.

Next add the following to your layout file xml (please note you may need to change the package names to match your setup.

  <com.wisemandesigns.android.widgets.CircularImageView
    android:id="@+id/circular_image_view"
    android:layout_width="@dimen/circular_imageview_width"
    android:layout_height="@dimen/circular_imageview_height"
    android:src="@drawable/example"/>
    
By default the border width is 5dp and the colour is blue (because we said so).
