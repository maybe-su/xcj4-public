# 外部資料索引（新·成吉思汗4 公開資料）

> 給 claude.ai 一般聊天視窗用：使用者要查**人物**或**地圖**資料時，照下表用網頁讀取打開對應網址再回答，不要憑記憶。
> 能力值判斷一律看潛力欄（統潛、武潛、智潛、政潛、文潛，D640）。

## 人物（1189 劇本人物總表 v3，依國家拆檔）
查人時：先開「姓名索引」找到該人所在檔案，再開那個檔案。知道國家就直接開該國檔。

| 檔案 | 內容 | 網址 |
|---|---|---|
| 人物_依血緣.csv | 國家欄＝依血緣 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E4%BE%9D%E8%A1%80%E7%B7%A3.csv |
| 人物_克烈.csv | 國家欄＝克烈 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E5%85%8B%E7%83%88.csv |
| 人物_在野.csv | 國家欄＝在野 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E5%9C%A8%E9%87%8E.csv |
| 人物_塔塔兒.csv | 國家欄＝塔塔兒 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E5%A1%94%E5%A1%94%E5%85%92.csv |
| 人物_宋.csv | 國家欄＝宋 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E5%AE%8B.csv |
| 人物_日本擴張版.csv | 日本擴張版名冊 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E6%97%A5%E6%9C%AC%E6%93%B4%E5%BC%B5%E7%89%88.csv |
| 人物_札答剌.csv | 國家欄＝札答剌 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E6%9C%AD%E7%AD%94%E5%89%8C.csv |
| 人物_汪古.csv | 國家欄＝汪古 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E6%B1%AA%E5%8F%A4.csv |
| 人物_蔑兒乞.csv | 國家欄＝蔑兒乞 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E8%94%91%E5%85%92%E4%B9%9E.csv |
| 人物_西夏.csv | 國家欄＝西夏 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E8%A5%BF%E5%A4%8F.csv |
| 人物_金.csv | 國家欄＝金 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E9%87%91.csv |
| 人物_鐵木真.csv | 國家欄＝鐵木真 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E9%90%B5%E6%9C%A8%E7%9C%9F.csv |
| 人物_高麗擴張版.csv | 高麗擴張版名冊 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E4%BA%BA%E7%89%A9_%E9%AB%98%E9%BA%97%E6%93%B4%E5%BC%B5%E7%89%88.csv |
| 姓名索引.csv | 依姓名查所在檔案 | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/people/%E5%A7%93%E5%90%8D%E7%B4%A2%E5%BC%95.csv |

## 地圖（測試版東亞九國 v1.8、日本、高麗）

- **正式測試版地圖＝`測試版_東亞九國_v1.8.csv`**（2026-10-27 下午起唯一正式版；v1.7＋東北外緣（黑龍江下游、濱海，K3c）＋西域外緣（沙州以西：高昌、北庭、伊州、羅布泊，D962）；矩形欄 147–231、列 30–134；格號＝世界母圖全域格號 (世界欄, 世界列)）。
- 外緣格是荒野、外族地（高昌回鶻，不是可玩國），人口見 `格人口_東北外緣_v1.8.csv`、`格人口_西域外緣_v1.8.csv`（未編戶，推估 ⚠）；已併入 `格人口_測試版.csv`。
- 近海海格的「水深」自 v1.8 起用近岸帶判定（離岸 ≤ 20 公里的海點水深中位數，ETOPO5；D966）；船級：輕舟、江船只走近海淺海，海船以上照水深。
- `測試版_東亞九國_v1.7.csv` 是 v1.8 的底圖（日本、高麗在這裡改，再由併圖程式產生 v1.8）；其餘 `測試版_東亞六國／七國／八國_*.csv`、`v1.7輪廓*` 是舊版或草案，只供對照；舊測試版格號 (col,row) ＝ 全域格號 −(153, 48)，對照表 `world/格號對照_測試版v1.6_母圖.csv`。
- `格人口_測試版.csv` 是全域格號（世界欄,世界列），含日本、高麗、東北外緣、西域外緣；`格人口_日本_v1.7.csv` 等是各區原始檔（同為全域格號）。

