<?xml version="1.0" encoding="utf-8"?>

<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#3996F8">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:gravity="center_horizontal"
        android:padding="32dp">

        <ImageView
            android:layout_width="228dp"
            android:layout_height="123dp"
            android:layout_marginTop="10dp"
            android:adjustViewBounds="true"
            android:contentDescription="Logo"
            android:src="@drawable/bittwatt_logo" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="50dp"
            android:text="⚡ Save Energy. Get Bittwatt ⚡"
            android:textColor="#FFFFFF"
            android:textSize="20sp" />

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:orientation="horizontal"
            android:background="@drawable/input_bg"
            android:layout_marginTop="32dp"
            android:paddingHorizontal="16dp"
            android:gravity="center_vertical">

            <ImageView
                android:layout_width="20dp"
                android:layout_height="20dp"
                android:src="@drawable/email_icon"
                android:layout_marginEnd="8dp" />

            <EditText
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:hint="Email"
                android:background="@android:color/transparent"
                android:textSize="16sp" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:orientation="horizontal"
            android:background="@drawable/input_bg"
            android:layout_marginTop="16dp"
            android:paddingHorizontal="16dp"
            android:gravity="center_vertical">

            <ImageView
                android:layout_width="20dp"
                android:layout_height="20dp"
                android:src="@drawable/lock_icon"
                android:layout_marginEnd="8dp" />

            <EditText
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:hint="Password"
                android:inputType="textPassword"
                android:background="@android:color/transparent"
                android:textSize="16sp" />
        </LinearLayout>

        <Button
            android:layout_width="219dp"
            android:layout_height="wrap_content"
            android:layout_marginTop="24dp"
            android:background="@drawable/outline_button"
            android:backgroundTint="#FFFFFF"
            android:text="Login"
            android:textAllCaps="false"
            android:textColor="#2196F3" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Forgot Password?"
            android:textColor="#FFFFFF"
            android:layout_marginTop="16dp" />

        <Button
            android:layout_width="158dp"
            android:layout_height="wrap_content"
            android:layout_marginTop="110dp"
            android:background="@drawable/outline_button"
            android:hint="Sign Up"
            android:textAllCaps="false"
            android:textColor="#FFFFFF" />
    </LinearLayout>

</ScrollView>