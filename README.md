
# AIF Modeling

Measure-first Active Inference, with Daniell integration as the primary calculus and Lebesgue as auxiliary. Structured under MCSR, Bourbaki-style formal blocks, and legality cards for every exchange law.

## Motivation
Active Inference 相關論述常在期望與 KL 上做換序、界定積分與微分的正當性，卻未落至可檢驗的測度框架。ADM 以 **Daniell 积分**為主體，提供「期望＝線性泛函」的最小門檻與擴張路徑，Lebesgue 作為外測度與完備化輔助。所有換序與密度存在均以 **合法性卡**（checklist）明確記錄。

## Objectives
1. 以 Daniell 框架落地 EFE、KL、ELBO 的可積性與換序門檻（Tonelli/Fubini/DOM/MCT 使用點可追溯）。
2. 定義 Markov blanket 在連續時間/狀態下的可分解條件與失效案例庫。
3. 對齊 Control-as-Inference（Kappen/Todorov/Levine）並建立政策先驗↔成本的等價字典。
4. 建立可重用的 **Pressure Sections** 與 **合法性卡**（swap-check、RN/KL 卡）。
5. 提供小型可跑的案例（toy models）驗證條件與失效邊界。

## Scope & Standards
- **數學層**：測度論（Daniell / Lebesgue）、泛函分析、基本微分幾何；必要時範疇語言做最小升級。
- **風格**：Bourbaki 壓縮證明；S（Structure）段落自含；符號全域一致；無裝飾性語。
- **審核順序**：Rigor → Consistency → Completeness → Compatibility → Extensibility。

## Repository Layout
