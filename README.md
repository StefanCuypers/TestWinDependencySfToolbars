# SfToolbars in .Net 9 self-contained

This is a .Net 9 WPF application with Syncfusion toolbars.
You can run it without a problem. It will show a blank Window.
However if you try to publish it Self-contained and then run the executable from the publish folder that does not work and you get no window.

Seems there is a dependency on Windows Forms. If you add &lt;UseWindowsForms&gt;true&lt;/UseWindowsForms&gt; to the project file and then publish again it does work.



