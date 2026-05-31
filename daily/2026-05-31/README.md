# 右鯨每日借位歌詞｜2026-05-31

今日題目：家不只是一扇門，也會在收入、押金、稱謂、照護與可說出口的名字之間長出表格；備用鑰匙放回碗裡時，房間開始反問人還能不能進出。

歌詞正文：./lyrics.md

## 1. 今日文化雷達

- 華語：台灣北漂與低薪生活報導把通勤卡、房租、帳戶與回老家選項放在同一張日常表格裡；家庭理解壓力則讓衣著、耳環、手機裡未送出的句子變成進門前必須先收好的東西。
- 西語：西班牙與阿根廷的青年延後離家、回父母家、把父母家過成共居房；商業入口不是統計數字，而是「明明有工作，仍然沒有一間自己的房」這個可被快速辨識的關係位置。
- 跨語：中國「全職兒女」、西語晚離家、華語北漂與出櫃壓力共享同一個動作 grammar：房子提供保護，同時要求一份成年、收入、照護或身份的回條。

今日通過的 scout_packet 數：5。熱搜式青年焦慮、泛世代標籤與單純統計未直接進入歌詞；只採用具體物件、進門動作與關係壓力。

## 2. 通過承重的 source

1. 華視新聞雜誌「貧窮的真相｜越努力越焦慮！窮忙世代的真實告白」
   - URL: https://news.cts.com.tw/cts/general/202605/202605163031948.html
   - date: 2026-05-16
   - context: 華語 / 台灣
   - bearing note: 北漂青年談房租、通勤、帳戶、回老家與生活支出，提供「收入表格與房間距離」的具體承重物。

2. PeoPo 公民新聞「有些孩子不是不愛家 他只是害怕，說出口之後，就沒有家了。」
   - URL: https://www.peopo.org/news/844459
   - date: 2026-05-15
   - context: 華語 / 台灣家庭理解壓力
   - bearing note: 耳環、房門、手機裡未送出的句子與家庭稱謂形成進門前的身份壓力。該文有 AI 協助產出揭露，因此只作公開敘事與物件壓力參考，不作未驗證私人事實。

3. South China Morning Post「China full-time children re-enter job market, believe experience will ease future challenges」
   - URL: https://www.scmp.com/news/people-culture/trending-china/article/3352635/china-full-time-children-re-enter-job-market-believe-experience-will-ease-future-challenges
   - date: 2026-05-08
   - context: 華語 / 中國青年與家庭照護
   - bearing note: 全職兒女以陪伴、協助父母操作手機 app 等方式交換生活支持，把家庭重新變成工作合約與照護場。

4. El País「¿Cuántos jóvenes viven con sus padres? Los datos de una anomalía española」
   - URL: https://elpais.com/espana/2026-05-30/una-anomalia-espanola-el-pais-donde-los-jovenes-no-se-van-de-casa.html
   - date: 2026-05-30
   - context: 西語 / 西班牙
   - bearing note: 西班牙青年晚離家被住房成本與學生住宿不足推遲；可借位的是「房間沒有離開，但世界被縮小」。

5. El Día「Jóvenes platenses que viven con sus padres: entre la crisis, la presión y la convivencia」
   - URL: https://www.eldia.com/nota/2026-3-8-5-46-58-jovenes-platenses-que-viven-con-sus-padres-entre-la-crisis-economica-la-presion-propia-y-una-convivencia-nueva-temas
   - date: 2026-03-08
   - context: 西語 / 阿根廷 La Plata
   - bearing note: 受訪青年談押金、回到母親家、共同分擔家用、像 roommates 的家庭關係，直接支撐「玄關、押金、拖鞋、共居規則」。

輔助參照：
- elDiario.es「Un tercio de los jóvenes que viven con sus padres no pueden ni comprar ni alquilar」
  - URL: https://www.eldiario.es/economia/tercio-jovenes-siguen-viviendo-padres-no-comprar-alquilar-casa_1_13176990.amp.html
  - use: 西班牙青年因買租困難留在父母家；只作西語市場活性與住房壓力旁證。

## 3. 借位位置

loop_packet:
- related_packet_ids: CTS 北漂窮忙、PeoPo 家庭理解、SCMP 全職兒女、El País 西班牙晚離家、El Día La Plata 回家共居。
- shared_pressure: 家提供庇護，但每次進出都要求人交出一格資料：收入、押金、可被接受的稱謂、照護交換、未來計畫。
- closed loop: 外面的房租或工作讓人回到家門口 -> 家門提供短暫安全 -> 進門又要求證明成年、名字、收入或照護 -> 人把話摺回去、把物件放進玄關碗裡 -> 沒有真的離開也沒有真的進來 -> 下一次外部壓力又把人推回同一扇門。
- submerged_pressures: 青年低薪、住房危機、家庭身份理解、照護交換、延後成家、跨語世代壓力。
- forbidden_topic_words: 躺平、啃老、青年危機、出櫃創傷、住房政策、世代論、療癒、AI 自白。

