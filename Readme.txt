�Шϥ�python jupyter notebook�}��(python 3.6)


�M��
selenium, time, urllib, json, os, random, csv, codecs
�нT�{�H�W�M��H�U��

Drivers
Chrome   http://chromedriver.chromium.org/downloads
Firefox  https://github.com/mozilla/geckodriver/releases
Edge(�{�����õL�ϥ�)     https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
�U���H�W�T��DRIVER



1. final_version_crawler
�D�n�t�d�d��Ҧ��ؼЦbfb�W�P�W�Τ᪺�Ҧ����}��T
EDGEDRIVER_PATH, FIREFOXDRIVER_PATH, CHROMEDRIVER_PATH �е���W���һݤU�����M�󪺦�m
FIREFOX_PATH, CHROME_PATH �е��󤺳��s�����Ҧs�񪺦�m

�һݸ�ơ�
�Ҧp:
target=["�d�T�M","�d�T��","�����","�����","�d�T��"]

#�Q�n�Ϊ��s�����ν������b��(�ثe�]�w�|��)
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
����e�A�нT�{�Ĥ@��final_version_crawler�w���槹���A�åB��o�j������T
����{���A���Ψӿ�{�@��P�W�C���֬O�ڷQ�n���ؼСA�åB���P�ؼЦ����p���C��
�C���]�|�]�t��{�X���ؼ�

�һݸ�ơ�
�Ҧp:
target=["�d�T�M","�d�T��","�����","�����","�d�T��"]   (�ҭn�j�M���ؼ�)

#�Q�n�Ϊ��s�����ν������b��(�ثe�]�w4��--�T�{4�ձb������fb���b���K�X)
browser="Chrome"
email0="123456@gmail.com"
password0="123"
email1="123456@yahoo.com.tw"
password1="123"
email2="123456789@yahoo.com.tw"
password2="123"
email3="123@gmail.com"
password3="123"

�פJ�Q�n�j�M�C��ؼЪ����--�Φ��p�U:
identifier(filename, ocr_addr, ocr_brdy_phone, work_comp_job_name, comn(target))
->identifier("�d�T��", ["�Ὤ", "�N�w"], ["1981�~12��28��", "12��28��", "0932651189"], ["�}��","�}���@��"], comn(target))



�Y�H�W�һݸ�T������ʥ��ΰ��D�A�Чi��jeffrey2820@gmail.com�A�P��
