# todolist
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="20dp"
    android:background="@color/light_gray"
    android:gravity="center">

    <!-- App Header -->
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="My To-Do List"
        android:textSize="30sp"
        android:textStyle="bold"
        android:textColor="@color/black"
        android:layout_gravity="center"
        android:paddingBottom="16dp" />


    <EditText
        android:id="@+id/taskInput"
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:hint="Enter a task"
        android:padding="10dp"
        android:background=""
        android:textSize="16sp"
        android:layout_marginBottom="10dp" />


    <Button
        android:id="@+id/addButton"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Add Task"
        android:textSize="16sp"
        android:backgroundTint="@color/blue"
        android:textColor="@color/white"
        android:layout_marginBottom="20dp"
        android:padding="10dp" />


    <ListView
        android:id="@+id/taskList"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="@color/white"
        android:divider="@android:color/darker_gray"
        android:dividerHeight="1dp"
        android:elevation="4dp"
        android:padding="5dp" />

</LinearLayout>


