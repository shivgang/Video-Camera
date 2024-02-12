<?xml version="1.0" encoding="utf-8"?>

<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextureView
        android:id="@+id/textureView"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_alignParentStart="true"
        android:layout_alignParentTop="true"
        tools:layout_editor_absoluteX="-27dp"
        tools:layout_editor_absoluteY="157dp" />

    <Chronometer
        android:id="@+id/chronometer"
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:paddingTop="10dp"
        android:background="@color/black"
        android:textColor="@color/white"
        android:textAlignment="center"
        android:textSize="22dp" />

    <androidx.constraintlayout.widget.ConstraintLayout
        android:id="@+id/captureConstraintLayout"
        android:layout_width="match_parent"
        android:layout_height="200dp"
        android:background="#80555555"
        app:layout_constraintBottom_toBottomOf="parent"
        >

        <androidx.appcompat.widget.AppCompatButton
            android:id="@+id/videoOnlineImageButton"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:background="@drawable/circular_button"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent" />

        <androidx.appcompat.widget.AppCompatButton
            android:id="@+id/inner_button"
            android:layout_width="30dp"
            android:layout_height="30dp"
            android:background="@drawable/circular_button"
            android:backgroundTint="#F40000"
            app:layout_constraintBottom_toBottomOf="@id/videoOnlineImageButton"
            app:layout_constraintEnd_toEndOf="@id/videoOnlineImageButton"
            app:layout_constraintStart_toStartOf="@id/videoOnlineImageButton"
            app:layout_constraintTop_toTopOf="@id/videoOnlineImageButton"
            />

        <androidx.appcompat.widget.AppCompatButton
            android:id="@+id/slowMotionButton"
            android:layout_width="60dp"
            android:layout_height="60dp"
            android:background="@drawable/circular_button"
            android:backgroundTint="#716C6C"
            app:layout_constraintBottom_toBottomOf="@id/videoOnlineImageButton"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toEndOf="@id/videoOnlineImageButton"
            app:layout_constraintTop_toTopOf="@id/videoOnlineImageButton" />


    </androidx.constraintlayout.widget.ConstraintLayout>


    <TextView
        android:id="@+id/bottomTextView"
        android:layout_width="match_parent"
        android:layout_height="40dp"
        android:background="@color/black"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintVertical_bias="1.0" />


</androidx.constraintlayout.widget.ConstraintLayout>