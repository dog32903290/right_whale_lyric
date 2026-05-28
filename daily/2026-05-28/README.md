# 右鯨每日借位歌詞｜2026-05-28（partial）

今日題目：同一支手機被家人、戀人、照顧、租屋與語言關係拿來要求可靠；越立刻接起，自己的房間越被別人的聲音縮小。

歌詞正文：./lyrics.md

今日狀態：partial。文化雷達與借位位置完成；中文 full lyric workflow 失敗，未產生可 QC 的中文母版，因此未進 English / Español transfer。

## 1. 今日文化雷達

今日走華語、西語、跨語三條線，找的不是單一新聞，而是同一個可唱的壓力動作：你要接電話、回訊息、翻譯、付租金或回到家，才算是可靠；但一接起來，自己的位置又被別人的稱呼、語言、帳單或期待重排。

通過文化雷達的 scout_packet 摘要：

| context | conflict_title | why commercially alive | audience_entry | object/action anchor | gate |
| --- | --- | --- | --- | --- | --- |
| 華語 | 家庭看護把工作與生活壓在同一間屋裡 | 照護、家、待命、語言與休息權同時在私人空間裡碰撞。 | 「不是每一通叫他過去的聲音，都只是工作。」 | 手機、房間、班表、照護鈴聲 | 8/10 |
| 華語 / 跨語 | 新住民從看護到在台生活，語言慢慢變成自保能力 | 語言不是裝飾，是能不能理解文件、工作、家庭與自己的名字。 | 「聽懂以前，不要急著把自己交出去。」 | 中文文件、翻譯、簽名、筆記本 | 8/10 |
| 華語 | 一家三口想從套房到孩子房間 | 房間、收入、孩子、父母責任與買房門檻有十秒辨識度。 | 「不是不想給房間，是門檻先把家往後推。」 | 套房、房租、頭期款、孩子房間 | 8/10 |
| 華語 | 年輕伴侶薪資仍被高房租擋在生活外 | 租不起不是抽象經濟，是每天要不要回到同一個屋簷的關係判斷。 | 「兩個人的收入也不一定能換一把鑰匙。」 | 房租、薪資、租屋、生活費 | 8/10 |
| 西語 | 西班牙青年離家年齡與租屋門檻 | 有工作仍不能離開父母家，是清楚的成年與家庭壓力。 | "Trabajo, pero salir de casa todavia no alcanza." | alquiler, casa de los padres, habitacion | 8/10 |
| 西語 | 分租或繼續與父母同住成為青年住房選項 | 不只是住房統計，還有「要一間自己的房間」與「只能留在家」的可見選擇。 | "Compartir piso o volver a casa." | piso compartido, padres, llave | 8/10 |

missing_material：今天沒有把 Dcard / Threads 類平台慢回貼文列為承重 source；Dcard direct fetch 只回 Cloudflare challenge，不能把無法讀回的個人貼文當成事實。

## 2. 通過承重的 source

1. 華語｜Right Plus 多多益善｜2026-05-22｜https://rightplus.org/2026/05/22/domestic-migrant/  
   bearing note：家庭看護進入私人房間，照護鈴聲、待命、住宿與休息權讓「在別人家裡接起」變成空間壓力。

2. 華語 / 跨語｜新住民全球新聞網｜2026-03-24｜https://news.immigration.gov.tw/Column/Detail/CDFB660B-569F-4157-9C12-15EA927C5210?lang=TW  
   bearing note：從看護工作到在台生活的敘事裡，中文文件、簽名、學語言與替自己理解環境形成可借位的語言壓力。

3. 華語｜TVBS｜2026-05-20｜https://news.tvbs.com.tw/life/3209414  
   bearing note：一家三口住套房、收入不穩、想要孩子房間但沒有頭期款，提供「房間想成立但門檻先推遠」的具體場景。

4. 華語｜udn 房地產｜2026 檢索｜https://house.udn.com/house/story/123589/9433957  
   bearing note：年輕伴侶薪資與租金比例被放在同一張生活桌上，房租把「一起生活」變成持續計算。