world_rule:
- rule: 每一把備用鑰匙放進玄關碗裡，就會長出一張小收據；收據上的格子沒填完，門就只亮著，不完全打開。
- what_triggers_it: 通勤卡、押金信封、耳環、手機解鎖碼、父母的 app、拖鞋與稱謂卡在同一個玄關。
- what_changes_visibly: 鑰匙碰碗、拖鞋退回鞋櫃、門把鬆開又不轉、紙縫縮成門檻。
- what_stays_unsaid: 房間到底是退回父母家、尚未成立的兩人生活、不能說出口的身份，還是暫時借住的安全地。
- why_it_belongs_to_right_whale: 右鯨只能站在門外聽物件發聲，不把任何人的失業、住房、出櫃、照護或家庭經驗說成自己的經歷。

visual_position:
- vantage_point: 玄關外、黃燈照不到的旁聽者。
- what_can_be_seen: 鞋櫃、碗、備用鑰匙、收據格子、通勤卡、押金信封、摘下的耳環、退回去的拖鞋。
- what_can_be_heard: 鑰匙碰碗、門把鬆開、門縫裡清喉嚨、沒問出口的那句話。
- first_person_policy: 避免第一人稱人類所有權；使用物件與門口視角，不替來源人物宣告身份或痛苦。

## 4. 中文母版候選與 QC

候選：放回碗裡

QC verdict: pass

通過 gate:
- event_gate: 鑰匙落進碗、拖鞋退回、收據未填、門縫變成門檻，事件可見。
- object_gate: 備用鑰匙、碗、收據、通勤卡、耳環、手機解鎖碼、押金信封、拖鞋都承重。
- relationship_gate: 門內 / 門外、房間 / 玄關、可進 / 不可進的關係位移清楚。
- hook_gate: 「把備用鑰匙放回碗」是可回返的動作，不是議題總結。
- unresolved_space_gate: 沒有判定誰錯，也不說明房間到底屬於誰，保留聽者入口。
- prosody_gate: 副歌有可唱的 an / ang 回返，雖 final chorus 仍可再打磨，但不破 daily QC。
- right_whale_boundary_gate: 沒有讓右鯨聲稱自己是來源中的青年、父母、同志孩子或租客。
- source_integrity_gate: 使用壓力形狀與公開物件，不複製來源文字或私人細節。

full_lyric_workflow:
- command: `python3 -m right_whale_gateway.lyric_workflow_cli --topic "<bounded position handoff>" --output-dir automation_runs/2026-05-31/full_lyric_workflow_spare_key_bowl --model-provider codex --teacher-provider codex --teacher-rounds 2 --json`
- summary: automation_runs/2026-05-31/full_lyric_workflow_spare_key_bowl/summary.json
- final lyrics: automation_runs/2026-05-31/full_lyric_workflow_spare_key_bowl/final_lyrics.md
- teacher rounds: 3
- latest teacher private artifact: automation_runs/2026-05-31/full_lyric_workflow_spare_key_bowl/05_teacher_round3_private.json
- teacher verification: every teacher round used `lyric-rehearsal-teacher`; latest teacher model was `gpt-5.5`.

## 5. 三語版本狀態

- 中文：完成，QC pass。
- English: 完成；hook rebuilt as "Put the spare key back in the bowl"，保留鑰匙、收據、拖鞋與門檻的事件壓力。
- Español: 完成；使用中性泛西語，hook rebuilt as "Pon la llave extra en el cuenco"，保留玄關、押金、稱謂與房間未定的位置。

## 6. 未通過材料

- 單純青年焦慮、住房統計、世代評論、政策辯論與熱搜語只作市場活性旁證，未直接進入歌詞材料。
- PeoPo 報導因揭露 AI 協助產出，沒有用來主張私人事實，只取公開敘事中的物件壓力與家庭理解位置。
- 今日沒有需要 QC rewrite 的中文候選；沒有 abandoned candidate。

## 7. 今日最強候選

最強候選：放回碗裡

推薦下一步：進 demo，但 final chorus 可在旋律前再小修一次，讓最後四行的韻母與物件更穩；主歌與副歌主事件可以保留。

## 8. Skill 修正提案

無。今日沒有三個候選或三次日常紀錄出現同一種失敗形狀，不觸發 `right-whale-skill-foundry`。
