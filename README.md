# Grid-View-Using-Constraint-Layout

Grid view using constraint layout instead of legacy grid layout

```xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <Button
        android:id="@+id/button9"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:text="Button 1"
        app:layout_constraintBottom_toTopOf="@+id/button11"
        app:layout_constraintEnd_toStartOf="@+id/button10"
        app:layout_constraintHorizontal_bias="0.5"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button10"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:text="Button 2"
        app:layout_constraintBottom_toTopOf="@+id/button12"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.5"
        app:layout_constraintStart_toEndOf="@+id/button9"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button11"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:text="Button 3"
        app:layout_constraintBottom_toTopOf="@+id/button13"
        app:layout_constraintEnd_toStartOf="@+id/button12"
        app:layout_constraintHorizontal_bias="0.5"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/button9" />

    <Button
        android:id="@+id/button12"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:text="Button 4"
        app:layout_constraintBottom_toTopOf="@+id/button14"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.5"
        app:layout_constraintStart_toEndOf="@+id/button11"
        app:layout_constraintTop_toBottomOf="@+id/button10" />

    <Button
        android:id="@+id/button13"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:text="Button 5"
        app:layout_constraintBottom_toTopOf="@+id/button15"
        app:layout_constraintEnd_toStartOf="@+id/button14"
        app:layout_constraintHorizontal_bias="0.5"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/button11" />

    <Button
        android:id="@+id/button14"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:text="Button 6"
        app:layout_constraintBottom_toTopOf="@+id/button16"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.5"
        app:layout_constraintStart_toEndOf="@+id/button13"
        app:layout_constraintTop_toBottomOf="@+id/button12" />

    <Button
        android:id="@+id/button15"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:text="Button 7"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@+id/button16"
        app:layout_constraintHorizontal_bias="0.5"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/button13" />

    <Button
        android:id="@+id/button16"
        android:layout_width="0dp"
        android:layout_height="0dp"
        android:text="Button 8"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.5"
        app:layout_constraintStart_toEndOf="@+id/button15"
        app:layout_constraintTop_toBottomOf="@+id/button14" />
</androidx.constraintlayout.widget.ConstraintLayout>
```
