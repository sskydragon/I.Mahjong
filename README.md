# 「I.Mahjong」（一點麻雀）字型說明檔

「I.Mahjong」（一點麻雀）爲內木一郎製作的開源字型系列，支換OpenType字符轉換功能。字型基於古騰堡實驗室（Gutenberg Labo）維護的GL-MahjongTile字型改作，沿用與之相同的「M+字型授權條款」釋出。

依據麻雀牌的圖樣，分別有「I.Mahjong-JP」（日本麻雀牌）、「I.Mahjong-HK」（香港麻雀牌）、「I.Mahjong-TW」（臺灣麻將牌）、「I.Mahjong-CAN」（廣東麻雀牌）四種樣式選擇，每種圖樣參考了當地的主流麻雀牌設計，不過基於美觀、可讀程度、不同大小的字形清晰度等設計原因，圖樣不一定跟參考對象完全一樣。

本字型能顯示麻雀牌（麻將牌）的標準牌張（包括：筒、索、萬三門的一至九數牌，東、南、西、北、中、發、白七種字牌），八張花牌（春、夏、秋、冬、梅、蘭、菊、竹），用於日本的赤牌（包括：赤一、三、五、七、九牌，赤北風、一般赤白板、九州款赤白板），任意替代牌（包括：問號牌、百搭牌、飛牌）以及牌背。各牌均備豎立和橫臥兩種方向。牌的高闊比爲4：3，跟標準麻雀牌相同。此外還備有六面六點骰圖案。

## 使用說明

使用本字型時，可以透過以下方法輸入麻雀牌張：

### Unicode碼位

本字型支援Unicode的麻將牌區段（U+1F000至U+1F02B），可直接顯示。字符包括：🀀🀁🀂🀃🀄🀅🀆🀇🀈🀉🀊🀋🀌🀍🀎🀏🀐🀑🀒🀓🀔🀕🀖🀗🀘🀙🀚🀛🀜🀝🀞🀟🀠🀡🀢🀣🀤🀥🀦🀧🀨🀩🀪🀫。

本字型支援Unicode雜項符號區段裏的六個六面骰字元（U+2680至U+2685），可直接顯示。字符包括：⚀⚁⚂⚃⚄⚅

### 牌譜表記法

本字型於支換OpenType字符轉換功能的環境下，支援數字併字母的牌譜表記。所輸入的字元（包括數字、字母、符號）必須爲半形，而且英文字母必須爲小楷，包括：

* **筒子**：數字1至9後加上「p」（日語『ピンズ』之首音）、「t」（粵客閩湘贛官等漢語『筒』之首音）、「c」（英語『coin』或『circle』之首字母）或「d」（吳語等漢語『筒』之首音、英語『dot』之首字母），如：「1p」→🀙（一筒），「9t」→🀡（九筒）。而「0p」、「0t」、「0c」或「0d」爲赤五筒。

* **索子**：數字1至9後加上「s」（日語『ソーズ』之首音、粵客閩湘贛吳官等漢語『索』之首音、英語『string』或『stick』之首字母）或「b」（英語『bamboo』之首字母），如：「1s」→🀐（一索），「9b」→🀘（九索）。而「0s」或「0b」爲赤五索。「1sb／1bb」爲一索異體。

* **萬子**：數字1至9後加上「m」（日語『マンズ』之首音、粵贛等漢語『萬』之首音、英語『myriad』之首字母）、「w」（日語『ワンズ』之首音、湘官等漢語『萬』之首音）、「v」（客吳等漢語『萬』之首音）或「n」（英語『number』之首字母），如：「1m」→🀇（一萬），「9w」→🀏（九萬）。而「0m」、「0w」、「0v」或「0n」爲赤五萬。

* **字牌（日麻序）**：順序爲「東南西北白發中」。數字1至7後加上「z」（日語『ジハイ』之首音），如：「1z」→🀀（東風），「7z」→🀄（紅中）。而「8z」爲赤北風，「9z」爲九州款赤白板，「0z」爲赤白板，「5zb」爲漢字白板。

