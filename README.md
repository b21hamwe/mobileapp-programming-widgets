
# Rapport

**Skriv din rapport här!**


Jag har programmerat om i activity_main.xml filen som finns under layout mappen.
Här har jag lagt till tre widgets, Image view, textview och en button och designat layouten med
hjälp av en constraint layout samt margin attributet.
Detta kan ses i figur 1 nedanför

``` FIGUR 1
<Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/button"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="@id/textView2"
        android:layout_marginTop="2dp"
        android:layout_marginBottom="80dp"
        />
```

