## 列の作成

ウェブサイトでは複数の列が使用されることがよくあります。雑誌の2段組を作成しましょう。

+ まず、2列の`div`を作成します。
    
    強調表示されたHTMLを`index.html`に追加：
    
    ![screenshot](images/magazine-columns.png)

+ 1つは左にフロートし、残りの1つは右にフロートするように列のdivを設定します。
    
    ![screenshot](images/magazine-columns-style.png)
    
    各列は50％未満ですので、パディングの余地があります。
    
    その効果を見るには、列に何かを追加する必要があります。

+ 列2の上部に子猫の画像を追加しましょう。
    
    ![screenshot](images/magazine-kitten.png)
    
    Notice that the kitten image is positioned about half-way across the page, in the second column.
    
    It's a bit big though!

+ Let's use `max-width:` to make images fit within their container.
    
    Add the following style to `style.css`.
    
    ![screenshot](images/magazine-img-width.png)
    
    This will apply to all images you use in your magazine, not just the kitten.

+ Now add a class `photo` to the image so that you can style it:
    
    ![screenshot](images/magazine-photo.png)

+ And style the image to add a shadow and a twist to make the photo pop out of the page:
    
    ![screenshot](images/magazine-photo-style.png)
    
    Make some changes until you like the result.