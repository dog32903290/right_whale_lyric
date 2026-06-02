# 右鯨每日借位歌詞｜2026-06-01

今日題目：每個門口都要求一種正確語言；名字被迫用錯的語言登記時，門牌就少亮一個聲音。

歌詞正文：./lyrics.md

## 1. 今日文化雷達

今天採到的可承重壓力不是「語言身份」這個議題本身，而是語言被拿來驗證親密、安全與通行資格時，人的聲音如何被門口先行改寫。

- 華語線：海外華人家庭把中文當成孩子與祖輩、母親經驗、家庭記憶之間的脆弱連線；廣州/粵語材料也顯示學校與城市語言環境會讓孩子與祖輩之間的日常話語變窄。
- 西語線：南佛州 No Sabo Kids 的敘事把「不夠會說西語」變成拉丁身份的公開驗證，語言能力被誤認為歸屬程度。
- 跨語線：美國官方 English-only 走向與 limited English proficiency 的公共服務討論，使「表格先問哪種語言」成為安全、醫療、政府服務與被聽見資格的入口壓力。

商業生命：一般聽眾能在十秒內抓到「名字被念錯、語音未回、表格語言選錯」的場景；hook 可以落在「門牌少一個聲音」而不是政策評論。

## 2. 通過承重的 source

1. WLRN, "'No Sabo Kids': How South Florida Latinos confront language, identity", 2025-04-25  
   URL: https://www.wlrn.org/arts-culture/2025-04-25/no-sabo-kids-south-florida-latinos-language-identity  
   bearing note: 有具體社群語境與身份誤讀壓力，可承載「不會某種語言就被判定不夠屬於」。

2. Sixth Tone, "A Love Letter to Overseas Chinese Moms"  
   URL: https://www.sixthtone.com/news/1017070  
   bearing note: 可承載母親、孩子、中文與家庭情感線之間的壓力，不需要右鯨冒領母親身份。

3. Sixth Tone, "Canton's Unease: As Mandarin Spreads, Locals Face Identity Crisis", 2021-11-10  
   URL: https://www.sixthtone.com/news/1008922/cantons-unease-as-mandarin-spreads-locals-face-identity-crisis  
   bearing note: 有兒童、學校、祖輩與地方語言環境的具體場景，可承載「家裡聽得懂、學校不一定容納」的壓力。

4. KFF, "Designating English as the Official Language of the United States Could Impact Millions with Limited English Proficiency", 2025  
   URL: https://www.kff.org/racial-equity-and-health-policy/designating-english-as-the-official-language-of-the-united-states-could-impact-millions-with-limited-english-proficiency/  
   bearing note: 作為公共服務與語言通行資格的 factual context；不單獨承擔私人場景。

5. The White House, "Designating English as the Official Language of The United States", 2025-03-01  
   URL: https://www.whitehouse.gov/presidential-actions/2025/03/designating-english-as-the-official-language-of-the-united-states/  
   bearing note: 作為政策背景路徑，不作為歌詞事件本身。

## 3. 借位位置

loop packet:

- shared pressure: 一個人為了被門口放行，先把名字、家語或回覆改成比較容易登記的語言；這讓他通過門口，卻讓親密關係與安全需求被誤讀。
- loop nodes: 身份驗證、家族語音、學校作業本、診間平板、官方表格都要求一種「夠用」的語言。
- false exit: 換成強勢語言好像能解決通行問題，但每換一次，某個家人、地方或未說出口的需要就被留在門外。
- return pressure: 下一個門口又要求他證明自己屬於哪一邊。

world rule:

每當一個名字被迫用錯的語言登記，門牌就少亮一個字，房間往走廊退一步。

visual position:

右鯨站在診間平板、家門、視訊通話與作業本旁邊，只聽見門牌少亮的那個聲音。右鯨不能說自己是移民、病人、No Sabo kid、母親、祖輩或地方語言承受者；他只能唱那塊沒有完全亮起來的門牌。

lyric-writing handoff:

- allowed objects: 門牌、掛號平板、語言選單、叫號螢幕、病歷腕帶、Enter、游標、作業本、橡皮擦屑、家族群組語音、退格鍵。
- forbidden claims: 不寫身份宣言、不寫政策評論、不擁有移民或家庭創傷、不把源材料人物變成右鯨第一人稱。
- hook pressure: 門牌少一個聲音。

## 4. 中文母版候選與 QC

候選數：1

### 候選 A：《門牌少一個聲音》

- full lyric workflow run dir: `automation_runs/2026-06-01/full_lyric_workflow_language_doorplate`
- CLI command: `python3 -m right_whale_gateway.lyric_workflow_cli --topic "<bounded position handoff>" --output-dir automation_runs/2026-06-01/full_lyric_workflow_language_doorplate --model-provider codex --teacher-provider codex --teacher-rounds 2`
- first run status: `full_lyric_workflow_failed` because `ModelClientError:codex_cli_timeout` at the default 180-second timeout.
- retry status: passed with `RIGHT_WHALE_CODEX_TIMEOUT=600`, same output directory, no duplicate date path.
- summary check: `ok: true`; `model_provider: codex`; `teacher_provider: codex`; `teacher_round_count: 3`.
- teacher check: every private teacher round records `teacher_skill_used: true`, `teacher_method: lyric-rehearsal-teacher`, and `teacher_model: gpt-5.5`.

QC result:

- verdict: pass
- passed gates: event, object, relationship, hook, unresolved space, prosody, Right Whale boundary, source integrity.
- hard failure: false
- transfer_ready: true
- note: the lyric stays with doorplates, tablets, Enter keys, homework books, voicemail, names and rooms. It does not claim direct human biography.

## 5. 三語版本狀態

- 中文：passed QC; master lyric archived in `lyrics.md`.
- English: transfer complete; preserves doorplate/Enter/cursor pressure and keeps the voice observational.
- Español: transfer complete; neutral pan-Hispanic register; preserves doorplate/voice/name pressure without turning into policy explanation.

## 6. 未通過材料

- Mixteco-Spanish-English medical interpretation path: discarded from load-bearing source set for today because I did not obtain a stable concrete narrative URL during the run. It remains useful as a future scout direction, not as today's source-bearing packet.
- Hot-take/debate-only language identity material: discarded because it lacked scene, object, or relation pressure.
- Statistics-only LEP material: used only as factual context, not as lyric event.

## 7. 今日最強候選

《門牌少一個聲音》是今日最強候選。

Recommended next step: demo it with a restrained mid-tempo pulse. Let `Enter 懸在手中 / 那個聲音沒回頭` carry the pre-drop suspension, and keep the chorus mouth-feel simple enough that the title can return without explanation.

## 8. Skill 修正提案

No active skill modification.

Proposal only: the workflow should expose `RIGHT_WHALE_CODEX_TIMEOUT` in the daily automation prompt or archive README metadata. Today's failure shape was not lyric-writing weakness; it was model-wrapper timeout under a long prompt.
