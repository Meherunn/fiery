<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:orientation="horizontal"
    android:weightSum="2">

    <LinearLayout
        android:layout_width="0dp"
        android:layout_height="match_parent"
        android:layout_weight="0.8"
        android:orientation="vertical"
        android:weightSum="4"
        >

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="3">

            <Button
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:text="A"
                android:layout_margin="10dp"
                android:background="#9DE6F0"/>
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="1">


        </LinearLayout>

    </LinearLayout>

    <LinearLayout
        android:layout_width="0dp"
        android:layout_height="match_parent"
        android:layout_weight="1.2"
        android:orientation="vertical"
        android:weightSum="4"
        >

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="1"

            >
            <Button
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="A"
                android:layout_margin="10dp"
                android:background="#9DE6F0"/>
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="1"
            android:orientation="horizontal"
            android:weightSum="3"

            >
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="A"
                android:layout_margin="10dp"
                android:background="#9DE6F0"/>

            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="A"
                android:layout_margin="10dp"
                android:background="#9DE6F0"/>

            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="A"
                android:layout_margin="10dp"
                android:background="#9DE6F0"/>

        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="1"
            android:orientation="horizontal"
            android:weightSum="2"
            >
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1.4"
                android:text="A"
                android:layout_margin="10dp"
                android:background="#9DE6F0"/>

            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="0.6"
                android:text="A"
                android:layout_margin="10dp"
                android:background="#9DE6F0"/>
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="1"
            android:weightSum="4"
            >
            <Button
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="A"
                android:layout_margin="10dp"
                android:background="#9DE6F0"/>
        </LinearLayout>
    </LinearLayout>



</LinearLayout>