* **番子（國際序）**：順序爲「東南西北中發白」。數字1至7後加上「f」（粵客閩湘贛吳官等漢語『番』之首音）或「h」（英語『honor』之首字母），如：「1f」→🀀（東風），「7h」→🀆（白板）。而「8f／8h」爲赤北風，「9f／9h」爲九州款赤白板，「0f／0h」爲赤白板，「7fb／7hb」爲白板異體。

* **花牌**：順序爲「春夏秋冬梅蘭菊竹」。數字1至8後加上「*」（形狀像一朵花）或「q」（英語『quartet』之首字母，quartet指一臺花）。如：「1*」→🀦（春花），「8q」→🀤（竹花）。

* **任意替代牌**：輸入「9?」、「0?」、「9*」或「9q」可得問號牌。輸入「9!」或「0!」可得百搭牌。輸入「9@」或「0@」可得飛牌。

* **牌背**：輸入「00」、「0u」、「0*」或「0q」可得牌背。

* **赤牌**：在筒、索、萬的一、三、五、七、九，以及白板、北風後加上「a」（日語『あかはい』之首音），可得對應的赤牌，牌上有寶石點。而在白板後加上「k」（日語『きゅうしゅう』之首音），可得九州款赤白板。赤五牌亦可如前述般，用「0」配上該門的代表字母打出。

* **橫臥牌**：在各牌張後加上「-」（表示橫臥），可得對應的橫臥牌。據日本麻雀規則，立直時打出的牌要橫向放置，吃牌、碰牌、槓牌時，也應根據在哪家得牌，而把相對應位置的牌橫放，如：「1z1z-1z」表示碰了對家打出的東。

* **橫臥疊牌**：在各牌張後加上「=」（表示第二張橫臥），可得對應的橫臥牌，並疊在之前已橫臥牌張的上方。據日本麻雀規則，加槓時，開槓的牌便會這樣放置。注意：應先輸入疊在下方的牌，才在其後方輸入疊於其上的牌，如：「1z1z-1z=1z」表示碰了對家打出的東後加槓。

* **六點骰**：數字1至6後加上「.」（表示點），如：「1.」→⚀（一點骰），「6.」→⚅（六點骰）。

* **半形空格**：本字型的麻將外框線條粗度爲66px，後方牌張的左邊框線會疊着前方牌張的右邊框線，使相鄰的麻雀牌緊貼。若在兩牌之間加一個半形空格，其寬度剛好是66px，可讓兩張牌的外框不重疊。按兩次半形空格鍵，即可得與邊框等粗的縫隙。按三次空格鍵，縫隙會明顯增闊至¼張麻雀的寬度。按四次空格鍵，縫隙會增至半張麻雀的寬度。按五次空格鍵，縫隙會增至一張麻雀的寬度。

* **全形空格**：本字型的全形空格爲半張麻雀的寬度。

## 授權條款

本字型檔案採用「M+字型授權條款」釋出。如下：

這些字型爲自由軟件，您可以自由使用、複製和分發它。不論是否修改過它，不論作爲商業使用還是作爲非商業性使用，都是許可的。
我們按照這些字型的「現狀」釋出它們，然而我們並無責任確保這一點。

These fonts are free softwares.
Unlimited permission is granted to use, copy, and distribute it, with or without modification, either commercially and noncommercially.
THESE FONTS ARE PROVIDED "AS IS" WITHOUT WARRANTY.

これらのフォントはフリー（自由な）ソフトウエアです。
あらゆる改変の有無に関わらず、また商業的な利用であっても、自由にご利用、複製、再配布することができますが、全て無保証とさせていただきます。

## 鳴謝

本字型基於古騰堡實驗室（Gutenberg Labo，網址：http://gutenberg.osdn.jp ）維護的GL-MahjongTile字型改作。

本字型的英數符號部份，使用了Das Ende der Wildnis（網址：http://heiden.daynight.jp ）設計、古騰堡實驗室維護的GL-Otomanopee字型。

本字型製作時，使用過古騰堡實驗室的其他開源字型和Cangjie6（網址：https://commons.wikimedia.org/wiki/User:Cangjie6 ）的開源檔案。

特此鳴謝。

## 更新履歷

### 2020/11/22
公開發佈JP、HK、TW、CAN四款字型，版本爲1.00。
