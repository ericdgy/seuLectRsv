# seuLectRsv
A script for SEU automatic lecture reservation.

Tips:
 - This script requires `requests`, `pycryptodome` and `ddddocr` to work properly. Use `pip install -r requirements.txt` for a quick start.
 - Edit **config.json** before running the script.
     - `onlineOnly` determines whether the script will ignore all offline lectures.
     - `district` filters the lecture list with certain campus area. The available choices are `四牌楼校区`, `九龙湖校区`, `丁家桥校区`, `苏州校区` and `无锡分校`.
     - `filter` is used to focus on certain lecture categories. The list's order will be taken into consideration when determining priorities. The available choices are `心理`, `法律`, `艺术`, `其他` and `非讲座`.
 - Check configExample.json for tutorial.