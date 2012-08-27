enpsheet
========

========================================================
FONTS
========================================================

Font face generator:
 http://www.fontsquirrel.com/fontface/generator
 http://fontface.codeandmore.com/

Base64 encode:
 http://www.opinionatedgeek.com/dotnet/tools/base64encode/

CSS:
 do podmiany: nazwa_fonta, plik_font, [_kod_base64_]

@font-face {
    font-family: 'nazwa_fonta';
    src: url('fonts/plik_font.eot');
    src: url('fonts/plik_font.eot?#iefix') format('embedded-opentype');
	font-weight: normal; font-style: normal;
}

@font-face {
    font-family: 'nazwa_fonta';
	src: url('fonts/plik_font.woff') format('woff'),
         url(data:application/x-font-tff;charset=utf-8;base64,[_kod_base64_]) format('truetype'),
         url('fonts/plik_font.svg#nazwa_fonta') format('svg');
    font-weight: normal; font-style: normal;
}


========================================================
EMULATORS
========================================================
 Opera Mobile 	http://www.opera.com/developer/tools/mobile/
 Windows Phone 	http://www.microsoft.com/download/en/details.aspx?id=13890
 Android 		http://developer.android.com/guide/developing/tools/emulator.html



