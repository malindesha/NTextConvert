NTextConvert by JMMS Karunarathne
https://www.codeproject.com/script/Articles/ArticleVersion.aspx?waid=4276739&aid=5364648

Every .net developer needs to restrict users to type only numeric data in TextBox at some point. 
for this developers should make their own class or 3rd party textbox components for their .net application. 
in my more than 15 years of developing carrier, I have developed many .NET applications. 
For many of these applications, I need some custom-made classes for certain functions. 
I have a collection of classes that I have developed in past years for doing some complex work in .net development. 
I am Thinking for share these Classes with the developing community to save developers time doing the same. 
this is my 1st class of many. see you soon.

Extract the RAR file using WinRAR and Add "NTextConvert.dll" to project reference and use like Following Code.

Usage:

 NTextConvert.NumericOnly.ApplyNumericInputRestriction(textBox1, true, 3, true, "0.000");
 NTextConvert.NumericOnly.ApplyNumericInputRestriction(textBox2, false, 2, false, "0.00");


<param name="textBox"></param> - witch text box need to apply restriction<br />
<param name="allowDecimal"></param> - textbox allow decimal numbers (true/false)<br />
<param name="decimalPlaces"></param> - how many decimal places for textbox<br />
<param name="Auto_Value_for_focus_out"></param> - is fill with auto value when focus out if textbox empty (true/false_<br />
<param name="autovalue_if_empy"></param> - auto fill value when focus out
