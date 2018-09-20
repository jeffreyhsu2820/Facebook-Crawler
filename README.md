請使用python jupyter notebook開啟(python 3.6)


套件
selenium, time, urllib, json, os, random, csv, codecs
請確認以上套件以下載

Drivers
Chrome   http://chromedriver.chromium.org/downloads
Firefox  https://github.com/mozilla/geckodriver/releases
Edge(程式中並無使用)     https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
下載以上三個DRIVER



1. final_version_crawler
主要負責查找所有目標在fb上同名用戶的所有公開資訊
EDGEDRIVER_PATH, FIREFOXDRIVER_PATH, CHROMEDRIVER_PATH 請等於上面所需下載的套件的位置
FIREFOX_PATH, CHROME_PATH 請等於內部瀏覽器所存放的位置

所需資料－
例如:
target=["吳俊霖","吳俊樺","黃秋敏","黃秋米","吳俊融"]

#想要用的瀏覽器及輪換的帳號(目前設定四組)
browser="Chrome"
email0="123456@gmail.com"
password0="123"
email1="123456@yahoo.com.tw"
password1="123"
email2="123456789@yahoo.com.tw"
password2="123"
email3="123@gmail.com"
password3="123"



2. final_version_identification
執行前，請確認第一支final_version_crawler已執行完畢，並且獲得大部分資訊
此支程式，為用來辨認一堆同名列表中誰是我想要的目標，並且找到與目標有關聯的列表
列表中也會包含辨認出的目標

所需資料－
例如:
target=["吳俊霖","吳俊樺","黃秋敏","黃秋米","吳俊融"]   (所要搜尋的目標)

#想要用的瀏覽器及輪換的帳號(目前設定4組--確認4組帳號均為fb的帳號密碼)
browser="Chrome"
email0="123456@gmail.com"
password0="123"
email1="123456@yahoo.com.tw"
password1="123"
email2="123456789@yahoo.com.tw"
password2="123"
email3="123@gmail.com"
password3="123"

匯入想要搜尋每位目標的資料--形式如下:
identifier(filename, ocr_addr, ocr_brdy_phone, work_comp_job_name, comn(target))
->identifier("吳俊樺", ["花蓮", "吉安"], ["1981年12月28日", "12月28日", "0932651189"], ["開車","開救護車"], comn(target))



若以上所需資訊有任何缺失及問題，請告知jeffrey2820@gmail.com，感謝
