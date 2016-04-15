# 第一次作業

## 從哪個API來的？
  >TwitterAPI

## 主題為何？
  > 動畫、跟Apple及Android有相關的資訊
  
## 下哪個查詢字串？
  > ***#animation***, ***#apple***, ***#android***

## 收集到的其中一筆資料
```json
{
    "contributors": "使用者物件的集合，代表幫助Tweet的人",
    "truncated": "tweet的內文是否有被裁減掉",
    "text": "文字內容",
    "is_quote_status": "是不是被引用的狀態",
    "in_reply_to_status_id": "若此篇Tweet是回覆別人的Tweet才會顯示被回覆的Tweet的ID",
    "id": "這篇Tweet的ID",
    "favorite_count": "這篇Tweet有多少個讚(like)",
    "entities": {
        "symbols": ["hashtag的功能，用$做表示"],
        "user_mentions": ["有無tag到其他Twitter使用者"],
        "hashtags": ["被解析出來的hashtag"],
        "urls": ["包含在這篇Tweet裡面的網址"]
    },
    "retweeted": "這篇Tweet是否有被其他Twitter使用者分享",
    "coordinates": "這篇Tweet的發文位置",
    "source": "這篇Tweet內提到的網址",
    "in_reply_to_screen_name": "可為空值，若這篇Tweet為回覆別人的Tweet，會顯示原Tweet名稱",
    "in_reply_to_user_id": "可為空值，若這篇Tweet為回覆別人的Tweet，會顯示原Tweet的使用者ID",
    "retweet_count": "這篇Tweet被分享的次數",
    "id_str": "這篇Tweet的ID",
    "favorited": "這篇Tweet是否有被其他已驗證的使用者按讚(like)",
    "user": {
        "follow_request_sent": "是否有已驗證的使用者要求追蹤這位受到保護的使用者帳戶",
        "has_extended_profile": "有沒有額外的profile內容",
        "profile_use_background_image": "使用者是否同意可以使用他們上傳的背景圖片",
        "default_profile_image": "使用者是否有上傳他們的照片",
        "id": "使用者的ID",
        "profile_background_image_url_https": "使用者背景圖片的連結",
        "verified": "使用者是否有通過Email驗證",
        "profile_text_color": "使用者使用的的字體顏色",
        "profile_image_url_https": "使用者大頭貼的連結",
        "profile_sidebar_fill_color": "使用者使用的側邊欄位的背景顏色",
        "entities": "Entity會提供metadata以及，額外有關於這篇Tweet的資訊",
        "followers_count": "追蹤這個使用者帳號的人數",
        "profile_sidebar_border_color": "使用者使用的側邊Bar的背景顏色",
        "id_str": "使用者ID",
        "profile_background_color": "使用者使用的側邊欄位的邊框顏色",
        "listed_count": "使用者所擁有的list數量",
        "is_translation_enabled": "使用者是不是允許翻譯",
        "utc_offset": "與GMT標準時間的時差",
        "statuses_count": "使用者發出的Tweet數量",
        "description": "使用者簡介",
        "friends_count": "使用者追蹤其他使用者的數量",
        "location": "使用者可自行定義的座標位置",
        "profile_link_color": "使用者使用的的連結顏色",
        "profile_image_url": "使用者照片的網址",
        "following": "使用者是否有被其他已驗證的使用者追蹤",
        "geo_enabled": "使用者是否同意將座標位置顯示於照片上",
        "profile_background_image_url": "使用者背景圖片的連結",
        "screen_name": "使用者自行定義的名稱",
        "lang": "使用者自行選擇顯示介面的語言",
        "profile_background_tile": "是否顯示使用者背景圖片的連結",
        "favourites_count": "使用者喜歡的Tweet數量",
        "name": "使用者顯示的名稱",
        "notifications": "當該使用者發布新Tweet時，是否同意收到SMS的更新通知",
        "url": "使用者所提供的連結",
        "created_at": "使用者註冊帳號的時間",
        "contributors_enabled": "使用者是否有連結貢獻者模式(contributor mode)",
        "time_zone": "使用者自行定義的座標位置",
        "protected": "使用者是否有選擇保護他們的Tweet",
        "default_profile": "使用者是否使用預設的圖片",
        "is_translator": "使用者是否有參與幫助翻譯Twitter的工作"
    },
    "geo": "比較少使用現在都使用coordinates欄位紀錄",
    "in_reply_to_user_id_str": "若這篇Tweet為回覆別人的Tweet，會顯示被回覆的Tweet的作者ID",
    "possibly_sensitive": "是否可能為敏感的文",
    "lang": "根據機器偵測自動判斷出該Tweet文章的語系",
    "created_at": "使用者發出Tweet的時間",
    "in_reply_to_status_id_str": "若這篇Tweet為回覆別人的Tweet，會顯示被回覆的Tweet的ID",
    "place": "該Tweet是否有與某個地方連結",
    "metadata": {
        "iso_language_code": "該網站使用的語系",
        "result_type": "Tweet的型態為何，是熱門Tweet還是近期所發出的Tweet"
    }
}
```