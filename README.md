# Product Planning Skill

基於 **Double Diamond（雙菱形）** 方法論的產品企劃引導工具，幫助你從零到一系統性地完成產品企劃。

## 這個 Skill 做什麼？

這個 Skill 會引導你走過產品企劃的四個階段：

- **Discover（發現）**：建立 Persona Table、Persona 卡片、User Journey Map，全面理解目標用戶
- - **Define（定義）**：彙整痛點、轉化 HMW 問題、用機會評估表找出最值得解決的問題
  - - **Develop（開發）**：發想解法、用 Impact/Effort Matrix 排優先級、定義 User Story 和 MVP 範圍
    - - **Deliver（交付）**：設定成功指標、產出產品規格摘要
     
      - 每個階段都會展現完整的思考過程，不只給結果，還告訴你「為什麼這樣做」。
     
      - ## 使用方法
     
      - 1. 將 `SKILL.md` 放入你的 Claude 技能資料夾
        2. 2. 在對話中說出以下任一句話即可觸發：
           3.    - 「我要做一個產品」
                 -    - 「我想做個產品改版」
                      -    - 「我想做產品企劃」
                           -    - 「我有一個產品 idea」
                                - 3. Skill 會先詢問你的產品背景，再根據你的狀況建議從哪個階段開始
                                  4. 4. 接著逐步產出各階段的表格和分析，每個階段完成後會請你確認再繼續
                                    
                                     5. ## 範例
                                    
                                     6. **輸入：**
                                    
                                     7. > 我想做一個背單字的 App
                                        >
                                        > **Skill 會依序產出：**
                                        >
                                        > **Discover 階段**
                                        > - Persona Table（用「動機」區分用戶，例如：考試衝刺者 / 職場進修者 / 自學探索者）
                                        > - - 每個 Persona 的詳細卡片（背景、目標、現行做法、痛點）
                                        >   - - User Journey Map 概覽表 + 逐段展開細節
                                        >    
                                        >     - **Define 階段**
                                        >     - - 痛點彙整表（跨 Persona 提取所有痛點）
                                        >       - - HMW 問題轉化（將痛點轉為可行動的問題）
                                        >         - - 機會評估表（含 Persona 覆蓋範圍和規模的加權評估）
                                        >          
                                        >           - **Develop 階段**
                                        >           - - 解法發想表（每個 HMW 產生多個解法方向）
                                        >             - - Impact / Effort Matrix（找出 Quick Win）
                                        >               - - User Story 表 + MVP 範圍定義
                                        >                
                                        >                 - **Deliver 階段**
                                        >                 - - 成功指標表（核心指標 / 次要指標 / 護欄指標）
                                        >                   - - 產品規格摘要（一頁式總覽）
                                        >                    
                                        >                     - **最終產出：** 最佳切入點分析，包含完整的推導邏輯鏈和建議的第一步行動。
                                        >                    
                                        >                     - ## 作者
                                        >                    
                                        >                     - **Mr. PM（Stanley）**
                                        > [https://mrpm.cc](https://mrpm.cc)

## License

[MIT License](./LICENSE)