| 檔案 | 網址 |
|---|---|
| 擴張版_日本放大區_v1地形草案.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%93%B4%E5%BC%B5%E7%89%88_%E6%97%A5%E6%9C%AC%E6%94%BE%E5%A4%A7%E5%8D%80_v1%E5%9C%B0%E5%BD%A2%E8%8D%89%E6%A1%88.csv |
| 普查_物產格總表_2026-10-24.md | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%99%AE%E6%9F%A5_%E7%89%A9%E7%94%A2%E6%A0%BC%E7%B8%BD%E8%A1%A8_2026-10-24.md |
| 格人口_日本_v1.7.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%A0%BC%E4%BA%BA%E5%8F%A3_%E6%97%A5%E6%9C%AC_v1.7.csv |
| 格人口_東北外緣_v1.8.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%A0%BC%E4%BA%BA%E5%8F%A3_%E6%9D%B1%E5%8C%97%E5%A4%96%E7%B7%A3_v1.8.csv |
| 格人口_測試版.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%A0%BC%E4%BA%BA%E5%8F%A3_%E6%B8%AC%E8%A9%A6%E7%89%88.csv |
| 格人口_西域外緣_v1.8.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%A0%BC%E4%BA%BA%E5%8F%A3_%E8%A5%BF%E5%9F%9F%E5%A4%96%E7%B7%A3_v1.8.csv |
| 格人口_高麗_v1.7.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%A0%BC%E4%BA%BA%E5%8F%A3_%E9%AB%98%E9%BA%97_v1.7.csv |
| 河流屬性表.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%B2%B3%E6%B5%81%E5%B1%AC%E6%80%A7%E8%A1%A8.csv |
| 測試版_東亞七國_草案.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%B8%AC%E8%A9%A6%E7%89%88_%E6%9D%B1%E4%BA%9E%E4%B8%83%E5%9C%8B_%E8%8D%89%E6%A1%88.csv |
| 測試版_東亞九國_v1.7.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%B8%AC%E8%A9%A6%E7%89%88_%E6%9D%B1%E4%BA%9E%E4%B9%9D%E5%9C%8B_v1.7.csv |
| 測試版_東亞九國_v1.7輪廓草案.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%B8%AC%E8%A9%A6%E7%89%88_%E6%9D%B1%E4%BA%9E%E4%B9%9D%E5%9C%8B_v1.7%E8%BC%AA%E5%BB%93%E8%8D%89%E6%A1%88.csv |
| 測試版_東亞九國_v1.8.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%B8%AC%E8%A9%A6%E7%89%88_%E6%9D%B1%E4%BA%9E%E4%B9%9D%E5%9C%8B_v1.8.csv |
| 測試版_東亞八國_v1.4河流草案.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%B8%AC%E8%A9%A6%E7%89%88_%E6%9D%B1%E4%BA%9E%E5%85%AB%E5%9C%8B_v1.4%E6%B2%B3%E6%B5%81%E8%8D%89%E6%A1%88.csv |
| 測試版_東亞八國_v1.5地形草案.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%B8%AC%E8%A9%A6%E7%89%88_%E6%9D%B1%E4%BA%9E%E5%85%AB%E5%9C%8B_v1.5%E5%9C%B0%E5%BD%A2%E8%8D%89%E6%A1%88.csv |
| 測試版_東亞八國_v1.6關口草案.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%B8%AC%E8%A9%A6%E7%89%88_%E6%9D%B1%E4%BA%9E%E5%85%AB%E5%9C%8B_v1.6%E9%97%9C%E5%8F%A3%E8%8D%89%E6%A1%88.csv |
| 測試版_東亞八國_草案.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%B8%AC%E8%A9%A6%E7%89%88_%E6%9D%B1%E4%BA%9E%E5%85%AB%E5%9C%8B_%E8%8D%89%E6%A1%88.csv |
| 測試版_東亞六國.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E6%B8%AC%E8%A9%A6%E7%89%88_%E6%9D%B1%E4%BA%9E%E5%85%AD%E5%9C%8B.csv |
| 總表_關口_2026-10-24.md | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/%E7%B8%BD%E8%A1%A8_%E9%97%9C%E5%8F%A3_2026-10-24.md |
| cities/城市_v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/cities/%E5%9F%8E%E5%B8%82_v1.7.json |
| cities/城市_v2.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/cities/%E5%9F%8E%E5%B8%82_v2.json |
| expand/坡度校準_ETOPO20_東北.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E5%9D%A1%E5%BA%A6%E6%A0%A1%E6%BA%96_ETOPO20_%E6%9D%B1%E5%8C%97.json |
| expand/坡度校準_ETOPO5_東北.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E5%9D%A1%E5%BA%A6%E6%A0%A1%E6%BA%96_ETOPO5_%E6%9D%B1%E5%8C%97.json |
| expand/坡度校準_ETOPO5_西域.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E5%9D%A1%E5%BA%A6%E6%A0%A1%E6%BA%96_ETOPO5_%E8%A5%BF%E5%9F%9F.json |
| expand/東北外緣_v1.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E6%9D%B1%E5%8C%97%E5%A4%96%E7%B7%A3_v1.csv |
| expand/東北外緣_v1_取樣.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E6%9D%B1%E5%8C%97%E5%A4%96%E7%B7%A3_v1_%E5%8F%96%E6%A8%A3.npz |
| expand/東北外緣_v1_紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E6%9D%B1%E5%8C%97%E5%A4%96%E7%B7%A3_v1_%E7%B4%80%E9%8C%84.json |
| expand/東北外緣_v1_說明.md | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E6%9D%B1%E5%8C%97%E5%A4%96%E7%B7%A3_v1_%E8%AA%AA%E6%98%8E.md |
| expand/範圍_東北外緣_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E7%AF%84%E5%9C%8D_%E6%9D%B1%E5%8C%97%E5%A4%96%E7%B7%A3_v1.json |
| expand/範圍_西域外緣_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E7%AF%84%E5%9C%8D_%E8%A5%BF%E5%9F%9F%E5%A4%96%E7%B7%A3_v1.json |
| expand/西域外緣_v1.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E8%A5%BF%E5%9F%9F%E5%A4%96%E7%B7%A3_v1.csv |
| expand/西域外緣_v1_紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E8%A5%BF%E5%9F%9F%E5%A4%96%E7%B7%A3_v1_%E7%B4%80%E9%8C%84.json |
| expand/西域外緣_v1_說明.md | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E8%A5%BF%E5%9F%9F%E5%A4%96%E7%B7%A3_v1_%E8%AA%AA%E6%98%8E.md |
| expand/西緣沙州_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/expand/%E8%A5%BF%E7%B7%A3%E6%B2%99%E5%B7%9E_v1.json |
| goryeo/山城_高麗_v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/goryeo/%E5%B1%B1%E5%9F%8E_%E9%AB%98%E9%BA%97_v1.7.json |
| goryeo/建城候選_高麗_v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/goryeo/%E5%BB%BA%E5%9F%8E%E5%80%99%E9%81%B8_%E9%AB%98%E9%BA%97_v1.7.json |
| goryeo/港口_高麗_v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/goryeo/%E6%B8%AF%E5%8F%A3_%E9%AB%98%E9%BA%97_v1.7.json |
| goryeo/航路與險地_高麗_v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/goryeo/%E8%88%AA%E8%B7%AF%E8%88%87%E9%9A%AA%E5%9C%B0_%E9%AB%98%E9%BA%97_v1.7.json |
| goryeo/道路_高麗_v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/goryeo/%E9%81%93%E8%B7%AF_%E9%AB%98%E9%BA%97_v1.7.json |
| guan/封路_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/guan/%E5%B0%81%E8%B7%AF_v1.json |
| guan/無主城堡_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/guan/%E7%84%A1%E4%B8%BB%E5%9F%8E%E5%A0%A1_v1.json |
| guan/西夏城堡_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/guan/%E8%A5%BF%E5%A4%8F%E5%9F%8E%E5%A0%A1_v1.json |
| guan/關口_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/guan/%E9%97%9C%E5%8F%A3_v1.json |
| guan/關口_日本_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/guan/%E9%97%9C%E5%8F%A3_%E6%97%A5%E6%9C%AC_v1.json |
| japan/v2_輪廓_格寬20.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/v2_%E8%BC%AA%E5%BB%93_%E6%A0%BC%E5%AF%AC20.npz |
| japan/v2_輪廓_格寬25.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/v2_%E8%BC%AA%E5%BB%93_%E6%A0%BC%E5%AF%AC25.npz |
| japan/v2_輪廓_格寬30.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/v2_%E8%BC%AA%E5%BB%93_%E6%A0%BC%E5%AF%AC30.npz |
| japan/v2_輪廓_比較.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/v2_%E8%BC%AA%E5%BB%93_%E6%AF%94%E8%BC%83.json |
| japan/商路提案_日本_v1.7.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/%E5%95%86%E8%B7%AF%E6%8F%90%E6%A1%88_%E6%97%A5%E6%9C%AC_v1.7.csv |
| japan/坡度校準_ETOPO5.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/%E5%9D%A1%E5%BA%A6%E6%A0%A1%E6%BA%96_ETOPO5.json |
| japan/河道_日本放大區_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/%E6%B2%B3%E9%81%93_%E6%97%A5%E6%9C%AC%E6%94%BE%E5%A4%A7%E5%8D%80_v1.json |
| japan/港口_日本_v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/%E6%B8%AF%E5%8F%A3_%E6%97%A5%E6%9C%AC_v1.7.json |
| japan/覆蓋_查無.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/%E8%A6%86%E8%93%8B_%E6%9F%A5%E7%84%A1.json |
| japan/覆蓋_查無_v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/%E8%A6%86%E8%93%8B_%E6%9F%A5%E7%84%A1_v1.7.json |
| japan/輪廓_v1.4.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/%E8%BC%AA%E5%BB%93_v1.4.npz |
| japan/輪廓方案_乙之一含淡路格.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/%E8%BC%AA%E5%BB%93%E6%96%B9%E6%A1%88_%E4%B9%99%E4%B9%8B%E4%B8%80%E5%90%AB%E6%B7%A1%E8%B7%AF%E6%A0%BC.npz |
| japan/輪廓方案_乙之二無淡路格.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/%E8%BC%AA%E5%BB%93%E6%96%B9%E6%A1%88_%E4%B9%99%E4%B9%8B%E4%BA%8C%E7%84%A1%E6%B7%A1%E8%B7%AF%E6%A0%BC.npz |
| japan/道路_日本_v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/japan/%E9%81%93%E8%B7%AF_%E6%97%A5%E6%9C%AC_v1.7.json |
| jiehao/測試版_東亞八國_界壕草案.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/jiehao/%E6%B8%AC%E8%A9%A6%E7%89%88_%E6%9D%B1%E4%BA%9E%E5%85%AB%E5%9C%8B_%E7%95%8C%E5%A3%95%E8%8D%89%E6%A1%88.csv |
| jiehao/金界壕草案示意圖.png | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/jiehao/%E9%87%91%E7%95%8C%E5%A3%95%E8%8D%89%E6%A1%88%E7%A4%BA%E6%84%8F%E5%9C%96.png |
| ridge/山脊_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/ridge/%E5%B1%B1%E8%84%8A_v1.json |
| ridge/山脊_日本_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/ridge/%E5%B1%B1%E8%84%8A_%E6%97%A5%E6%9C%AC_v1.json |
| ridge/山脊_高麗_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/ridge/%E5%B1%B1%E8%84%8A_%E9%AB%98%E9%BA%97_v1.json |
| world/D942_水域拆欄_紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/D942_%E6%B0%B4%E5%9F%9F%E6%8B%86%E6%AC%84_%E7%B4%80%E9%8C%84.json |
| world/v1.7第三階段_檢查.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/v1.7%E7%AC%AC%E4%B8%89%E9%9A%8E%E6%AE%B5_%E6%AA%A2%E6%9F%A5.json |
| world/v1.7輪廓_C3.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/v1.7%E8%BC%AA%E5%BB%93_C3.csv |
| world/v1.7輪廓_C4.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/v1.7%E8%BC%AA%E5%BB%93_C4.csv |
| world/v1.7輪廓_剛體A.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/v1.7%E8%BC%AA%E5%BB%93_%E5%89%9B%E9%AB%94A.csv |
| world/v1.7輪廓_剛體B.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/v1.7%E8%BC%AA%E5%BB%93_%E5%89%9B%E9%AB%94B.csv |
| world/v1.7輪廓_剛體C.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/v1.7%E8%BC%AA%E5%BB%93_%E5%89%9B%E9%AB%94C.csv |
| world/v1.7輪廓_剛體C2.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/v1.7%E8%BC%AA%E5%BB%93_%E5%89%9B%E9%AB%94C2.csv |
| world/v1.8併圖_紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/v1.8%E4%BD%B5%E5%9C%96_%E7%B4%80%E9%8C%84.json |
| world/v1.8第三階段_檢查.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/v1.8%E7%AC%AC%E4%B8%89%E9%9A%8E%E6%AE%B5_%E6%AA%A2%E6%9F%A5.json |
| world/世界母圖_v1.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E4%B8%96%E7%95%8C%E6%AF%8D%E5%9C%96_v1.csv |
| world/日本_v1.7第三階段_紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC_v1.7%E7%AC%AC%E4%B8%89%E9%9A%8E%E6%AE%B5_%E7%B4%80%E9%8C%84.json |
| world/日本_v1.7第二階段_檢查.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC_v1.7%E7%AC%AC%E4%BA%8C%E9%9A%8E%E6%AE%B5_%E6%AA%A2%E6%9F%A5.json |
| world/日本_v1.7第二階段_紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC_v1.7%E7%AC%AC%E4%BA%8C%E9%9A%8E%E6%AE%B5_%E7%B4%80%E9%8C%84.json |
| world/日本_v1.8第二階段_檢查.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC_v1.8%E7%AC%AC%E4%BA%8C%E9%9A%8E%E6%AE%B5_%E6%AA%A2%E6%9F%A5.json |
| world/日本取樣_v9.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC%E5%8F%96%E6%A8%A3_v9.npz |
| world/日本海岸線_v9平面.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC%E6%B5%B7%E5%B2%B8%E7%B7%9A_v9%E5%B9%B3%E9%9D%A2.npz |
| world/日本輪廓_v1.7C3_四國重找紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC%E8%BC%AA%E5%BB%93_v1.7C3_%E5%9B%9B%E5%9C%8B%E9%87%8D%E6%89%BE%E7%B4%80%E9%8C%84.json |
| world/日本輪廓_v1.7C3_島對間隙表.md | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC%E8%BC%AA%E5%BB%93_v1.7C3_%E5%B3%B6%E5%B0%8D%E9%96%93%E9%9A%99%E8%A1%A8.md |
| world/日本輪廓_v1.7C3_紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC%E8%BC%AA%E5%BB%93_v1.7C3_%E7%B4%80%E9%8C%84.json |
| world/日本輪廓_v1.7C4_島對間隙表.md | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC%E8%BC%AA%E5%BB%93_v1.7C4_%E5%B3%B6%E5%B0%8D%E9%96%93%E9%9A%99%E8%A1%A8.md |
| world/日本輪廓_v1.7C4_紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC%E8%BC%AA%E5%BB%93_v1.7C4_%E7%B4%80%E9%8C%84.json |
| world/日本輪廓_v1.7C4_近遠海.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC%E8%BC%AA%E5%BB%93_v1.7C4_%E8%BF%91%E9%81%A0%E6%B5%B7.json |
| world/日本輪廓_v1.7_檢查.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC%E8%BC%AA%E5%BB%93_v1.7_%E6%AA%A2%E6%9F%A5.json |
| world/日本輪廓_v1.7_紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC%E8%BC%AA%E5%BB%93_v1.7_%E7%B4%80%E9%8C%84.json |
| world/日本輪廓_v1.7剛體C2_半島補格紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC%E8%BC%AA%E5%BB%93_v1.7%E5%89%9B%E9%AB%94C2_%E5%8D%8A%E5%B3%B6%E8%A3%9C%E6%A0%BC%E7%B4%80%E9%8C%84.json |
| world/日本輪廓_v1.7剛體_紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%97%A5%E6%9C%AC%E8%BC%AA%E5%BB%93_v1.7%E5%89%9B%E9%AB%94_%E7%B4%80%E9%8C%84.json |
| world/格號對照_測試版v1.6_母圖.csv | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%A0%BC%E8%99%9F%E5%B0%8D%E7%85%A7_%E6%B8%AC%E8%A9%A6%E7%89%88v1.6_%E6%AF%8D%E5%9C%96.csv |
| world/水深_ETOPO5_v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%B0%B4%E6%B7%B1_ETOPO5_v1.7.json |
| world/水深近岸帶_ETOPO5_v1.8.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E6%B0%B4%E6%B7%B1%E8%BF%91%E5%B2%B8%E5%B8%B6_ETOPO5_v1.8.json |
| world/範圍_測試版v1.6.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E7%AF%84%E5%9C%8D_%E6%B8%AC%E8%A9%A6%E7%89%88v1.6.json |
| world/範圍_測試版v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E7%AF%84%E5%9C%8D_%E6%B8%AC%E8%A9%A6%E7%89%88v1.7.json |
| world/範圍_測試版v1.8.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E7%AF%84%E5%9C%8D_%E6%B8%AC%E8%A9%A6%E7%89%88v1.8.json |
| world/覆蓋_查無_v1.7全圖.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E8%A6%86%E8%93%8B_%E6%9F%A5%E7%84%A1_v1.7%E5%85%A8%E5%9C%96.json |
| world/覆蓋_查無_v1.8全圖.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E8%A6%86%E8%93%8B_%E6%9F%A5%E7%84%A1_v1.8%E5%85%A8%E5%9C%96.json |
| world/高麗_v1.7_紀錄.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E9%AB%98%E9%BA%97_v1.7_%E7%B4%80%E9%8C%84.json |
| world/高麗取樣_v9.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E9%AB%98%E9%BA%97%E5%8F%96%E6%A8%A3_v9.npz |
| world/高麗海岸線_v9平面.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world/%E9%AB%98%E9%BA%97%E6%B5%B7%E5%B2%B8%E7%B7%9A_v9%E5%B9%B3%E9%9D%A2.npz |
| world_src/boundary.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world_src/boundary.json |
| world_src/boundary_v4.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world_src/boundary_v4.json |
| world_src/boundary_v5.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world_src/boundary_v5.json |
| world_src/etopo20.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world_src/etopo20.npz |
| world_src/hexgrid_v4.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world_src/hexgrid_v4.npz |
| world_src/hexgrid_v9.npz | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world_src/hexgrid_v9.npz |
| world_src/ne_10m_geography_regions_polys.geojson | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world_src/ne_10m_geography_regions_polys.geojson |
| world_src/ne_50m_lakes.geojson | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world_src/ne_50m_lakes.geojson |
| world_src/ne_50m_land.geojson | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world_src/ne_50m_land.geojson |
| world_src/ne_50m_rivers_lake_centerlines.geojson | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/world_src/ne_50m_rivers_lake_centerlines.geojson |
| wuchan/物產上圖_v1.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/wuchan/%E7%89%A9%E7%94%A2%E4%B8%8A%E5%9C%96_v1.json |
| wuchan/物產上圖_日本_v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/wuchan/%E7%89%A9%E7%94%A2%E4%B8%8A%E5%9C%96_%E6%97%A5%E6%9C%AC_v1.7.json |
| wuchan/物產上圖_高麗_v1.7.json | https://raw.githubusercontent.com/maybe-su/xcj4-public/main/map/wuchan/%E7%89%A9%E7%94%A2%E4%B8%8A%E5%9C%96_%E9%AB%98%E9%BA%97_v1.7.json |

## 說明
- 本庫是私人主庫 maybe-su/xcj4 的公開子集，只放人物與地圖；設計文件、劇本、模擬程式不在這裡。
- 檔案由工作視窗以 tools/sync_public.py 同步；以主庫為準。
