# fonts-optimize-for-arabic-and-farsi-text
this fonts optimize for show arabic and farsi font in textview android well.
All number in this fonts show farsi number or arabic.

this fonts show quran or doa or other arabic and farsi text very well in: 

android 4.0 ,
android 4.1,
android 4.2,
android 4.3,
android 4.4,
android 5,
android 5.1,
android 6

------------------------------------------------------------------
how to use:

first copy fonts to assets/fonts folder.

 TextView tvarabic = (TextView) findViewById(R.id.tvArabic);
 
 Typeface NameFont = Typeface.createFromAsset(this.getAssets(), "fonts/Al Qalam New.otf");
 
 tvarabic.setTypeface(NameFont);
 
 //for set linespacing:
 
 tvarabic.setLineSpacing(1.1f, 1.1f);