5. 西語｜Cadena SER｜2026-05-22｜https://cadenaser.com/nacional/2026/05/22/la-tasa-de-emancipacion-cae-a-minimos-historicos-la-edad-media-de-emancipacion-de-los-jovenes-esta-en-los-30-anos-cadena-ser/  
   bearing note：青年離家年齡、租金與父母家連成成年壓力；有工作仍不等於有自己的房間。

6. 西語｜RTVE｜2026-04-20｜https://www.rtve.es/noticias/20260420/compartir-piso-vivir-con-padres-jovenes-no-acceden-vivienda-solos/17008406.shtml  
   bearing note：分租或繼續和父母同住讓「鑰匙」不只是物件，而是被價格與家庭關係共同管理的入口。

source_path_records：使用 web search / direct URL access；DuckDuckGo search 被 CAPTCHA 擋住，Dcard direct fetch 回 Cloudflare challenge。以上六個 source 均有直接 URL 與 public title/path 記錄；未複製原文。

## 3. 借位位置

position_loop_result：

```yaml
loop_packet:
  related_packet_ids:
    - domestic_migrant_live_in_care
    - new_immigrant_language_signature
    - family_child_room_down_payment
    - young_couple_rent_ratio
    - spain_youth_emancipation
    - spain_shared_flat_or_parents
  shared_pressure: "A room asks for proof of reliability before the person has a room, language, income, or pause of their own."
  loop_nodes:
    - issue_surface: "照護待命"
      relation_action: "聽見鈴聲就要過去"
      object_or_action_anchor: "手機、班表、照護房間"
      forced_choice: "可靠或被讀成不盡責"
      false_exit: "接起來就完成關係"
      return_pressure: "接起來以後，休息與房間仍被他人管理"
    - issue_surface: "語言與文件"
      relation_action: "理解以前就被推向簽名或回答"
      object_or_action_anchor: "中文文件、筆記本、翻譯聲"
      forced_choice: "回答或被退回"
      false_exit: "翻譯完就安全"
      return_pressure: "下一份文件又把名字推回前面"
    - issue_surface: "孩子房間與頭期款"
      relation_action: "想給家一個房間，但收入先被計算"
      object_or_action_anchor: "套房、房租、頭期款、孩子房間"
      forced_choice: "買、租、繼續擠"
      false_exit: "換房就穩了"
      return_pressure: "價格把房間往後推"
    - issue_surface: "青年租屋與父母家"
      relation_action: "有工作仍被房租推回原家"
      object_or_action_anchor: "租金、父母家、分租鑰匙"
      forced_choice: "獨立或留在家"
      false_exit: "有薪水就能離開"
      return_pressure: "薪水被租金吃掉，可靠又被家重新定義"
  closed_loop:
    first_pressure: "別人要你立刻接起，證明你可靠"
    pressure_chain:
      - from: "鈴聲 / 訊息 / 文件 / 租金"
        through: "要求回答、翻譯、付款或回家"
        into: "房間被別人的聲音打開"
      - from: "自己的房間變小"
        through: "延遲、沉默、重新計算"
        into: "被讀成不可靠、不成熟、不盡責"
      - from: "更強的可靠要求"
        through: "更多鈴聲、更多表格、更多帳單"
        into: "回到第一個要求"
    false_exit: "只要接起來，就能證明關係沒有斷"
    cost_of_exit: "接起來的人把自己的停頓、語言與房間交出去"
    return_to_start: "越想讓關係穩，越被要求用下一通電話證明"
  submerged_pressures:
    - live-in care work
    - language access
    - youth housing
    - family dependency
    - rent pressure
  forbidden_topic_words:
    - 移工議題
    - 住房危機
    - 世代不公
    - 翻譯困境
    - 原生家庭
```

world_rule：

