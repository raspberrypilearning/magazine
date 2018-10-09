## إنشاء الأعمدة

غالبًا ما تستخدم مواقع الويب أعمدة متعددة في تصميمها. لننشئ تخطيط بعمودين لمجلتك.

+ أولاً، أنشئ عمودين `div`.
    
    أضف تعليمات HTML المظللة إلى ملف `index.html`:
    
    ![screenshot](images/magazine-columns.png)

+ واﻵن صمم العمودين divs بحيث يظهر واحد على اليسار واﻵخر على اليمين.
    
    ![screenshot](images/magazine-columns-style.png)
    
    قيمة العرض لكل عمود أقل من 50%، لذا توجد مساحة لهامش الكتابة padding.
    
    ستحتاج إلى إضافة شيء ما إلى العمود لرؤية النتيجة.

+ لنضف صورة لقطة إلى أعلى العمود الثاني.
    
    ![screenshot](images/magazine-kitten.png)
    
    لاحظ أن موضع صورة القطة في العمود الثاني يأخذ نصف عرض الصفحة تقريبًا.
    
    عرض الصورة هذا كبير إلى حد ما!

+ Let's use `max-width:` to make images fit within their container.
    
    Add the following style to `style.css`.
    
    ![screenshot](images/magazine-img-width.png)
    
    This will apply to all images you use in your magazine, not just the kitten.

+ Now add a class `photo` to the image so that you can style it:
    
    ![screenshot](images/magazine-photo.png)

+ And style the image to add a shadow and a twist to make the photo pop out of the page:
    
    ![screenshot](images/magazine-photo-style.png)
    
    Make some changes until you like the result.