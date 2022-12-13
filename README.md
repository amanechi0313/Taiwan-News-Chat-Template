# 目前只支援 **Twitch聊天室** ！ 

使用範例：https://gyazo.com/d5abb40cbf2823d93e98fc389671e71b

# 使用說明

請參照以下的文字說明，**一步一步來**！

1. 至以下位址把html檔中的`ComfyJS.Init("amane_tainan");` 中的"amane_tainan"改成 **你的圖奇ID**

    (如果你沒有IDE，可以按右鍵->開啟檔案->記事本編輯)
    >   subtitle/subtitle.html \



2. 至`src`裡取用圖片素材，先組裝到OBS中
3. 新增電子鐘：於OBS中新增`瀏覽器`，選擇「本地檔案」->`digital_clock.html`
4. 新增大標題： \
    (1) 新增一個txt檔(或者可以在\src底下修改我的範例) \
    (2) 逐行輸入想要的標題，並在最尾端留下一行空白 \
    (3) 用瀏覽器打開`ReadFile.html`檔案，選擇`選擇檔案`，選取剛剛製作的txt檔 \
    (4) 到OBS中選擇「視窗拓取」，並加上「濾鏡」->「色度鍵」，參考以下設定：
    > 相似性271 \
    > 平滑度75 \
    > 鍵色溢出減少948 \
    > 不透明度10000 \
    > 對比4.00 \
    > 亮度-0.1447 \
    > 伽瑪0.0
5. 新增小標題： 小標題用「瀏覽器」或「視窗拓取」都可以，如果要用視窗拓取，可以參考我的色度鍵設定：
    > 相似性400 \
    > 平滑度80 \
    > 鍵色溢出減少333 \
    > 不透明度10000 \
    > 對比0.00 \
    > 亮度0.0000 \
    > 伽瑪0.0



# 注意事項

1. title(新聞標題)字數上限19個字
2. 下方聊天室觀眾名字上限5個中文字，英文ID如果太長可能爆開
3. 聊天室如果刷太快，會漏訊息！

# 使用規範

1. 本模板含有一些素材，已附上來源網址。
2. 使用時如果可以介紹一下我並附網址，我會很感謝你(非強制)
3. 如果用來做影片，我想了一個tag，打上它，讓大家知道你使用了這個素材！

> #我是亂源主播


## Contact Me

如果有任何問題，可以到推特(https://twitter.com/Amane_Tainan)或DC(周汰南#4183)找我。
程式新手，請不吝指教。


###### Reference

- Background Picture
https://ja.pngtree.com/freebackground/television-news-background_1594889.html



###### 特別感謝

雲在山之下(nextnew)提供指導！
