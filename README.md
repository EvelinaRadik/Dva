xml
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerInParent="true"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="horizontal">

            <Button
android:id="@+id/button_00"
                android:layout_width="100dp"
                android:layout_height="100dp"
                android:layout_margin="5dp"
                android:textSize="25sp" />

            <Button
                android:id="@+id/button_01"
                android:layout_width="100dp"
                android:layout_height="100dp"
                android:layout_margin="5dp"
                android:textSize="25sp" />

            <Button
                android:id="@+id/button_02"
                android:layout_width="100dp"
                android:layout_height="100dp"
                android:layout_margin="5dp"
                android:textSize="25sp" />

        </LinearLayout>

        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button_10"
                android:layout_width="100dp"
                android:layout_height="100dp"
                android:layout_margin="5dp"
                android:textSize="25sp" />

            <Button
                android:id="@+id/button_11"
                android:layout_width="100dp"
                android:layout_height="100dp"
                android:layout_margin="5dp"
                android:textSize="25sp" />

            <Button
                android:id="@+id/button_12"
                android:layout_width="100dp"
                android:layout_height="100dp"
                android:layout_margin="5dp"
                android:textSize="25sp" />

        </LinearLayout>

        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button_20"
                android:layout_width="100dp"
                android:layout_height="100dp"
                android:layout_margin="5dp"
                android:textSize="25sp" />

            <Button
                android:id="@+id/button_21"
                android:layout_width="100dp"
                android:layout_height="100dp"
                android:layout_margin="5dp"
                android:textSize="25sp" />

            <Button
                android:id="@+id/button_22"
                android:layout_width="100dp"
                android:layout_height="100dp"
                android:layout_margin="5dp"
                android:textSize="25sp" />

        </LinearLayout>

    </LinearLayout>

    <Button
        android:id="@+id/button_reset"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/button_22"
        android:layout_centerHorizontal="true"
        android:marginTop="20dp"
        android:text="Reset" />

</RelativeLayout>
