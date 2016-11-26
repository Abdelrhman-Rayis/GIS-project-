#بسم الله الرحمن الرحيم
المراحل العامه لي مشروع
Gis
1-	يأتي ملف في صيغه GPX  أو يتم تحويلها الى صيغه Text  هذا الملف يحوي معلومات مثل X , Y  و إسم الشارع  ... و كل المعلموات التى تم جمعا من أجهزه GPS  .
2- بواسطه QGIS  أو Arcgis  نحول ملفات Text  الى Shape file .
3- بعد ذلك نقوم بإختيار import  لي  shape file  في File Geodatabase  ونقوم بتحويل Shape files  الى Future class  (لإن ليه إمكنايات أعلى في تعامل معه و لإن Geodatabase  لا تستقبل shape files  )
أو يمكننا أن نصنع sde  و هي عباره عن داتابيز مثل Geodatabase  لكن يستطيع أكثر من شخص أن يعدل فيها بواسطه server .
4- يمكن بواسطه postgres  عمل أو تعامل مع الداتابيز و ذلك إما عن طريق PostGis  أو sde  الخاص ب ArcMap
5-نقوم بعمل داتابيز بواسطه Postgresql  مثلا يشرح لاحقا مع الصور 
6- بعد عمل داتابز نقوم بعمل database connection  يشرح لاحقا مع الصور  
 




7-بواسطه برنامج GeoServer  بإستقبال Database  و نعدل فيها و نكون إستايل الذي نريده ثم بعد ذلك نستطيع إخراجه في شكل صفحه ويب حتى تتم مشاركته بواسطه web server  و يستطيع client  الإطلاع عليه و عرضه  .
 

ملاحظات :
*  File Geo database and Spatial data Engine or .gdb and .sde  are both database but in the first the database is localhost that mean only you the owner or the database can edit it but the second the database can be edit from any device in the server.


GIS-project-
my GIS doc and task 
