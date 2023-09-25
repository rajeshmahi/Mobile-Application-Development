# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
Program to print the text “Hello World”.

# Activity_main.xml:
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android" xmlns:app="http://schemas.android.com/apk/res-auto" xmlns:tools="http://schemas.android.com/tools" android:layout_width="match_parent" android:layout_height="match_parent" tools:context=".MainActivity">
```
<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:textSize="40dp"
    android:text="Hello World!"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent" />
 ```
    </androidx.constraintlayout.widget.ConstraintLayout>
   # MainActivity.java:
    package com.example.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle; import android.widget.Toast;

public class MainActivity extends AppCompatActivity {
```
@Override
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_main);
    Toast toast = Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onStart() {
    super.onStart();
    Toast toast = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
    toast.show();
}
@Override
protected void onRestart() {
    super.onRestart();
    Toast toast = Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onPause() {
    super.onPause();
    Toast toast = Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG);
    toast.show();![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/fcd214fc-b2e8-429d-83db-86b8f6d38913)
    
}
protected void onResume() {
    super.onResume();
    Toast toast = Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onStop() {
    super.onStop();
    Toast toast = Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onDestroy() {
    super.onDestroy();
    Toast toast = Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG);
    toast.show();
}
```
Developed by: Rajesh K
Registeration Number :212221220041
    
    

## OUTPUT
![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/7c5c74ac-8fe0-4d07-a327-8c9891e06129)
![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/2168693f-9faf-4b29-b74a-bd4296ef49d1)
![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/2c2659bf-89f9-48b3-9c22-0e85a16ea9fb)
![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/8868c073-c1ac-4923-8e85-a9ac90a80d95)
![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/28e45b84-06e5-41ea-95f9-4a613d314225)
![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/814582de-feae-428f-8b3a-75b0d17e1f96)
![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/ccf696cb-1e42-4050-8a1b-598771fed800)
![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/3cf6e40a-8bf4-4ae8-af71-719b0fa13058)
![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/a7a52e2d-4a5f-44b6-b2a0-8e12d52cde1c)
![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/fa98bec2-7c14-4855-be28-118ca186c0a9)
![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/937c232a-3b2a-4886-8667-9f05dac3f191)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/a8059867-8fed-49bb-b3ff-fd505d78cc69)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/46375b71-4ff4-4e75-91ba-b4fe45a65a1c)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/6e57d008-08e2-4127-827a-596d4f060e96)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/838936a2-38b1-4af8-96d6-557a2dc51787)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/87be7775-2bef-42a2-98d4-89c9ad186261)
# ![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/5ae484a0-5721-4067-9155-e197ca07ceac)



## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
