# Basic-AndroidStudio
```
Developed: P Deepika
Registered Number: 212221240035
```
### MainActivity.java:
```
package com.example.lifecycle;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);




        Toast toast = Toast.makeText(getApplicationContext(), "OnCreate Executed", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStart(){
        super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStart Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onResume(){
        super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),"OnResume Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onPause(){
        super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"OnPause Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStop(){
        super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStop Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onRestart(){
        super.onRestart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onDestroy(){
        super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Executed",Toast.LENGTH_LONG);
        toast.show();
    }
}
```
### activity_main.xml:
```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="HelloWorld!"
        android:layout_centerVertical="true"
        android:layout_centerHorizontal="true"
        android:textSize="20sp"
        android:textColor="@color/black"

        />
</RelativeLayout>
```

### Output:
![exp1](https://user-images.githubusercontent.com/94154679/198346555-372fa088-6bf9-4adc-9f8a-1a3b445f3e77.jpg)
![exp2](https://user-images.githubusercontent.com/94154679/198346576-7f623bdf-f9ba-4c3f-bc15-8d3fed2000ca.jpg)
![exp3](https://user-images.githubusercontent.com/94154679/198346584-3cafc8c3-cac1-41e3-b8af-b1e725412fbc.jpg)
![exp4](https://user-images.githubusercontent.com/94154679/198346589-d499573d-5940-4260-8eb6-bfcec5a8f519.jpg)
![exp5](https://user-images.githubusercontent.com/94154679/198346602-4cdf2b63-27f2-4a18-8152-5053ae62b88b.jpg)
![exp6](https://user-images.githubusercontent.com/94154679/198346607-8fc098b3-3d1c-4652-b7ef-8edb003f2025.jpg)

### Result:
Therefore a program is return to develop a program to detect the various life cycles of an activity. The program is successfully executed.
