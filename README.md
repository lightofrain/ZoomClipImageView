# ZoomClipImageView
可缩放截图的ImageView(类似微信)
直接在布局中使用
 <com.suhang.zoomclipimageview.views.ZoomClipImageView
        android:id="@+id/ziv"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:src="@drawable/dog"
        android:scaleType="centerCrop"
       />
       
       通过getClipBitmap()方法获取截取的Bitmap
       
       通过setSize(int size);设置截选框大小
  
