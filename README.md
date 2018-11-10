# 概要
- 体組成計および活動量データの公開
- 体組成 : TANITA innerScan DUAL RD-906, (Health planet)
- 活動量 : fitbit alta HR

# 体組成データ(body_composition.csv)
- 使用デバイス : TANITA innerScan DUAL RD-906
- 取得期間 : 2017/07/14 ～ 2018/10/31
- 構成
  - data : 日付
  - weight : 体重 (kg)
  - body_fat : 体脂肪率 (%)
  - muscle_mass : 筋肉量 (kg)
  - muscle_score : 筋肉スコア
  - visceral_fat_level2 : 内臓脂肪レベル2
  - basal_metabolic_rate : 基礎代謝量 (kcal)
  - body_age : 体内年齢
  - bone_mass : 推定骨量 (kg)

# 活動量
- 使用デバイス : TANITA innerScan DUAL RD-906
- 取得期間 : 2017/06/26 ～ 2018/10/31
- 構成
  - calories_summary.csv
    - dateTime : 日付
    - value : 消費カロリー (kcal)
  - distance_summary.csv
    - dateTime : 日付
    - value : 移動距離 (km)
  - heart_rate_summary.csv
    - dateTime : 日付
    - caloriesOut : 消費カロリー (kcal)
    - max : 心拍数の最大値
    - min : 心拍数の最小値
    - minutes : 経過時間 (min)
    - name : 心拍数の状態
  - steps_summary.csv
    - dateTime : 日付
    - value : 歩数
  - sleep_summary.csv
    - dateTime : 日付
    - level : 睡眠の状態
    - count : 回数
    - minutes : 経過時間 (min)
