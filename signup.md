<?xml version="1.0" encoding="utf-8"?>

<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#3996F8"
    android:orientation="vertical"
    android:padding="24dp"
    android:gravity="top|center_horizontal">

    <ImageView
        android:layout_width="228dp"
        android:layout_height="123dp"
        android:layout_marginTop="0dp"
        android:adjustViewBounds="true"
        android:contentDescription="Logo"
        android:src="@drawable/bittwatt_logo" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="⚡ Save Energy. Get Bittwatt ⚡"
        android:textColor="#FFFFFF"
        android:textSize="20sp"
        android:layout_marginBottom="30dp" />
    
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:layout_marginBottom="12dp"
        android:orientation="horizontal"
        android:background="@drawable/input_bg"
        android:gravity="center_vertical">

        <ImageView
            android:layout_width="24dp"
            android:layout_height="24dp"
            android:src="@drawable/account"
            android:layout_marginStart="12dp"
            android:layout_marginEnd="8dp" />

        <EditText
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:hint="Name"
            android:background="@android:color/transparent"
            android:padding="0dp" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:layout_marginBottom="12dp"
        android:orientation="horizontal"
        android:background="@drawable/input_bg"
        android:gravity="center_vertical">

        <ImageView
            android:layout_width="24dp"
            android:layout_height="24dp"
            android:src="@drawable/email_icon"
            android:layout_marginStart="12dp"
            android:layout_marginEnd="8dp" />

        <EditText
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:hint="Email"
            android:background="@android:color/transparent"
            android:padding="0dp" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:layout_marginBottom="12dp"
        android:orientation="horizontal"
        android:background="@drawable/input_bg"
        android:gravity="center_vertical">

        <ImageView
            android:layout_width="24dp"
            android:layout_height="24dp"
            android:src="@drawable/phone"
            android:layout_marginStart="12dp"
            android:layout_marginEnd="8dp" />

        <EditText
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:hint="Phone"
            android:background="@android:color/transparent"
            android:padding="0dp" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:layout_marginBottom="12dp"
        android:orientation="horizontal"
        android:background="@drawable/input_bg"
        android:gravity="center_vertical">

        <ImageView
            android:layout_width="24dp"
            android:layout_height="24dp"
            android:src="@drawable/client"
            android:layout_marginStart="12dp"
            android:layout_marginEnd="8dp" />

        <EditText
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:hint="Client Code"
            android:background="@android:color/transparent"
            android:padding="0dp" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:layout_marginBottom="24dp"
        android:orientation="horizontal"
        android:background="@drawable/input_bg"
        android:gravity="center_vertical">

        <ImageView
            android:layout_width="24dp"
            android:layout_height="24dp"
            android:src="@drawable/lock_icon"
            android:layout_marginStart="12dp"
            android:layout_marginEnd="8dp" />

        <EditText
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:hint="Password"
            android:inputType="textPassword"
            android:background="@android:color/transparent"
            android:padding="0dp" />
    </LinearLayout>

    <Button
        android:layout_width="200dp"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:background="@drawable/outline_button"
        android:hint="Sign Up"
        android:textAllCaps="false"
        android:textColor="#FFFFFF" />

</LinearLayout>