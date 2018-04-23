# How to implement custom binary storage configuration


<p>This example demonstrates how to implement different storage strategies for the DevExpress control's binary images.</p><p>The  <strong>FileCacheStrategy</strong> scenario implies the use of a specific folder on the server for storing the <strong>ASPxGauge's</strong>  binary images. Changing the control's value causes generating its new image, which is stored into a specified folder. Cache is cleared every 10 minutes. Each image can be obtained by using its recourse key. </p><p>The  <strong>StaticImageStrategy</strong> scenario implements storing the ASPxGridView binary data (a specific column with binary images) into a public folder within an application. Each image within the folder has its own static URL. In this scenario, cache is cleared every 60 minutes.</p><p><strong>See Also:</strong><br />
<a href="http://documentation.devexpress.com/#AspNet/CustomDocument6874">Binary Storage Configuration</a></p>

<br/>