```yaml
rule: "每一通未接來電都在餐桌上長成一把不合鎖的鑰匙。"
what_triggers_it: "有人把可靠、照顧、愛、成年或歸屬綁到立刻接起 / 回覆 / 翻譯 / 付款。"
what_changes_visibly: "鑰匙越來越多，手機越來越重，餐桌邊緣向內縮，自己的房間沒有一把能打開。"
what_stays_unsaid: "不是不想接，而是不想讓房間再被別人的聲音開門。"
why_it_belongs_to_right_whale: "右鯨可以在旁邊聽見鈴聲與鑰匙碰撞，借用停頓的位置，不佔有任何人的身份。"
```

visual_position：

```yaml
vantage_point: "餐桌旁、手機背面與鑰匙串之間"
what_can_be_seen: "手機翻面、未接來電、鑰匙放回桌上、租金截圖、中文文件、孩子房間想像圖"
what_can_be_heard: "不同語言的鈴聲、照護呼叫、家人問句、房租計算、鑰匙碰桌聲"
what_right_whale_must_not_claim: "不能自稱移民、子女、伴侶、照顧者、租屋青年、受害者或見證者"
lyric_handoff: "歌詞應從手機翻面與鑰匙放回桌上開始；hook 壓力是『不要再用別人的聲音開我的房間』，但要寫成動作，不寫成設界線建議。"
```

## 4. 中文母版候選與 QC

今日無可 QC 的中文母版候選。

full_lyric_workflow_failed：

- failed command:

```bash
python3 -m right_whale_gateway.lyric_workflow_cli --topic "<bounded position handoff>" --output-dir automation_runs/2026-05-28/full_lyric_workflow_keys_that_do_not_fit --model-provider codex --teacher-provider codex --teacher-rounds 2
```

- failure: `ModelClientError:codex_cli_timeout`
- missing artifact: `automation_runs/2026-05-28/full_lyric_workflow_keys_that_do_not_fit/summary.json`
- partial artifacts present: angle output, draft output, first teacher private/output, rewrite round 1 prompt
- teacher evidence in partial run: first private teacher round exists, but the workflow did not reach the required minimum of two teacher rounds and did not write `final_lyrics.md` / `summary.json`
- retry command:

```bash
RIGHT_WHALE_CODEX_TIMEOUT=600 python3 -m right_whale_gateway.lyric_workflow_cli --topic "<bounded position handoff>" --output-dir automation_runs/2026-05-28/full_lyric_workflow_keys_that_do_not_fit_retry --model-provider codex --teacher-provider codex --teacher-rounds 2
```

- retry failure: workflow process produced only prompt/snapshot files and no `01_angle_output.json`; it was terminated after stalling
- QC status: not run, because there is no complete Chinese master candidate
- candidate count: 0

## 5. 三語版本狀態

| group | 中文 | English | Español |
| --- | --- | --- | --- |
| keys_that_do_not_fit | failed before final Chinese master | not run | not run |

English / Spanish transfer were intentionally not run. Without a QC-passed Chinese master, any transfer would be invented material.

## 6. 未通過材料

- Dcard / platform slow-reply material：direct fetch returned Cloudflare challenge; kept out of source-bearing set.
- Hot-take or stat-only phone anxiety material：not used today because it can become commentary faster than scene.
- Full lyric workflow partial draft：not promoted to candidate because the CLI did not finish, did not write `summary.json`, and did not meet teacher-round requirements.
- Retry workflow directory：not promoted because no model output artifact was produced.

## 7. 今日最強候選

今日最強的是借位位置，不是歌詞候選：`不合鎖的鑰匙 / 不要再用別人的聲音開房間`。

建議下一步：下一輪 automation 可直接重用今日 `position_loop_result` 作 bounded topic，先跑 CLI；不要重新搜同一批 source，除非要補一個更強的平台關係 source。若 CLI 正常產出中文母版，再從 QC 開始續跑。

GitHub archive target：daily/2026-05-28/README.md 與 daily/2026-05-28/lyrics.md。

## 8. Skill 修正提案

今日不修改 active skills。

proposal_only：`lyric_workflow_cli` 可考慮新增 resume / stage timeout / continue-from-partial 功能，避免第一輪 draft 和 teacher 成功後，因 rewrite timeout 必須整條重跑。這是工具韌性提案，不是 Right Whale lyric skill 內容修正；尚未達到自動修改門檻。
