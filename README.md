# robototextviews
Text Views for controlling standard android fonts

Add to xml layout:

	<com.samueljbeck.robototextviews.RobotoTextView
        android:id="@+id/initial_text"
        style="@style/TextStyle"
        android:text="Text in textview" />
        
	<com.samueljbeck.robototextviews.RobotoEditText
            android:id="@+id/initial_edit_text"
            android:hint="Search information"
        	style="@style/TextStyle"
            android:textColorHint="@android:color/white" />


Add to styles:

	<style name="TextStyle" parent="AppTheme">
        <item name="android:textColor">@android:color/white</item>
        <item name="android:textSize">16sp</item>
        <item name="typeface">roboto_regular</item>
    </style>
    

Font styles:

	roboto_thin
	roboto_thin_italic
	roboto_light
	roboto_light_italic
	roboto_regular
	roboto_italic
	roboto_medium
	roboto_medium_italic
	roboto_bold
	roboto_bold_italic
	roboto_black
	roboto_black_italic
	roboto_condensed
	roboto_condensed_italic
	roboto_condensed_bold
	roboto_condensed_bold_italic
	

Also contains:  RobotoAutoCompleteTextView and RobotoEditTextBackSpaceDetection


