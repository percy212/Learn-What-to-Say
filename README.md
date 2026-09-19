# Learn What to Say: Generalizable Active Enrollment for Few-Shot Voice Personalization

This repository contains the lexicon files used in **LEAP** (**L**anguage-Transferable **E**nrollment via **A**ctive **P**olicy Learning).

## Overview

To support the methodology proposed in **LEAP**, we provide lexicon CSV files across four languages:
- English
- Korean
- Japanese
- Vietnamese

All lexicon files can be found in the `csv/` directory.

## Preview
Below is a preview of the lexicon CSV data used in our framework.

| Language | Path |
| :--- | :--- |
| **English** | `csv/english.csv` |
| **Korean** | `csv/korean.csv` |
| **Japanese** | `csv/japanese.csv` |
| **Vietnamese** | `csv/vietnamese.csv` |

> **Note:** For more implementation and experiment details, please refer to our main paper.

### English


### Korean

<div style="overflow-x: auto; max-height: 400px; overflow-y: auto;">

<style>
  .github-csv-viewer {
    border: 1px solid var(--color-border-default, currentColor);
    border-radius: 6px;
    overflow: auto;
    max-height: 400px;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans", Helvetica, Arial, sans-serif;
    font-size: 12px;
  }
  
  .github-csv-table {
    border-collapse: separate;
    border-spacing: 0;
    width: max-content;
    min-width: 100%;
  }

  .github-csv-table th {
    background-color: var(--color-canvas-subtle, transparent);
    font-weight: 600;
    padding: 6px 12px;
    white-space: nowrap;
    text-align: left;
  }

  .github-csv-table td {
    padding: 6px 12px;
    white-space: nowrap;
  }

  .github-csv-table .line-num {
    background-color: var(--color-canvas-subtle, transparent);
    opacity: 0.7;
    text-align: right;
    width: 1%;
    padding: 6px 10px;
    user-select: none;
  }

  .github-csv-table th.line-num-header {
    text-align: center;
    width: 1%;
  }
</style>
<div class="github-csv-viewer">
  <table class="github-csv-table">
    <thead>
      <tr>
        <th class="line-num line-num-header"></th>
        <th>id</th>
        <th>type</th>
        <th>text</th>
        <th>syllable_count</th>
        <th>estimated_duration</th>
        <th>actual_duration_mean</th>
        <th>standard_deviation</th>
        <th>pronunciation</th>
        <th>onsets</th>
        <th>nuclei</th>
        <th>codas</th>
        <th>phoneme_sequence</th>
        <th>phoneme_set</th>
        <th>phoneme_transitions</th>
        <th>cross-word transition</th>
        <th>morphophonological_processes</th>
        <th>morphophonology_count</th>
        <th>viseme_sequence</th>
        <th>viseme_set</th>
        <th>viseme_transitions</th>
        <th>visual_features</th>
        <th>phoneme_viseme_pairs</th>
        <th>av_transitions</th>
        <th>phoneme_coverage_gain</th>
        <th>coda_coverage_gain</th>
        <th>morph_coverage_gain</th>
        <th>viseme_coverage_gain</th>
        <th>viseme_transition_gain</th>
        <th>av_transition_gain</th>
        <th>audio_score</th>
        <th>vision_score</th>
        <th>joint_av_score</th>
        <th>phoneme_transition_gain</th>
        <th>audio_score_per_sec</th>
        <th>vision_score_per_sec</th>
        <th>joint_av_score_per_sec</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="line-num">1</td>
        <td>K001</td>
        <td>word</td>
        <td>바다</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.63</td>
        <td>0.06</td>
        <td>바다</td>
        <td>ㅂ,ㄷ</td>
        <td>ㅏ</td>
        <td></td>
        <td>ㅂ-ㅏ-ㄷ-ㅏ</td>
        <td>ㅂ,ㅏ,ㄷ</td>
        <td>ㅂ→ㅏ,ㅏ→ㄷ,ㄷ→ㅏ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>bilabial closure → open vowel → alveolar → open vowel</td>
        <td>bilabial closure,open vowel,alveolar</td>
        <td>bilabial closure→open vowel,open vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㅂ:bilabial closure,ㅏ:open vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.06</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.16666666666666700</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.017688172043010800</td>
        <td>0.053672316384180800</td>
        <td>0.020985469860484000</td>
        <td>0.010752688172043000</td>
        <td>0.028076463560334500</td>
        <td>0.08519415299076320</td>
        <td>0.033310269619815900</td>
      </tr>
      <tr>
        <td class="line-num">2</td>
        <td>K002</td>
        <td>word</td>
        <td>가방</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.6</td>
        <td>0.0</td>
        <td>가방</td>
        <td>ㄱ,ㅂ</td>
        <td>ㅏ</td>
        <td>ㅇ</td>
        <td>ㄱ-ㅏ-ㅂ-ㅏ-ㅇ</td>
        <td>ㄱ,ㅏ,ㅂ,ㅇ</td>
        <td>ㄱ→ㅏ,ㅏ→ㅂ,ㅂ→ㅏ,ㅏ→ㅇ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>low-visibility velar → open vowel → bilabial closure → open vowel → low-visibility coda</td>
        <td>low-visibility velar,open vowel,bilabial closure,low-visibility coda</td>
        <td>low-visibility velar→open vowel,open vowel→bilabial closure,bilabial closure→open vowel,open vowel→low-visibility coda</td>
        <td>양순음에서 입술 폐쇄가 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㄱ:low-visibility velar,ㅏ:open vowel,ㅂ:bilabial closure,ㅏ:open vowel,ㅇ:low-visibility coda</td>
        <td>ㄱ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅇ:low-visibility coda</td>
        <td>0.08</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.03389830508474580</td>
        <td>0.016736401673640200</td>
        <td>0.04631150211795370</td>
        <td>0.07156308851224110</td>
        <td>0.040434084951870400</td>
        <td>0.014336917562724000</td>
        <td>0.07718583686325620</td>
        <td>0.11927181418706800</td>
        <td>0.06739014158645080</td>
      </tr>
      <tr>
        <td class="line-num">3</td>
        <td>K003</td>
        <td>word</td>
        <td>다리</td>
        <td>2</td>
        <td>0.5</td>
        <td>0.53</td>
        <td>0.06</td>
        <td>다리</td>
        <td>ㄷ,ㄹ</td>
        <td>ㅏ,ㅣ</td>
        <td></td>
        <td>ㄷ-ㅏ-ㄹ-ㅣ</td>
        <td>ㄷ,ㅏ,ㄹ,ㅣ</td>
        <td>ㄷ→ㅏ,ㅏ→ㄹ,ㄹ→ㅣ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>alveolar → open vowel → liquid → spread vowel</td>
        <td>alveolar,open vowel,liquid,spread vowel</td>
        <td>alveolar→open vowel,open vowel→liquid,liquid→spread vowel</td>
        <td>ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㄷ:alveolar,ㅏ:open vowel,ㄹ:liquid,ㅣ:spread vowel</td>
        <td>ㄷ:alveolar→ㅏ:open vowel,ㅏ:open vowel→ㄹ:liquid,ㄹ:liquid→ㅣ:spread vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.022688172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.025184960784060100</td>
        <td>0.010752688172043000</td>
        <td>0.04280787177926560</td>
        <td>0.1222328820665890</td>
        <td>0.04751879393218890</td>
      </tr>
      <tr>
        <td class="line-num">4</td>
        <td>K004</td>
        <td>word</td>
        <td>사과</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.63</td>
        <td>0.06</td>
        <td>사과</td>
        <td>ㅅ,ㄱ</td>
        <td>ㅏ,ㅘ</td>
        <td></td>
        <td>ㅅ-ㅏ-ㄱ-ㅘ</td>
        <td>ㅅ,ㅏ,ㄱ,ㅘ</td>
        <td>ㅅ→ㅏ,ㅏ→ㄱ,ㄱ→ㅘ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>fricative → open vowel → low-visibility velar → rounded vowel</td>
        <td>fricative,open vowel,low-visibility velar,rounded vowel</td>
        <td>fricative→open vowel,open vowel→low-visibility velar,low-visibility velar→rounded vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㅅ:fricative,ㅏ:open vowel,ㄱ:low-visibility velar,ㅘ:rounded vowel</td>
        <td>ㅅ:fricative→ㅏ:open vowel,ㅏ:open vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅘ:rounded vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.022688172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.025184960784060100</td>
        <td>0.010752688172043000</td>
        <td>0.03601297149684250</td>
        <td>0.10283083729411400</td>
        <td>0.03997612822866680</td>
      </tr>
      <tr>
        <td class="line-num">5</td>
        <td>K005</td>
        <td>word</td>
        <td>자두</td>
        <td>2</td>
        <td>0.5</td>
        <td>0.47</td>
        <td>0.06</td>
        <td>자두</td>
        <td>ㅈ,ㄷ</td>
        <td>ㅏ,ㅜ</td>
        <td></td>
        <td>ㅈ-ㅏ-ㄷ-ㅜ</td>
        <td>ㅈ,ㅏ,ㄷ,ㅜ</td>
        <td>ㅈ→ㅏ,ㅏ→ㄷ,ㄷ→ㅜ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>affricate → open vowel → alveolar → rounded/protruded vowel</td>
        <td>affricate,open vowel,alveolar,rounded/protruded vowel</td>
        <td>affricate→open vowel,open vowel→alveolar,alveolar→rounded/protruded vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㅈ:affricate,ㅏ:open vowel,ㄷ:alveolar,ㅜ:rounded/protruded vowel</td>
        <td>ㅈ:affricate→ㅏ:open vowel,ㅏ:open vowel→ㄷ:alveolar,ㄷ:alveolar→ㅜ:rounded/protruded vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.022688172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.025184960784060100</td>
        <td>0.010752688172043000</td>
        <td>0.048272706474491000</td>
        <td>0.13783707977721700</td>
        <td>0.05358502294480870</td>
      </tr>
      <tr>
        <td class="line-num">6</td>
        <td>K006</td>
        <td>word</td>
        <td>까치</td>
        <td>2</td>
        <td>0.7</td>
        <td>0.57</td>
        <td>0.12</td>
        <td>까치</td>
        <td>ㄲ,ㅊ</td>
        <td>ㅏ,ㅣ</td>
        <td></td>
        <td>ㄲ-ㅏ-ㅊ-ㅣ</td>
        <td>ㄲ,ㅏ,ㅊ,ㅣ</td>
        <td>ㄲ→ㅏ,ㅏ→ㅊ,ㅊ→ㅣ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>low-visibility velar → open vowel → affricate → spread vowel</td>
        <td>low-visibility velar,open vowel,affricate,spread vowel</td>
        <td>low-visibility velar→open vowel,open vowel→affricate,affricate→spread vowel</td>
        <td>ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㄲ:low-visibility velar,ㅏ:open vowel,ㅊ:affricate,ㅣ:spread vowel</td>
        <td>ㄲ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㅊ:affricate,ㅊ:affricate→ㅣ:spread vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.022688172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.025184960784060100</td>
        <td>0.010752688172043000</td>
        <td>0.03980381060177330</td>
        <td>0.11365513595665200</td>
        <td>0.044184141726421200</td>
      </tr>
      <tr>
        <td class="line-num">7</td>
        <td>K007</td>
        <td>word</td>
        <td>딸기</td>
        <td>2</td>
        <td>0.8</td>
        <td>0.77</td>
        <td>0.06</td>
        <td>딸기</td>
        <td>ㄸ,ㄱ</td>
        <td>ㅏ,ㅣ</td>
        <td>ㄹ</td>
        <td>ㄸ-ㅏ-ㄹ-ㄱ-ㅣ</td>
        <td>ㄸ,ㅏ,ㄹ,ㄱ,ㅣ</td>
        <td>ㄸ→ㅏ,ㅏ→ㄹ,ㄹ→ㄱ,ㄱ→ㅣ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>alveolar → open vowel → low-visibility coda → low-visibility velar → spread vowel</td>
        <td>alveolar,open vowel,low-visibility coda,low-visibility velar,spread vowel</td>
        <td>alveolar→open vowel,open vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→spread vowel</td>
        <td>ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㄸ:alveolar,ㅏ:open vowel,ㄹ:low-visibility coda,ㄱ:low-visibility velar,ㅣ:spread vowel</td>
        <td>ㄸ:alveolar→ㅏ:open vowel,ㅏ:open vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅣ:spread vowel</td>
        <td>0.1</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.2777777777777780</td>
        <td>0.03389830508474580</td>
        <td>0.016736401673640200</td>
        <td>0.05131150211795370</td>
        <td>0.08267419962335220</td>
        <td>0.04468790172597980</td>
        <td>0.014336917562724000</td>
        <td>0.06663831443890100</td>
        <td>0.10736909041993800</td>
        <td>0.05803623600776600</td>
      </tr>
      <tr>
        <td class="line-num">8</td>
        <td>K008</td>
        <td>word</td>
        <td>빨대</td>
        <td>2</td>
        <td>0.8</td>
        <td>0.8</td>
        <td>0.1</td>
        <td>빨때</td>
        <td>ㅃ,ㄷ</td>
        <td>ㅏ,ㅐ</td>
        <td>ㄹ</td>
        <td>ㅃ-ㅏ-ㄹ-ㄸ-ㅐ</td>
        <td>ㅃ,ㅏ,ㄹ,ㄸ,ㅐ</td>
        <td>ㅃ→ㅏ,ㅏ→ㄹ,ㄹ→ㄸ,ㄸ→ㅐ</td>
        <td></td>
        <td>tensification</td>
        <td>1.0</td>
        <td>bilabial closure → open vowel → low-visibility coda → alveolar → front/open-mid vowel</td>
        <td>bilabial closure,open vowel,low-visibility coda,alveolar,front/open-mid vowel</td>
        <td>bilabial closure→open vowel,open vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→front/open-mid vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅃ:bilabial closure,ㅏ:open vowel,ㄹ:low-visibility coda,ㄸ:alveolar,ㅐ:front/open-mid vowel</td>
        <td>ㅃ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅐ:front/open-mid vowel</td>
        <td>0.1</td>
        <td>0.09090909090909090</td>
        <td>0.125</td>
        <td>0.2777777777777780</td>
        <td>0.03389830508474580</td>
        <td>0.016736401673640200</td>
        <td>0.08256150211795370</td>
        <td>0.08267419962335220</td>
        <td>0.05626524513255730</td>
        <td>0.014336917562724000</td>
        <td>0.10320187764744200</td>
        <td>0.10334274952919000</td>
        <td>0.0703315564156966</td>
      </tr>
      <tr>
        <td class="line-num">9</td>
        <td>K009</td>
        <td>word</td>
        <td>쌀밥</td>
        <td>2</td>
        <td>0.8</td>
        <td>0.77</td>
        <td>0.06</td>
        <td>쌀밥</td>
        <td>ㅆ,ㅂ</td>
        <td>ㅏ</td>
        <td>ㄹ,ㅂ</td>
        <td>ㅆ-ㅏ-ㄹ-ㅂ-ㅏ-ㅂ</td>
        <td>ㅆ,ㅏ,ㄹ,ㅂ</td>
        <td>ㅆ→ㅏ,ㅏ→ㄹ,ㄹ→ㅂ,ㅂ→ㅏ,ㅏ→ㅂ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>fricative → open vowel → low-visibility coda → bilabial closure → open vowel → bilabial coda closure</td>
        <td>fricative,open vowel,low-visibility coda,bilabial closure,bilabial coda closure</td>
        <td>fricative→open vowel,open vowel→low-visibility coda,low-visibility coda→bilabial closure,bilabial closure→open vowel,open vowel→bilabial coda closure</td>
        <td>양순음에서 입술 폐쇄가 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅆ:fricative,ㅏ:open vowel,ㄹ:low-visibility coda,ㅂ:bilabial closure,ㅏ:open vowel,ㅂ:bilabial coda closure</td>
        <td>ㅆ:fricative→ㅏ:open vowel,ㅏ:open vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅂ:bilabial coda closure</td>
        <td>0.08</td>
        <td>0.18181818181818200</td>
        <td>0.0</td>
        <td>0.2777777777777780</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.06993483219289670</td>
        <td>0.08945386064030130</td>
        <td>0.05546770504270960</td>
        <td>0.017921146953405000</td>
        <td>0.09082445739337240</td>
        <td>0.11617384498740400</td>
        <td>0.07203598057494760</td>
      </tr>
      <tr>
        <td class="line-num">10</td>
        <td>K010</td>
        <td>word</td>
        <td>짜장</td>
        <td>2</td>
        <td>0.7</td>
        <td>0.6</td>
        <td>0.1</td>
        <td>짜장</td>
        <td>ㅉ,ㅈ</td>
        <td>ㅏ</td>
        <td>ㅇ</td>
        <td>ㅉ-ㅏ-ㅈ-ㅏ-ㅇ</td>
        <td>ㅉ,ㅏ,ㅈ,ㅇ</td>
        <td>ㅉ→ㅏ,ㅏ→ㅈ,ㅈ→ㅏ,ㅏ→ㅇ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>affricate → open vowel → affricate → open vowel → low-visibility coda</td>
        <td>affricate,open vowel,low-visibility coda</td>
        <td>affricate→open vowel,open vowel→affricate,affricate→open vowel,open vowel→low-visibility coda</td>
        <td>개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㅉ:affricate,ㅏ:open vowel,ㅈ:affricate,ㅏ:open vowel,ㅇ:low-visibility coda</td>
        <td>ㅉ:affricate→ㅏ:open vowel,ㅏ:open vowel→ㅈ:affricate,ㅈ:affricate→ㅏ:open vowel,ㅏ:open vowel→ㅇ:low-visibility coda</td>
        <td>0.08</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.16666666666666700</td>
        <td>0.025423728813559300</td>
        <td>0.016736401673640200</td>
        <td>0.04631150211795370</td>
        <td>0.053672316384180800</td>
        <td>0.03652713216993710</td>
        <td>0.014336917562724000</td>
        <td>0.07718583686325620</td>
        <td>0.08945386064030130</td>
        <td>0.0608785536165619</td>
      </tr>
      <tr>
        <td class="line-num">11</td>
        <td>K011</td>
        <td>word</td>
        <td>카드</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.63</td>
        <td>0.06</td>
        <td>카드</td>
        <td>ㅋ,ㄷ</td>
        <td>ㅏ,ㅡ</td>
        <td></td>
        <td>ㅋ-ㅏ-ㄷ-ㅡ</td>
        <td>ㅋ,ㅏ,ㄷ,ㅡ</td>
        <td>ㅋ→ㅏ,ㅏ→ㄷ,ㄷ→ㅡ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>low-visibility velar → open vowel → alveolar → neutral/unrounded vowel</td>
        <td>low-visibility velar,open vowel,alveolar,neutral/unrounded vowel</td>
        <td>low-visibility velar→open vowel,open vowel→alveolar,alveolar→neutral/unrounded vowel</td>
        <td>개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㅋ:low-visibility velar,ㅏ:open vowel,ㄷ:alveolar,ㅡ:neutral/unrounded vowel</td>
        <td>ㅋ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㄷ:alveolar,ㄷ:alveolar→ㅡ:neutral/unrounded vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.022688172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.025184960784060100</td>
        <td>0.010752688172043000</td>
        <td>0.03601297149684250</td>
        <td>0.10283083729411400</td>
        <td>0.03997612822866680</td>
      </tr>
      <tr>
        <td class="line-num">12</td>
        <td>K012</td>
        <td>word</td>
        <td>토끼</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.6</td>
        <td>0.1</td>
        <td>토끼</td>
        <td>ㅌ,ㄲ</td>
        <td>ㅗ,ㅣ</td>
        <td></td>
        <td>ㅌ-ㅗ-ㄲ-ㅣ</td>
        <td>ㅌ,ㅗ,ㄲ,ㅣ</td>
        <td>ㅌ→ㅗ,ㅗ→ㄲ,ㄲ→ㅣ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>alveolar → rounded vowel → low-visibility velar → spread vowel</td>
        <td>alveolar,rounded vowel,low-visibility velar,spread vowel</td>
        <td>alveolar→rounded vowel,rounded vowel→low-visibility velar,low-visibility velar→spread vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㅌ:alveolar,ㅗ:rounded vowel,ㄲ:low-visibility velar,ㅣ:spread vowel</td>
        <td>ㅌ:alveolar→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄲ:low-visibility velar,ㄲ:low-visibility velar→ㅣ:spread vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.022688172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.025184960784060100</td>
        <td>0.010752688172043000</td>
        <td>0.037813620071684600</td>
        <td>0.10797237915882000</td>
        <td>0.041974934640100200</td>
      </tr>
      <tr>
        <td class="line-num">13</td>
        <td>K013</td>
        <td>word</td>
        <td>포도</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.67</td>
        <td>0.06</td>
        <td>포도</td>
        <td>ㅍ,ㄷ</td>
        <td>ㅗ</td>
        <td></td>
        <td>ㅍ-ㅗ-ㄷ-ㅗ</td>
        <td>ㅍ,ㅗ,ㄷ</td>
        <td>ㅍ→ㅗ,ㅗ→ㄷ,ㄷ→ㅗ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>bilabial closure → rounded vowel → alveolar → rounded vowel</td>
        <td>bilabial closure,rounded vowel,alveolar</td>
        <td>bilabial closure→rounded vowel,rounded vowel→alveolar,alveolar→rounded vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㅍ:bilabial closure,ㅗ:rounded vowel,ㄷ:alveolar,ㅗ:rounded vowel</td>
        <td>ㅍ:bilabial closure→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄷ:alveolar,ㄷ:alveolar→ㅗ:rounded vowel</td>
        <td>0.06</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.16666666666666700</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.017688172043010800</td>
        <td>0.053672316384180800</td>
        <td>0.020985469860484000</td>
        <td>0.010752688172043000</td>
        <td>0.026400256780613100</td>
        <td>0.08010793490176240</td>
        <td>0.0313215968066926</td>
      </tr>
      <tr>
        <td class="line-num">14</td>
        <td>K014</td>
        <td>word</td>
        <td>차표</td>
        <td>2</td>
        <td>0.7</td>
        <td>0.77</td>
        <td>0.06</td>
        <td>차표</td>
        <td>ㅊ,ㅍ</td>
        <td>ㅏ,ㅛ</td>
        <td></td>
        <td>ㅊ-ㅏ-ㅍ-ㅛ</td>
        <td>ㅊ,ㅏ,ㅍ,ㅛ</td>
        <td>ㅊ→ㅏ,ㅏ→ㅍ,ㅍ→ㅛ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>affricate → open vowel → bilabial closure → rounded vowel</td>
        <td>affricate,open vowel,bilabial closure,rounded vowel</td>
        <td>affricate→open vowel,open vowel→bilabial closure,bilabial closure→rounded vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㅊ:affricate,ㅏ:open vowel,ㅍ:bilabial closure,ㅛ:rounded vowel</td>
        <td>ㅊ:affricate→ㅏ:open vowel,ㅏ:open vowel→ㅍ:bilabial closure,ㅍ:bilabial closure→ㅛ:rounded vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.022688172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.025184960784060100</td>
        <td>0.010752688172043000</td>
        <td>0.029465158497416600</td>
        <td>0.08413432142245700</td>
        <td>0.03270774127800010</td>
      </tr>
      <tr>
        <td class="line-num">15</td>
        <td>K015</td>
        <td>word</td>
        <td>커피</td>
        <td>2</td>
        <td>0.7</td>
        <td>0.7</td>
        <td>0.1</td>
        <td>커피</td>
        <td>ㅋ,ㅍ</td>
        <td>ㅓ,ㅣ</td>
        <td></td>
        <td>ㅋ-ㅓ-ㅍ-ㅣ</td>
        <td>ㅋ,ㅓ,ㅍ,ㅣ</td>
        <td>ㅋ→ㅓ,ㅓ→ㅍ,ㅍ→ㅣ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>low-visibility velar → open-mid vowel → bilabial closure → spread vowel</td>
        <td>low-visibility velar,open-mid vowel,bilabial closure,spread vowel</td>
        <td>low-visibility velar→open-mid vowel,open-mid vowel→bilabial closure,bilabial closure→spread vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㅋ:low-visibility velar,ㅓ:open-mid vowel,ㅍ:bilabial closure,ㅣ:spread vowel</td>
        <td>ㅋ:low-visibility velar→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㅍ:bilabial closure,ㅍ:bilabial closure→ㅣ:spread vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.022688172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.025184960784060100</td>
        <td>0.010752688172043000</td>
        <td>0.03241167434715820</td>
        <td>0.09254775356470270</td>
        <td>0.03597851540580010</td>
      </tr>
      <tr>
        <td class="line-num">16</td>
        <td>K016</td>
        <td>word</td>
        <td>나무</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.5</td>
        <td>0.1</td>
        <td>나무</td>
        <td>ㄴ,ㅁ</td>
        <td>ㅏ,ㅜ</td>
        <td></td>
        <td>ㄴ-ㅏ-ㅁ-ㅜ</td>
        <td>ㄴ,ㅏ,ㅁ,ㅜ</td>
        <td>ㄴ→ㅏ,ㅏ→ㅁ,ㅁ→ㅜ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>alveolar → open vowel → bilabial closure → rounded/protruded vowel</td>
        <td>alveolar,open vowel,bilabial closure,rounded/protruded vowel</td>
        <td>alveolar→open vowel,open vowel→bilabial closure,bilabial closure→rounded/protruded vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㄴ:alveolar,ㅏ:open vowel,ㅁ:bilabial closure,ㅜ:rounded/protruded vowel</td>
        <td>ㄴ:alveolar→ㅏ:open vowel,ㅏ:open vowel→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅜ:rounded/protruded vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.022688172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.025184960784060100</td>
        <td>0.010752688172043000</td>
        <td>0.04537634408602150</td>
        <td>0.12956685499058400</td>
        <td>0.050369921568120200</td>
      </tr>
      <tr>
        <td class="line-num">17</td>
        <td>K017</td>
        <td>word</td>
        <td>마음</td>
        <td>2</td>
        <td>0.5</td>
        <td>0.5</td>
        <td>0.0</td>
        <td>마음</td>
        <td>ㅁ,ㅇ</td>
        <td>ㅏ,ㅡ</td>
        <td>ㅁ</td>
        <td>ㅁ-ㅏ-ㅇ-ㅡ-ㅁ</td>
        <td>ㅁ,ㅏ,ㅇ,ㅡ</td>
        <td>ㅁ→ㅏ,ㅏ→ㅇ,ㅇ→ㅡ,ㅡ→ㅁ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>bilabial closure → open vowel → null/velar onset → neutral/unrounded vowel → bilabial nasal coda</td>
        <td>bilabial closure,open vowel,null/velar onset,neutral/unrounded vowel,bilabial nasal coda</td>
        <td>bilabial closure→open vowel,open vowel→null/velar onset,null/velar onset→neutral/unrounded vowel,neutral/unrounded vowel→bilabial nasal coda</td>
        <td>양순음에서 입술 폐쇄가 나타남; 개방 모음에서 입이 크게 열림; 다양한 viseme 전환을 포함</td>
        <td>ㅁ:bilabial closure,ㅏ:open vowel,ㅇ:null/velar onset,ㅡ:neutral/unrounded vowel,ㅁ:bilabial nasal coda</td>
        <td>ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㅁ:bilabial nasal coda</td>
        <td>0.08</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.2777777777777780</td>
        <td>0.03389830508474580</td>
        <td>0.016736401673640200</td>
        <td>0.04631150211795370</td>
        <td>0.08267419962335220</td>
        <td>0.042314937400509700</td>
        <td>0.014336917562724000</td>
        <td>0.09262300423590750</td>
        <td>0.16534839924670400</td>
        <td>0.08462987480101940</td>
      </tr>
      <tr>
        <td class="line-num">18</td>
        <td>K018</td>
        <td>word</td>
        <td>안녕</td>
        <td>2</td>
        <td>0.5</td>
        <td>0.6</td>
        <td>0.1</td>
        <td>안녕</td>
        <td>ㅇ,ㄴ</td>
        <td>ㅏ,ㅕ</td>
        <td>ㄴ,ㅇ</td>
        <td>ㅇ-ㅏ-ㄴ-ㄴ-ㅕ-ㅇ</td>
        <td>ㅇ,ㅏ,ㄴ,ㅕ</td>
        <td>ㅇ→ㅏ,ㅏ→ㄴ,ㄴ→ㄴ,ㄴ→ㅕ,ㅕ→ㅇ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → open vowel → low-visibility coda → alveolar → open-mid vowel → low-visibility coda</td>
        <td>null/velar onset,open vowel,low-visibility coda,alveolar,open-mid vowel</td>
        <td>null/velar onset→open vowel,open vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open-mid vowel,open-mid vowel→low-visibility coda</td>
        <td>개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅏ:open vowel,ㄴ:low-visibility coda,ㄴ:alveolar,ㅕ:open-mid vowel,ㅇ:low-visibility coda</td>
        <td>ㅇ:null/velar onset→ㅏ:open vowel,ㅏ:open vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㄴ:alveolar,ㄴ:alveolar→ㅕ:open-mid vowel,ㅕ:open-mid vowel→ㅇ:low-visibility coda</td>
        <td>0.08</td>
        <td>0.18181818181818200</td>
        <td>0.0</td>
        <td>0.2777777777777780</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.06993483219289670</td>
        <td>0.08945386064030130</td>
        <td>0.05546770504270960</td>
        <td>0.017921146953405000</td>
        <td>0.11655805365482800</td>
        <td>0.14908976773383600</td>
        <td>0.09244617507118270</td>
      </tr>
      <tr>
        <td class="line-num">19</td>
        <td>K019</td>
        <td>word</td>
        <td>강물</td>
        <td>2</td>
        <td>0.7</td>
        <td>0.7</td>
        <td>0.0</td>
        <td>강물</td>
        <td>ㄱ,ㅁ</td>
        <td>ㅏ,ㅜ</td>
        <td>ㅇ,ㄹ</td>
        <td>ㄱ-ㅏ-ㅇ-ㅁ-ㅜ-ㄹ</td>
        <td>ㄱ,ㅏ,ㅇ,ㅁ,ㅜ,ㄹ</td>
        <td>ㄱ→ㅏ,ㅏ→ㅇ,ㅇ→ㅁ,ㅁ→ㅜ,ㅜ→ㄹ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>low-visibility velar → open vowel → low-visibility coda → bilabial closure → rounded/protruded vowel → low-visibility coda</td>
        <td>low-visibility velar,open vowel,low-visibility coda,bilabial closure,rounded/protruded vowel</td>
        <td>low-visibility velar→open vowel,open vowel→low-visibility coda,low-visibility coda→bilabial closure,bilabial closure→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㄱ:low-visibility velar,ㅏ:open vowel,ㅇ:low-visibility coda,ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄹ:low-visibility coda</td>
        <td>ㄱ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㅇ:low-visibility coda,ㅇ:low-visibility coda→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄹ:low-visibility coda</td>
        <td>0.12</td>
        <td>0.18181818181818200</td>
        <td>0.0</td>
        <td>0.2777777777777780</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.07993483219289670</td>
        <td>0.08945386064030130</td>
        <td>0.059024325263232700</td>
        <td>0.017921146953405000</td>
        <td>0.11419261741842400</td>
        <td>0.12779122948614500</td>
        <td>0.08432046466176100</td>
      </tr>
      <tr>
        <td class="line-num">20</td>
        <td>K020</td>
        <td>word</td>
        <td>라면</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.57</td>
        <td>0.06</td>
        <td>라면</td>
        <td>ㄹ,ㅁ</td>
        <td>ㅏ,ㅕ</td>
        <td>ㄴ</td>
        <td>ㄹ-ㅏ-ㅁ-ㅕ-ㄴ</td>
        <td>ㄹ,ㅏ,ㅁ,ㅕ,ㄴ</td>
        <td>ㄹ→ㅏ,ㅏ→ㅁ,ㅁ→ㅕ,ㅕ→ㄴ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>liquid → open vowel → bilabial closure → open-mid vowel → low-visibility coda</td>
        <td>liquid,open vowel,bilabial closure,open-mid vowel,low-visibility coda</td>
        <td>liquid→open vowel,open vowel→bilabial closure,bilabial closure→open-mid vowel,open-mid vowel→low-visibility coda</td>
        <td>양순음에서 입술 폐쇄가 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㄹ:liquid,ㅏ:open vowel,ㅁ:bilabial closure,ㅕ:open-mid vowel,ㄴ:low-visibility coda</td>
        <td>ㄹ:liquid→ㅏ:open vowel,ㅏ:open vowel→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅕ:open-mid vowel,ㅕ:open-mid vowel→ㄴ:low-visibility coda</td>
        <td>0.1</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.2777777777777780</td>
        <td>0.03389830508474580</td>
        <td>0.016736401673640200</td>
        <td>0.05131150211795370</td>
        <td>0.08267419962335220</td>
        <td>0.04468790172597980</td>
        <td>0.014336917562724000</td>
        <td>0.0900201791543048</td>
        <td>0.14504245547956500</td>
        <td>0.07839982758943830</td>
      </tr>
      <tr>
        <td class="line-num">21</td>
        <td>K021</td>
        <td>word</td>
        <td>노래</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.53</td>
        <td>0.06</td>
        <td>노래</td>
        <td>ㄴ,ㄹ</td>
        <td>ㅗ,ㅐ</td>
        <td></td>
        <td>ㄴ-ㅗ-ㄹ-ㅐ</td>
        <td>ㄴ,ㅗ,ㄹ,ㅐ</td>
        <td>ㄴ→ㅗ,ㅗ→ㄹ,ㄹ→ㅐ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>alveolar → rounded vowel → liquid → front/open-mid vowel</td>
        <td>alveolar,rounded vowel,liquid,front/open-mid vowel</td>
        <td>alveolar→rounded vowel,rounded vowel→liquid,liquid→front/open-mid vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㄴ:alveolar,ㅗ:rounded vowel,ㄹ:liquid,ㅐ:front/open-mid vowel</td>
        <td>ㄴ:alveolar→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄹ:liquid,ㄹ:liquid→ㅐ:front/open-mid vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.022688172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.025184960784060100</td>
        <td>0.010752688172043000</td>
        <td>0.04280787177926560</td>
        <td>0.1222328820665890</td>
        <td>0.04751879393218890</td>
      </tr>
      <tr>
        <td class="line-num">22</td>
        <td>K022</td>
        <td>word</td>
        <td>거리</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.57</td>
        <td>0.06</td>
        <td>거리</td>
        <td>ㄱ,ㄹ</td>
        <td>ㅓ,ㅣ</td>
        <td></td>
        <td>ㄱ-ㅓ-ㄹ-ㅣ</td>
        <td>ㄱ,ㅓ,ㄹ,ㅣ</td>
        <td>ㄱ→ㅓ,ㅓ→ㄹ,ㄹ→ㅣ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>low-visibility velar → open-mid vowel → liquid → spread vowel</td>
        <td>low-visibility velar,open-mid vowel,liquid,spread vowel</td>
        <td>low-visibility velar→open-mid vowel,open-mid vowel→liquid,liquid→spread vowel</td>
        <td>ㅣ 계열에서 입술이 옆으로 벌어짐; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㄱ:low-visibility velar,ㅓ:open-mid vowel,ㄹ:liquid,ㅣ:spread vowel</td>
        <td>ㄱ:low-visibility velar→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄹ:liquid,ㄹ:liquid→ㅣ:spread vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.022688172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.025184960784060100</td>
        <td>0.010752688172043000</td>
        <td>0.03980381060177330</td>
        <td>0.11365513595665200</td>
        <td>0.044184141726421200</td>
      </tr>
      <tr>
        <td class="line-num">23</td>
        <td>K023</td>
        <td>word</td>
        <td>국물</td>
        <td>2</td>
        <td>0.7</td>
        <td>0.6</td>
        <td>0.1</td>
        <td>궁물</td>
        <td>ㄱ,ㅁ</td>
        <td>ㅜ</td>
        <td>ㅇ,ㄹ</td>
        <td>ㄱ-ㅜ-ㅇ-ㅁ-ㅜ-ㄹ</td>
        <td>ㄱ,ㅜ,ㅇ,ㅁ,ㄹ</td>
        <td>ㄱ→ㅜ,ㅜ→ㅇ,ㅇ→ㅁ,ㅁ→ㅜ,ㅜ→ㄹ</td>
        <td></td>
        <td>nasal_assimilation</td>
        <td>1.0</td>
        <td>low-visibility velar → rounded/protruded vowel → low-visibility coda → bilabial closure → rounded/protruded vowel → low-visibility coda</td>
        <td>low-visibility velar,rounded/protruded vowel,low-visibility coda,bilabial closure</td>
        <td>low-visibility velar→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,low-visibility coda→bilabial closure,bilabial closure→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㄱ:low-visibility velar,ㅜ:rounded/protruded vowel,ㅇ:low-visibility coda,ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄹ:low-visibility coda</td>
        <td>ㄱ:low-visibility velar→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㅇ:low-visibility coda,ㅇ:low-visibility coda→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄹ:low-visibility coda</td>
        <td>0.1</td>
        <td>0.18181818181818200</td>
        <td>0.125</td>
        <td>0.2222222222222220</td>
        <td>0.03389830508474580</td>
        <td>0.02092050209205020</td>
        <td>0.10618483219289700</td>
        <td>0.07156308851224110</td>
        <td>0.05966948697657320</td>
        <td>0.017921146953405000</td>
        <td>0.17697472032149500</td>
        <td>0.11927181418706800</td>
        <td>0.09944914496095530</td>
      </tr>
      <tr>
        <td class="line-num">24</td>
        <td>K024</td>
        <td>word</td>
        <td>신라</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.6</td>
        <td>0.0</td>
        <td>실라</td>
        <td>ㅅ,ㄹ</td>
        <td>ㅣ,ㅏ</td>
        <td>ㄹ</td>
        <td>ㅅ-ㅣ-ㄹ-ㄹ-ㅏ</td>
        <td>ㅅ,ㅣ,ㄹ,ㄹ,ㅏ</td>
        <td>ㅅ→ㅣ,ㅣ→ㄹ,ㄹ→ㄹ,ㄹ→ㅏ</td>
        <td></td>
        <td>liquid_assimilation</td>
        <td>1.0</td>
        <td>fricative → spread vowel → low-visibility coda → liquid → open vowel</td>
        <td>fricative,spread vowel,low-visibility coda,liquid,open vowel</td>
        <td>fricative→spread vowel,spread vowel→low-visibility coda,low-visibility coda→liquid,liquid→open vowel</td>
        <td>ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅅ:fricative,ㅣ:spread vowel,ㄹ:low-visibility coda,ㄹ:liquid,ㅏ:open vowel</td>
        <td>ㅅ:fricative→ㅣ:spread vowel,ㅣ:spread vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄹ:liquid,ㄹ:liquid→ㅏ:open vowel</td>
        <td>0.08</td>
        <td>0.09090909090909090</td>
        <td>0.125</td>
        <td>0.2777777777777780</td>
        <td>0.03389830508474580</td>
        <td>0.016736401673640200</td>
        <td>0.07756150211795370</td>
        <td>0.08267419962335220</td>
        <td>0.054716328397782800</td>
        <td>0.014336917562724000</td>
        <td>0.12926917019659000</td>
        <td>0.13779033270558700</td>
        <td>0.09119388066297140</td>
      </tr>
      <tr>
        <td class="line-num">25</td>
        <td>K025</td>
        <td>word</td>
        <td>같이</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.53</td>
        <td>0.06</td>
        <td>가치</td>
        <td>ㄱ,ㅊ</td>
        <td>ㅏ,ㅣ</td>
        <td></td>
        <td>ㄱ-ㅏ-ㅊ-ㅣ</td>
        <td>ㄱ,ㅏ,ㅊ,ㅣ</td>
        <td>ㄱ→ㅏ,ㅏ→ㅊ,ㅊ→ㅇ,ㅇ→ㅣ</td>
        <td></td>
        <td>palatalization</td>
        <td>1.0</td>
        <td>low-visibility velar → open vowel → affricate → spread vowel</td>
        <td>low-visibility velar,open vowel,affricate,spread vowel</td>
        <td>low-visibility velar→open vowel,open vowel→affricate,affricate→spread vowel</td>
        <td>ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㄱ:low-visibility velar,ㅏ:open vowel,ㅊ:affricate,ㅣ:spread vowel</td>
        <td>ㄱ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㅊ:affricate,ㅊ:affricate→ㅣ:spread vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.125</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.05483422939068100</td>
        <td>0.06478342749529190</td>
        <td>0.040657957235581000</td>
        <td>0.014336917562724000</td>
        <td>0.10346081017109600</td>
        <td>0.1222328820665890</td>
        <td>0.07671312685958690</td>
      </tr>
      <tr>
        <td class="line-num">26</td>
        <td>K026</td>
        <td>word</td>
        <td>학교</td>
        <td>2</td>
        <td>0.7</td>
        <td>0.63</td>
        <td>0.06</td>
        <td>학꾜</td>
        <td>ㅎ,ㄲ</td>
        <td>ㅏ,ㅛ</td>
        <td>ㄱ</td>
        <td>ㅎ-ㅏ-ㄲ-ㅛ</td>
        <td>ㅎ,ㅏ,ㄲ,ㅛ</td>
        <td>ㅎ→ㅏ,ㅏ→ㄱ,ㄱ→ㄲ,ㄲ→ㅛ</td>
        <td></td>
        <td>tensification</td>
        <td>1.0</td>
        <td>glottal → open vowel → low-visibility coda → low-visibility velar → rounded vowel</td>
        <td>glottal,open vowel,low-visibility coda,low-visibility velar,rounded vowel</td>
        <td>glottal→open vowel,open vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→rounded vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅎ:glottal,ㅏ:open vowel,ㄱ:low-visibility coda,ㄲ:low-visibility velar,ㅛ:rounded vowel</td>
        <td>ㅎ:glottal→ㅏ:open vowel,ㅏ:open vowel→ㄱ:low-visibility coda,ㄱ:low-visibility coda→ㄲ:low-visibility velar,ㄲ:low-visibility velar→ㅛ:rounded vowel</td>
        <td>0.08</td>
        <td>0.09090909090909090</td>
        <td>0.125</td>
        <td>0.2777777777777780</td>
        <td>0.03389830508474580</td>
        <td>0.016736401673640200</td>
        <td>0.07756150211795370</td>
        <td>0.08267419962335220</td>
        <td>0.054716328397782800</td>
        <td>0.014336917562724000</td>
        <td>0.12311349542532300</td>
        <td>0.1312288882910350</td>
        <td>0.08685131491711560</td>
      </tr>
      <tr>
        <td class="line-num">27</td>
        <td>K027</td>
        <td>word</td>
        <td>좋다</td>
        <td>2</td>
        <td>0.8</td>
        <td>0.73</td>
        <td>0.06</td>
        <td>조타</td>
        <td>ㅈ,ㅌ</td>
        <td>ㅗ,ㅏ</td>
        <td></td>
        <td>ㅈ-ㅗ-ㅌ-ㅏ</td>
        <td>ㅈ,ㅗ,ㅌ,ㅏ</td>
        <td>ㅈ→ㅗ,ㅗ→ㅌ,ㅌ→ㅏ</td>
        <td></td>
        <td>aspiration</td>
        <td>1.0</td>
        <td>affricate → rounded vowel → alveolar → open vowel</td>
        <td>affricate,rounded vowel,alveolar,open vowel</td>
        <td>affricate→rounded vowel,rounded vowel→alveolar,alveolar→open vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㅈ:affricate,ㅗ:rounded vowel,ㅌ:alveolar,ㅏ:open vowel</td>
        <td>ㅈ:affricate→ㅗ:rounded vowel,ㅗ:rounded vowel→ㅌ:alveolar,ㅌ:alveolar→ㅏ:open vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.125</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.053938172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.04034018213979370</td>
        <td>0.010752688172043000</td>
        <td>0.07388790690823390</td>
        <td>0.08874442122642730</td>
        <td>0.055260523479169400</td>
      </tr>
      <tr>
        <td class="line-num">28</td>
        <td>K028</td>
        <td>word</td>
        <td>옷이</td>
        <td>2</td>
        <td>0.5</td>
        <td>0.6</td>
        <td>0.1</td>
        <td>오시</td>
        <td>ㅇ, ㅅ</td>
        <td>ㅗ,ㅣ</td>
        <td></td>
        <td>ㅇ-ㅗ-ㅅ-ㅣ</td>
        <td>ㅇ,ㅗ,ㅅ,ㅣ</td>
        <td>ㅇ→ㅗ,ㅗ→ㅅ,ㅅ→ㅣ</td>
        <td></td>
        <td>resyllabification</td>
        <td>1.0</td>
        <td>null/velar onset → rounded vowel → fricative → spread vowel</td>
        <td>null/velar onset,rounded vowel,fricative,spread vowel</td>
        <td>null/velar onset→rounded vowel,rounded vowel→fricative,fricative→spread vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㅇ:null/velar onset,ㅗ:rounded vowel,ㅅ:fricative,ㅣ:spread vowel</td>
        <td>ㅇ:null/velar onset→ㅗ:rounded vowel,ㅗ:rounded vowel→ㅅ:fricative,ㅅ:fricative→ㅣ:spread vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.125</td>
        <td>0.2222222222222220</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.053938172043010800</td>
        <td>0.06478342749529190</td>
        <td>0.04034018213979370</td>
        <td>0.010752688172043000</td>
        <td>0.08989695340501790</td>
        <td>0.10797237915882000</td>
        <td>0.06723363689965610</td>
      </tr>
      <tr>
        <td class="line-num">29</td>
        <td>K029</td>
        <td>word</td>
        <td>앞문</td>
        <td>2</td>
        <td>0.8</td>
        <td>0.7</td>
        <td>0.1</td>
        <td>암문</td>
        <td>ㅇ,ㅁ</td>
        <td>ㅏ,ㅜ</td>
        <td>ㅁ, ㄴ</td>
        <td>ㅇ-ㅏ-ㅁ-ㅁ-ㅜ-ㄴ</td>
        <td>ㅇ,ㅏ,ㅁ,ㅁ,ㅜ,ㄴ</td>
        <td>ㅇ→ㅏ,ㅏ→ㅁ,ㅁ→ㅁ,ㅁ→ㅜ,ㅜ→ㄴ</td>
        <td></td>
        <td>nasal_assimilation</td>
        <td>1.0</td>
        <td>null/velar onset → open vowel → bilabial nasal coda → bilabial closure → rounded/protruded vowel → low-visibility coda</td>
        <td>null/velar onset,open vowel,bilabial nasal coda,bilabial closure,rounded/protruded vowel,low-visibility coda</td>
        <td>null/velar onset→open vowel,open vowel→bilabial nasal coda,bilabial nasal coda→bilabial closure,bilabial closure→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅏ:open vowel,ㅁ:bilabial nasal coda,ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄴ:low-visibility coda</td>
        <td>ㅇ:null/velar onset→ㅏ:open vowel,ㅏ:open vowel→ㅁ:bilabial nasal coda,ㅁ:bilabial nasal coda→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄴ:low-visibility coda</td>
        <td>0.1</td>
        <td>0.18181818181818200</td>
        <td>0.125</td>
        <td>0.3333333333333330</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.10618483219289700</td>
        <td>0.10056497175141200</td>
        <td>0.07034731141217580</td>
        <td>0.017921146953405000</td>
        <td>0.15169261741842400</td>
        <td>0.14366424535916100</td>
        <td>0.10049615916025100</td>
      </tr>
      <tr>
        <td class="line-num">30</td>
        <td>K030</td>
        <td>word</td>
        <td>꽃말</td>
        <td>2</td>
        <td>0.8</td>
        <td>0.67</td>
        <td>0.12</td>
        <td>꼰말</td>
        <td>ㄲ,ㅁ</td>
        <td>ㅗ,ㅏ</td>
        <td>ㄴ, ㄹ</td>
        <td>ㄲ-ㅗ-ㄴ-ㅁ-ㅏ-ㄹ</td>
        <td>ㄲ,ㅗ,ㄴ,ㅁ,ㅏ,ㄹ</td>
        <td>ㄲ→ㅗ,ㅗ→ㄴ,ㄴ→ㅁ,ㅁ→ㅏ,ㅏ→ㄹ</td>
        <td></td>
        <td>nasal_assimilation</td>
        <td>1.0</td>
        <td>low-visibility velar → rounded vowel → low-visibility coda → bilabial closure → open vowel → low-visibility coda</td>
        <td>low-visibility velar,rounded vowel,low-visibility coda,bilabial closure,open vowel</td>
        <td>low-visibility velar→rounded vowel,rounded vowel→low-visibility coda,low-visibility coda→bilabial closure,bilabial closure→open vowel,open vowel→low-visibility coda</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㄲ:low-visibility velar,ㅗ:rounded vowel,ㄴ:low-visibility coda,ㅁ:bilabial closure,ㅏ:open vowel,ㄹ:low-visibility coda</td>
        <td>ㄲ:low-visibility velar→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄹ:low-visibility coda</td>
        <td>0.12</td>
        <td>0.18181818181818200</td>
        <td>0.125</td>
        <td>0.2777777777777780</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.11118483219289700</td>
        <td>0.08945386064030130</td>
        <td>0.06785370793302930</td>
        <td>0.017921146953405000</td>
        <td>0.16594751073566700</td>
        <td>0.13351322483627100</td>
        <td>0.10127419094482000</td>
      </tr>
      <tr>
        <td class="line-num">31</td>
        <td>K031</td>
        <td>word</td>
        <td>먹는</td>
        <td>2</td>
        <td>0.7</td>
        <td>0.63</td>
        <td>0.06</td>
        <td>멍는</td>
        <td>ㅁ,ㄴ</td>
        <td>ㅓ,ㅡ</td>
        <td>ㄱ,ㄴ</td>
        <td>ㅁ-ㅓ-ㄱ-ㄴ-ㅡ-ㄴ</td>
        <td>ㅁ,ㅓ,ㄱ,ㄴ,ㅡ</td>
        <td>ㅁ→ㅓ,ㅓ→ㄱ,ㄱ→ㄴ,ㄴ→ㅡ,ㅡ→ㄴ</td>
        <td></td>
        <td>nasal_assimilation</td>
        <td>1.0</td>
        <td>bilabial closure → open-mid vowel → low-visibility coda → alveolar → neutral/unrounded vowel → low-visibility coda</td>
        <td>bilabial closure,open-mid vowel,low-visibility coda,alveolar,neutral/unrounded vowel</td>
        <td>bilabial closure→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda</td>
        <td>양순음에서 입술 폐쇄가 나타남; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅁ:bilabial closure,ㅓ:open-mid vowel,ㅇ:low-visibility coda,ㄴ:alveolar,ㅡ:neutral/unrounded vowel,ㄴ:low-visibility coda</td>
        <td>ㅁ:bilabial closure→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㅇ:low-visibility coda,ㅇ:low-visibility coda→ㄴ:alveolar,ㄴ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄴ:low-visibility coda</td>
        <td>0.1</td>
        <td>0.18181818181818200</td>
        <td>0.125</td>
        <td>0.2777777777777780</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.10618483219289700</td>
        <td>0.08945386064030130</td>
        <td>0.06663055717147070</td>
        <td>0.017921146953405000</td>
        <td>0.16854735268713800</td>
        <td>0.14199025498460500</td>
        <td>0.10576278916106500</td>
      </tr>
      <tr>
        <td class="line-num">32</td>
        <td>K032</td>
        <td>word</td>
        <td>닫는</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.53</td>
        <td>0.06</td>
        <td>단는</td>
        <td>ㄷ,ㄴ</td>
        <td>ㅏ,ㅡ</td>
        <td>ㄴ</td>
        <td>ㄷ-ㅏ-ㄴ-ㄴ-ㅡ-ㄴ</td>
        <td>ㄷ,ㅏ,ㄴ,ㅡ</td>
        <td>ㄷ→ㅏ,ㅏ→ㄴ,ㄴ→ㄴ,ㄴ→ㅡ,ㅡ→ㄴ</td>
        <td></td>
        <td>nasal_assimilation</td>
        <td>1.0</td>
        <td>alveolar → open vowel → low-visibility coda → alveolar → neutral/unrounded vowel → low-visibility coda</td>
        <td>alveolar,open vowel,low-visibility coda,neutral/unrounded vowel</td>
        <td>alveolar→open vowel,open vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda</td>
        <td>개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㄷ:alveolar,ㅏ:open vowel,ㄴ:low-visibility coda,ㄴ:alveolar,ㅡ:neutral/unrounded vowel,ㄴ:low-visibility coda</td>
        <td>ㄷ:alveolar→ㅏ:open vowel,ㅏ:open vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㄴ:alveolar,ㄴ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄴ:low-visibility coda</td>
        <td>0.08</td>
        <td>0.09090909090909090</td>
        <td>0.125</td>
        <td>0.2222222222222220</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.07845755946562400</td>
        <td>0.07834274952919020</td>
        <td>0.055408265315950700</td>
        <td>0.017921146953405000</td>
        <td>0.14803313106721500</td>
        <td>0.1478165085456420</td>
        <td>0.10454389682254900</td>
      </tr>
      <tr>
        <td class="line-num">33</td>
        <td>K033</td>
        <td>word</td>
        <td>설날</td>
        <td>2</td>
        <td>0.6</td>
        <td>0.57</td>
        <td>0.06</td>
        <td>설랄</td>
        <td>ㅅ,ㄹ</td>
        <td>ㅓ,ㅏ</td>
        <td>ㄹ</td>
        <td>ㅅ-ㅓ-ㄹ-ㄹ-ㅏ-ㄹ</td>
        <td>ㅅ,ㅓ,ㄹ,ㄹ,ㅏ</td>
        <td>ㅅ→ㅓ,ㅓ→ㄹ,ㄹ→ㄹ,ㄹ→ㅏ,ㅏ→ㄹ</td>
        <td></td>
        <td>liquid_assimilation</td>
        <td>1.0</td>
        <td>fricative → open-mid vowel → low-visibility coda → liquid → open vowel → low-visibility coda</td>
        <td>fricative,open-mid vowel,low-visibility coda,liquid,open vowel</td>
        <td>fricative→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→liquid,liquid→open vowel,open vowel→low-visibility coda</td>
        <td>개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅅ:fricative,ㅓ:open-mid vowel,ㄹ:low-visibility coda,ㄹ:liquid,ㅏ:open vowel,ㄹ:low-visibility coda</td>
        <td>ㅅ:fricative→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄹ:liquid,ㄹ:liquid→ㅏ:open vowel,ㅏ:open vowel→ㄹ:low-visibility coda</td>
        <td>0.08</td>
        <td>0.09090909090909090</td>
        <td>0.125</td>
        <td>0.2777777777777780</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.07845755946562400</td>
        <td>0.08945386064030130</td>
        <td>0.05852558382990380</td>
        <td>0.017921146953405000</td>
        <td>0.13764484116776100</td>
        <td>0.15693659761456400</td>
        <td>0.10267646285948000</td>
      </tr>
      <tr>
        <td class="line-num">34</td>
        <td>K034</td>
        <td>word</td>
        <td>색연필</td>
        <td>3</td>
        <td>1.5</td>
        <td>0.93</td>
        <td>0.49</td>
        <td>생년필</td>
        <td>ㅅ,ㄴ,ㅍ</td>
        <td>ㅐ,ㅕ,ㅣ</td>
        <td>ㅇ, ㄴ, ㄹ</td>
        <td>ㅅ-ㅐ-ㅇ-ㄴ-ㅕ-ㄴ-ㅍ-ㅣ-ㄹ</td>
        <td>ㅅ,ㅐ,ㄱ,ㄴ,ㅕ,ㄴ,ㅍ,ㅣ,ㄹ</td>
        <td>ㅅ→ㅐ,ㅐ→ㅇ,ㅇ→ㄴ,ㄴ→ㅕ,ㅕ→ㄴ,ㄴ→ㅍ,ㅍ→ㅣ,ㅣ→ㄹ</td>
        <td></td>
        <td>nasal_assimilation</td>
        <td>1.0</td>
        <td>fricative → front/open-mid vowel → low-visibility coda → alveolar → open-mid vowel → low-visibility coda → bilabial closure → spread vowel → low-visibility coda</td>
        <td>fricative,front/open-mid vowel,low-visibility coda,alveolar,open-mid vowel,bilabial closure,spread vowel</td>
        <td>fricative→front/open-mid vowel,front/open-mid vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→bilabial closure,bilabial closure→spread vowel,spread vowel→low-visibility coda</td>
        <td>양순음에서 입술 폐쇄가 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅅ:fricative,ㅐ:front/open-mid vowel,ㅇ:low-visibility coda,ㄴ:alveolar,ㅕ:open-mid vowel,ㄴ:low-visibility coda,ㅍ:bilabial closure,ㅣ:spread vowel,ㄹ:low-visibility coda</td>
        <td>ㅅ:fricative→ㅐ:front/open-mid vowel,ㅐ:front/open-mid vowel→ㅇ:low-visibility coda,ㅇ:low-visibility coda→ㄴ:alveolar,ㄴ:alveolar→ㅕ:open-mid vowel,ㅕ:open-mid vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㅍ:bilabial closure,ㅍ:bilabial closure→ㅣ:spread vowel,ㅣ:spread vowel→ㄹ:low-visibility coda</td>
        <td>0.16</td>
        <td>0.2727272727272730</td>
        <td>0.125</td>
        <td>0.3888888888888890</td>
        <td>0.06779661016949150</td>
        <td>0.03347280334728030</td>
        <td>0.1466002769631800</td>
        <td>0.132015065913371</td>
        <td>0.09674466521572560</td>
        <td>0.02867383512544800</td>
        <td>0.1576347064120220</td>
        <td>0.14195168377781800</td>
        <td>0.1040265217373390</td>
      </tr>
      <tr>
        <td class="line-num">35</td>
        <td>K035</td>
        <td>word</td>
        <td>독립</td>
        <td>2</td>
        <td>0.8</td>
        <td>0.67</td>
        <td>0.12</td>
        <td>동닙</td>
        <td>ㄷ,ㄴ</td>
        <td>ㅗ,ㅣ</td>
        <td>ㅇ, ㅂ</td>
        <td>ㄷ-ㅗ-ㅇ-ㄴ-ㅣ-ㅂ</td>
        <td>ㄷ,ㅗ,ㅇ,ㄴ,ㅣ,ㅂ</td>
        <td>ㄷ→ㅗ,ㅗ→ㅇ,ㅇ→ㄴ,ㄴ→ㅣ,ㅣ→ㅂ</td>
        <td></td>
        <td>nasal_assimilation</td>
        <td>1.0</td>
        <td>alveolar → rounded vowel → low-visibility coda → alveolar → spread vowel → bilabial coda closure</td>
        <td>alveolar,rounded vowel,low-visibility coda,spread vowel,bilabial coda closure</td>
        <td>alveolar→rounded vowel,rounded vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→spread vowel,spread vowel→bilabial coda closure</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㄷ:alveolar,ㅗ:rounded vowel,ㅇ:low-visibility coda,ㄴ:alveolar,ㅣ:spread vowel,ㅂ:bilabial coda closure</td>
        <td>ㄷ:alveolar→ㅗ:rounded vowel,ㅗ:rounded vowel→ㅇ:low-visibility coda,ㅇ:low-visibility coda→ㄴ:alveolar,ㄴ:alveolar→ㅣ:spread vowel,ㅣ:spread vowel→ㅂ:bilabial coda closure</td>
        <td>0.12</td>
        <td>0.18181818181818200</td>
        <td>0.125</td>
        <td>0.2777777777777780</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.11118483219289700</td>
        <td>0.08945386064030130</td>
        <td>0.06785370793302930</td>
        <td>0.017921146953405000</td>
        <td>0.16594751073566700</td>
        <td>0.13351322483627100</td>
        <td>0.10127419094482000</td>
      </tr>
      <tr>
        <td class="line-num">36</td>
        <td>K036</td>
        <td>word</td>
        <td>아이</td>
        <td>2</td>
        <td>0.4</td>
        <td>0.47</td>
        <td>0.06</td>
        <td>아이</td>
        <td>ㅇ</td>
        <td>ㅏ,ㅣ</td>
        <td></td>
        <td>ㅇ-ㅏ-ㅇ-ㅣ</td>
        <td>ㅇ,ㅏ,ㅣ</td>
        <td>ㅇ→ㅏ,ㅏ→ㅇ,ㅇ→ㅣ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → open vowel → null/velar onset → spread vowel</td>
        <td>null/velar onset,open vowel,spread vowel</td>
        <td>null/velar onset→open vowel,open vowel→null/velar onset,null/velar onset→spread vowel</td>
        <td>ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림</td>
        <td>ㅇ:null/velar onset,ㅏ:open vowel,ㅇ:null/velar onset,ㅣ:spread vowel</td>
        <td>ㅇ:null/velar onset→ㅏ:open vowel,ㅏ:open vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅣ:spread vowel</td>
        <td>0.06</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.16666666666666700</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.017688172043010800</td>
        <td>0.053672316384180800</td>
        <td>0.020985469860484000</td>
        <td>0.010752688172043000</td>
        <td>0.03763440860215050</td>
        <td>0.11419641783868300</td>
        <td>0.04464993587337030</td>
      </tr>
      <tr>
        <td class="line-num">37</td>
        <td>K037</td>
        <td>word</td>
        <td>오이</td>
        <td>2</td>
        <td>0.4</td>
        <td>0.5</td>
        <td>0.1</td>
        <td>오이</td>
        <td>ㅇ</td>
        <td>ㅗ,ㅣ</td>
        <td></td>
        <td>ㅇ-ㅗ-ㅇ-ㅣ</td>
        <td>ㅇ,ㅗ,ㅣ</td>
        <td>ㅇ→ㅗ,ㅗ→ㅇ,ㅇ→ㅣ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → rounded vowel → null/velar onset → spread vowel</td>
        <td>null/velar onset,rounded vowel,spread vowel</td>
        <td>null/velar onset→rounded vowel,rounded vowel→null/velar onset,null/velar onset→spread vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐</td>
        <td>ㅇ:null/velar onset,ㅗ:rounded vowel,ㅇ:null/velar onset,ㅣ:spread vowel</td>
        <td>ㅇ:null/velar onset→ㅗ:rounded vowel,ㅗ:rounded vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅣ:spread vowel</td>
        <td>0.06</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.16666666666666700</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.017688172043010800</td>
        <td>0.053672316384180800</td>
        <td>0.020985469860484000</td>
        <td>0.010752688172043000</td>
        <td>0.035376344086021500</td>
        <td>0.10734463276836200</td>
        <td>0.04197093972096810</td>
      </tr>
      <tr>
        <td class="line-num">38</td>
        <td>K038</td>
        <td>word</td>
        <td>우유</td>
        <td>2</td>
        <td>0.4</td>
        <td>0.5</td>
        <td>0.1</td>
        <td>우유</td>
        <td>ㅇ</td>
        <td>ㅜ,ㅠ</td>
        <td></td>
        <td>ㅇ-ㅜ-ㅇ-ㅠ</td>
        <td>ㅇ,ㅜ,ㅠ</td>
        <td>ㅇ→ㅜ,ㅜ→ㅇ,ㅇ→ㅠ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → rounded/protruded vowel → null/velar onset → rounded/protruded vowel</td>
        <td>null/velar onset,rounded/protruded vowel</td>
        <td>null/velar onset→rounded/protruded vowel,rounded/protruded vowel→null/velar onset,null/velar onset→rounded/protruded vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남</td>
        <td>ㅇ:null/velar onset,ㅜ:rounded/protruded vowel,ㅇ:null/velar onset,ㅠ:rounded/protruded vowel</td>
        <td>ㅇ:null/velar onset→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅠ:rounded/protruded vowel</td>
        <td>0.06</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.1111111111111110</td>
        <td>0.01694915254237290</td>
        <td>0.012552301255230100</td>
        <td>0.017688172043010800</td>
        <td>0.035781544256120500</td>
        <td>0.019225072748380500</td>
        <td>0.010752688172043000</td>
        <td>0.035376344086021500</td>
        <td>0.07156308851224110</td>
        <td>0.038450145496761100</td>
      </tr>
      <tr>
        <td class="line-num">39</td>
        <td>K039</td>
        <td>word</td>
        <td>여우</td>
        <td>2</td>
        <td>0.5</td>
        <td>0.5</td>
        <td>0.0</td>
        <td>여우</td>
        <td>ㅇ</td>
        <td>ㅕ,ㅜ</td>
        <td></td>
        <td>ㅇ-ㅕ-ㅇ-ㅜ</td>
        <td>ㅇ,ㅕ,ㅜ</td>
        <td>ㅇ→ㅕ,ㅕ→ㅇ,ㅇ→ㅜ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → open-mid vowel → null/velar onset → rounded/protruded vowel</td>
        <td>null/velar onset,open-mid vowel,rounded/protruded vowel</td>
        <td>null/velar onset→open-mid vowel,open-mid vowel→null/velar onset,null/velar onset→rounded/protruded vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; 중간 개구의 모음 변화가 나타남</td>
        <td>ㅇ:null/velar onset,ㅕ:open-mid vowel,ㅇ:null/velar onset,ㅜ:rounded/protruded vowel</td>
        <td>ㅇ:null/velar onset→ㅕ:open-mid vowel,ㅕ:open-mid vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅜ:rounded/protruded vowel</td>
        <td>0.06</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.16666666666666700</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.017688172043010800</td>
        <td>0.053672316384180800</td>
        <td>0.020985469860484000</td>
        <td>0.010752688172043000</td>
        <td>0.035376344086021500</td>
        <td>0.10734463276836200</td>
        <td>0.04197093972096810</td>
      </tr>
      <tr>
        <td class="line-num">40</td>
        <td>K040</td>
        <td>word</td>
        <td>이유</td>
        <td>2</td>
        <td>0.4</td>
        <td>0.4</td>
        <td>0.0</td>
        <td>이유</td>
        <td>ㅇ</td>
        <td>ㅣ,ㅠ</td>
        <td></td>
        <td>ㅇ-ㅣ-ㅇ-ㅠ</td>
        <td>ㅇ,ㅣ,ㅠ</td>
        <td>ㅇ→ㅣ,ㅣ→ㅇ,ㅇ→ㅠ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → spread vowel → null/velar onset → rounded/protruded vowel</td>
        <td>null/velar onset,spread vowel,rounded/protruded vowel</td>
        <td>null/velar onset→spread vowel,spread vowel→null/velar onset,null/velar onset→rounded/protruded vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐</td>
        <td>ㅇ:null/velar onset,ㅣ:spread vowel,ㅇ:null/velar onset,ㅠ:rounded/protruded vowel</td>
        <td>ㅇ:null/velar onset→ㅣ:spread vowel,ㅣ:spread vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅠ:rounded/protruded vowel</td>
        <td>0.06</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.16666666666666700</td>
        <td>0.025423728813559300</td>
        <td>0.012552301255230100</td>
        <td>0.017688172043010800</td>
        <td>0.053672316384180800</td>
        <td>0.020985469860484000</td>
        <td>0.010752688172043000</td>
        <td>0.04422043010752690</td>
        <td>0.134180790960452</td>
        <td>0.05246367465121010</td>
      </tr>
      <tr>
        <td class="line-num">41</td>
        <td>K041</td>
        <td>word</td>
        <td>바구니</td>
        <td>3</td>
        <td>0.9</td>
        <td>0.8</td>
        <td>0.1</td>
        <td>바구니</td>
        <td>ㅂ,ㄱ,ㄴ</td>
        <td>ㅏ,ㅜ,ㅣ</td>
        <td></td>
        <td>ㅂ-ㅏ-ㄱ-ㅜ-ㄴ-ㅣ</td>
        <td>ㅂ,ㅏ,ㄱ,ㅜ,ㄴ,ㅣ</td>
        <td>ㅂ→ㅏ,ㅏ→ㄱ,ㄱ→ㅜ,ㅜ→ㄴ,ㄴ→ㅣ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>bilabial closure → open vowel → low-visibility velar → rounded/protruded vowel → alveolar → spread vowel</td>
        <td>bilabial closure,open vowel,low-visibility velar,rounded/protruded vowel,alveolar,spread vowel</td>
        <td>bilabial closure→open vowel,open vowel→low-visibility velar,low-visibility velar→rounded/protruded vowel,rounded/protruded vowel→alveolar,alveolar→spread vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅂ:bilabial closure,ㅏ:open vowel,ㄱ:low-visibility velar,ㅜ:rounded/protruded vowel,ㄴ:alveolar,ㅣ:spread vowel</td>
        <td>ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄴ:alveolar,ㄴ:alveolar→ㅣ:spread vowel</td>
        <td>0.12</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.3333333333333330</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.034480286738351300</td>
        <td>0.10056497175141200</td>
        <td>0.03918017167238380</td>
        <td>0.017921146953405000</td>
        <td>0.043100358422939100</td>
        <td>0.12570621468926600</td>
        <td>0.04897521459047980</td>
      </tr>
      <tr>
        <td class="line-num">42</td>
        <td>K042</td>
        <td>word</td>
        <td>고구마</td>
        <td>3</td>
        <td>0.8</td>
        <td>0.73</td>
        <td>0.06</td>
        <td>고구마</td>
        <td>ㄱ,ㅁ</td>
        <td>ㅗ,ㅜ,ㅏ</td>
        <td></td>
        <td>ㄱ-ㅗ-ㄱ-ㅜ-ㅁ-ㅏ</td>
        <td>ㄱ,ㅗ,ㅜ,ㅁ,ㅏ</td>
        <td>ㄱ→ㅗ,ㅗ→ㄱ,ㄱ→ㅜ,ㅜ→ㅁ,ㅁ→ㅏ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>low-visibility velar → rounded vowel → low-visibility velar → rounded/protruded vowel → bilabial closure → open vowel</td>
        <td>low-visibility velar,rounded vowel,rounded/protruded vowel,bilabial closure,open vowel</td>
        <td>low-visibility velar→rounded vowel,rounded vowel→low-visibility velar,low-visibility velar→rounded/protruded vowel,rounded/protruded vowel→bilabial closure,bilabial closure→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㄱ:low-visibility velar,ㅗ:rounded vowel,ㄱ:low-visibility velar,ㅜ:rounded/protruded vowel,ㅁ:bilabial closure,ㅏ:open vowel</td>
        <td>ㄱ:low-visibility velar→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅏ:open vowel</td>
        <td>0.1</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2777777777777780</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.029480286738351300</td>
        <td>0.08945386064030130</td>
        <td>0.03497578459225280</td>
        <td>0.017921146953405000</td>
        <td>0.040383954436097600</td>
        <td>0.12253953512370000</td>
        <td>0.04791203368801760</td>
      </tr>
      <tr>
        <td class="line-num">43</td>
        <td>K043</td>
        <td>word</td>
        <td>비빔밥</td>
        <td>3</td>
        <td>1.1</td>
        <td>0.97</td>
        <td>0.15</td>
        <td>비빔빱</td>
        <td>ㅂ, ㅃ</td>
        <td>ㅣ,ㅏ</td>
        <td>ㅁ,ㅂ</td>
        <td>ㅂ-ㅣ-ㅂ-ㅣ-ㅁ-ㅃ-ㅏ-ㅂ</td>
        <td>ㅂ,ㅣ,ㅁ,ㅏ</td>
        <td>ㅂ→ㅣ,ㅣ→ㅂ,ㅂ→ㅣ,ㅣ→ㅁ,ㅁ→ㅃ,ㅃ→ㅏ,ㅏ→ㅂ</td>
        <td></td>
        <td>tensification</td>
        <td>1.0</td>
        <td>bilabial closure → spread vowel → bilabial closure → spread vowel → bilabial nasal coda → bilabial closure → open vowel → bilabial coda closure</td>
        <td>bilabial closure,spread vowel,bilabial nasal coda,open vowel,bilabial coda closure</td>
        <td>bilabial closure→spread vowel,spread vowel→bilabial closure,bilabial closure→spread vowel,spread vowel→bilabial nasal coda,bilabial nasal coda→bilabial closure,bilabial closure→open vowel,open vowel→bilabial coda closure</td>
        <td>양순음에서 입술 폐쇄가 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 다양한 viseme 전환을 포함</td>
        <td>ㅂ:bilabial closure,ㅣ:spread vowel,ㅂ:bilabial closure,ㅣ:spread vowel,ㅁ:bilabial nasal coda,ㅃ:bilabial closure,ㅏ:open vowel,ㅂ:bilabial coda closure</td>
        <td>ㅂ:bilabial closure→ㅣ:spread vowel,ㅣ:spread vowel→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅣ:spread vowel,ㅣ:spread vowel→ㅁ:bilabial nasal coda,ㅁ:bilabial nasal coda→ㅃ:bilabial closure,ㅃ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅂ:bilabial coda closure</td>
        <td>0.08</td>
        <td>0.18181818181818200</td>
        <td>0.125</td>
        <td>0.2777777777777780</td>
        <td>0.05084745762711870</td>
        <td>0.02510460251046030</td>
        <td>0.10208088954056700</td>
        <td>0.09623352165725050</td>
        <td>0.06948443787672050</td>
        <td>0.021505376344086000</td>
        <td>0.10523803045419300</td>
        <td>0.09920981614149530</td>
        <td>0.07163344111002120</td>
      </tr>
      <tr>
        <td class="line-num">44</td>
        <td>K044</td>
        <td>word</td>
        <td>보리밥</td>
        <td>3</td>
        <td>0.8</td>
        <td>0.83</td>
        <td>0.06</td>
        <td>보리밥</td>
        <td>ㅂ,ㄹ</td>
        <td>ㅗ,ㅣ,ㅏ</td>
        <td>ㅂ</td>
        <td>ㅂ-ㅗ-ㄹ-ㅣ-ㅂ-ㅏ-ㅂ</td>
        <td>ㅂ,ㅗ,ㄹ,ㅣ,ㅏ</td>
        <td>ㅂ→ㅗ,ㅗ→ㄹ,ㄹ→ㅣ,ㅣ→ㅂ,ㅂ→ㅏ,ㅏ→ㅂ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>bilabial closure → rounded vowel → liquid → spread vowel → bilabial closure → open vowel → bilabial coda closure</td>
        <td>bilabial closure,rounded vowel,liquid,spread vowel,open vowel,bilabial coda closure</td>
        <td>bilabial closure→rounded vowel,rounded vowel→liquid,liquid→spread vowel,spread vowel→bilabial closure,bilabial closure→open vowel,open vowel→bilabial coda closure</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅂ:bilabial closure,ㅗ:rounded vowel,ㄹ:liquid,ㅣ:spread vowel,ㅂ:bilabial closure,ㅏ:open vowel,ㅂ:bilabial coda closure</td>
        <td>ㅂ:bilabial closure→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄹ:liquid,ㄹ:liquid→ㅣ:spread vowel,ㅣ:spread vowel→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅂ:bilabial coda closure</td>
        <td>0.1</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.3333333333333330</td>
        <td>0.05084745762711870</td>
        <td>0.02510460251046030</td>
        <td>0.05310361681329420</td>
        <td>0.10734463276836200</td>
        <td>0.05267530996439160</td>
        <td>0.021505376344086000</td>
        <td>0.06398026122083640</td>
        <td>0.1293308828534480</td>
        <td>0.06346422887276090</td>
      </tr>
      <tr>
        <td class="line-num">45</td>
        <td>K045</td>
        <td>word</td>
        <td>카메라</td>
        <td>3</td>
        <td>0.8</td>
        <td>0.77</td>
        <td>0.06</td>
        <td>카메라</td>
        <td>ㅋ,ㅁ,ㄹ</td>
        <td>ㅏ,ㅔ</td>
        <td></td>
        <td>ㅋ-ㅏ-ㅁ-ㅔ-ㄹ-ㅏ</td>
        <td>ㅋ,ㅏ,ㅁ,ㅔ,ㄹ</td>
        <td>ㅋ→ㅏ,ㅏ→ㅁ,ㅁ→ㅔ,ㅔ→ㄹ,ㄹ→ㅏ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>low-visibility velar → open vowel → bilabial closure → front/open-mid vowel → liquid → open vowel</td>
        <td>low-visibility velar,open vowel,bilabial closure,front/open-mid vowel,liquid</td>
        <td>low-visibility velar→open vowel,open vowel→bilabial closure,bilabial closure→front/open-mid vowel,front/open-mid vowel→liquid,liquid→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅋ:low-visibility velar,ㅏ:open vowel,ㅁ:bilabial closure,ㅔ:front/open-mid vowel,ㄹ:liquid,ㅏ:open vowel</td>
        <td>ㅋ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅔ:front/open-mid vowel,ㅔ:front/open-mid vowel→ㄹ:liquid,ㄹ:liquid→ㅏ:open vowel</td>
        <td>0.1</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2777777777777780</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.029480286738351300</td>
        <td>0.08945386064030130</td>
        <td>0.03497578459225280</td>
        <td>0.017921146953405000</td>
        <td>0.03828608667318350</td>
        <td>0.11617384498740400</td>
        <td>0.045423096873055600</td>
      </tr>
      <tr>
        <td class="line-num">46</td>
        <td>K046</td>
        <td>word</td>
        <td>토마토</td>
        <td>3</td>
        <td>0.8</td>
        <td>0.73</td>
        <td>0.06</td>
        <td>토마토</td>
        <td>ㅌ,ㅁ</td>
        <td>ㅗ,ㅏ</td>
        <td></td>
        <td>ㅌ-ㅗ-ㅁ-ㅏ-ㅌ-ㅗ</td>
        <td>ㅌ,ㅗ,ㅁ,ㅏ</td>
        <td>ㅌ→ㅗ,ㅗ→ㅁ,ㅁ→ㅏ,ㅏ→ㅌ,ㅌ→ㅗ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>alveolar → rounded vowel → bilabial closure → open vowel → alveolar → rounded vowel</td>
        <td>alveolar,rounded vowel,bilabial closure,open vowel</td>
        <td>alveolar→rounded vowel,rounded vowel→bilabial closure,bilabial closure→open vowel,open vowel→alveolar,alveolar→rounded vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적</td>
        <td>ㅌ:alveolar,ㅗ:rounded vowel,ㅁ:bilabial closure,ㅏ:open vowel,ㅌ:alveolar,ㅗ:rounded vowel</td>
        <td>ㅌ:alveolar→ㅗ:rounded vowel,ㅗ:rounded vowel→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅌ:alveolar,ㅌ:alveolar→ㅗ:rounded vowel</td>
        <td>0.08</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2222222222222220</td>
        <td>0.03389830508474580</td>
        <td>0.016736401673640200</td>
        <td>0.023584229390681000</td>
        <td>0.07156308851224110</td>
        <td>0.02798062722636840</td>
        <td>0.014336917562724000</td>
        <td>0.03230716354887810</td>
        <td>0.09803162809896040</td>
        <td>0.03832962633749100</td>
      </tr>
      <tr>
        <td class="line-num">47</td>
        <td>K047</td>
        <td>word</td>
        <td>운동화</td>
        <td>3</td>
        <td>0.9</td>
        <td>0.8</td>
        <td>0.1</td>
        <td>운동화</td>
        <td>ㅇ,ㄷ,ㅎ</td>
        <td>ㅜ,ㅗ,ㅘ</td>
        <td>ㄴ,ㅇ</td>
        <td>ㅇ-ㅜ-ㄴ-ㄷ-ㅗ-ㅇ-ㅎ-ㅘ</td>
        <td>ㅇ,ㅜ,ㄴ,ㄷ,ㅗ,ㅎ,ㅘ</td>
        <td>ㅇ→ㅜ,ㅜ→ㄴ,ㄴ→ㄷ,ㄷ→ㅗ,ㅗ→ㅇ,ㅇ→ㅎ,ㅎ→ㅘ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → rounded/protruded vowel → low-visibility coda → alveolar → rounded vowel → low-visibility coda → glottal → rounded vowel</td>
        <td>null/velar onset,rounded/protruded vowel,low-visibility coda,alveolar,rounded vowel,glottal</td>
        <td>null/velar onset→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→rounded vowel,rounded vowel→low-visibility coda,low-visibility coda→glottal,glottal→rounded vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅜ:rounded/protruded vowel,ㄴ:low-visibility coda,ㄷ:alveolar,ㅗ:rounded vowel,ㅇ:low-visibility coda,ㅎ:glottal,ㅘ:rounded vowel</td>
        <td>ㅇ:null/velar onset→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㄷ:alveolar,ㄷ:alveolar→ㅗ:rounded vowel,ㅗ:rounded vowel→ㅇ:low-visibility coda,ㅇ:low-visibility coda→ㅎ:glottal,ㅎ:glottal→ㅘ:rounded vowel</td>
        <td>0.14</td>
        <td>0.18181818181818200</td>
        <td>0.0</td>
        <td>0.3333333333333330</td>
        <td>0.059322033898305100</td>
        <td>0.029288702928870300</td>
        <td>0.08672694688823720</td>
        <td>0.11412429378531100</td>
        <td>0.0708497003466926</td>
        <td>0.025089605734767000</td>
        <td>0.10840868361029700</td>
        <td>0.1426553672316380</td>
        <td>0.08856212543336580</td>
      </tr>
      <tr>
        <td class="line-num">48</td>
        <td>K048</td>
        <td>word</td>
        <td>원피스</td>
        <td>3</td>
        <td>0.9</td>
        <td>0.77</td>
        <td>0.12</td>
        <td>원피스</td>
        <td>ㅇ,ㅍ,ㅅ</td>
        <td>ㅝ,ㅣ,ㅡ</td>
        <td>ㄴ</td>
        <td>ㅇ-ㅝ-ㄴ-ㅍ-ㅣ-ㅅ-ㅡ</td>
        <td>ㅇ,ㅝ,ㄴ,ㅍ,ㅣ,ㅅ,ㅡ</td>
        <td>ㅇ→ㅝ,ㅝ→ㄴ,ㄴ→ㅍ,ㅍ→ㅣ,ㅣ→ㅅ,ㅅ→ㅡ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → rounded vowel → low-visibility coda → bilabial closure → spread vowel → fricative → neutral/unrounded vowel</td>
        <td>null/velar onset,rounded vowel,low-visibility coda,bilabial closure,spread vowel,fricative,neutral/unrounded vowel</td>
        <td>null/velar onset→rounded vowel,rounded vowel→low-visibility coda,low-visibility coda→bilabial closure,bilabial closure→spread vowel,spread vowel→fricative,fricative→neutral/unrounded vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅝ:rounded vowel,ㄴ:low-visibility coda,ㅍ:bilabial closure,ㅣ:spread vowel,ㅅ:fricative,ㅡ:neutral/unrounded vowel</td>
        <td>ㅇ:null/velar onset→ㅝ:rounded vowel,ㅝ:rounded vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㅍ:bilabial closure,ㅍ:bilabial closure→ㅣ:spread vowel,ㅣ:spread vowel→ㅅ:fricative,ㅅ:fricative→ㅡ:neutral/unrounded vowel</td>
        <td>0.14</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.3888888888888890</td>
        <td>0.05084745762711870</td>
        <td>0.02510460251046030</td>
        <td>0.06310361681329420</td>
        <td>0.11845574387947300</td>
        <td>0.059447074185476000</td>
        <td>0.021505376344086000</td>
        <td>0.08195274910817430</td>
        <td>0.1538386284149000</td>
        <td>0.07720399244867010</td>
      </tr>
      <tr>
        <td class="line-num">49</td>
        <td>K049</td>
        <td>word</td>
        <td>초콜릿</td>
        <td>3</td>
        <td>0.9</td>
        <td>0.8</td>
        <td>0.1</td>
        <td>초콜릳</td>
        <td>ㅊ,ㅋ,ㄹ</td>
        <td>ㅗ,ㅣ</td>
        <td>ㄹ,ㄷ</td>
        <td>ㅊ-ㅗ-ㅋ-ㅗ-ㄹ-ㄹ-ㅣ-ㅅ</td>
        <td>ㅊ,ㅗ,ㅋ,ㄹ,ㅣ,ㅅ</td>
        <td>ㅊ→ㅗ,ㅗ→ㅋ,ㅋ→ㅗ,ㅗ→ㄹ,ㄹ→ㄹ,ㄹ→ㅣ,ㅣ→ㅅ</td>
        <td></td>
        <td>coda_neutralization</td>
        <td>1.0</td>
        <td>affricate → rounded vowel → low-visibility velar → rounded vowel → low-visibility coda → liquid → spread vowel → low-visibility coda</td>
        <td>affricate,rounded vowel,low-visibility velar,low-visibility coda,liquid,spread vowel</td>
        <td>affricate→rounded vowel,rounded vowel→low-visibility velar,low-visibility velar→rounded vowel,rounded vowel→low-visibility coda,low-visibility coda→liquid,liquid→spread vowel,spread vowel→low-visibility coda</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅊ:affricate,ㅗ:rounded vowel,ㅋ:low-visibility velar,ㅗ:rounded vowel,ㄹ:low-visibility coda,ㄹ:liquid,ㅣ:spread vowel,ㄷ:low-visibility coda</td>
        <td>ㅊ:affricate→ㅗ:rounded vowel,ㅗ:rounded vowel→ㅋ:low-visibility velar,ㅋ:low-visibility velar→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄹ:liquid,ㄹ:liquid→ㅣ:spread vowel,ㅣ:spread vowel→ㄷ:low-visibility coda</td>
        <td>0.12</td>
        <td>0.18181818181818200</td>
        <td>0.125</td>
        <td>0.3333333333333330</td>
        <td>0.059322033898305100</td>
        <td>0.029288702928870300</td>
        <td>0.11297694688823700</td>
        <td>0.11412429378531100</td>
        <td>0.07984411140709660</td>
        <td>0.025089605734767000</td>
        <td>0.1412211836102970</td>
        <td>0.1426553672316380</td>
        <td>0.09980513925887080</td>
      </tr>
      <tr>
        <td class="line-num">50</td>
        <td>K050</td>
        <td>word</td>
        <td>빨간색</td>
        <td>3</td>
        <td>1.5</td>
        <td>1.1</td>
        <td>0.36</td>
        <td>빨간색</td>
        <td>ㅃ,ㄱ,ㅅ</td>
        <td>ㅏ,ㅐ</td>
        <td>ㄹ,ㄴ,ㄱ</td>
        <td>ㅃ-ㅏ-ㄹ-ㄱ-ㅏ-ㄴ-ㅅ-ㅐ-ㄱ</td>
        <td>ㅃ,ㅏ,ㄹ,ㄱ,ㄴ,ㅅ,ㅐ</td>
        <td>ㅃ→ㅏ,ㅏ→ㄹ,ㄹ→ㄱ,ㄱ→ㅏ,ㅏ→ㄴ,ㄴ→ㅅ,ㅅ→ㅐ,ㅐ→ㄱ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>bilabial closure → open vowel → low-visibility coda → low-visibility velar → open vowel → low-visibility coda → fricative → front/open-mid vowel → low-visibility coda</td>
        <td>bilabial closure,open vowel,low-visibility coda,low-visibility velar,fricative,front/open-mid vowel</td>
        <td>bilabial closure→open vowel,open vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→open vowel,open vowel→low-visibility coda,low-visibility coda→fricative,fricative→front/open-mid vowel,front/open-mid vowel→low-visibility coda</td>
        <td>양순음에서 입술 폐쇄가 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅃ:bilabial closure,ㅏ:open vowel,ㄹ:low-visibility coda,ㄱ:low-visibility velar,ㅏ:open vowel,ㄴ:low-visibility coda,ㅅ:fricative,ㅐ:front/open-mid vowel,ㄱ:low-visibility coda</td>
        <td>ㅃ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㅅ:fricative,ㅅ:fricative→ㅐ:front/open-mid vowel,ㅐ:front/open-mid vowel→ㄱ:low-visibility coda</td>
        <td>0.14</td>
        <td>0.2727272727272730</td>
        <td>0.0</td>
        <td>0.3333333333333330</td>
        <td>0.059322033898305100</td>
        <td>0.03347280334728030</td>
        <td>0.11035027696318000</td>
        <td>0.11412429378531100</td>
        <td>0.08071245417478490</td>
        <td>0.02867383512544800</td>
        <td>0.10031843360289100</td>
        <td>0.10374935798664600</td>
        <td>0.07337495834071360</td>
      </tr>
      <tr>
        <td class="line-num">51</td>
        <td>K051</td>
        <td>word</td>
        <td>텔레비전</td>
        <td>4</td>
        <td>1.0</td>
        <td>0.93</td>
        <td>0.12</td>
        <td>텔레비전</td>
        <td>ㅌ,ㄹ,ㅂ,ㅈ</td>
        <td>ㅔ,ㅣ,ㅓ</td>
        <td>ㄹ,ㄴ</td>
        <td>ㅌ-ㅔ-ㄹ-ㄹ-ㅔ-ㅂ-ㅣ-ㅈ-ㅓ-ㄴ</td>
        <td>ㅌ,ㅔ,ㄹ,ㅂ,ㅣ,ㅈ,ㅓ,ㄴ</td>
        <td>ㅌ→ㅔ,ㅔ→ㄹ,ㄹ→ㄹ,ㄹ→ㅔ,ㅔ→ㅂ,ㅂ→ㅣ,ㅣ→ㅈ,ㅈ→ㅓ,ㅓ→ㄴ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>alveolar → front/open-mid vowel → low-visibility coda → liquid → front/open-mid vowel → bilabial closure → spread vowel → affricate → open-mid vowel → low-visibility coda</td>
        <td>alveolar,front/open-mid vowel,low-visibility coda,liquid,bilabial closure,spread vowel,affricate,open-mid vowel</td>
        <td>alveolar→front/open-mid vowel,front/open-mid vowel→low-visibility coda,low-visibility coda→liquid,liquid→front/open-mid vowel,front/open-mid vowel→bilabial closure,bilabial closure→spread vowel,spread vowel→affricate,affricate→open-mid vowel,open-mid vowel→low-visibility coda</td>
        <td>양순음에서 입술 폐쇄가 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅌ:alveolar,ㅔ:front/open-mid vowel,ㄹ:low-visibility coda,ㄹ:liquid,ㅔ:front/open-mid vowel,ㅂ:bilabial closure,ㅣ:spread vowel,ㅈ:affricate,ㅓ:open-mid vowel,ㄴ:low-visibility coda</td>
        <td>ㅌ:alveolar→ㅔ:front/open-mid vowel,ㅔ:front/open-mid vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄹ:liquid,ㄹ:liquid→ㅔ:front/open-mid vowel,ㅔ:front/open-mid vowel→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅣ:spread vowel,ㅣ:spread vowel→ㅈ:affricate,ㅈ:affricate→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄴ:low-visibility coda</td>
        <td>0.16</td>
        <td>0.18181818181818200</td>
        <td>0.0</td>
        <td>0.4444444444444440</td>
        <td>0.07627118644067800</td>
        <td>0.03765690376569040</td>
        <td>0.0935190615835777</td>
        <td>0.14990583804143100</td>
        <td>0.08417181031051150</td>
        <td>0.03225806451612900</td>
        <td>0.10055813073503000</td>
        <td>0.1611890731628290</td>
        <td>0.09050732291452850</td>
      </tr>
      <tr>
        <td class="line-num">52</td>
        <td>K052</td>
        <td>word</td>
        <td>아버지</td>
        <td>3</td>
        <td>0.8</td>
        <td>0.77</td>
        <td>0.06</td>
        <td>아버지</td>
        <td>ㅇ,ㅂ,ㅈ</td>
        <td>ㅏ,ㅓ,ㅣ</td>
        <td></td>
        <td>ㅇ-ㅏ-ㅂ-ㅓ-ㅈ-ㅣ</td>
        <td>ㅇ,ㅏ,ㅂ,ㅓ,ㅈ,ㅣ</td>
        <td>ㅇ→ㅏ,ㅏ→ㅂ,ㅂ→ㅓ,ㅓ→ㅈ,ㅈ→ㅣ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → open vowel → bilabial closure → open-mid vowel → affricate → spread vowel</td>
        <td>null/velar onset,open vowel,bilabial closure,open-mid vowel,affricate,spread vowel</td>
        <td>null/velar onset→open vowel,open vowel→bilabial closure,bilabial closure→open-mid vowel,open-mid vowel→affricate,affricate→spread vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅏ:open vowel,ㅂ:bilabial closure,ㅓ:open-mid vowel,ㅈ:affricate,ㅣ:spread vowel</td>
        <td>ㅇ:null/velar onset→ㅏ:open vowel,ㅏ:open vowel→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㅈ:affricate,ㅈ:affricate→ㅣ:spread vowel</td>
        <td>0.12</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.3333333333333330</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.034480286738351300</td>
        <td>0.10056497175141200</td>
        <td>0.03918017167238380</td>
        <td>0.017921146953405000</td>
        <td>0.04477959316668990</td>
        <td>0.13060385941741900</td>
        <td>0.050883339834264700</td>
      </tr>
      <tr>
        <td class="line-num">53</td>
        <td>K053</td>
        <td>word</td>
        <td>어머니</td>
        <td>3</td>
        <td>0.9</td>
        <td>0.77</td>
        <td>0.15</td>
        <td>어머니</td>
        <td>ㅇ,ㅁ,ㄴ</td>
        <td>ㅓ,ㅣ</td>
        <td></td>
        <td>ㅇ-ㅓ-ㅁ-ㅓ-ㄴ-ㅣ</td>
        <td>ㅇ,ㅓ,ㅁ,ㄴ,ㅣ</td>
        <td>ㅇ→ㅓ,ㅓ→ㅁ,ㅁ→ㅓ,ㅓ→ㄴ,ㄴ→ㅣ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → open-mid vowel → bilabial closure → open-mid vowel → alveolar → spread vowel</td>
        <td>null/velar onset,open-mid vowel,bilabial closure,alveolar,spread vowel</td>
        <td>null/velar onset→open-mid vowel,open-mid vowel→bilabial closure,bilabial closure→open-mid vowel,open-mid vowel→alveolar,alveolar→spread vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅓ:open-mid vowel,ㅁ:bilabial closure,ㅓ:open-mid vowel,ㄴ:alveolar,ㅣ:spread vowel</td>
        <td>ㅇ:null/velar onset→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄴ:alveolar,ㄴ:alveolar→ㅣ:spread vowel</td>
        <td>0.1</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.2777777777777780</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.029480286738351300</td>
        <td>0.08945386064030130</td>
        <td>0.03497578459225280</td>
        <td>0.017921146953405000</td>
        <td>0.03828608667318350</td>
        <td>0.11617384498740400</td>
        <td>0.045423096873055600</td>
      </tr>
      <tr>
        <td class="line-num">54</td>
        <td>K054</td>
        <td>word</td>
        <td>엘리베이터</td>
        <td>5</td>
        <td>1.2</td>
        <td>1.07</td>
        <td>0.12</td>
        <td>엘리베이터</td>
        <td>ㅇ,ㄹ,ㅂ,ㅌ</td>
        <td>ㅔ,ㅣ,ㅓ</td>
        <td>ㄹ</td>
        <td>ㅇ-ㅔ-ㄹ-ㄹ-ㅣ-ㅂ-ㅔ-ㅇ-ㅣ-ㅌ-ㅓ</td>
        <td>ㅇ,ㅔ,ㄹ,ㅣ,ㅂ,ㅌ,ㅓ</td>
        <td>ㅇ→ㅔ,ㅔ→ㄹ,ㄹ→ㄹ,ㄹ→ㅣ,ㅣ→ㅂ,ㅂ→ㅔ,ㅔ→ㅇ,ㅇ→ㅣ,ㅣ→ㅌ,ㅌ→ㅓ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → front/open-mid vowel → low-visibility coda → liquid → spread vowel → bilabial closure → front/open-mid vowel → null/velar onset → spread vowel → alveolar → open-mid vowel</td>
        <td>null/velar onset,front/open-mid vowel,low-visibility coda,liquid,spread vowel,bilabial closure,alveolar,open-mid vowel</td>
        <td>null/velar onset→front/open-mid vowel,front/open-mid vowel→low-visibility coda,low-visibility coda→liquid,liquid→spread vowel,spread vowel→bilabial closure,bilabial closure→front/open-mid vowel,front/open-mid vowel→null/velar onset,null/velar onset→spread vowel,spread vowel→alveolar,alveolar→open-mid vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅔ:front/open-mid vowel,ㄹ:low-visibility coda,ㄹ:liquid,ㅣ:spread vowel,ㅂ:bilabial closure,ㅔ:front/open-mid vowel,ㅇ:null/velar onset,ㅣ:spread vowel,ㅌ:alveolar,ㅓ:open-mid vowel</td>
        <td>ㅇ:null/velar onset→ㅔ:front/open-mid vowel,ㅔ:front/open-mid vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄹ:liquid,ㄹ:liquid→ㅣ:spread vowel,ㅣ:spread vowel→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅔ:front/open-mid vowel,ㅔ:front/open-mid vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅣ:spread vowel,ㅣ:spread vowel→ㅌ:alveolar,ㅌ:alveolar→ㅓ:open-mid vowel</td>
        <td>0.14</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.4444444444444440</td>
        <td>0.0847457627118644</td>
        <td>0.04184100418410040</td>
        <td>0.06668784620397520</td>
        <td>0.15668549905838000</td>
        <td>0.07287032212977960</td>
        <td>0.035842293906810000</td>
        <td>0.062325089910257200</td>
        <td>0.14643504584895400</td>
        <td>0.06810310479418660</td>
      </tr>
      <tr>
        <td class="line-num">55</td>
        <td>K055</td>
        <td>word</td>
        <td>아이스크림</td>
        <td>5</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>0.0</td>
        <td>아이스크림</td>
        <td>ㅇ,ㅅ,ㅋ,ㄹ</td>
        <td>ㅏ,ㅣ,ㅡ</td>
        <td>ㅁ</td>
        <td>ㅇ-ㅏ-ㅇ-ㅣ-ㅅ-ㅡ-ㅋ-ㅡ-ㄹ-ㅣ-ㅁ</td>
        <td>ㅇ,ㅏ,ㅣ,ㅅ,ㅡ,ㅋ,ㄹ,ㅁ</td>
        <td>ㅇ→ㅏ,ㅏ→ㅇ,ㅇ→ㅣ,ㅣ→ㅅ,ㅅ→ㅡ,ㅡ→ㅋ,ㅋ→ㅡ,ㅡ→ㄹ,ㄹ→ㅣ,ㅣ→ㅁ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → open vowel → null/velar onset → spread vowel → fricative → neutral/unrounded vowel → low-visibility velar → neutral/unrounded vowel → liquid → spread vowel → bilabial nasal coda</td>
        <td>null/velar onset,open vowel,spread vowel,fricative,neutral/unrounded vowel,low-visibility velar,liquid,bilabial nasal coda</td>
        <td>null/velar onset→open vowel,open vowel→null/velar onset,null/velar onset→spread vowel,spread vowel→fricative,fricative→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility velar,low-visibility velar→neutral/unrounded vowel,neutral/unrounded vowel→liquid,liquid→spread vowel,spread vowel→bilabial nasal coda</td>
        <td>양순음에서 입술 폐쇄가 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅏ:open vowel,ㅇ:null/velar onset,ㅣ:spread vowel,ㅅ:fricative,ㅡ:neutral/unrounded vowel,ㅋ:low-visibility velar,ㅡ:neutral/unrounded vowel,ㄹ:liquid,ㅣ:spread vowel,ㅁ:bilabial nasal coda</td>
        <td>ㅇ:null/velar onset→ㅏ:open vowel,ㅏ:open vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅣ:spread vowel,ㅣ:spread vowel→ㅅ:fricative,ㅅ:fricative→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㅋ:low-visibility velar,ㅋ:low-visibility velar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:liquid,ㄹ:liquid→ㅣ:spread vowel,ㅣ:spread vowel→ㅁ:bilabial nasal coda</td>
        <td>0.16</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.4444444444444440</td>
        <td>0.0847457627118644</td>
        <td>0.04184100418410040</td>
        <td>0.07168784620397520</td>
        <td>0.15668549905838000</td>
        <td>0.07575788925122430</td>
        <td>0.035842293906810000</td>
        <td>0.07168784620397520</td>
        <td>0.15668549905838000</td>
        <td>0.07575788925122430</td>
      </tr>
      <tr>
        <td class="line-num">56</td>
        <td>K056</td>
        <td>word</td>
        <td>아메리카노</td>
        <td>5</td>
        <td>1.4</td>
        <td>1.13</td>
        <td>0.23</td>
        <td>아메리카노</td>
        <td>ㅇ,ㅁ,ㄹ,ㅋ,ㄴ</td>
        <td>ㅏ,ㅔ,ㅣ,ㅗ</td>
        <td></td>
        <td>ㅇ-ㅏ-ㅁ-ㅔ-ㄹ-ㅣ-ㅋ-ㅏ-ㄴ-ㅗ</td>
        <td>ㅇ,ㅏ,ㅁ,ㅔ,ㄹ,ㅣ,ㅋ,ㄴ,ㅗ</td>
        <td>ㅇ→ㅏ,ㅏ→ㅁ,ㅁ→ㅔ,ㅔ→ㄹ,ㄹ→ㅣ,ㅣ→ㅋ,ㅋ→ㅏ,ㅏ→ㄴ,ㄴ→ㅗ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>null/velar onset → open vowel → bilabial closure → front/open-mid vowel → liquid → spread vowel → low-visibility velar → open vowel → alveolar → rounded vowel</td>
        <td>null/velar onset,open vowel,bilabial closure,front/open-mid vowel,liquid,spread vowel,low-visibility velar,alveolar,rounded vowel</td>
        <td>null/velar onset→open vowel,open vowel→bilabial closure,bilabial closure→front/open-mid vowel,front/open-mid vowel→liquid,liquid→spread vowel,spread vowel→low-visibility velar,low-visibility velar→open vowel,open vowel→alveolar,alveolar→rounded vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅏ:open vowel,ㅁ:bilabial closure,ㅔ:front/open-mid vowel,ㄹ:liquid,ㅣ:spread vowel,ㅋ:low-visibility velar,ㅏ:open vowel,ㄴ:alveolar,ㅗ:rounded vowel</td>
        <td>ㅇ:null/velar onset→ㅏ:open vowel,ㅏ:open vowel→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅔ:front/open-mid vowel,ㅔ:front/open-mid vowel→ㄹ:liquid,ㄹ:liquid→ㅣ:spread vowel,ㅣ:spread vowel→ㅋ:low-visibility velar,ㅋ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㄴ:alveolar,ㄴ:alveolar→ㅗ:rounded vowel</td>
        <td>0.18</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.5</td>
        <td>0.07627118644067800</td>
        <td>0.03765690376569040</td>
        <td>0.053064516129032300</td>
        <td>0.1610169491525420</td>
        <td>0.06295641405579050</td>
        <td>0.03225806451612900</td>
        <td>0.04695974878675420</td>
        <td>0.1424928753562320</td>
        <td>0.055713640757336700</td>
      </tr>
      <tr>
        <td class="line-num">57</td>
        <td>P001</td>
        <td>short phrase</td>
        <td>밥 먹다</td>
        <td>3</td>
        <td>1.5</td>
        <td>1.13</td>
        <td>0.32</td>
        <td>밤 먹따</td>
        <td>ㅂ,ㅁ,ㄸ</td>
        <td>ㅏ,ㅓ</td>
        <td>ㅁ,ㄱ</td>
        <td>ㅂ-ㅏ-ㅁ | ㅁ-ㅓ-ㄱ-ㄸ-ㅏ</td>
        <td>ㅂ,ㅏ,ㅁ,ㅓ,ㄱ,ㄸ</td>
        <td>ㅂ→ㅏ,ㅏ→ㅁ,ㅁ→ㅁ,ㅁ→ㅓ,ㅓ→ㄱ,ㄱ→ㄸ,ㄸ→ㅏ</td>
        <td>ㅁ→ㅁ</td>
        <td>nasal_assimilation;tensification</td>
        <td>2.0</td>
        <td>bilabial closure → open vowel → bilabial nasal coda | bilabial closure → open-mid vowel → low-visibility coda → alveolar → open vowel</td>
        <td>bilabial closure,open vowel,bilabial nasal coda,open-mid vowel,low-visibility coda,alveolar</td>
        <td>bilabial closure→open vowel,open vowel→bilabial nasal coda,bilabial closure→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅂ:bilabial closure,ㅏ:open vowel,ㅁ:bilabial nasal coda | ㅁ:bilabial closure,ㅓ:open-mid vowel,ㄱ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅁ:bilabial nasal coda,ㅁ:bilabial closure→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄱ:low-visibility coda,ㄱ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.12</td>
        <td>0.18181818181818200</td>
        <td>0.25</td>
        <td>0.3333333333333330</td>
        <td>0.05084745762711870</td>
        <td>0.02510460251046030</td>
        <td>0.1442269468882370</td>
        <td>0.10734463276836200</td>
        <td>0.08389114332080780</td>
        <td>0.025089605734767000</td>
        <td>0.1276344662727760</td>
        <td>0.09499525023748810</td>
        <td>0.07423994984142290</td>
      </tr>
      <tr>
        <td class="line-num">58</td>
        <td>P002</td>
        <td>short phrase</td>
        <td>물 마시다</td>
        <td>4</td>
        <td>1.3</td>
        <td>1.1</td>
        <td>0.17</td>
        <td>물 마시다</td>
        <td>ㅁ,ㅅ,ㄷ</td>
        <td>ㅜ,ㅏ,ㅣ</td>
        <td>ㄹ</td>
        <td>ㅁ-ㅜ-ㄹ-|-ㅁ-ㅏ-ㅅ-ㅣ-ㄷ-ㅏ</td>
        <td>ㅁ,ㅜ,ㄹ,ㅏ,ㅅ,ㅣ,ㄷ</td>
        <td>ㅁ→ㅜ,ㅜ→ㄹ,ㄹ→|,|→ㅁ,ㅁ→ㅏ,ㅏ→ㅅ,ㅅ→ㅣ,ㅣ→ㄷ,ㄷ→ㅏ</td>
        <td>ㄹ→ㅁ</td>
        <td></td>
        <td></td>
        <td>bilabial closure → rounded/protruded vowel → low-visibility coda | bilabial closure → open vowel → fricative → spread vowel → alveolar → open vowel</td>
        <td>bilabial closure,rounded/protruded vowel,low-visibility coda,open vowel,fricative,spread vowel,alveolar</td>
        <td>bilabial closure→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,bilabial closure→open vowel,open vowel→fricative,fricative→spread vowel,spread vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄹ:low-visibility coda | ㅁ:bilabial closure,ㅏ:open vowel,ㅅ:fricative,ㅣ:spread vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄹ:low-visibility coda,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅅ:fricative,ㅅ:fricative→ㅣ:spread vowel,ㅣ:spread vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.14</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.3888888888888890</td>
        <td>0.059322033898305100</td>
        <td>0.029288702928870300</td>
        <td>0.06579178885630500</td>
        <td>0.12523540489642200</td>
        <td>0.06347435836442000</td>
        <td>0.03225806451612900</td>
        <td>0.05981071714209540</td>
        <td>0.11385036808765600</td>
        <td>0.05770396214947270</td>
      </tr>
      <tr>
        <td class="line-num">59</td>
        <td>P003</td>
        <td>short phrase</td>
        <td>문 열다</td>
        <td>4</td>
        <td>1.0</td>
        <td>0.97</td>
        <td>0.06</td>
        <td>문녈다</td>
        <td>ㅁ,ㄴ,ㄷ</td>
        <td>ㅜ,ㅕ,ㅏ</td>
        <td>ㄴ,ㄹ</td>
        <td>ㅁ-ㅜ-ㄴ-|-ㄴ-ㅕ-ㄹ-ㄷ-ㅏ</td>
        <td>ㅁ,ㅜ,ㄴ,ㅕ,ㄹ,ㄷ,ㅏ</td>
        <td>ㅁ→ㅜ,ㅜ→ㄴ,ㄴ→|,|→ㄴ,ㄴ→ㅕ,ㅕ→ㄹ,ㄹ→ㄷ,ㄷ→ㅏ</td>
        <td>ㄴ→ㄴ</td>
        <td>n_insertion</td>
        <td>1.0</td>
        <td>bilabial closure → rounded/protruded vowel → low-visibility coda → alveolar → open-mid vowel → low-visibility coda → alveolar → open vowel</td>
        <td>bilabial closure,rounded/protruded vowel,low-visibility coda,alveolar,open-mid vowel,open vowel</td>
        <td>bilabial closure→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄴ:low-visibility coda,ㄴ:alveolar,ㅕ:open-mid vowel,ㄹ:low-visibility coda,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㄴ:alveolar,ㄴ:alveolar→ㅕ:open-mid vowel,ㅕ:open-mid vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.14</td>
        <td>0.18181818181818200</td>
        <td>0.125</td>
        <td>0.3333333333333330</td>
        <td>0.05084745762711870</td>
        <td>0.029288702928870300</td>
        <td>0.11887300423590700</td>
        <td>0.10734463276836200</td>
        <td>0.07940451863484330</td>
        <td>0.02867383512544800</td>
        <td>0.12254948890299700</td>
        <td>0.11066456986429000</td>
        <td>0.08186032848952920</td>
      </tr>
      <tr>
        <td class="line-num">60</td>
        <td>P004</td>
        <td>short phrase</td>
        <td>문 닫다</td>
        <td>3</td>
        <td>1.0</td>
        <td>0.97</td>
        <td>0.06</td>
        <td>문 닫따</td>
        <td>ㅁ,ㄷ, ㄸ</td>
        <td>ㅜ,ㅏ</td>
        <td>ㄴ,ㄷ</td>
        <td>ㅁ-ㅜ-ㄴ-|-ㄷ-ㅏ-ㄷ-ㄸ-ㅏ</td>
        <td>ㅁ,ㅜ,ㄴ,ㄷ,ㄸ,ㅏ</td>
        <td>ㅁ→ㅜ,ㅜ→ㄴ,ㄴ→|,|→ㄷ,ㄷ→ㅏ,ㅏ→ㄷ,ㄷ→ㄸ,ㄸ→ㅏ</td>
        <td>ㄴ→ㄷ</td>
        <td>tensification</td>
        <td>1.0</td>
        <td>bilabial closure → rounded/protruded vowel → low-visibility coda | alveolar → open vowel → low-visibility coda → alveolar → open vowel</td>
        <td>bilabial closure,rounded/protruded vowel,low-visibility coda,alveolar,open vowel</td>
        <td>bilabial closure→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,alveolar→open vowel,open vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄴ:low-visibility coda | ㄷ:alveolar,ㅏ:open vowel,ㄷ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄴ:low-visibility coda,ㄷ:alveolar→ㅏ:open vowel,ㅏ:open vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.12</td>
        <td>0.18181818181818200</td>
        <td>0.125</td>
        <td>0.2777777777777780</td>
        <td>0.0423728813559322</td>
        <td>0.02510460251046030</td>
        <td>0.11387300423590700</td>
        <td>0.08945386064030130</td>
        <td>0.07016009064223950</td>
        <td>0.02867383512544800</td>
        <td>0.11739484972774000</td>
        <td>0.09222047488690860</td>
        <td>0.07232999035282420</td>
      </tr>
      <tr>
        <td class="line-num">61</td>
        <td>P005</td>
        <td>short phrase</td>
        <td>옷 입다</td>
        <td>3</td>
        <td>1.3</td>
        <td>1.17</td>
        <td>0.15</td>
        <td>온 닙따</td>
        <td>ㅇ,ㄴ, ㄸ</td>
        <td>ㅗ,ㅣ,ㅏ</td>
        <td>ㄴ, ㅂ</td>
        <td>ㅇ-ㅗ-ㄴ-|-ㄴ-ㅣ-ㅂ-ㄸ-ㅏ</td>
        <td>ㅇ,ㅗ,ㄴ,ㅣ,ㅂ,ㄸ,ㅏ</td>
        <td>ㅇ→ㅗ,ㅗ→ㄴ,ㄴ→|,|→ㅇ,ㅇ→ㅣ,ㅣ→ㅂ,ㅂ→ㄸ,ㄸ→ㅏ</td>
        <td>ㄴ→ㄴ</td>
        <td>n_insertion;nasal_assimilation;tensification</td>
        <td>3.0</td>
        <td>null/velar onset → rounded vowel → low-visibility coda | alveolar → spread vowel → bilabial coda closure → alveolar → open vowel</td>
        <td>null/velar onset,rounded vowel,low-visibility coda,alveolar,spread vowel,bilabial coda closure,open vowel</td>
        <td>null/velar onset→rounded vowel,rounded vowel→low-visibility coda,alveolar→spread vowel,spread vowel→bilabial coda closure,bilabial coda closure→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅗ:rounded vowel,ㄴ:low-visibility coda | ㄴ:alveolar,ㅣ:spread vowel,ㅂ:bilabial coda closure,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅇ:null/velar onset→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄴ:low-visibility coda,ㄴ:alveolar→ㅣ:spread vowel,ㅣ:spread vowel→ㅂ:bilabial coda closure,ㅂ:bilabial coda closure→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.14</td>
        <td>0.18181818181818200</td>
        <td>0.375</td>
        <td>0.3888888888888890</td>
        <td>0.05084745762711870</td>
        <td>0.02510460251046030</td>
        <td>0.18137300423590700</td>
        <td>0.11845574387947300</td>
        <td>0.09602961991424360</td>
        <td>0.02867383512544800</td>
        <td>0.15501966174009200</td>
        <td>0.10124422553801100</td>
        <td>0.08207659821730220</td>
      </tr>
      <tr>
        <td class="line-num">62</td>
        <td>P006</td>
        <td>short phrase</td>
        <td>책 읽다</td>
        <td>3</td>
        <td>1.0</td>
        <td>1.13</td>
        <td>0.12</td>
        <td>챙 닉따</td>
        <td>ㅊ,ㄴ,ㄸ</td>
        <td>ㅐ,ㅣ,ㅏ</td>
        <td>ㅇ,ㄱ</td>
        <td>ㅊ-ㅐ-ㅇ-|-ㄴ-ㅣㄱ-ㄸ-ㅏ</td>
        <td>ㅊ,ㅐ,ㅇ,ㄴ,ㅣ,ㄱ,ㄸ,ㅏ</td>
        <td>ㅊ→ㅐ,ㅐ→ㅇ,ㅇ→|,|→ㄴ,ㄴ→ㅣ,ㅣ→ㄱ,ㄱ→ㄸ,ㄸ→ㅏ</td>
        <td>ㅇ → ㄴ</td>
        <td>n_insertion</td>
        <td>1.0</td>
        <td>affricate → front/open-mid vowel → low-visibility coda | alveolar → spread vowel → low-visibility coda → alveolar → open vowel</td>
        <td>affricate,front/open-mid vowel,low-visibility coda,alveolar,spread vowel,open vowel</td>
        <td>affricate→front/open-mid vowel,front/open-mid vowel→low-visibility coda,alveolar→spread vowel,spread vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅊ:affricate,ㅐ:front/open-mid vowel,ㅇ:low-visibility coda | ㄴ:alveolar,ㅣ:spread vowel,ㄱ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅊ:affricate→ㅐ:front/open-mid vowel,ㅐ:front/open-mid vowel→ㅇ:low-visibility coda,ㄴ:alveolar→ㅣ:spread vowel,ㅣ:spread vowel→ㄱ:low-visibility coda,ㄱ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.16</td>
        <td>0.18181818181818200</td>
        <td>0.125</td>
        <td>0.3333333333333330</td>
        <td>0.05084745762711870</td>
        <td>0.02510460251046030</td>
        <td>0.12387300423590700</td>
        <td>0.10734463276836200</td>
        <td>0.07905267467660710</td>
        <td>0.02867383512544800</td>
        <td>0.10962212764239600</td>
        <td>0.09499525023748810</td>
        <td>0.06995811918283810</td>
      </tr>
      <tr>
        <td class="line-num">63</td>
        <td>P007</td>
        <td>short phrase</td>
        <td>커피 마시다</td>
        <td>5</td>
        <td>1.2</td>
        <td>1.1</td>
        <td>0.1</td>
        <td>커피 마시다</td>
        <td>ㅋ,ㅍ,ㅁ,ㅅ,ㄷ</td>
        <td>ㅓ,ㅣ,ㅏ</td>
        <td></td>
        <td>ㅋ-ㅓ-ㅍ-ㅣ-|-ㅁ-ㅏ-ㅅ-ㅣ-ㄷ-ㅏ</td>
        <td>ㅋ,ㅓ,ㅍ,ㅣ,ㅁ,ㅏ,ㅅ,ㄷ</td>
        <td>ㅋ→ㅓ,ㅓ→ㅍ,ㅍ→ㅣ,ㅣ→|,|→ㅁ,ㅁ→ㅏ,ㅏ→ㅅ,ㅅ→ㅣ,ㅣ→ㄷ,ㄷ→ㅏ</td>
        <td>ㅣ → ㅁ</td>
        <td></td>
        <td></td>
        <td>low-visibility velar → open-mid vowel → bilabial closure → spread vowel | bilabial closure → open vowel → fricative → spread vowel → alveolar → open vowel</td>
        <td>low-visibility velar,open-mid vowel,bilabial closure,spread vowel,open vowel,fricative,alveolar</td>
        <td>low-visibility velar→open-mid vowel,open-mid vowel→bilabial closure,bilabial closure→spread vowel,bilabial closure→open vowel,open vowel→fricative,fricative→spread vowel,spread vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅋ:low-visibility velar,ㅓ:open-mid vowel,ㅍ:bilabial closure,ㅣ:spread vowel | ㅁ:bilabial closure,ㅏ:open vowel,ㅅ:fricative,ㅣ:spread vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅋ:low-visibility velar→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㅍ:bilabial closure,ㅍ:bilabial closure→ㅣ:spread vowel,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅅ:fricative,ㅅ:fricative→ㅣ:spread vowel,ㅣ:spread vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.16</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.3888888888888890</td>
        <td>0.06779661016949150</td>
        <td>0.03347280334728030</td>
        <td>0.04896057347670250</td>
        <td>0.132015065913371</td>
        <td>0.05624704188104130</td>
        <td>0.035842293906810000</td>
        <td>0.04450961225154770</td>
        <td>0.12001369628488300</td>
        <td>0.051133674437310200</td>
      </tr>
      <tr>
        <td class="line-num">64</td>
        <td>P008</td>
        <td>short phrase</td>
        <td>우유 마시다</td>
        <td>5</td>
        <td>1.4</td>
        <td>1.27</td>
        <td>0.15</td>
        <td>우유 마시다</td>
        <td>ㅇ,ㅁ,ㅅ,ㄷ</td>
        <td>ㅜ,ㅠ,ㅏ,ㅣ</td>
        <td></td>
        <td>ㅇ-ㅜ-ㅇ-ㅠ-|-ㅁ-ㅏ-ㅅ-ㅣ-ㄷ-ㅏ</td>
        <td>ㅇ,ㅜ,ㅠ,ㅁ,ㅏ,ㅅ,ㅣ,ㄷ</td>
        <td>ㅇ→ㅜ,ㅜ→ㅇ,ㅇ→ㅠ,ㅠ→|,|→ㅁ,ㅁ→ㅏ,ㅏ→ㅅ,ㅅ→ㅣ,ㅣ→ㄷ,ㄷ→ㅏ</td>
        <td>ㅠ → ㅁ</td>
        <td></td>
        <td></td>
        <td>null/velar onset → rounded/protruded vowel → null/velar onset → rounded/protruded vowel | bilabial closure → open vowel → fricative → spread vowel → alveolar → open vowel</td>
        <td>null/velar onset,rounded/protruded vowel,bilabial closure,open vowel,fricative,spread vowel,alveolar</td>
        <td>null/velar onset→rounded/protruded vowel,rounded/protruded vowel→null/velar onset,null/velar onset→rounded/protruded vowel,bilabial closure→open vowel,open vowel→fricative,fricative→spread vowel,spread vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅜ:rounded/protruded vowel,ㅇ:null/velar onset,ㅠ:rounded/protruded vowel | ㅁ:bilabial closure,ㅏ:open vowel,ㅅ:fricative,ㅣ:spread vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅇ:null/velar onset→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅠ:rounded/protruded vowel,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅅ:fricative,ㅅ:fricative→ㅣ:spread vowel,ㅣ:spread vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.16</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.3888888888888890</td>
        <td>0.059322033898305100</td>
        <td>0.03347280334728030</td>
        <td>0.04896057347670250</td>
        <td>0.12523540489642200</td>
        <td>0.05562842179983040</td>
        <td>0.035842293906810000</td>
        <td>0.038551632658820900</td>
        <td>0.09861055503655260</td>
        <td>0.043801906929000300</td>
      </tr>
      <tr>
        <td class="line-num">65</td>
        <td>P009</td>
        <td>short phrase</td>
        <td>밥 먹어요</td>
        <td>4</td>
        <td>1.6</td>
        <td>1.23</td>
        <td>0.35</td>
        <td>밤 머거요</td>
        <td>ㅂ,ㅁ,ㄱ,ㅇ</td>
        <td>ㅏ,ㅓ,ㅛ</td>
        <td>ㅁ</td>
        <td>ㅂ-ㅏ-ㅁ-|-ㅁ-ㅓ-ㄱ-ㅇ-ㅓ-ㅇ-ㅛ</td>
        <td>ㅂ,ㅏ,ㅁ,ㅓ,ㄱ,ㅇ,ㅛ</td>
        <td>ㅂ→ㅏ,ㅏ→ㅁ,ㅁ→|,|→ㅁ,ㅁ→ㅓ,ㅓ→ㄱ,ㄱ→ㅇ,ㅇ→ㅓ,ㅓ→ㅇ,ㅇ→ㅛ</td>
        <td>ㅁ → ㅁ</td>
        <td>nasal_assimilation;resyllabification</td>
        <td>2.0</td>
        <td>bilabial closure → open vowel → bilabial nasal coda | bilabial closure → open-mid vowel → low-visibility velar → open-mid vowel → null/velar onset → rounded vowel</td>
        <td>bilabial closure,open vowel,bilabial nasal coda,open-mid vowel,low-visibility velar,null/velar onset,rounded vowel</td>
        <td>bilabial closure→open vowel,open vowel→bilabial nasal coda,bilabial closure→open-mid vowel,open-mid vowel→low-visibility velar,low-visibility velar→open-mid vowel,open-mid vowel→null/velar onset,null/velar onset→rounded vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅂ:bilabial closure,ㅏ:open vowel,ㅁ:bilabial nasal coda | ㅁ:bilabial closure,ㅓ:open-mid vowel,ㄱ:low-visibility velar,ㅓ:open-mid vowel,ㅇ:null/velar onset,ㅛ:rounded vowel</td>
        <td>ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅁ:bilabial nasal coda,ㅁ:bilabial closure→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅛ:rounded vowel</td>
        <td>0.14</td>
        <td>0.09090909090909090</td>
        <td>0.25</td>
        <td>0.3888888888888890</td>
        <td>0.059322033898305100</td>
        <td>0.029288702928870300</td>
        <td>0.12918784620397500</td>
        <td>0.12523540489642200</td>
        <td>0.08802403326105480</td>
        <td>0.035842293906810000</td>
        <td>0.10503076927152500</td>
        <td>0.10181740235481500</td>
        <td>0.07156425468378440</td>
      </tr>
      <tr>
        <td class="line-num">66</td>
        <td>P010</td>
        <td>short phrase</td>
        <td>물 주세요</td>
        <td>4</td>
        <td>1.2</td>
        <td>1.1</td>
        <td>0.17</td>
        <td>물 주세요</td>
        <td>ㅁ,ㅈ,ㅅ,ㅇ</td>
        <td>ㅜ,ㅔ,ㅛ</td>
        <td>ㄹ</td>
        <td>ㅁ-ㅜ-ㄹ-|-ㅈ-ㅜ-ㅅ-ㅔ-ㅇ-ㅛ</td>
        <td>ㅁ,ㅜ,ㄹ,ㅈ,ㅅ,ㅔ,ㅇ,ㅛ</td>
        <td>ㅁ→ㅜ,ㅜ→ㄹ,ㄹ→|,|→ㅈ,ㅈ→ㅜ,ㅜ→ㅅ,ㅅ→ㅔ,ㅔ→ㅇ,ㅇ→ㅛ</td>
        <td>ㄹ → ㅈ</td>
        <td></td>
        <td></td>
        <td>bilabial closure → rounded/protruded vowel → low-visibility coda | affricate → rounded/protruded vowel → fricative → front/open-mid vowel → null/velar onset → rounded vowel</td>
        <td>bilabial closure,rounded/protruded vowel,low-visibility coda,affricate,fricative,front/open-mid vowel,null/velar onset,rounded vowel</td>
        <td>bilabial closure→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,affricate→rounded/protruded vowel,rounded/protruded vowel→fricative,fricative→front/open-mid vowel,front/open-mid vowel→null/velar onset,null/velar onset→rounded vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄹ:low-visibility coda | ㅈ:affricate,ㅜ:rounded/protruded vowel,ㅅ:fricative,ㅔ:front/open-mid vowel,ㅇ:null/velar onset,ㅛ:rounded vowel</td>
        <td>ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄹ:low-visibility coda,ㅈ:affricate→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㅅ:fricative,ㅅ:fricative→ㅔ:front/open-mid vowel,ㅔ:front/open-mid vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅛ:rounded vowel</td>
        <td>0.16</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.4444444444444440</td>
        <td>0.059322033898305100</td>
        <td>0.029288702928870300</td>
        <td>0.070791788856305</td>
        <td>0.13634651600753300</td>
        <td>0.06763298023304010</td>
        <td>0.03225806451612900</td>
        <td>0.06435617168755000</td>
        <td>0.1239513781886660</td>
        <td>0.06148452748458190</td>
      </tr>
      <tr>
        <td class="line-num">67</td>
        <td>P011</td>
        <td>short phrase</td>
        <td>문 열어</td>
        <td>4</td>
        <td>1.3</td>
        <td>1.07</td>
        <td>0.25</td>
        <td>문 녀러</td>
        <td>ㅁ,ㄴ, ㄹ</td>
        <td>ㅜ,ㅕ,ㅓ</td>
        <td>ㄴ</td>
        <td>ㅁ-ㅜ-ㄴ-|-ㄴ-ㅕ-ㄹ-ㅓ</td>
        <td>ㅁ,ㅜ,ㄴ,ㅕ,ㄹ,ㅓ</td>
        <td>ㅁ→ㅜ,ㅜ→ㄴ,ㄴ→|,|→ㄴ,ㄴ→ㅕ,ㅕ→ㄹ,ㄹ→ㅓ</td>
        <td>ㄴ→ㄴ</td>
        <td>n_insertion;resyllabification</td>
        <td>2.0</td>
        <td>bilabial closure → rounded/protruded vowel → low-visibility coda | alveolar → open-mid vowel → liquid → open-mid vowel</td>
        <td>bilabial closure,rounded/protruded vowel,low-visibility coda,alveolar,open-mid vowel,liquid</td>
        <td>bilabial closure→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,alveolar→open-mid vowel,open-mid vowel→liquid,liquid→open-mid vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄴ:low-visibility coda | ㄴ:alveolar,ㅕ:open-mid vowel,ㄹ:liquid,ㅓ:open-mid vowel</td>
        <td>ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄴ:low-visibility coda,ㄴ:alveolar→ㅕ:open-mid vowel,ㅕ:open-mid vowel→ㄹ:liquid,ㄹ:liquid→ㅓ:open-mid vowel</td>
        <td>0.12</td>
        <td>0.09090909090909090</td>
        <td>0.25</td>
        <td>0.3333333333333330</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.1214996741609650</td>
        <td>0.10056497175141200</td>
        <td>0.07439551841926940</td>
        <td>0.025089605734767000</td>
        <td>0.11355109734669600</td>
        <td>0.09398595490786210</td>
        <td>0.0695285218871677</td>
      </tr>
      <tr>
        <td class="line-num">68</td>
        <td>P012</td>
        <td>short phrase</td>
        <td>문 닫아</td>
        <td>4</td>
        <td>1.5</td>
        <td>1.2</td>
        <td>0.36</td>
        <td>문 다다</td>
        <td>ㅁ,ㄷ</td>
        <td>ㅜ,ㅏ</td>
        <td>ㄴ</td>
        <td>ㅁ-ㅜ-ㄴ-|-ㄷ-ㅏ-ㄷ-ㅏ</td>
        <td>ㅁ,ㅜ,ㄴ,ㄷ,ㅏ</td>
        <td>ㅁ→ㅜ,ㅜ→ㄴ,ㄴ→|,|→ㄷ,ㄷ→ㅏ,ㅏ→ㄷ→ㅏ</td>
        <td>ㄴ→ㄷ</td>
        <td>resyllabification</td>
        <td>1.0</td>
        <td>bilabial closure → rounded/protruded vowel → low-visibility coda | alveolar → open vowel → alveolar → open vowel</td>
        <td>bilabial closure,rounded/protruded vowel,low-visibility coda,alveolar,open vowel</td>
        <td>bilabial closure→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,alveolar→open vowel,open vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄴ:low-visibility coda | ㄷ:alveolar,ㅏ:open vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄴ:low-visibility coda,ㄷ:alveolar→ㅏ:open vowel,ㅏ:open vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.1</td>
        <td>0.09090909090909090</td>
        <td>0.125</td>
        <td>0.2777777777777780</td>
        <td>0.03389830508474580</td>
        <td>0.016736401673640200</td>
        <td>0.08435361681329420</td>
        <td>0.08267419962335220</td>
        <td>0.056797836782092800</td>
        <td>0.021505376344086000</td>
        <td>0.07029468067774520</td>
        <td>0.06889516635279350</td>
        <td>0.04733153065174400</td>
      </tr>
      <tr>
        <td class="line-num">69</td>
        <td>P013</td>
        <td>short phrase</td>
        <td>빨리 와</td>
        <td>3</td>
        <td>1.2</td>
        <td>1.03</td>
        <td>0.15</td>
        <td>빨리 와</td>
        <td>ㅃ,ㄹ,ㅇ</td>
        <td>ㅏ,ㅣ,ㅘ</td>
        <td>ㄹ</td>
        <td>ㅃ-ㅏ-ㄹ-ㄹ-ㅣ-|-ㅇ-ㅘ</td>
        <td>ㅃ,ㅏ,ㄹ,ㅣ, ㅇ,ㅘ</td>
        <td>ㅃ→ㅏ,ㅏ→ㄹ,ㄹ→ㄹ,ㄹ→ㅣ,ㅣ→|,|→ㅇ,ㅇ→ㅘ</td>
        <td>ㄹ→ㄹ</td>
        <td></td>
        <td></td>
        <td>bilabial closure → open vowel → low-visibility coda → liquid → spread vowel | null/velar onset → rounded vowel</td>
        <td>bilabial closure,open vowel,low-visibility coda,liquid,spread vowel,null/velar onset,rounded vowel</td>
        <td>bilabial closure→open vowel,open vowel→low-visibility coda,low-visibility coda→liquid,liquid→spread vowel,null/velar onset→rounded vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅃ:bilabial closure,ㅏ:open vowel,ㄹ:low-visibility coda,ㄹ:liquid,ㅣ:spread vowel | ㅇ:null/velar onset,ㅘ:rounded vowel</td>
        <td>ㅃ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄹ:liquid,ㄹ:liquid→ㅣ:spread vowel,ㅇ:null/velar onset→ㅘ:rounded vowel</td>
        <td>0.12</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.3888888888888890</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.05899967416096450</td>
        <td>0.11167608286252400</td>
        <td>0.05469359979908760</td>
        <td>0.025089605734767000</td>
        <td>0.05728123704948010</td>
        <td>0.10842338141992600</td>
        <td>0.05310058232921130</td>
      </tr>
      <tr>
        <td class="line-num">70</td>
        <td>P014</td>
        <td>short phrase</td>
        <td>같이 가요</td>
        <td>4</td>
        <td>1.2</td>
        <td>1.0</td>
        <td>0.2</td>
        <td>가치 가요</td>
        <td>ㄱ,ㅊ</td>
        <td>ㅏ,ㅣ,ㅛ</td>
        <td></td>
        <td>ㄱ-ㅏ-ㅊ-ㅣ-|-ㄱ-ㅏ-ㅇ-ㅛ</td>
        <td>ㄱ,ㅏ,ㅊㅣ,|,ㅛ, ㅇ</td>
        <td>ㄱ→ㅏ, ㅏ→ㅊ, ㅊ→ㅣ, ㄱ→ㅏ, ㅏ→ㅇ, ㅇ→ㅛ</td>
        <td>ㅣ→ㄱ</td>
        <td>palatalization</td>
        <td>1.0</td>
        <td>low-visibility velar → open vowel → affricate → spread vowel | low-visibility velar → open vowel → null/velar onset → rounded vowel</td>
        <td>low-visibility velar,open vowel,affricate,spread vowel,null/velar onset,rounded vowel</td>
        <td>low-visibility velar→open vowel,open vowel→affricate,affricate→spread vowel,low-visibility velar→open vowel,open vowel→null/velar onset,null/velar onset→rounded vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㄱ:low-visibility velar,ㅏ:open vowel,ㅊ:affricate,ㅣ:spread vowel | ㄱ:low-visibility velar,ㅏ:open vowel,ㅇ:null/velar onset,ㅛ:rounded vowel</td>
        <td>ㄱ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㅊ:affricate,ㅊ:affricate→ㅣ:spread vowel,ㄱ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅛ:rounded vowel</td>
        <td>0.12</td>
        <td>0.0</td>
        <td>0.125</td>
        <td>0.3333333333333330</td>
        <td>0.0423728813559322</td>
        <td>0.02092050209205020</td>
        <td>0.06573028673835130</td>
        <td>0.10056497175141200</td>
        <td>0.056067677718531300</td>
        <td>0.017921146953405000</td>
        <td>0.06573028673835130</td>
        <td>0.10056497175141200</td>
        <td>0.056067677718531300</td>
      </tr>
      <tr>
        <td class="line-num">71</td>
        <td>P015</td>
        <td>short phrase</td>
        <td>집에 가다</td>
        <td>4</td>
        <td>1.0</td>
        <td>0.93</td>
        <td>0.12</td>
        <td>지베 가다</td>
        <td>ㅈ,ㅂ,ㄱ,ㄷ</td>
        <td>ㅣ,ㅔ,ㅏ</td>
        <td></td>
        <td>ㅈ-ㅣ-ㅂ-ㅔ-|-ㄱ-ㅏ-ㄷ-ㅏ</td>
        <td>ㅈ,ㅣ,ㅂ,ㅔ,ㄱ,ㅏ,ㄷ</td>
        <td>ㅈ→ㅣ,ㅣ→ㅂ,ㅂ→ㅔ,ㅔ→|,|→ㄱ,ㄱ→ㅏ,ㅏ→ㄷ,ㄷ→ㅏ</td>
        <td>ㅔ→ㄱ</td>
        <td>resyllabification</td>
        <td>1.0</td>
        <td>affricate → spread vowel → bilabial closure → front/open-mid vowel | low-visibility velar → open vowel → alveolar → open vowel</td>
        <td>affricate,spread vowel,bilabial closure,front/open-mid vowel,low-visibility velar,open vowel,alveolar</td>
        <td>affricate→spread vowel,spread vowel→bilabial closure,bilabial closure→front/open-mid vowel,low-visibility velar→open vowel,open vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅈ:affricate,ㅣ:spread vowel,ㅂ:bilabial closure,ㅔ:front/open-mid vowel | ㄱ:low-visibility velar,ㅏ:open vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅈ:affricate→ㅣ:spread vowel,ㅣ:spread vowel→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅔ:front/open-mid vowel,ㄱ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.14</td>
        <td>0.0</td>
        <td>0.125</td>
        <td>0.3888888888888890</td>
        <td>0.05084745762711870</td>
        <td>0.02510460251046030</td>
        <td>0.07341845878136200</td>
        <td>0.11845574387947300</td>
        <td>0.06443271320421370</td>
        <td>0.02867383512544800</td>
        <td>0.07894457933479790</td>
        <td>0.12737176761233600</td>
        <td>0.06928248731635890</td>
      </tr>
      <tr>
        <td class="line-num">72</td>
        <td>P016</td>
        <td>short phrase</td>
        <td>학교 가다</td>
        <td>4</td>
        <td>1.0</td>
        <td>0.83</td>
        <td>0.15</td>
        <td>학꾜 가다</td>
        <td>ㅎ,ㄲ,ㄱ,ㄷ</td>
        <td>ㅏ,ㅛ</td>
        <td>ㄱ</td>
        <td>ㅎ-ㅏ-ㄱ-ㄲ-ㅛ-|-ㄱ-ㅏ-ㄷ-ㅏ</td>
        <td>ㅎ,ㅏ,ㄲ,ㅛ,ㄱ,ㄷ</td>
        <td>ㅎ→ㅏ,ㅏ→ㄱ,ㄱ→ㄲ,→ㅛ,ㅛ→|,|→ㄱ,ㄱ→ㅏ,ㅏ→ㄷ,ㄷ→ㅏ</td>
        <td>ㅛ → ㄱ</td>
        <td>tensification</td>
        <td>1.0</td>
        <td>glottal → open vowel → low-visibility coda → low-visibility velar → rounded vowel | low-visibility velar → open vowel → alveolar → open vowel</td>
        <td>glottal,open vowel,low-visibility coda,low-visibility velar,rounded vowel,alveolar</td>
        <td>glottal→open vowel,open vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→rounded vowel,low-visibility velar→open vowel,open vowel→alveolar,alveolar→open vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅎ:glottal,ㅏ:open vowel,ㄱ:low-visibility coda,ㄲ:low-visibility velar,ㅛ:rounded vowel | ㄱ:low-visibility velar,ㅏ:open vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅎ:glottal→ㅏ:open vowel,ㅏ:open vowel→ㄱ:low-visibility coda,ㄱ:low-visibility coda→ㄲ:low-visibility velar,ㄲ:low-visibility velar→ㅛ:rounded vowel,ㄱ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.12</td>
        <td>0.09090909090909090</td>
        <td>0.125</td>
        <td>0.3333333333333330</td>
        <td>0.059322033898305100</td>
        <td>0.029288702928870300</td>
        <td>0.09204178885630500</td>
        <td>0.11412429378531100</td>
        <td>0.07285572407398640</td>
        <td>0.03225806451612900</td>
        <td>0.11089372151362000</td>
        <td>0.1374991491389290</td>
        <td>0.08777798081203190</td>
      </tr>
      <tr>
        <td class="line-num">73</td>
        <td>P017</td>
        <td>short phrase</td>
        <td>사진 찍다</td>
        <td>4</td>
        <td>1.3</td>
        <td>1.13</td>
        <td>0.21</td>
        <td>사진 찍따</td>
        <td>ㅅ,ㅈ,ㅉ,ㄸ</td>
        <td>ㅏ,ㅣ</td>
        <td>ㄴ,ㄱ</td>
        <td>ㅅ-ㅏ-ㅈ-ㅣ-ㄴ-|-ㅉ-ㅣ-ㄱ-ㄸ-ㅏ</td>
        <td>ㅅ,ㅏ,ㅈ,ㅣ,ㄴ,ㅉ,ㄱ,ㄸ</td>
        <td>ㅅ→ㅏ,ㅏ→ㅈ,ㅈ→ㅣ,ㅣ→ㄴ,ㄴ→|,|→ㅉ,ㅉ→ㅣ,ㅣ→ㄱ,ㄱ→ㄷ,ㄷ→ㅏ</td>
        <td>ㄴ→ㅉ</td>
        <td>tensification</td>
        <td>1.0</td>
        <td>fricative → open vowel → affricate → spread vowel → low-visibility coda | affricate → spread vowel → low-visibility coda → alveolar → open vowel</td>
        <td>fricative,open vowel,affricate,spread vowel,low-visibility coda,alveolar</td>
        <td>fricative→open vowel,open vowel→affricate,affricate→spread vowel,spread vowel→low-visibility coda,affricate→spread vowel,spread vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅅ:fricative,ㅏ:open vowel,ㅈ:affricate,ㅣ:spread vowel,ㄴ:low-visibility coda | ㅉ:affricate,ㅣ:spread vowel,ㄱ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅅ:fricative→ㅏ:open vowel,ㅏ:open vowel→ㅈ:affricate,ㅈ:affricate→ㅣ:spread vowel,ㅣ:spread vowel→ㄴ:low-visibility coda,ㅉ:affricate→ㅣ:spread vowel,ㅣ:spread vowel→ㄱ:low-visibility coda,ㄱ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.16</td>
        <td>0.18181818181818200</td>
        <td>0.125</td>
        <td>0.3333333333333330</td>
        <td>0.05084745762711870</td>
        <td>0.03347280334728030</td>
        <td>0.12566511893124800</td>
        <td>0.10734463276836200</td>
        <td>0.08285990717246500</td>
        <td>0.035842293906810000</td>
        <td>0.11120806985066200</td>
        <td>0.09499525023748810</td>
        <td>0.0733273514800575</td>
      </tr>
      <tr>
        <td class="line-num">74</td>
        <td>P018</td>
        <td>short phrase</td>
        <td>전화 받다</td>
        <td>4</td>
        <td>1.3</td>
        <td>1.1</td>
        <td>0.2</td>
        <td>전화 받따</td>
        <td>ㅈ,ㅎ,ㅂ,ㄸ</td>
        <td>ㅓ,ㅘ,ㅏ</td>
        <td>ㄴ,ㄷ</td>
        <td>ㅈ-ㅓ-ㄴ-ㅎ-ㅘ-|-ㅂ-ㅏ-ㄷ-ㄸ-ㅏ</td>
        <td>ㅈ,ㅓ,ㄴ,ㅎ,ㅘ,ㅂ,ㅏ,ㄷ,ㄸ</td>
        <td>ㅈ→ㅓ,ㅓ→ㄴ,ㄴ→ㅎ,ㅎ→ㅘ,ㅘ→|,|→ㅂ,ㅂ→ㅏ,ㅏ→ㄷ,ㄷ→ㄸ,ㄸ→ㅏ</td>
        <td>ㅘ → ㅂ</td>
        <td>tensification</td>
        <td>1.0</td>
        <td>affricate → open-mid vowel → low-visibility coda → glottal → rounded vowel | bilabial closure → open vowel → low-visibility coda → alveolar → open vowel</td>
        <td>affricate,open-mid vowel,low-visibility coda,glottal,rounded vowel,bilabial closure,open vowel,alveolar</td>
        <td>affricate→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→glottal,glottal→rounded vowel,bilabial closure→open vowel,open vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅈ:affricate,ㅓ:open-mid vowel,ㄴ:low-visibility coda,ㅎ:glottal,ㅘ:rounded vowel | ㅂ:bilabial closure,ㅏ:open vowel,ㄷ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅈ:affricate→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㅎ:glottal,ㅎ:glottal→ㅘ:rounded vowel,ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.18</td>
        <td>0.18181818181818200</td>
        <td>0.125</td>
        <td>0.4444444444444440</td>
        <td>0.06779661016949150</td>
        <td>0.03347280334728030</td>
        <td>0.13066511893124800</td>
        <td>0.1431261770244820</td>
        <td>0.09535636516119500</td>
        <td>0.035842293906810000</td>
        <td>0.11878647175568000</td>
        <td>0.13011470638589300</td>
        <td>0.08668760469199540</td>
      </tr>
      <tr>
        <td class="line-num">75</td>
        <td>P019</td>
        <td>short phrase</td>
        <td>음악 듣다</td>
        <td>4</td>
        <td>1.4</td>
        <td>1.2</td>
        <td>0.26</td>
        <td>으막 듣따</td>
        <td>ㅇ,ㅁ,ㄷ</td>
        <td>ㅡ,ㅏ</td>
        <td>ㄱ,ㄷ</td>
        <td>ㅇ-ㅡ-ㅁ-ㅁ-ㅏ-ㄱ-|-ㄷ-ㅡ-ㄷ-ㄸ-ㅏ</td>
        <td>ㅇ,ㅡ,ㅁ,ㅏ,ㄱ,ㄷ,ㄸ</td>
        <td>ㅇ→ㅡ,ㅡ→ㅁ,ㅁ→ㅁ,ㅁ→ㅏ,ㅏ→ㄱ,ㄱ→|,|→ㄷ,ㄷ→ㅡ,ㅡ→ㄷ,ㄷ→ㄸ,ㄸ→ㅏ</td>
        <td>ㄱ → ㄷ</td>
        <td>resyllabification;tensification</td>
        <td>2.0</td>
        <td>null/velar onset → neutral/unrounded vowel → bilabial closure → open vowel → low-visibility coda | alveolar → neutral/unrounded vowel → low-visibility coda → alveolar → open vowel</td>
        <td>null/velar onset,neutral/unrounded vowel,bilabial closure,open vowel,low-visibility coda,alveolar</td>
        <td>null/velar onset→neutral/unrounded vowel,neutral/unrounded vowel→bilabial closure,bilabial closure→open vowel,open vowel→low-visibility coda,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅡ:neutral/unrounded vowel,ㅁ:bilabial closure,ㅏ:open vowel,ㄱ:low-visibility coda | ㄷ:alveolar,ㅡ:neutral/unrounded vowel,ㄷ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅇ:null/velar onset→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄱ:low-visibility coda,ㄷ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.14</td>
        <td>0.18181818181818200</td>
        <td>0.25</td>
        <td>0.3333333333333330</td>
        <td>0.06779661016949150</td>
        <td>0.03347280334728030</td>
        <td>0.15281117627891800</td>
        <td>0.12090395480226000</td>
        <td>0.09438782156628640</td>
        <td>0.03942652329749100</td>
        <td>0.12734264689909900</td>
        <td>0.10075329566855000</td>
        <td>0.07865651797190530</td>
      </tr>
      <tr>
        <td class="line-num">76</td>
        <td>P020</td>
        <td>short phrase</td>
        <td>이름 부르다</td>
        <td>5</td>
        <td>1.3</td>
        <td>1.23</td>
        <td>0.06</td>
        <td>이름 부르다</td>
        <td>ㅇ,ㄹ,ㅂ,ㄷ</td>
        <td>ㅣ,ㅡ,ㅜ,ㅏ</td>
        <td>ㅁ</td>
        <td>ㅇ-ㅣ-ㄹ-ㅡ-ㅁ-|-ㅂ-ㅜ-ㄹ-ㅡ-ㄷ-ㅏ</td>
        <td>ㅇ,ㅣ,ㄹ,ㅡ,ㅁ,|,ㅂ,ㅜ,ㄷ,ㅏ</td>
        <td>ㅇ→ㅣ,ㅣ→ㄹ,ㄹ→ㅡ,ㅡ→ㅁ,ㅁ→|,|→ㅂ,ㅂ→ㅜ,ㅜ→ㄹ,ㄹ→ㅡ,ㅡ→ㄷ,ㄷ→ㅏ</td>
        <td>ㅁ→ㅂ</td>
        <td></td>
        <td></td>
        <td>null/velar onset → spread vowel → liquid → neutral/unrounded vowel → bilabial nasal coda | bilabial closure → rounded/protruded vowel → liquid → neutral/unrounded vowel → alveolar → open vowel</td>
        <td>null/velar onset,spread vowel,liquid,neutral/unrounded vowel,bilabial nasal coda,bilabial closure,rounded/protruded vowel,alveolar,open vowel</td>
        <td>null/velar onset→spread vowel,spread vowel→liquid,liquid→neutral/unrounded vowel,neutral/unrounded vowel→bilabial nasal coda,bilabial closure→rounded/protruded vowel,rounded/protruded vowel→liquid,liquid→neutral/unrounded vowel,neutral/unrounded vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅣ:spread vowel,ㄹ:liquid,ㅡ:neutral/unrounded vowel,ㅁ:bilabial nasal coda | ㅂ:bilabial closure,ㅜ:rounded/protruded vowel,ㄹ:liquid,ㅡ:neutral/unrounded vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅇ:null/velar onset→ㅣ:spread vowel,ㅣ:spread vowel→ㄹ:liquid,ㄹ:liquid→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㅁ:bilabial nasal coda,ㅂ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄹ:liquid,ㄹ:liquid→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.2</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.5</td>
        <td>0.06779661016949150</td>
        <td>0.03347280334728030</td>
        <td>0.08168784620397520</td>
        <td>0.15423728813559300</td>
        <td>0.07747374567554130</td>
        <td>0.035842293906810000</td>
        <td>0.06641288309266280</td>
        <td>0.12539616921592900</td>
        <td>0.06298678510206610</td>
      </tr>
      <tr>
        <td class="line-num">77</td>
        <td>P021</td>
        <td>short phrase</td>
        <td>얼굴 보다</td>
        <td>4</td>
        <td>1.3</td>
        <td>1.07</td>
        <td>0.21</td>
        <td>얼굴 보다</td>
        <td>ㅇ,ㄱ,ㅂ,ㄷ</td>
        <td>ㅓ,ㅜ,ㅗ,ㅏ</td>
        <td>ㄹ</td>
        <td>ㅇ-ㅓ-ㄹ-ㄱ-ㅜ-ㄹ-|-ㅂ-ㅗ-ㄷ-ㅏ</td>
        <td>ㅇ,ㅓ,ㄹ,ㄱ,ㅜ,ㅂ,ㅗ,ㄷ,ㅏ</td>
        <td>ㅇ→ㅓ,ㅓ→ㄹ,ㄹ→ㄱ,ㄱ→ㅜ,ㅜ→ㄹ,ㄹ→|,|→ㅂ,ㅂ→ㅗ,ㅗ→ㄷ,ㄷ→ㅏ</td>
        <td>ㄹ→ㅂ</td>
        <td></td>
        <td></td>
        <td>null/velar onset → open-mid vowel → low-visibility coda → low-visibility velar → rounded/protruded vowel → low-visibility coda | bilabial closure → rounded vowel → alveolar → open vowel</td>
        <td>null/velar onset,open-mid vowel,low-visibility coda,low-visibility velar,rounded/protruded vowel,bilabial closure,rounded vowel,alveolar,open vowel</td>
        <td>null/velar onset→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,bilabial closure→rounded vowel,rounded vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅓ:open-mid vowel,ㄹ:low-visibility coda,ㄱ:low-visibility velar,ㅜ:rounded/protruded vowel,ㄹ:low-visibility coda | ㅂ:bilabial closure,ㅗ:rounded vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅇ:null/velar onset→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄹ:low-visibility coda,ㅂ:bilabial closure→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.18</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.5</td>
        <td>0.06779661016949150</td>
        <td>0.03347280334728030</td>
        <td>0.07668784620397520</td>
        <td>0.15423728813559300</td>
        <td>0.07485384644862660</td>
        <td>0.035842293906810000</td>
        <td>0.07167088430278060</td>
        <td>0.14414699825756400</td>
        <td>0.06995686583983790</td>
      </tr>
      <tr>
        <td class="line-num">78</td>
        <td>P022</td>
        <td>short phrase</td>
        <td>친구 만나다</td>
        <td>5</td>
        <td>1.4</td>
        <td>1.13</td>
        <td>0.23</td>
        <td>친구 만나다</td>
        <td>ㅊ,ㄱ,ㅁ,ㄴ,ㄷ</td>
        <td>ㅣ,ㅜ,ㅏ</td>
        <td>ㄴ</td>
        <td>ㅊ-ㅣ-ㄴ-ㄱ-ㅜ-|-ㅁ-ㅏ-ㄴ-ㄴ-ㅏ-ㄷ-ㅏ</td>
        <td>ㅊ,ㅣ,ㄴ,ㄱ,ㅜ,ㅁ,ㅏ,ㄷ</td>
        <td>ㅊ→ㅣ,ㅣ→ㄴ,ㄴ→ㄱ,ㄱ→ㅜ,ㅜ→|,|→ㅁ,ㅁ→ㅏ,ㅏ→ㄴ,ㄴ→ㄴ,ㄴ→ㅏ,ㅏ→ㄷ,ㄷ→ㅏ</td>
        <td>ㅜ→ㅁ</td>
        <td></td>
        <td></td>
        <td>affricate → spread vowel → low-visibility coda → low-visibility velar → rounded/protruded vowel | bilabial closure → open vowel → low-visibility coda → alveolar → open vowel → alveolar → open vowel</td>
        <td>affricate,spread vowel,low-visibility coda,low-visibility velar,rounded/protruded vowel,bilabial closure,open vowel,alveolar</td>
        <td>affricate→spread vowel,spread vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→rounded/protruded vowel,bilabial closure→open vowel,open vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel,open vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅊ:affricate,ㅣ:spread vowel,ㄴ:low-visibility coda,ㄱ:low-visibility velar,ㅜ:rounded/protruded vowel | ㅁ:bilabial closure,ㅏ:open vowel,ㄴ:low-visibility coda,ㄴ:alveolar,ㅏ:open vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅊ:affricate→ㅣ:spread vowel,ㅣ:spread vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅜ:rounded/protruded vowel,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㄴ:alveolar,ㄴ:alveolar→ㅏ:open vowel,ㅏ:open vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.16</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.4444444444444440</td>
        <td>0.07627118644067800</td>
        <td>0.04184100418410040</td>
        <td>0.07347996089931570</td>
        <td>0.14990583804143100</td>
        <td>0.07590797664572050</td>
        <td>0.043010752688172000</td>
        <td>0.06502651407019090</td>
        <td>0.13266003366498300</td>
        <td>0.06717520057143410</td>
      </tr>
      <tr>
        <td class="line-num">79</td>
        <td>P023</td>
        <td>short phrase</td>
        <td>버스 타다</td>
        <td>4</td>
        <td>1.2</td>
        <td>1.03</td>
        <td>0.15</td>
        <td>버스 타다</td>
        <td>ㅂ,ㅅ,ㅌ,ㄷ</td>
        <td>ㅓ,ㅡ,ㅏ</td>
        <td></td>
        <td>ㅂ-ㅓ-ㅅ-ㅡ-|-ㅌ-ㅏ-ㄷ-ㅏ</td>
        <td>ㅂ,ㅓ,ㅅ,ㅡ,ㅌ,ㅏ,ㄷ</td>
        <td>ㅂ→ㅓ,ㅓ→ㅅ,ㅅ→ㅡ,ㅡ→|,|→ㅌ,ㅌ→ㅏ,ㅏ→ㄷ,ㄷ→ㅏ</td>
        <td>ㅡ → ㅌ</td>
        <td></td>
        <td></td>
        <td>bilabial closure → open-mid vowel → fricative → neutral/unrounded vowel | alveolar → open vowel → alveolar → open vowel</td>
        <td>bilabial closure,open-mid vowel,fricative,neutral/unrounded vowel,alveolar,open vowel</td>
        <td>bilabial closure→open-mid vowel,open-mid vowel→fricative,fricative→neutral/unrounded vowel,alveolar→open vowel,open vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅂ:bilabial closure,ㅓ:open-mid vowel,ㅅ:fricative,ㅡ:neutral/unrounded vowel | ㅌ:alveolar,ㅏ:open vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅂ:bilabial closure→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㅅ:fricative,ㅅ:fricative→ㅡ:neutral/unrounded vowel,ㅌ:alveolar→ㅏ:open vowel,ㅏ:open vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.14</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.3333333333333330</td>
        <td>0.0423728813559322</td>
        <td>0.02510460251046030</td>
        <td>0.04216845878136200</td>
        <td>0.10056497175141200</td>
        <td>0.04569433995876110</td>
        <td>0.02867383512544800</td>
        <td>0.040940251244040800</td>
        <td>0.09763589490428390</td>
        <td>0.044363436853166200</td>
      </tr>
      <tr>
        <td class="line-num">80</td>
        <td>P024</td>
        <td>short phrase</td>
        <td>택시 타다</td>
        <td>4</td>
        <td>1.2</td>
        <td>1.07</td>
        <td>0.23</td>
        <td>택씨 타다</td>
        <td>ㅌ,ㅅ,ㄷ</td>
        <td>ㅐ,ㅣ,ㅏ</td>
        <td>ㄱ</td>
        <td>ㅌ-ㅐ-ㄱ-ㅅ-ㅣ-|-ㅌ-ㅏ-ㄷ-ㅏ</td>
        <td>ㅌ,ㅐ,ㄱ,ㅅ,ㅣ,ㅏ,ㄷ</td>
        <td>ㅌ→ㅐ,ㅐ→ㄱ,ㄱ→ㅅ,ㅅ→ㅣ,ㅣ→|,|→ㅌ,ㅌ→ㅏ,ㅏ→ㄷ,ㄷ→ㅏ</td>
        <td>ㅣ→ㅌ</td>
        <td>tensification</td>
        <td>1.0</td>
        <td>alveolar → front/open-mid vowel → low-visibility coda → fricative → spread vowel | alveolar → open vowel → alveolar → open vowel</td>
        <td>alveolar,front/open-mid vowel,low-visibility coda,fricative,spread vowel,open vowel</td>
        <td>alveolar→front/open-mid vowel,front/open-mid vowel→low-visibility coda,low-visibility coda→fricative,fricative→spread vowel,alveolar→open vowel,open vowel→alveolar,alveolar→open vowel</td>
        <td>ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅌ:alveolar,ㅐ:front/open-mid vowel,ㄱ:low-visibility coda,ㅆ:fricative,ㅣ:spread vowel | ㅌ:alveolar,ㅏ:open vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅌ:alveolar→ㅐ:front/open-mid vowel,ㅐ:front/open-mid vowel→ㄱ:low-visibility coda,ㄱ:low-visibility coda→ㅆ:fricative,ㅆ:fricative→ㅣ:spread vowel,ㅌ:alveolar→ㅏ:open vowel,ㅏ:open vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.14</td>
        <td>0.09090909090909090</td>
        <td>0.125</td>
        <td>0.3333333333333330</td>
        <td>0.05084745762711870</td>
        <td>0.029288702928870300</td>
        <td>0.09704178885630500</td>
        <td>0.10734463276836200</td>
        <td>0.0728755989259075</td>
        <td>0.03225806451612900</td>
        <td>0.09069326061336910</td>
        <td>0.10032208669940300</td>
        <td>0.0681080363793528</td>
      </tr>
      <tr>
        <td class="line-num">81</td>
        <td>P025</td>
        <td>short phrase</td>
        <td>집에 오다</td>
        <td>4</td>
        <td>1.0</td>
        <td>0.97</td>
        <td>0.06</td>
        <td>지베 오다</td>
        <td>ㅈ,ㅂ,ㄷ</td>
        <td>ㅣ,ㅔ,ㅗ,ㅏ</td>
        <td></td>
        <td>ㅈ-ㅣ-ㅂ-ㅔ-|-ㅇ-ㅗ-ㄷ-ㅏ</td>
        <td>ㅈ,ㅣ,ㅂ,ㅔ,ㅗ,ㄷ,ㅏ</td>
        <td>ㅈ→ㅣ,ㅣ→ㅂ,ㅂ→ㅔ,ㅔ→|,|→ㅇ,ㅇ→ㅗ,ㅗ→ㄷ,ㄷ→ㅏ</td>
        <td>ㅔ→ㅇ</td>
        <td>resyllabification</td>
        <td>1.0</td>
        <td>affricate → spread vowel → bilabial closure → front/open-mid vowel | null/velar onset → rounded vowel → alveolar → open vowel</td>
        <td>affricate,spread vowel,bilabial closure,front/open-mid vowel,null/velar onset,rounded vowel,alveolar,open vowel</td>
        <td>affricate→spread vowel,spread vowel→bilabial closure,bilabial closure→front/open-mid vowel,null/velar onset→rounded vowel,rounded vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅈ:affricate,ㅣ:spread vowel,ㅂ:bilabial closure,ㅔ:front/open-mid vowel | ㅇ:null/velar onset,ㅗ:rounded vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅈ:affricate→ㅣ:spread vowel,ㅣ:spread vowel→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅔ:front/open-mid vowel,ㅇ:null/velar onset→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.14</td>
        <td>0.0</td>
        <td>0.125</td>
        <td>0.4444444444444440</td>
        <td>0.05084745762711870</td>
        <td>0.02510460251046030</td>
        <td>0.07341845878136200</td>
        <td>0.12956685499058400</td>
        <td>0.06627801784174280</td>
        <td>0.02867383512544800</td>
        <td>0.07568913276429070</td>
        <td>0.13357407730988000</td>
        <td>0.0683278534450957</td>
      </tr>
      <tr>
        <td class="line-num">82</td>
        <td>P026</td>
        <td>short phrase</td>
        <td>밥을 먹다</td>
        <td>4</td>
        <td>1.2</td>
        <td>1.03</td>
        <td>0.29</td>
        <td>바블 먹따</td>
        <td>ㅂ,ㅁ,ㄸ</td>
        <td>ㅏ,ㅡ,ㅓ</td>
        <td>ㄹ,ㄱ</td>
        <td>ㅂ-ㅏ-ㅂ-ㅡ-ㄹ-|-ㅁ-ㅓ-ㄱ-ㄸ-ㅏ</td>
        <td>ㅂ,ㅏ,ㅇ,ㅡ,ㄹ,ㅁ,ㅓ,ㄱ,ㄸ</td>
        <td>ㅂ→ㅏ,ㅏ→ㅂ,ㅂ→ㅡ,ㅡ→ㄹ,ㄹ→|,|→ㅁ,ㅁ→ㅓ,ㅓ→ㄱ,ㄱ→ㄸ,ㄸ→ㅏ</td>
        <td>ㄹ→ㅁ</td>
        <td>resyllabification;tensification</td>
        <td>2.0</td>
        <td>bilabial closure → open vowel → bilabial closure → neutral/unrounded vowel → low-visibility coda | bilabial closure → open-mid vowel → low-visibility coda → alveolar → open vowel</td>
        <td>bilabial closure,open vowel,neutral/unrounded vowel,low-visibility coda,open-mid vowel,alveolar</td>
        <td>bilabial closure→open vowel,open vowel→bilabial closure,bilabial closure→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,bilabial closure→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅂ:bilabial closure,ㅏ:open vowel,ㅂ:bilabial closure,ㅡ:neutral/unrounded vowel,ㄹ:low-visibility coda | ㅁ:bilabial closure,ㅓ:open-mid vowel,ㄱ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:low-visibility coda,ㅁ:bilabial closure→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄱ:low-visibility coda,ㄱ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.18</td>
        <td>0.18181818181818200</td>
        <td>0.25</td>
        <td>0.3333333333333330</td>
        <td>0.06779661016949150</td>
        <td>0.03347280334728030</td>
        <td>0.16191511893124800</td>
        <td>0.12090395480226000</td>
        <td>0.09645075054429720</td>
        <td>0.035842293906810000</td>
        <td>0.1571991445934450</td>
        <td>0.11738248039054400</td>
        <td>0.09364150538281280</td>
      </tr>
      <tr>
        <td class="line-num">83</td>
        <td>P027</td>
        <td>short phrase</td>
        <td>물을 먹다</td>
        <td>4</td>
        <td>1.2</td>
        <td>1.0</td>
        <td>0.2</td>
        <td>무를 먹따</td>
        <td>ㅁ,ㄹ,ㄸ</td>
        <td>ㅜ,ㅡ,ㅓ,ㅏ</td>
        <td>ㄹ,ㄱ</td>
        <td>ㅁ-ㅜ-ㄹ-ㅡ-ㄹ-|-ㅁ-ㅓ-ㄱ-ㄸ-ㅏ</td>
        <td>ㅁ,ㅜ,ㄹ,ㅡ,ㅓ,ㄱ,ㄸ,ㅏ</td>
        <td>ㅁ→ㅜ,ㅜ→ㄹ,ㄹ→ㅡ,ㅡ,ㅡ→ㄹ,ㄹ→|,|→ㅁ,ㅁ→ㅓ,ㅓ→ㄱ,ㄱ→ㄸ,ㄸ→ㅏ</td>
        <td>ㄹ→ㅁ</td>
        <td>resyllabification;tensification</td>
        <td>2.0</td>
        <td>bilabial closure → rounded/protruded vowel → liquid → neutral/unrounded vowel → low-visibility coda | bilabial closure → open-mid vowel → low-visibility coda → alveolar → open vowel</td>
        <td>bilabial closure,rounded/protruded vowel,liquid,neutral/unrounded vowel,low-visibility coda,open-mid vowel,alveolar,open vowel</td>
        <td>bilabial closure→rounded/protruded vowel,rounded/protruded vowel→liquid,liquid→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,bilabial closure→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄹ:liquid,ㅡ:neutral/unrounded vowel,ㄹ:low-visibility coda | ㅁ:bilabial closure,ㅓ:open-mid vowel,ㄱ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄹ:liquid,ㄹ:liquid→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:low-visibility coda,ㅁ:bilabial closure→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄱ:low-visibility coda,ㄱ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.16</td>
        <td>0.18181818181818200</td>
        <td>0.25</td>
        <td>0.4444444444444440</td>
        <td>0.06779661016949150</td>
        <td>0.03347280334728030</td>
        <td>0.15781117627891800</td>
        <td>0.1431261770244820</td>
        <td>0.10345534683355000</td>
        <td>0.03942652329749100</td>
        <td>0.15781117627891800</td>
        <td>0.1431261770244820</td>
        <td>0.10345534683355000</td>
      </tr>
      <tr>
        <td class="line-num">84</td>
        <td>P028</td>
        <td>short phrase</td>
        <td>사진 보다</td>
        <td>4</td>
        <td>1.0</td>
        <td>1.13</td>
        <td>0.12</td>
        <td>사진 보다</td>
        <td>ㅅ,ㅈ,ㅂ,ㄷ</td>
        <td>ㅏ,ㅣ,ㅗ</td>
        <td>ㄴ</td>
        <td>ㅅ-ㅏ-ㅈ-ㅣ-ㄴ-|-ㅂ-ㅗ-ㄷ-ㅏ</td>
        <td>ㅅ,ㅏ,ㅈ,ㅣ,ㄴ,ㅂ,ㅗ,ㄷ</td>
        <td>ㅅ→ㅏ,ㅏ→ㅈ,ㅈ→ㅣ,ㅣ→ㄴ,ㄴ→|,|→ㅂ,ㅂ→ㅗ,ㅗ→ㄷ,ㄷ→ㅏ</td>
        <td>ㄴ→ㅂ</td>
        <td></td>
        <td></td>
        <td>fricative → open vowel → affricate → spread vowel → low-visibility coda | bilabial closure → rounded vowel → alveolar → open vowel</td>
        <td>fricative,open vowel,affricate,spread vowel,low-visibility coda,bilabial closure,rounded vowel,alveolar</td>
        <td>fricative→open vowel,open vowel→affricate,affricate→spread vowel,spread vowel→low-visibility coda,bilabial closure→rounded vowel,rounded vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅅ:fricative,ㅏ:open vowel,ㅈ:affricate,ㅣ:spread vowel,ㄴ:low-visibility coda | ㅂ:bilabial closure,ㅗ:rounded vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅅ:fricative→ㅏ:open vowel,ㅏ:open vowel→ㅈ:affricate,ㅈ:affricate→ㅣ:spread vowel,ㅣ:spread vowel→ㄴ:low-visibility coda,ㅂ:bilabial closure→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.16</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.4444444444444440</td>
        <td>0.059322033898305100</td>
        <td>0.029288702928870300</td>
        <td>0.070791788856305</td>
        <td>0.13634651600753300</td>
        <td>0.06763298023304010</td>
        <td>0.03225806451612900</td>
        <td>0.06264760075779200</td>
        <td>0.12066063363498500</td>
        <td>0.0598521948964957</td>
      </tr>
      <tr>
        <td class="line-num">85</td>
        <td>P029</td>
        <td>short phrase</td>
        <td>노래 듣다</td>
        <td>4</td>
        <td>0.9</td>
        <td>1.03</td>
        <td>0.15</td>
        <td>노래 듣따</td>
        <td>ㄴ,ㄹ,ㄸ</td>
        <td>ㅗ,ㅐ,ㅡ,ㅏ</td>
        <td>ㄷ</td>
        <td>ㄴ-ㅗ-ㄹ-ㅐ-|-ㄷ-ㅡ-ㄷ-ㄸ-ㅏ</td>
        <td>ㄴ,ㅗ,ㄹ,ㅐ,|,ㄸ,ㅡ,ㅏ</td>
        <td>ㄴ→ㅗ,ㅗ→ㄹ,ㄹ→ㅐ,ㅐ→|,|→ㄷ,ㄷ→ㅡ,ㅡ→ㄷ,ㄷ→ㄸ,ㄸ→ㅏ</td>
        <td>ㅐ→ㄷ</td>
        <td>tensification</td>
        <td>1.0</td>
        <td>alveolar → rounded vowel → liquid → front/open-mid vowel | alveolar → neutral/unrounded vowel → low-visibility coda → alveolar → open vowel</td>
        <td>alveolar,rounded vowel,liquid,front/open-mid vowel,neutral/unrounded vowel,low-visibility coda,open vowel</td>
        <td>alveolar→rounded vowel,rounded vowel→liquid,liquid→front/open-mid vowel,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㄴ:alveolar,ㅗ:rounded vowel,ㄹ:liquid,ㅐ:front/open-mid vowel | ㄷ:alveolar,ㅡ:neutral/unrounded vowel,ㄷ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㄴ:alveolar→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄹ:liquid,ㄹ:liquid→ㅐ:front/open-mid vowel,ㄷ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.16</td>
        <td>0.09090909090909090</td>
        <td>0.125</td>
        <td>0.3888888888888890</td>
        <td>0.059322033898305100</td>
        <td>0.029288702928870300</td>
        <td>0.102041788856305</td>
        <td>0.12523540489642200</td>
        <td>0.07918856443428370</td>
        <td>0.03225806451612900</td>
        <td>0.0990696979187427</td>
        <td>0.12158777174409900</td>
        <td>0.07688210139250840</td>
      </tr>
      <tr>
        <td class="line-num">86</td>
        <td>P030</td>
        <td>short phrase</td>
        <td>영화 보다</td>
        <td>4</td>
        <td>0.9</td>
        <td>1.03</td>
        <td>0.15</td>
        <td>영화 보다</td>
        <td>ㅇ,ㅎ,ㅂ,ㄷ</td>
        <td>ㅕ,ㅘ,ㅗ,ㅏ</td>
        <td>ㅇ</td>
        <td>ㅇ-ㅕ-ㅇ-ㅎ-ㅘ-|-ㅂ-ㅗ-ㄷ-ㅏ</td>
        <td>ㅇ,ㅕ,ㅎ,ㅘ,ㅂ,ㅗ,ㄷ,ㅏ</td>
        <td>ㅇ→ㅕ,ㅕ→ㅇ,ㅇ→ㅎ,ㅎ→ㅘ,ㅘ→|,|→ㅂ,ㅂ→ㅗ,ㅗ→ㄷ,ㄷ→ㅏ</td>
        <td>ㅘ → ㅂ</td>
        <td></td>
        <td></td>
        <td>null/velar onset → open-mid vowel → low-visibility coda → glottal → rounded vowel | bilabial closure → rounded vowel → alveolar → open vowel</td>
        <td>null/velar onset,open-mid vowel,low-visibility coda,glottal,rounded vowel,bilabial closure,alveolar,open vowel</td>
        <td>null/velar onset→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→glottal,glottal→rounded vowel,bilabial closure→rounded vowel,rounded vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅕ:open-mid vowel,ㅇ:low-visibility coda,ㅎ:glottal,ㅘ:rounded vowel | ㅂ:bilabial closure,ㅗ:rounded vowel,ㄷ:alveolar,ㅏ:open vowel</td>
        <td>ㅇ:null/velar onset→ㅕ:open-mid vowel,ㅕ:open-mid vowel→ㅇ:low-visibility coda,ㅇ:low-visibility coda→ㅎ:glottal,ㅎ:glottal→ㅘ:rounded vowel,ㅂ:bilabial closure→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel</td>
        <td>0.16</td>
        <td>0.09090909090909090</td>
        <td>0.0</td>
        <td>0.4444444444444440</td>
        <td>0.059322033898305100</td>
        <td>0.029288702928870300</td>
        <td>0.070791788856305</td>
        <td>0.13634651600753300</td>
        <td>0.06763298023304010</td>
        <td>0.03225806451612900</td>
        <td>0.06872989209350000</td>
        <td>0.13237525825974100</td>
        <td>0.06566308760489330</td>
      </tr>
      <tr>
        <td class="line-num">87</td>
        <td>S001</td>
        <td>sentence</td>
        <td>오늘 오후에는 친구와 근처 공원에서 산책을 했다.</td>
        <td>20</td>
        <td>3.3</td>
        <td>3.87</td>
        <td>0.51</td>
        <td>오늘 오후에는 친구와 근처 공원에서 산채글 핻따</td>
        <td>ㅇ,ㅎ,ㅊ,ㄱ,ㅅ,ㄷ,ㄸ</td>
        <td>ㅗ,ㅡ,ㅜ,ㅔ,ㅣ,ㅘ,ㅓ,ㅝ,ㅏ,ㅐ</td>
        <td>ㄹ, ㄴ, ㅇ, ㄷ</td>
        <td>ㅇ-ㅗ-ㄴ-ㅡ-ㄹ | ㅇ-ㅗ-ㅎ-ㅜ-ㅇ-ㅔ-ㄴ-ㅡ-ㄴ | ㅊ-ㅣ-ㄴ-ㄱ-ㅜ-ㅇ-ㅘ | ㄱ-ㅡ-ㄴ-ㅊ-ㅓ | ㄱ-ㅗ-ㅇ-ㅇ-ㅝ-ㄴ-ㅇ-ㅔ-ㅅ-ㅓ | ㅅ-ㅏ-ㄴ-ㅊ-ㅐ-ㄱ-ㅡ-ㄹ | ㅎ-ㅐ-ㄷ-ㄸ-ㅏ</td>
        <td>ㅇ,ㅗ,ㄴ,ㅡ,ㄹ,ㅎ,ㅜ,ㅔ,ㅊ,ㅣ,ㄱ,ㅘ,ㅓ,ㅝ,ㅅ,ㅏ,ㅐ,ㄷ,ㄸ</td>
        <td>ㅇ→ㅗ,ㅗ→ㄴ,ㄴ→ㅡ,ㅡ→ㄹ; ㅇ→ㅗ,ㅗ→ㅎ,ㅎ→ㅜ,ㅜ→ㅇ,ㅇ→ㅔ,ㅔ→ㄴ,ㄴ→ㅡ,ㅡ→ㄴ; ㅊ→ㅣ,ㅣ→ㄴ,ㄴ→ㄱ,ㄱ→ㅜ,ㅜ→ㅇ,ㅇ→ㅘ; ㄱ→ㅡ,ㅡ→ㄴ,ㄴ→ㅊ,ㅊ→ㅓ; ㄱ→ㅗ,ㅗ→ㅇ,ㅇ→ㅇ,ㅇ→ㅝ,ㅝ→ㄴ,ㄴ→ㅇ,ㅇ→ㅔ,ㅔ→ㅅ,ㅅ→ㅓ; ㅅ→ㅏ,ㅏ→ㄴ,ㄴ→ㅊ,ㅊ→ㅐ,ㅐ→ㄱ,ㄱ→ㅡ,ㅡ→ㄹ; ㅎ→ㅐ,ㅐ→ㄷ,ㄷ→ㄸ,ㄸ→ㅏ</td>
        <td>ㄹ→ㅇ, ㄴ→ㅊ, ㅘ→ㄱ, ㅓ→ㄱ, ㅓ→ㅅ, ㄹ→ㅎ</td>
        <td>resyllabification;tensification</td>
        <td>2.0</td>
        <td>null/velar onset → rounded vowel → alveolar → neutral/unrounded vowel → low-visibility coda | null/velar onset → rounded vowel → glottal → rounded/protruded vowel → null/velar onset → front/open-mid vowel → alveolar → neutral/unrounded vowel → low-visibility coda | affricate → spread vowel → low-visibility coda → low-visibility velar → rounded/protruded vowel → null/velar onset → rounded vowel | low-visibility velar → neutral/unrounded vowel → low-visibility coda → affricate → open-mid vowel | low-visibility velar → rounded vowel → low-visibility coda → null/velar onset → rounded vowel → low-visibility coda → null/velar onset → front/open-mid vowel → fricative → open-mid vowel | fricative → open vowel → low-visibility coda → affricate → front/open-mid vowel → low-visibility velar → neutral/unrounded vowel → low-visibility coda | glottal → front/open-mid vowel → low-visibility coda → alveolar → open vowel</td>
        <td>null/velar onset,rounded vowel,alveolar,neutral/unrounded vowel,low-visibility coda,glottal,rounded/protruded vowel,front/open-mid vowel,affricate,spread vowel,low-visibility velar,open-mid vowel,fricative,open vowel</td>
        <td>null/velar onset→rounded vowel,rounded vowel→alveolar,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,null/velar onset→rounded vowel,rounded vowel→glottal,glottal→rounded/protruded vowel,rounded/protruded vowel→null/velar onset,null/velar onset→front/open-mid vowel,front/open-mid vowel→alveolar,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,affricate→spread vowel,spread vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→rounded/protruded vowel,rounded/protruded vowel→null/velar onset,null/velar onset→rounded vowel,low-visibility velar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,low-visibility coda→affricate,affricate→open-mid vowel,low-visibility velar→rounded vowel,rounded vowel→low-visibility coda,low-visibility coda→null/velar onset,null/velar onset→rounded vowel,rounded vowel→low-visibility coda,low-visibility coda→null/velar onset,null/velar onset→front/open-mid vowel,front/open-mid vowel→fricative,fricative→open-mid vowel,fricative→open vowel,open vowel→low-visibility coda,low-visibility coda→affricate,affricate→front/open-mid vowel,front/open-mid vowel→low-visibility velar,low-visibility velar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,glottal→front/open-mid vowel,front/open-mid vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅗ:rounded vowel,ㄴ:alveolar,ㅡ:neutral/unrounded vowel,ㄹ:low-visibility coda | ㅇ:null/velar onset,ㅗ:rounded vowel,ㅎ:glottal,ㅜ:rounded/protruded vowel,ㅇ:null/velar onset,ㅔ:front/open-mid vowel,ㄴ:alveolar,ㅡ:neutral/unrounded vowel,ㄴ:low-visibility coda | ㅊ:affricate,ㅣ:spread vowel,ㄴ:low-visibility coda,ㄱ:low-visibility velar,ㅜ:rounded/protruded vowel,ㅇ:null/velar onset,ㅘ:rounded vowel | ㄱ:low-visibility velar,ㅡ:neutral/unrounded vowel,ㄴ:low-visibility coda,ㅊ:affricate,ㅓ:open-mid vowel | ㄱ:low-visibility velar,ㅗ:rounded vowel,ㅇ:low-visibility coda,ㅇ:null/velar onset,ㅝ:rounded vowel,ㄴ:low-visibility coda,ㅇ:null/velar onset,ㅔ:front/open-mid vowel,ㅅ:fricative,ㅓ:open-mid vowel | ㅅ:fricative,ㅏ:open vowel,ㄴ:low-visibility coda,ㅊ:affricate,ㅐ:front/open-mid vowel,ㄱ:low-visibility velar,ㅡ:neutral/unrounded vowel,ㄹ:low-visibility coda | ㅎ:glottal,ㅐ:front/open-mid vowel,ㄷ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅇ:null/velar onset→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄴ:alveolar,ㄴ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:low-visibility coda,ㅇ:null/velar onset→ㅗ:rounded vowel,ㅗ:rounded vowel→ㅎ:glottal,ㅎ:glottal→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅔ:front/open-mid vowel,ㅔ:front/open-mid vowel→ㄴ:alveolar,ㄴ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄴ:low-visibility coda,ㅊ:affricate→ㅣ:spread vowel,ㅣ:spread vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅘ:rounded vowel,ㄱ:low-visibility velar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㅊ:affricate,ㅊ:affricate→ㅓ:open-mid vowel,ㄱ:low-visibility velar→ㅗ:rounded vowel,ㅗ:rounded vowel→ㅇ:low-visibility coda,ㅇ:low-visibility coda→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅝ:rounded vowel,ㅝ:rounded vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅔ:front/open-mid vowel,ㅔ:front/open-mid vowel→ㅅ:fricative,ㅅ:fricative→ㅓ:open-mid vowel,ㅅ:fricative→ㅏ:open vowel,ㅏ:open vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㅊ:affricate,ㅊ:affricate→ㅐ:front/open-mid vowel,ㅐ:front/open-mid vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:low-visibility coda,ㅎ:glottal→ㅐ:front/open-mid vowel,ㅐ:front/open-mid vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.38</td>
        <td>0.36363636363636400</td>
        <td>0.25</td>
        <td>0.7777777777777780</td>
        <td>0.2457627118644070</td>
        <td>0.14225941422594100</td>
        <td>0.27708292603453900</td>
        <td>0.352165725047081</td>
        <td>0.24299066375841400</td>
        <td>0.11469534050179200</td>
        <td>0.0715976553060824</td>
        <td>0.09099889536100280</td>
        <td>0.06278828520889240</td>
      </tr>
      <tr>
        <td class="line-num">88</td>
        <td>S002</td>
        <td>sentence</td>
        <td>아침에 일어나 창문을 열고 밖을 바라봤다.</td>
        <td>17</td>
        <td>3.0</td>
        <td>3.07</td>
        <td>0.12</td>
        <td>아치메 이러나 창무늘 열고 바끌 바라봗따</td>
        <td>ㅇ,ㅊ,ㄴ,ㅁ,ㄱ,ㅂ,ㄹ,ㄷ</td>
        <td>ㅏ,ㅣ,ㅔ,ㅓ,ㅜ,ㅡ,ㅕ,ㅗ,ㅘ</td>
        <td>ㄹ, ㄷ</td>
        <td>ㅇ-ㅏ-ㅊ-ㅣ-ㅁ-ㅔ | ㅇ-ㅣ-ㄹ-ㅓ-ㄴ-ㅏ | ㅊ-ㅏ-ㅇ-ㅁ-ㅜ-ㄴ-ㅡ-ㄹ | ㅇ-ㅕ-ㄹ-ㄱ-ㅗ | ㅂ-ㅏ-ㄲ-ㅡ-ㄹ | ㅂ-ㅏ-ㄹ-ㅏ-ㅂ-ㅘ-ㄷ-ㄸ-ㅏ</td>
        <td>ㅇ,ㅏ,ㅊ,ㅣ,ㅁ,ㅔ,ㄹ,ㅓ,ㄴ,ㅜ,ㅡ,ㅕ,ㄱ,ㅗ,ㅂ,ㄲ,ㅘ,ㄷ,ㄸ</td>
        <td>ㅇ→ㅏ,ㅏ→ㅊ,ㅊ→ㅣ,ㅣ→ㅁ,ㅁ→ㅔ; ㅇ→ㅣ,ㅣ→ㄹ,ㄹ→ㅓ,ㅓ→ㄴ,ㄴ→ㅏ; ㅊ→ㅏ,ㅏ→ㅇ,ㅇ→ㅁ,ㅁ→ㅜ,ㅜ→ㄴ,ㄴ→ㅡ,ㅡ→ㄹ; ㅇ→ㅕ,ㅕ→ㄹ,ㄹ→ㄱ,ㄱ→ㅗ; ㅂ→ㅏ,ㅏ→ㄲ,ㄲ→ㅡ,ㅡ→ㄹ; ㅂ→ㅏ,ㅏ→ㄹ,ㄹ→ㅏ,ㅏ→ㅂ,ㅂ→ㅘ,ㅘ→ㄷ,ㄷ→ㄸ,ㄸ→ㅏ</td>
        <td>ㅔ→ㅇ, ㅏ→ㅊ, ㄹ→ㅇ, ㅗ→ㅂ, ㄹ→ㅂ</td>
        <td>resyllabification;tensification</td>
        <td>2.0</td>
        <td>null/velar onset → open vowel → affricate → spread vowel → bilabial closure → front/open-mid vowel | null/velar onset → spread vowel → liquid → open-mid vowel → alveolar → open vowel | affricate → open vowel → low-visibility coda → bilabial closure → rounded/protruded vowel → alveolar → neutral/unrounded vowel → low-visibility coda | null/velar onset → open-mid vowel → low-visibility coda → low-visibility velar → rounded vowel | bilabial closure → open vowel → low-visibility velar → neutral/unrounded vowel → low-visibility coda | bilabial closure → open vowel → liquid → open vowel → bilabial closure → rounded vowel → low-visibility coda → alveolar → open vowel</td>
        <td>null/velar onset,open vowel,affricate,spread vowel,bilabial closure,front/open-mid vowel,liquid,open-mid vowel,alveolar,low-visibility coda,rounded/protruded vowel,neutral/unrounded vowel,low-visibility velar,rounded vowel</td>
        <td>null/velar onset→open vowel,open vowel→affricate,affricate→spread vowel,spread vowel→bilabial closure,bilabial closure→front/open-mid vowel,null/velar onset→spread vowel,spread vowel→liquid,liquid→open-mid vowel,open-mid vowel→alveolar,alveolar→open vowel,affricate→open vowel,open vowel→low-visibility coda,low-visibility coda→bilabial closure,bilabial closure→rounded/protruded vowel,rounded/protruded vowel→alveolar,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,null/velar onset→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→rounded vowel,bilabial closure→open vowel,open vowel→low-visibility velar,low-visibility velar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,bilabial closure→open vowel,open vowel→liquid,liquid→open vowel,open vowel→bilabial closure,bilabial closure→rounded vowel,rounded vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅏ:open vowel,ㅊ:affricate,ㅣ:spread vowel,ㅁ:bilabial closure,ㅔ:front/open-mid vowel | ㅇ:null/velar onset,ㅣ:spread vowel,ㄹ:liquid,ㅓ:open-mid vowel,ㄴ:alveolar,ㅏ:open vowel | ㅊ:affricate,ㅏ:open vowel,ㅇ:low-visibility coda,ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄴ:alveolar,ㅡ:neutral/unrounded vowel,ㄹ:low-visibility coda | ㅇ:null/velar onset,ㅕ:open-mid vowel,ㄹ:low-visibility coda,ㄱ:low-visibility velar,ㅗ:rounded vowel | ㅂ:bilabial closure,ㅏ:open vowel,ㄲ:low-visibility velar,ㅡ:neutral/unrounded vowel,ㄹ:low-visibility coda | ㅂ:bilabial closure,ㅏ:open vowel,ㄹ:liquid,ㅏ:open vowel,ㅂ:bilabial closure,ㅘ:rounded vowel,ㄷ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅇ:null/velar onset→ㅏ:open vowel,ㅏ:open vowel→ㅊ:affricate,ㅊ:affricate→ㅣ:spread vowel,ㅣ:spread vowel→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅔ:front/open-mid vowel,ㅇ:null/velar onset→ㅣ:spread vowel,ㅣ:spread vowel→ㄹ:liquid,ㄹ:liquid→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄴ:alveolar,ㄴ:alveolar→ㅏ:open vowel,ㅊ:affricate→ㅏ:open vowel,ㅏ:open vowel→ㅇ:low-visibility coda,ㅇ:low-visibility coda→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄴ:alveolar,ㄴ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:low-visibility coda,ㅇ:null/velar onset→ㅕ:open-mid vowel,ㅕ:open-mid vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅗ:rounded vowel,ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄲ:low-visibility velar,ㄲ:low-visibility velar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:low-visibility coda,ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄹ:liquid,ㄹ:liquid→ㅏ:open vowel,ㅏ:open vowel→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅘ:rounded vowel,ㅘ:rounded vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.38</td>
        <td>0.5454545454545450</td>
        <td>0.25</td>
        <td>0.7777777777777780</td>
        <td>0.2542372881355930</td>
        <td>0.1297071129707110</td>
        <td>0.31895324209840300</td>
        <td>0.35894538606403000</td>
        <td>0.25454463828181700</td>
        <td>0.1003584229390680</td>
        <td>0.10389356420143400</td>
        <td>0.11692032119349500</td>
        <td>0.0829135629582466</td>
      </tr>
      <tr>
        <td class="line-num">89</td>
        <td>S003</td>
        <td>sentence</td>
        <td>학교가 끝나고 친구와 같이 집에 돌아왔다.</td>
        <td>18</td>
        <td>3.0</td>
        <td>3.3</td>
        <td>0.3</td>
        <td>학꾜가 끈나고 친구와 가치 지베 도라왇따</td>
        <td>ㅎ,ㄲ,ㄴ,ㄱ,ㅊ,ㅇ,ㅈ,ㅂ,ㄷ,ㄹ,ㄸ</td>
        <td>ㅏ,ㅛ,ㅡ,ㅗ,ㅣ,ㅜ,ㅘ,ㅔ</td>
        <td>ㄴ, ㄷ</td>
        <td>ㅎ-ㅏ-ㄱ-ㄲ-ㅛ-ㄱ-ㅏ | ㄲ-ㅡ-ㄴ-ㄴ-ㅏ-ㄱ-ㅗ | ㅊ-ㅣ-ㄴ-ㄱ-ㅜ-ㅇ-ㅘ | ㄱ-ㅏ-ㅊ-ㅣ | ㅈ-ㅣ-ㅂ-ㅔ | ㄷ-ㅗ-ㄹ-ㅏ-ㅇ-ㅘ-ㄷ-ㄸ-ㅏ</td>
        <td>ㅎ,ㅏ,ㄱ,ㄲ,ㅛ,ㅡ,ㄴ,ㅗ,ㅊ,ㅣ,ㅜ,ㅇ,ㅘ,ㅈ,ㅂ,ㅔ,ㄷ,ㄹ,ㄸ</td>
        <td>ㅎ→ㅏ,ㅏ→ㄱ,ㄱ→ㄲ,ㄲ→ㅛ,ㅛ→ㄱ,ㄱ→ㅏ; ㄲ→ㅡ,ㅡ→ㄴ,ㄴ→ㄴ,ㄴ→ㅏ,ㅏ→ㄱ,ㄱ→ㅗ; ㅊ→ㅣ,ㅣ→ㄴ,ㄴ→ㄱ,ㄱ→ㅜ,ㅜ→ㅇ,ㅇ→ㅘ; ㄱ→ㅏ,ㅏ→ㅊ,ㅊ→ㅣ; ㅈ→ㅣ,ㅣ→ㅂ,ㅂ→ㅔ; ㄷ→ㅗ,ㅗ→ㄹ,ㄹ→ㅏ,ㅏ→ㅇ,ㅇ→ㅘ,ㅘ→ㄷ,ㄷ→ㄸ,ㄸ→ㅏ</td>
        <td>ㅏ→ㄲ, ㅗ→ㅊ, ㅘ→ㄱ, ㅣ→ㅈ, ㅔ→ㄷ</td>
        <td>tensification;nasal_assimilation;palatalization;resyllabification</td>
        <td>4.0</td>
        <td>glottal → open vowel → low-visibility coda → low-visibility velar → rounded vowel → low-visibility velar → open vowel | low-visibility velar → neutral/unrounded vowel → low-visibility coda → alveolar → open vowel → low-visibility velar → rounded vowel | affricate → spread vowel → low-visibility coda → low-visibility velar → rounded/protruded vowel → null/velar onset → rounded vowel | low-visibility velar → open vowel → affricate → spread vowel | affricate → spread vowel → bilabial closure → front/open-mid vowel | alveolar → rounded vowel → liquid → open vowel → null/velar onset → rounded vowel → low-visibility coda → alveolar → open vowel</td>
        <td>glottal,open vowel,low-visibility coda,low-visibility velar,rounded vowel,neutral/unrounded vowel,alveolar,affricate,spread vowel,rounded/protruded vowel,null/velar onset,bilabial closure,front/open-mid vowel,liquid</td>
        <td>glottal→open vowel,open vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→rounded vowel,rounded vowel→low-visibility velar,low-visibility velar→open vowel,low-visibility velar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel,open vowel→low-visibility velar,low-visibility velar→rounded vowel,affricate→spread vowel,spread vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→rounded/protruded vowel,rounded/protruded vowel→null/velar onset,null/velar onset→rounded vowel,low-visibility velar→open vowel,open vowel→affricate,affricate→spread vowel,affricate→spread vowel,spread vowel→bilabial closure,bilabial closure→front/open-mid vowel,alveolar→rounded vowel,rounded vowel→liquid,liquid→open vowel,open vowel→null/velar onset,null/velar onset→rounded vowel,rounded vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅎ:glottal,ㅏ:open vowel,ㄱ:low-visibility coda,ㄲ:low-visibility velar,ㅛ:rounded vowel,ㄱ:low-visibility velar,ㅏ:open vowel | ㄲ:low-visibility velar,ㅡ:neutral/unrounded vowel,ㄴ:low-visibility coda,ㄴ:alveolar,ㅏ:open vowel,ㄱ:low-visibility velar,ㅗ:rounded vowel | ㅊ:affricate,ㅣ:spread vowel,ㄴ:low-visibility coda,ㄱ:low-visibility velar,ㅜ:rounded/protruded vowel,ㅇ:null/velar onset,ㅘ:rounded vowel | ㄱ:low-visibility velar,ㅏ:open vowel,ㅊ:affricate,ㅣ:spread vowel | ㅈ:affricate,ㅣ:spread vowel,ㅂ:bilabial closure,ㅔ:front/open-mid vowel | ㄷ:alveolar,ㅗ:rounded vowel,ㄹ:liquid,ㅏ:open vowel,ㅇ:null/velar onset,ㅘ:rounded vowel,ㄷ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅎ:glottal→ㅏ:open vowel,ㅏ:open vowel→ㄱ:low-visibility coda,ㄱ:low-visibility coda→ㄲ:low-visibility velar,ㄲ:low-visibility velar→ㅛ:rounded vowel,ㅛ:rounded vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅏ:open vowel,ㄲ:low-visibility velar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㄴ:alveolar,ㄴ:alveolar→ㅏ:open vowel,ㅏ:open vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅗ:rounded vowel,ㅊ:affricate→ㅣ:spread vowel,ㅣ:spread vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅘ:rounded vowel,ㄱ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㅊ:affricate,ㅊ:affricate→ㅣ:spread vowel,ㅈ:affricate→ㅣ:spread vowel,ㅣ:spread vowel→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅔ:front/open-mid vowel,ㄷ:alveolar→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄹ:liquid,ㄹ:liquid→ㅏ:open vowel,ㅏ:open vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅘ:rounded vowel,ㅘ:rounded vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.38</td>
        <td>0.36363636363636400</td>
        <td>0.5</td>
        <td>0.7777777777777780</td>
        <td>0.2033898305084750</td>
        <td>0.12133891213389100</td>
        <td>0.33420658194851700</td>
        <td>0.3182674199623350</td>
        <td>0.24416095001121400</td>
        <td>0.0931899641577061</td>
        <td>0.10127472180258100</td>
        <td>0.09644467271585920</td>
        <td>0.0739881666700648</td>
      </tr>
      <tr>
        <td class="line-num">90</td>
        <td>S004</td>
        <td>sentence</td>
        <td>점심에는 따뜻한 국물과 밥을 함께 먹었다.</td>
        <td>17</td>
        <td>3.0</td>
        <td>3.23</td>
        <td>0.21</td>
        <td>점시메는 따뜨탄 궁물과 바블 함께 머걷따</td>
        <td>ㅈ,ㅅ,ㅇ,ㄴ,ㄸ,ㅎ,ㄱ,ㅁ,ㅂ,ㄲ,ㄷ</td>
        <td>ㅓ,ㅣ,ㅔ,ㅡ,ㅏ,ㅜ,ㅘ</td>
        <td>ㅁ, ㅇ, ㄷ</td>
        <td>ㅈ-ㅓ-ㅁ-ㅅ-ㅣ-ㅁ-ㅔ-ㄴ-ㅡ-ㄴ | ㄸ-ㅏ-ㄸ-ㅡ-ㅌ-ㅏ-ㄴ | ㄱ-ㅜ-ㅇ-ㅁ-ㅜ-ㄹ-ㄱ-ㅘ | ㅂ-ㅏ-ㅂ-ㅡ-ㄹ | ㅎ-ㅏ-ㅁ-ㄲ-ㅔ | ㅁ-ㅓ-ㄱ-ㅓ-ㄷ-ㄸ-ㅏ</td>
        <td>ㅈ,ㅓ,ㅁ,ㅅ,ㅣ,ㅔ,ㄴ,ㅡ,ㄸ,ㅏ,ㅌ,ㄱ,ㅜ,ㅇ,ㄹ,ㅘ,ㅂ,ㅎ,ㄲ,ㄷ</td>
        <td>ㅈ→ㅓ,ㅓ→ㅁ,ㅁ→ㅅ,ㅅ→ㅣ,ㅣ→ㅁ,ㅁ→ㅔ,ㅔ→ㄴ,ㄴ→ㅡ,ㅡ→ㄴ; ㄸ→ㅏ,ㅏ→ㄸ,ㄸ→ㅡ,ㅡ→ㅌ,ㅌ→ㅏ,ㅏ→ㄴ; ㄱ→ㅜ,ㅜ→ㅇ,ㅇ→ㅁ,ㅁ→ㅜ,ㅜ→ㄹ,ㄹ→ㄱ,ㄱ→ㅘ; ㅂ→ㅏ,ㅏ→ㅂ,ㅂ→ㅡ,ㅡ→ㄹ; ㅎ→ㅏ,ㅏ→ㅁ,ㅁ→ㄲ,ㄲ→ㅔ; ㅁ→ㅓ,ㅓ→ㄱ,ㄱ→ㅓ,ㅓ→ㄷ,ㄷ→ㄸ,ㄸ→ㅏ</td>
        <td>ㄴ→ㄸ, ㄴ→ㄱ, ㅘ→ㅂ, ㄹ→ㅎ, ㅔ→ㅁ</td>
        <td>resyllabification;aspiration;nasal_assimilation;tensification</td>
        <td>4.0</td>
        <td>affricate → open-mid vowel → bilabial nasal coda → fricative → spread vowel → bilabial closure → front/open-mid vowel → alveolar → neutral/unrounded vowel → low-visibility coda | alveolar → open vowel → alveolar → neutral/unrounded vowel → alveolar → open vowel → low-visibility coda | low-visibility velar → rounded/protruded vowel → low-visibility coda → bilabial closure → rounded/protruded vowel → low-visibility coda → low-visibility velar → rounded vowel | bilabial closure → open vowel → bilabial closure → neutral/unrounded vowel → low-visibility coda | glottal → open vowel → bilabial nasal coda → low-visibility velar → front/open-mid vowel | bilabial closure → open-mid vowel → low-visibility velar → open-mid vowel → low-visibility coda → alveolar → open vowel</td>
        <td>affricate,open-mid vowel,bilabial nasal coda,fricative,spread vowel,bilabial closure,front/open-mid vowel,alveolar,neutral/unrounded vowel,low-visibility coda,open vowel,low-visibility velar,rounded/protruded vowel,rounded vowel,glottal</td>
        <td>affricate→open-mid vowel,open-mid vowel→bilabial nasal coda,bilabial nasal coda→fricative,fricative→spread vowel,spread vowel→bilabial closure,bilabial closure→front/open-mid vowel,front/open-mid vowel→alveolar,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,alveolar→open vowel,open vowel→alveolar,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→alveolar,alveolar→open vowel,open vowel→low-visibility coda,low-visibility velar→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,low-visibility coda→bilabial closure,bilabial closure→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→rounded vowel,bilabial closure→open vowel,open vowel→bilabial closure,bilabial closure→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,glottal→open vowel,open vowel→bilabial nasal coda,bilabial nasal coda→low-visibility velar,low-visibility velar→front/open-mid vowel,bilabial closure→open-mid vowel,open-mid vowel→low-visibility velar,low-visibility velar→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅈ:affricate,ㅓ:open-mid vowel,ㅁ:bilabial nasal coda,ㅅ:fricative,ㅣ:spread vowel,ㅁ:bilabial closure,ㅔ:front/open-mid vowel,ㄴ:alveolar,ㅡ:neutral/unrounded vowel,ㄴ:low-visibility coda | ㄸ:alveolar,ㅏ:open vowel,ㄸ:alveolar,ㅡ:neutral/unrounded vowel,ㅌ:alveolar,ㅏ:open vowel,ㄴ:low-visibility coda | ㄱ:low-visibility velar,ㅜ:rounded/protruded vowel,ㅇ:low-visibility coda,ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄹ:low-visibility coda,ㄱ:low-visibility velar,ㅘ:rounded vowel | ㅂ:bilabial closure,ㅏ:open vowel,ㅂ:bilabial closure,ㅡ:neutral/unrounded vowel,ㄹ:low-visibility coda | ㅎ:glottal,ㅏ:open vowel,ㅁ:bilabial nasal coda,ㄲ:low-visibility velar,ㅔ:front/open-mid vowel | ㅁ:bilabial closure,ㅓ:open-mid vowel,ㄱ:low-visibility velar,ㅓ:open-mid vowel,ㄷ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅈ:affricate→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㅁ:bilabial nasal coda,ㅁ:bilabial nasal coda→ㅅ:fricative,ㅅ:fricative→ㅣ:spread vowel,ㅣ:spread vowel→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅔ:front/open-mid vowel,ㅔ:front/open-mid vowel→ㄴ:alveolar,ㄴ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄴ:low-visibility coda,ㄸ:alveolar→ㅏ:open vowel,ㅏ:open vowel→ㄸ:alveolar,ㄸ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㅌ:alveolar,ㅌ:alveolar→ㅏ:open vowel,ㅏ:open vowel→ㄴ:low-visibility coda,ㄱ:low-visibility velar→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㅇ:low-visibility coda,ㅇ:low-visibility coda→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅘ:rounded vowel,ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅂ:bilabial closure,ㅂ:bilabial closure→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:low-visibility coda,ㅎ:glottal→ㅏ:open vowel,ㅏ:open vowel→ㅁ:bilabial nasal coda,ㅁ:bilabial nasal coda→ㄲ:low-visibility velar,ㄲ:low-visibility velar→ㅔ:front/open-mid vowel,ㅁ:bilabial closure→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.4</td>
        <td>0.7272727272727270</td>
        <td>0.5</td>
        <td>0.8333333333333330</td>
        <td>0.2627118644067800</td>
        <td>0.14644351464435100</td>
        <td>0.43459595959596000</td>
        <td>0.37683615819209000</td>
        <td>0.30077359134975600</td>
        <td>0.1111111111111110</td>
        <td>0.13454983269224800</td>
        <td>0.11666754123594100</td>
        <td>0.09311875893181310</td>
      </tr>
      <tr>
        <td class="line-num">91</td>
        <td>S005</td>
        <td>sentence</td>
        <td>오늘 저녁에는 뭐 먹을까?</td>
        <td>11</td>
        <td>2.0</td>
        <td>2.0</td>
        <td>0.0</td>
        <td>오늘 저녀게는 뭐 머글까</td>
        <td>ㅇ,ㅈ,ㅁ,ㄱ,ㄲ</td>
        <td>ㅗ,ㅡ,ㅓ,ㅕ,ㅔ,ㅝ,ㅏ</td>
        <td>ㄹ, ㄴ</td>
        <td>ㅇ-ㅗ-ㄴ-ㅡ-ㄹ | ㅈ-ㅓ-ㄴ-ㅕ-ㅇ-ㅇ-ㅔ-ㄴ-ㅡ-ㄴ | ㅁ-ㅝ | ㅁ-ㅓ-ㄱ-ㅡ-ㄹ-ㄲ-ㅏ</td>
        <td>ㅇ→ㅗ,ㅗ→ㄴ,ㄴ→ㅡ,ㅡ→ㄹ; ㅈ→ㅓ,ㅓ→ㄴ,ㄴ→ㅕ,ㅕ→ㅇ,ㅇ→ㅇ,ㅇ→ㅔ,ㅔ→ㄴ,ㄴ→ㅡ,ㅡ→ㄴ; ㅁ→ㅝ; ㅁ→ㅓ,ㅓ→ㄱ,ㄱ→ㅡ,ㅡ→ㄹ,ㄹ→ㄲ,ㄲ→ㅏ</td>
        <td>ㅇ→ㅗ / ㄴ,ㅗ / ㄴ→ㅡ,ㅡ→ㄹ / ㅈ,ㄹ / ㅈ→ㅓ / ㄴ,ㅓ / ㄴ→ㅕ,ㅕ→ㄱ / ㅇ,ㄱ / ㅇ→ㅔ / ㄴ,ㅔ / ㄴ→ㅡ,ㅡ→ㄴ / ㅁ,ㄴ / ㅁ→ㅝ / ㅁ,ㅝ / ㅁ→ㅓ,ㅓ→ㄱ / ㅇ,ㄱ / ㅇ→ㅡ,ㅡ→ㄹ / ㄲ,ㄹ / ㄲ→ㅏ</td>
        <td>ㄹ→ㅈ, ㄴ→ㅁ, ㅝ→ㅁ</td>
        <td>resyllabification</td>
        <td>1.0</td>
        <td>null/velar onset → rounded vowel → alveolar → neutral/unrounded vowel → low-visibility coda | affricate → open-mid vowel → alveolar → open-mid vowel → low-visibility velar → front/open-mid vowel → alveolar → neutral/unrounded vowel → low-visibility coda | bilabial closure → rounded vowel | bilabial closure → open-mid vowel → low-visibility velar → neutral/unrounded vowel → low-visibility coda → low-visibility velar → open vowel</td>
        <td>null/velar onset,rounded vowel,alveolar,neutral/unrounded vowel,low-visibility coda,affricate,open-mid vowel,low-visibility velar,front/open-mid vowel,bilabial closure,open vowel</td>
        <td>null/velar onset→rounded vowel,rounded vowel→alveolar,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,affricate→open-mid vowel,open-mid vowel→alveolar,alveolar→open-mid vowel,open-mid vowel→low-visibility velar,low-visibility velar→front/open-mid vowel,front/open-mid vowel→alveolar,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,bilabial closure→rounded vowel,bilabial closure→open-mid vowel,open-mid vowel→low-visibility velar,low-visibility velar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅗ:rounded vowel,ㄴ:alveolar,ㅡ:neutral/unrounded vowel,ㄹ:low-visibility coda | ㅈ:affricate,ㅓ:open-mid vowel,ㄴ:alveolar,ㅕ:open-mid vowel,ㄱ:low-visibility velar,ㅔ:front/open-mid vowel,ㄴ:alveolar,ㅡ:neutral/unrounded vowel,ㄴ:low-visibility coda | ㅁ:bilabial closure,ㅝ:rounded vowel | ㅁ:bilabial closure,ㅓ:open-mid vowel,ㄱ:low-visibility velar,ㅡ:neutral/unrounded vowel,ㄹ:low-visibility coda,ㄲ:low-visibility velar,ㅏ:open vowel</td>
        <td>ㅇ:null/velar onset→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄴ:alveolar,ㄴ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:low-visibility coda,ㅈ:affricate→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄴ:alveolar,ㄴ:alveolar→ㅕ:open-mid vowel,ㅕ:open-mid vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅔ:front/open-mid vowel,ㅔ:front/open-mid vowel→ㄴ:alveolar,ㄴ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄴ:low-visibility coda,ㅁ:bilabial closure→ㅝ:rounded vowel,ㅁ:bilabial closure→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄲ:low-visibility velar,ㄲ:low-visibility velar→ㅏ:open vowel</td>
        <td>0.32</td>
        <td>0.36363636363636400</td>
        <td>0.125</td>
        <td>0.6111111111111110</td>
        <td>0.1271186440677970</td>
        <td>0.07112970711297070</td>
        <td>0.21559995112414500</td>
        <td>0.22391713747646000</td>
        <td>0.16025978943037300</td>
        <td>0.053763440860215100</td>
        <td>0.10779997556207200</td>
        <td>0.11195856873823000</td>
        <td>0.08012989471518630</td>
      </tr>
      <tr>
        <td class="line-num">92</td>
        <td>S006</td>
        <td>sentence</td>
        <td>잠깐만, 물 좀 마시고 가자.</td>
        <td>11</td>
        <td>2.0</td>
        <td>2.23</td>
        <td>0.21</td>
        <td>잠깐만 물 좀 마시고 가자</td>
        <td>ㅈ,ㄲ,ㅁ,ㅅ,ㄱ</td>
        <td>ㅏ,ㅜ,ㅗ,ㅣ</td>
        <td>ㅁ, ㄴ, ㄹ</td>
        <td>ㅈ-ㅏ-ㅁ-ㄲ-ㅏ-ㄴ-ㅁ-ㅏ-ㄴ | ㅁ-ㅜ-ㄹ | ㅈ-ㅗ-ㅁ | ㅁ-ㅏ-ㅅ-ㅣ-ㄱ-ㅗ | ㄱ-ㅏ-ㅈ-ㅏ</td>
        <td>ㅈ,ㅏ,ㅁ,ㄲ,ㄴ,ㅜ,ㄹ,ㅗ,ㅅ,ㅣ,ㄱ</td>
        <td>ㅈ→ㅏ,ㅏ→ㅁ,ㅁ→ㄲ,ㄲ→ㅏ,ㅏ→ㄴ,ㄴ→ㅁ,ㅁ→ㅏ,ㅏ→ㄴ; ㅁ→ㅜ,ㅜ→ㄹ; ㅈ→ㅗ,ㅗ→ㅁ; ㅁ→ㅏ,ㅏ→ㅅ,ㅅ→ㅣ,ㅣ→ㄱ,ㄱ→ㅗ; ㄱ→ㅏ,ㅏ→ㅈ,ㅈ→ㅏ</td>
        <td>ㄴ→ㅁ, ㄹ→ㅈ, ㅁ→ㅁ, ㅗ→ㄱ</td>
        <td></td>
        <td></td>
        <td>affricate → open vowel → bilabial nasal coda → low-visibility velar → open vowel → low-visibility coda → bilabial closure → open vowel → low-visibility coda | bilabial closure → rounded/protruded vowel → low-visibility coda | affricate → rounded vowel → bilabial nasal coda | bilabial closure → open vowel → fricative → spread vowel → low-visibility velar → rounded vowel | low-visibility velar → open vowel → affricate → open vowel</td>
        <td>affricate,open vowel,bilabial nasal coda,low-visibility velar,low-visibility coda,bilabial closure,rounded/protruded vowel,rounded vowel,fricative,spread vowel</td>
        <td>affricate→open vowel,open vowel→bilabial nasal coda,bilabial nasal coda→low-visibility velar,low-visibility velar→open vowel,open vowel→low-visibility coda,low-visibility coda→bilabial closure,bilabial closure→open vowel,open vowel→low-visibility coda,bilabial closure→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,affricate→rounded vowel,rounded vowel→bilabial nasal coda,bilabial closure→open vowel,open vowel→fricative,fricative→spread vowel,spread vowel→low-visibility velar,low-visibility velar→rounded vowel,low-visibility velar→open vowel,open vowel→affricate,affricate→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅈ:affricate,ㅏ:open vowel,ㅁ:bilabial nasal coda,ㄲ:low-visibility velar,ㅏ:open vowel,ㄴ:low-visibility coda,ㅁ:bilabial closure,ㅏ:open vowel,ㄴ:low-visibility coda | ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄹ:low-visibility coda | ㅈ:affricate,ㅗ:rounded vowel,ㅁ:bilabial nasal coda | ㅁ:bilabial closure,ㅏ:open vowel,ㅅ:fricative,ㅣ:spread vowel,ㄱ:low-visibility velar,ㅗ:rounded vowel | ㄱ:low-visibility velar,ㅏ:open vowel,ㅈ:affricate,ㅏ:open vowel</td>
        <td>ㅈ:affricate→ㅏ:open vowel,ㅏ:open vowel→ㅁ:bilabial nasal coda,ㅁ:bilabial nasal coda→ㄲ:low-visibility velar,ㄲ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄴ:low-visibility coda,ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄹ:low-visibility coda,ㅈ:affricate→ㅗ:rounded vowel,ㅗ:rounded vowel→ㅁ:bilabial nasal coda,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅅ:fricative,ㅅ:fricative→ㅣ:spread vowel,ㅣ:spread vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅗ:rounded vowel,ㄱ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㅈ:affricate,ㅈ:affricate→ㅏ:open vowel</td>
        <td>0.22</td>
        <td>0.2727272727272730</td>
        <td>0.0</td>
        <td>0.5555555555555560</td>
        <td>0.13559322033898300</td>
        <td>0.07112970711297070</td>
        <td>0.13662267839687200</td>
        <td>0.21958568738229800</td>
        <td>0.1295176189290130</td>
        <td>0.053763440860215100</td>
        <td>0.06126577506586190</td>
        <td>0.09846891810865360</td>
        <td>0.0580796497439518</td>
      </tr>
      <tr>
        <td class="line-num">93</td>
        <td>S007</td>
        <td>sentence</td>
        <td>주말에는 친구를 만나 영화도 보고 밥도 먹었다.</td>
        <td>20</td>
        <td>3.3</td>
        <td>3.47</td>
        <td>0.15</td>
        <td>주마레는 친구를 만나 영화도 보고 밥또 머걷따</td>
        <td>ㅈ,ㅁ,ㅇ,ㄴ,ㅊ,ㄱ,ㅎ,ㄷ,ㅂ,ㄸ</td>
        <td>ㅜ,ㅏ,ㅔ,ㅡ,ㅣ,ㅕ,ㅘ,ㅗ,ㅓ</td>
        <td>ㄴ, ㄹ, ㅇ, ㅂ, ㄷ</td>
        <td>ㅈ-ㅜ-ㅁ-ㅏ-ㄹ-ㅔ-ㄴ-ㅡ-ㄴ | ㅊ-ㅣ-ㄴ-ㄱ-ㅜ-ㄹ-ㅡ-ㄹ | ㅁ-ㅏ-ㄴ-ㄴ-ㅏ | ㅇ-ㅕ-ㅇ-ㅎ-ㅘ-ㄷ-ㅗ | ㅂ-ㅗ-ㄱ-ㅗ | ㅂ-ㅏ-ㅂ-ㄸ-ㅗ | ㅁ-ㅓ-ㄱ-ㅓ-ㄷ-ㄸ-ㅏ</td>
        <td>ㅈ,ㅜ,ㅁ,ㅏ,ㄹ,ㅔ,ㄴ,ㅡ,ㅊ,ㅣ,ㄱ,ㅇ,ㅕ,ㅎ,ㅘ,ㄷ,ㅗ,ㅂ,ㄸ,ㅓ</td>
        <td>ㅈ→ㅜ,ㅜ→ㅁ,ㅁ→ㅏ,ㅏ→ㄹ,ㄹ→ㅔ,ㅔ→ㄴ,ㄴ→ㅡ,ㅡ→ㄴ; ㅊ→ㅣ,ㅣ→ㄴ,ㄴ→ㄱ,ㄱ→ㅜ,ㅜ→ㄹ,ㄹ→ㅡ,ㅡ→ㄹ; ㅁ→ㅏ,ㅏ→ㄴ,ㄴ→ㄴ,ㄴ→ㅏ; ㅇ→ㅕ,ㅕ→ㅇ,ㅇ→ㅎ,ㅎ→ㅘ,ㅘ→ㄷ,ㄷ→ㅗ; ㅂ→ㅗ,ㅗ→ㄱ,ㄱ→ㅗ; ㅂ→ㅏ,ㅏ→ㅂ,ㅂ→ㄸ,ㄸ→ㅗ; ㅁ→ㅓ,ㅓ→ㄱ,ㄱ→ㅓ,ㅓ→ㄷ,ㄷ→ㄸ,ㄸ→ㅏ</td>
        <td>ㄴ→ㅊ, ㄹ→ㅁ, ㅏ→ㅇ, ㅗ→ㅂ, ㅗ→ㅂ, ㅗ→ㅁ</td>
        <td>resyllabification;tensification</td>
        <td>2.0</td>
        <td>affricate → rounded/protruded vowel → bilabial closure → open vowel → liquid → front/open-mid vowel → alveolar → neutral/unrounded vowel → low-visibility coda | affricate → spread vowel → low-visibility coda → low-visibility velar → rounded/protruded vowel → liquid → neutral/unrounded vowel → low-visibility coda | bilabial closure → open vowel → low-visibility coda → alveolar → open vowel | null/velar onset → open-mid vowel → low-visibility coda → glottal → rounded vowel → alveolar → rounded vowel | bilabial closure → rounded vowel → low-visibility velar → rounded vowel | bilabial closure → open vowel → bilabial coda closure → alveolar → rounded vowel | bilabial closure → open-mid vowel → low-visibility velar → open-mid vowel → low-visibility coda → alveolar → open vowel</td>
        <td>affricate,rounded/protruded vowel,bilabial closure,open vowel,liquid,front/open-mid vowel,alveolar,neutral/unrounded vowel,low-visibility coda,spread vowel,low-visibility velar,null/velar onset,open-mid vowel,glottal,rounded vowel,bilabial coda closure</td>
        <td>affricate→rounded/protruded vowel,rounded/protruded vowel→bilabial closure,bilabial closure→open vowel,open vowel→liquid,liquid→front/open-mid vowel,front/open-mid vowel→alveolar,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,affricate→spread vowel,spread vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→rounded/protruded vowel,rounded/protruded vowel→liquid,liquid→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,bilabial closure→open vowel,open vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel,null/velar onset→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→glottal,glottal→rounded vowel,rounded vowel→alveolar,alveolar→rounded vowel,bilabial closure→rounded vowel,rounded vowel→low-visibility velar,low-visibility velar→rounded vowel,bilabial closure→open vowel,open vowel→bilabial coda closure,bilabial coda closure→alveolar,alveolar→rounded vowel,bilabial closure→open-mid vowel,open-mid vowel→low-visibility velar,low-visibility velar→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅈ:affricate,ㅜ:rounded/protruded vowel,ㅁ:bilabial closure,ㅏ:open vowel,ㄹ:liquid,ㅔ:front/open-mid vowel,ㄴ:alveolar,ㅡ:neutral/unrounded vowel,ㄴ:low-visibility coda | ㅊ:affricate,ㅣ:spread vowel,ㄴ:low-visibility coda,ㄱ:low-visibility velar,ㅜ:rounded/protruded vowel,ㄹ:liquid,ㅡ:neutral/unrounded vowel,ㄹ:low-visibility coda | ㅁ:bilabial closure,ㅏ:open vowel,ㄴ:low-visibility coda,ㄴ:alveolar,ㅏ:open vowel | ㅇ:null/velar onset,ㅕ:open-mid vowel,ㅇ:low-visibility coda,ㅎ:glottal,ㅘ:rounded vowel,ㄷ:alveolar,ㅗ:rounded vowel | ㅂ:bilabial closure,ㅗ:rounded vowel,ㄱ:low-visibility velar,ㅗ:rounded vowel | ㅂ:bilabial closure,ㅏ:open vowel,ㅂ:bilabial coda closure,ㄸ:alveolar,ㅗ:rounded vowel | ㅁ:bilabial closure,ㅓ:open-mid vowel,ㄱ:low-visibility velar,ㅓ:open-mid vowel,ㄷ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅈ:affricate→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㅁ:bilabial closure,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄹ:liquid,ㄹ:liquid→ㅔ:front/open-mid vowel,ㅔ:front/open-mid vowel→ㄴ:alveolar,ㄴ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄴ:low-visibility coda,ㅊ:affricate→ㅣ:spread vowel,ㅣ:spread vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄹ:liquid,ㄹ:liquid→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:low-visibility coda,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㄴ:alveolar,ㄴ:alveolar→ㅏ:open vowel,ㅇ:null/velar onset→ㅕ:open-mid vowel,ㅕ:open-mid vowel→ㅇ:low-visibility coda,ㅇ:low-visibility coda→ㅎ:glottal,ㅎ:glottal→ㅘ:rounded vowel,ㅘ:rounded vowel→ㄷ:alveolar,ㄷ:alveolar→ㅗ:rounded vowel,ㅂ:bilabial closure→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅗ:rounded vowel,ㅂ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅂ:bilabial coda closure,ㅂ:bilabial coda closure→ㄸ:alveolar,ㄸ:alveolar→ㅗ:rounded vowel,ㅁ:bilabial closure→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.4</td>
        <td>0.5454545454545450</td>
        <td>0.25</td>
        <td>0.8888888888888890</td>
        <td>0.2627118644067800</td>
        <td>0.15481171548117200</td>
        <td>0.32753747148908400</td>
        <td>0.38794726930320200</td>
        <td>0.27503994968557600</td>
        <td>0.11469534050179200</td>
        <td>0.09439120215823760</td>
        <td>0.11180036579343000</td>
        <td>0.07926223333878280</td>
      </tr>
      <tr>
        <td class="line-num">94</td>
        <td>S008</td>
        <td>sentence</td>
        <td>이 옷보다 파란색이 더 잘 어울리는 것 같아.</td>
        <td>18</td>
        <td>3.0</td>
        <td>2.83</td>
        <td>0.15</td>
        <td>이 옫뽀다 파란새기 더 잘 어울리는 걷 까타</td>
        <td>ㅇ,ㅂ,ㄷ,ㅍ,ㄹ,ㅅ,ㄱ,ㅈ,ㄲ,ㅌ</td>
        <td>ㅣ,ㅗ,ㅏ,ㅐ,ㅓ,ㅜ,ㅡ</td>
        <td>ㄷ, ㄴ, ㄹ</td>
        <td>ㅇ-ㅣ | ㅇ-ㅗ-ㄷ-ㅃ-ㅗ-ㄷ-ㅏ | ㅍ-ㅏ-ㄹ-ㅏ-ㄴ-ㅅ-ㅐ-ㄱ-ㅣ | ㄷ-ㅓ | ㅈ-ㅏ-ㄹ | ㅇ-ㅓ-ㅇ-ㅜ-ㄹ-ㄹ-ㅣ-ㄴ-ㅡ-ㄴ | ㄱ-ㅓ-ㄷ | ㄲ-ㅏ-ㅌ-ㅏ</td>
        <td>ㅇ,ㅣ,ㅗ,ㄷ,ㅃ,ㅏ,ㅍ,ㄹ,ㄴ,ㅅ,ㅐ,ㄱ,ㅓ,ㅈ,ㅜ,ㅡ,ㄲ,ㅌ</td>
        <td>ㅇ→ㅣ; ㅇ→ㅗ,ㅗ→ㄷ,ㄷ→ㅃ,ㅃ→ㅗ,ㅗ→ㄷ,ㄷ→ㅏ; ㅍ→ㅏ,ㅏ→ㄹ,ㄹ→ㅏ,ㅏ→ㄴ,ㄴ→ㅅ,ㅅ→ㅐ,ㅐ→ㄱ,ㄱ→ㅣ; ㄷ→ㅓ; ㅈ→ㅏ,ㅏ→ㄹ; ㅇ→ㅓ,ㅓ→ㅇ,ㅇ→ㅜ,ㅜ→ㄹ,ㄹ→ㄹ,ㄹ→ㅣ,ㅣ→ㄴ,ㄴ→ㅡ,ㅡ→ㄴ; ㄱ→ㅓ,ㅓ→ㄷ; ㄲ→ㅏ,ㅏ→ㅌ,ㅌ→ㅏ</td>
        <td>ㄴ→ㅊ, ㄹ→ㅁ, ㅏ→ㅇ, ㅗ→ㅂ, ㅗ→ㅂ, ㅗ→ㅁ</td>
        <td>tensification;resyllabification;aspiration</td>
        <td>3.0</td>
        <td>null/velar onset → spread vowel | null/velar onset → rounded vowel → low-visibility coda → bilabial closure → rounded vowel → alveolar → open vowel | bilabial closure → open vowel → liquid → open vowel → low-visibility coda → fricative → front/open-mid vowel → low-visibility velar → spread vowel | alveolar → open-mid vowel | affricate → open vowel → low-visibility coda | null/velar onset → open-mid vowel → null/velar onset → rounded/protruded vowel → low-visibility coda → liquid → spread vowel → alveolar → neutral/unrounded vowel → low-visibility coda | low-visibility velar → open-mid vowel → low-visibility coda | low-visibility velar → open vowel → alveolar → open vowel</td>
        <td>null/velar onset,spread vowel,rounded vowel,low-visibility coda,bilabial closure,alveolar,open vowel,liquid,fricative,front/open-mid vowel,low-visibility velar,open-mid vowel,affricate,rounded/protruded vowel,neutral/unrounded vowel</td>
        <td>null/velar onset→spread vowel,null/velar onset→rounded vowel,rounded vowel→low-visibility coda,low-visibility coda→bilabial closure,bilabial closure→rounded vowel,rounded vowel→alveolar,alveolar→open vowel,bilabial closure→open vowel,open vowel→liquid,liquid→open vowel,open vowel→low-visibility coda,low-visibility coda→fricative,fricative→front/open-mid vowel,front/open-mid vowel→low-visibility velar,low-visibility velar→spread vowel,alveolar→open-mid vowel,affricate→open vowel,open vowel→low-visibility coda,null/velar onset→open-mid vowel,open-mid vowel→null/velar onset,null/velar onset→rounded/protruded vowel,rounded/protruded vowel→low-visibility coda,low-visibility coda→liquid,liquid→spread vowel,spread vowel→alveolar,alveolar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,low-visibility velar→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility velar→open vowel,open vowel→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅣ:spread vowel | ㅇ:null/velar onset,ㅗ:rounded vowel,ㄷ:low-visibility coda,ㅃ:bilabial closure,ㅗ:rounded vowel,ㄷ:alveolar,ㅏ:open vowel | ㅍ:bilabial closure,ㅏ:open vowel,ㄹ:liquid,ㅏ:open vowel,ㄴ:low-visibility coda,ㅅ:fricative,ㅐ:front/open-mid vowel,ㄱ:low-visibility velar,ㅣ:spread vowel | ㄷ:alveolar,ㅓ:open-mid vowel | ㅈ:affricate,ㅏ:open vowel,ㄹ:low-visibility coda | ㅇ:null/velar onset,ㅓ:open-mid vowel,ㅇ:null/velar onset,ㅜ:rounded/protruded vowel,ㄹ:low-visibility coda,ㄹ:liquid,ㅣ:spread vowel,ㄴ:alveolar,ㅡ:neutral/unrounded vowel,ㄴ:low-visibility coda | ㄱ:low-visibility velar,ㅓ:open-mid vowel,ㄷ:low-visibility coda | ㄲ:low-visibility velar,ㅏ:open vowel,ㅌ:alveolar,ㅏ:open vowel</td>
        <td>ㅇ:null/velar onset→ㅣ:spread vowel,ㅇ:null/velar onset→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㅃ:bilabial closure,ㅃ:bilabial closure→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄷ:alveolar,ㄷ:alveolar→ㅏ:open vowel,ㅍ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄹ:liquid,ㄹ:liquid→ㅏ:open vowel,ㅏ:open vowel→ㄴ:low-visibility coda,ㄴ:low-visibility coda→ㅅ:fricative,ㅅ:fricative→ㅐ:front/open-mid vowel,ㅐ:front/open-mid vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅣ:spread vowel,ㄷ:alveolar→ㅓ:open-mid vowel,ㅈ:affricate→ㅏ:open vowel,ㅏ:open vowel→ㄹ:low-visibility coda,ㅇ:null/velar onset→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄹ:liquid,ㄹ:liquid→ㅣ:spread vowel,ㅣ:spread vowel→ㄴ:alveolar,ㄴ:alveolar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄴ:low-visibility coda,ㄱ:low-visibility velar→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄷ:low-visibility coda,ㄲ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㅌ:alveolar,ㅌ:alveolar→ㅏ:open vowel</td>
        <td>0.36</td>
        <td>0.36363636363636400</td>
        <td>0.375</td>
        <td>0.8333333333333330</td>
        <td>0.2542372881355930</td>
        <td>0.13389121338912100</td>
        <td>0.2961644672531770</td>
        <td>0.3700564971751410</td>
        <td>0.2509641135381710</td>
        <td>0.08602150537634410</td>
        <td>0.10465175521313700</td>
        <td>0.13076201313609200</td>
        <td>0.08867989877673870</td>
      </tr>
      <tr>
        <td class="line-num">95</td>
        <td>S009</td>
        <td>sentence</td>
        <td>자기 전에 물을 마시고 책을 조금 읽었다.</td>
        <td>16</td>
        <td>2.7</td>
        <td>2.88</td>
        <td>0.16</td>
        <td>자기 저네 무를 마시고 채글 쪼금 일걷따</td>
        <td>ㅈ,ㄱ,ㄴ,ㅁ,ㅅ,ㅊ,ㅉ,ㅇ,ㄷ,ㄸ</td>
        <td>ㅏ,ㅣ,ㅓ,ㅔ,ㅜ,ㅡ,ㅗ,ㅐ</td>
        <td>ㄹ, ㅁ, ㄷ</td>
        <td>ㅈ-ㅏ-ㄱ-ㅣ | ㅈ-ㅓ-ㄴ-ㅔ | ㅁ-ㅜ-ㄹ-ㅡ-ㄹ | ㅁ-ㅏ-ㅅ-ㅣ-ㄱ-ㅗ | ㅊ-ㅐ-ㄱ-ㅡ-ㄹ | ㅉ-ㅗ-ㄱ-ㅡ-ㅁ | ㅇ-ㅣ-ㄹ-ㄱ-ㅓ-ㄷ-ㄸ-ㅏ</td>
        <td>ㅈ,ㅏ,ㄱ,ㅣ,ㅓ,ㄴ,ㅔ,ㅁ,ㅜ,ㄹ,ㅡ,ㅅ,ㅗ,ㅊ,ㅐ,ㅉ,ㅇ,ㄷ,ㄸ</td>
        <td>ㅈ→ㅏ,ㅏ→ㄱ,ㄱ→ㅣ; ㅈ→ㅓ,ㅓ→ㄴ,ㄴ→ㅔ; ㅁ→ㅜ,ㅜ→ㄹ,ㄹ→ㅡ,ㅡ→ㄹ; ㅁ→ㅏ,ㅏ→ㅅ,ㅅ→ㅣ,ㅣ→ㄱ,ㄱ→ㅗ; ㅊ→ㅐ,ㅐ→ㄱ,ㄱ→ㅡ,ㅡ→ㄹ; ㅉ→ㅗ,ㅗ→ㄱ,ㄱ→ㅡ,ㅡ→ㅁ; ㅇ→ㅣ,ㅣ→ㄹ,ㄹ→ㄱ,ㄱ→ㅓ,ㅓ→ㄷ,ㄷ→ㄸ,ㄸ→ㅏ</td>
        <td>ㅣ→ㅈ, ㅔ→ㅁ, ㄹ→ㅁ, ㅗ→ㅊ, ㄹ→ㅉ, ㅁ→ㅇ</td>
        <td>resyllabification;tensification</td>
        <td>2.0</td>
        <td>affricate → open vowel → low-visibility velar → spread vowel | affricate → open-mid vowel → alveolar → front/open-mid vowel | bilabial closure → rounded/protruded vowel → liquid → neutral/unrounded vowel → low-visibility coda | bilabial closure → open vowel → fricative → spread vowel → low-visibility velar → rounded vowel | affricate → front/open-mid vowel → low-visibility velar → neutral/unrounded vowel → low-visibility coda | affricate → rounded vowel → low-visibility velar → neutral/unrounded vowel → bilabial nasal coda | null/velar onset → spread vowel → low-visibility coda → low-visibility velar → open-mid vowel → low-visibility coda → alveolar → open vowel</td>
        <td>affricate,open vowel,low-visibility velar,spread vowel,open-mid vowel,alveolar,front/open-mid vowel,bilabial closure,rounded/protruded vowel,liquid,neutral/unrounded vowel,low-visibility coda,fricative,rounded vowel,bilabial nasal coda,null/velar onset</td>
        <td>affricate→open vowel,open vowel→low-visibility velar,low-visibility velar→spread vowel,affricate→open-mid vowel,open-mid vowel→alveolar,alveolar→front/open-mid vowel,bilabial closure→rounded/protruded vowel,rounded/protruded vowel→liquid,liquid→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,bilabial closure→open vowel,open vowel→fricative,fricative→spread vowel,spread vowel→low-visibility velar,low-visibility velar→rounded vowel,affricate→front/open-mid vowel,front/open-mid vowel→low-visibility velar,low-visibility velar→neutral/unrounded vowel,neutral/unrounded vowel→low-visibility coda,affricate→rounded vowel,rounded vowel→low-visibility velar,low-visibility velar→neutral/unrounded vowel,neutral/unrounded vowel→bilabial nasal coda,null/velar onset→spread vowel,spread vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→open-mid vowel,open-mid vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅈ:affricate,ㅏ:open vowel,ㄱ:low-visibility velar,ㅣ:spread vowel | ㅈ:affricate,ㅓ:open-mid vowel,ㄴ:alveolar,ㅔ:front/open-mid vowel | ㅁ:bilabial closure,ㅜ:rounded/protruded vowel,ㄹ:liquid,ㅡ:neutral/unrounded vowel,ㄹ:low-visibility coda | ㅁ:bilabial closure,ㅏ:open vowel,ㅅ:fricative,ㅣ:spread vowel,ㄱ:low-visibility velar,ㅗ:rounded vowel | ㅊ:affricate,ㅐ:front/open-mid vowel,ㄱ:low-visibility velar,ㅡ:neutral/unrounded vowel,ㄹ:low-visibility coda | ㅉ:affricate,ㅗ:rounded vowel,ㄱ:low-visibility velar,ㅡ:neutral/unrounded vowel,ㅁ:bilabial nasal coda | ㅇ:null/velar onset,ㅣ:spread vowel,ㄹ:low-visibility coda,ㄱ:low-visibility velar,ㅓ:open-mid vowel,ㄷ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel</td>
        <td>ㅈ:affricate→ㅏ:open vowel,ㅏ:open vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅣ:spread vowel,ㅈ:affricate→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄴ:alveolar,ㄴ:alveolar→ㅔ:front/open-mid vowel,ㅁ:bilabial closure→ㅜ:rounded/protruded vowel,ㅜ:rounded/protruded vowel→ㄹ:liquid,ㄹ:liquid→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:low-visibility coda,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㅅ:fricative,ㅅ:fricative→ㅣ:spread vowel,ㅣ:spread vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅗ:rounded vowel,ㅊ:affricate→ㅐ:front/open-mid vowel,ㅐ:front/open-mid vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㄹ:low-visibility coda,ㅉ:affricate→ㅗ:rounded vowel,ㅗ:rounded vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅡ:neutral/unrounded vowel,ㅡ:neutral/unrounded vowel→ㅁ:bilabial nasal coda,ㅇ:null/velar onset→ㅣ:spread vowel,ㅣ:spread vowel→ㄹ:low-visibility coda,ㄹ:low-visibility coda→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅓ:open-mid vowel,ㅓ:open-mid vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel</td>
        <td>0.38</td>
        <td>0.36363636363636400</td>
        <td>0.25</td>
        <td>0.8888888888888890</td>
        <td>0.23728813559322000</td>
        <td>0.11715481171548100</td>
        <td>0.2690184099055070</td>
        <td>0.3676082862523540</td>
        <td>0.23326955542955200</td>
        <td>0.08243727598566310</td>
        <td>0.09340917010607870</td>
        <td>0.12764176605984500</td>
        <td>0.08099637341303900</td>
      </tr>
      <tr>
        <td class="line-num">96</td>
        <td>S010</td>
        <td>sentence</td>
        <td>아, 맞다. 내일 같이 학교 가기로 했지?</td>
        <td>15</td>
        <td>2.7</td>
        <td>2.7</td>
        <td>0.1</td>
        <td>아 맏따 내일 가치 학꾜 가기로 핻찌</td>
        <td>ㅇ,ㅁ,ㄸ,ㄴ,ㄱ,ㅊ,ㅎ,ㅈ,ㅉ</td>
        <td>ㅏ,ㅐ,ㅣ,ㅛ,ㅗ</td>
        <td>ㄷ, ㄹ, ㄱ</td>
        <td>ㅇ-ㅏ | ㅁ-ㅏ-ㄷ-ㄸ-ㅏ | ㄴ-ㅐ-ㅇ-ㅣ-ㄹ | ㄱ-ㅏ-ㅊ-ㅣ | ㅎ-ㅏ-ㄱ-ㄲ-ㅛ | ㄱ-ㅏ-ㄱ-ㅣ-ㄹ-ㅗ | ㅎ-ㅐ-ㄷ-ㅉ-ㅣ</td>
        <td>ㅇ,ㅏ,ㅁ,ㄷ,ㄸ,ㄴ,ㅐ,ㅣ,ㄹ,ㄱ,ㅊ,ㅎ,ㄲ,ㅛ,ㅗ,ㅉ</td>
        <td>ㅇ→ㅏ; ㅁ→ㅏ,ㅏ→ㄷ,ㄷ→ㄸ,ㄸ→ㅏ; ㄴ→ㅐ,ㅐ→ㅇ,ㅇ→ㅣ,ㅣ→ㄹ; ㄱ→ㅏ,ㅏ→ㅊ,ㅊ→ㅣ; ㅎ→ㅏ,ㅏ→ㄱ,ㄱ→ㄲ,ㄲ→ㅛ; ㄱ→ㅏ,ㅏ→ㄱ,ㄱ→ㅣ,ㅣ→ㄹ,ㄹ→ㅗ; ㅎ→ㅐ,ㅐ→ㄷ,ㄷ→ㅉ,ㅉ→ㅣ</td>
        <td>ㅏ→ㅁ, ㅏ→ㄴ, ㄹ→ㄱ, ㅣ→ㅎ, ㅛ→ㄱ, ㅗ→ㅎ</td>
        <td>tensification;palatalization</td>
        <td>2.0</td>
        <td>null/velar onset → open vowel | bilabial closure → open vowel → low-visibility coda → alveolar → open vowel | alveolar → front/open-mid vowel → null/velar onset → spread vowel → low-visibility coda | low-visibility velar → open vowel → affricate → spread vowel | glottal → open vowel → low-visibility coda → low-visibility velar → rounded vowel | low-visibility velar → open vowel → low-visibility velar → spread vowel → liquid → rounded vowel | glottal → front/open-mid vowel → low-visibility coda → affricate → spread vowel</td>
        <td>null/velar onset,open vowel,bilabial closure,low-visibility coda,alveolar,front/open-mid vowel,spread vowel,low-visibility velar,affricate,glottal,rounded vowel,liquid</td>
        <td>null/velar onset→open vowel,bilabial closure→open vowel,open vowel→low-visibility coda,low-visibility coda→alveolar,alveolar→open vowel,alveolar→front/open-mid vowel,front/open-mid vowel→null/velar onset,null/velar onset→spread vowel,spread vowel→low-visibility coda,low-visibility velar→open vowel,open vowel→affricate,affricate→spread vowel,glottal→open vowel,open vowel→low-visibility coda,low-visibility coda→low-visibility velar,low-visibility velar→rounded vowel,low-visibility velar→open vowel,open vowel→low-visibility velar,low-visibility velar→spread vowel,spread vowel→liquid,liquid→rounded vowel,glottal→front/open-mid vowel,front/open-mid vowel→low-visibility coda,low-visibility coda→affricate,affricate→spread vowel</td>
        <td>양순음에서 입술 폐쇄가 나타남; 원순 모음에서 입술 원순화/돌출이 나타남; ㅣ 계열에서 입술이 옆으로 벌어짐; 개방 모음에서 입이 크게 열림; 중간 개구의 모음 변화가 나타남; 혀/후방 조음 중심 구간은 입술 단서가 비교적 제한적; 다양한 viseme 전환을 포함</td>
        <td>ㅇ:null/velar onset,ㅏ:open vowel | ㅁ:bilabial closure,ㅏ:open vowel,ㄷ:low-visibility coda,ㄸ:alveolar,ㅏ:open vowel | ㄴ:alveolar,ㅐ:front/open-mid vowel,ㅇ:null/velar onset,ㅣ:spread vowel,ㄹ:low-visibility coda | ㄱ:low-visibility velar,ㅏ:open vowel,ㅊ:affricate,ㅣ:spread vowel | ㅎ:glottal,ㅏ:open vowel,ㄱ:low-visibility coda,ㄲ:low-visibility velar,ㅛ:rounded vowel | ㄱ:low-visibility velar,ㅏ:open vowel,ㄱ:low-visibility velar,ㅣ:spread vowel,ㄹ:liquid,ㅗ:rounded vowel | ㅎ:glottal,ㅐ:front/open-mid vowel,ㄷ:low-visibility coda,ㅉ:affricate,ㅣ:spread vowel</td>
        <td>ㅇ:null/velar onset→ㅏ:open vowel,ㅁ:bilabial closure→ㅏ:open vowel,ㅏ:open vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㄸ:alveolar,ㄸ:alveolar→ㅏ:open vowel,ㄴ:alveolar→ㅐ:front/open-mid vowel,ㅐ:front/open-mid vowel→ㅇ:null/velar onset,ㅇ:null/velar onset→ㅣ:spread vowel,ㅣ:spread vowel→ㄹ:low-visibility coda,ㄱ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㅊ:affricate,ㅊ:affricate→ㅣ:spread vowel,ㅎ:glottal→ㅏ:open vowel,ㅏ:open vowel→ㄱ:low-visibility coda,ㄱ:low-visibility coda→ㄲ:low-visibility velar,ㄲ:low-visibility velar→ㅛ:rounded vowel,ㄱ:low-visibility velar→ㅏ:open vowel,ㅏ:open vowel→ㄱ:low-visibility velar,ㄱ:low-visibility velar→ㅣ:spread vowel,ㅣ:spread vowel→ㄹ:liquid,ㄹ:liquid→ㅗ:rounded vowel,ㅎ:glottal→ㅐ:front/open-mid vowel,ㅐ:front/open-mid vowel→ㄷ:low-visibility coda,ㄷ:low-visibility coda→ㅉ:affricate,ㅉ:affricate→ㅣ:spread vowel</td>
        <td>0.32</td>
        <td>0.2727272727272730</td>
        <td>0.25</td>
        <td>0.6666666666666670</td>
        <td>0.1864406779661020</td>
        <td>0.100418410041841</td>
        <td>0.2268108504398830</td>
        <td>0.2824858757062150</td>
        <td>0.1911305031666460</td>
        <td>0.06451612903225810</td>
        <td>0.08400401868143800</td>
        <td>0.10462439840970900</td>
        <td>0.07078907524690570</td>
      </tr>
    </tbody>
  </table>
</div>

</div>

### Japanese

<div style="overflow-x: auto; max-height: 400px; overflow-y: auto;">

<style>
  .github-csv-viewer {
    border: 1px solid var(--color-border-default, currentColor);
    border-radius: 6px;
    overflow: auto;
    max-height: 400px;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans", Helvetica, Arial, sans-serif;
    font-size: 12px;
  }
  
  .github-csv-table {
    border-collapse: separate;
    border-spacing: 0;
    width: max-content;
    min-width: 100%;
  }

  .github-csv-table th {
    background-color: var(--color-canvas-subtle, transparent);
    font-weight: 600;
    padding: 6px 12px;
    white-space: nowrap;
    text-align: left;
  }

  .github-csv-table td {
    padding: 6px 12px;
    white-space: nowrap;
  }

  .github-csv-table .line-num {
    background-color: var(--color-canvas-subtle, transparent);
    opacity: 0.7;
    text-align: right;
    width: 1%;
    padding: 6px 10px;
    user-select: none;
  }

  .github-csv-table th.line-num-header {
    text-align: center;
    width: 1%;
  }
</style>
<div class="github-csv-viewer">
  <table class="github-csv-table">
    <thead>
      <tr>
        <th class="line-num line-num-header"></th>
        <th>﻿id</th>
        <th>type</th>
        <th>text</th>
        <th>reading_kana</th>
        <th>mora_count</th>
        <th>estimated_duration</th>
        <th>actual_duration_mean</th>
        <th>standard_deviation</th>
        <th>pronunciation</th>
        <th>mora_sequence</th>
        <th>consonants</th>
        <th>vowels</th>
        <th>special_morae</th>
        <th>phoneme_sequence</th>
        <th>long_vowel_morae</th>
        <th>long_vowel_count</th>
        <th>phoneme_set</th>
        <th>phoneme_transitions</th>
        <th>cross_word_transition</th>
        <th>phonological_processes</th>
        <th>phonological_process_count</th>
        <th>prosodic_features</th>
        <th>pitch_accent_pattern</th>
        <th>pitch_accent_variants</th>
        <th>pitch_accent_unit</th>
        <th>pitch_accent_source</th>
        <th>pitch_accent_confidence</th>
        <th>reading_review_status</th>
        <th>long_vowel_review_status</th>
        <th>pitch_accent_review_status</th>
        <th>review_notes</th>
        <th>viseme_sequence</th>
        <th>viseme_set</th>
        <th>viseme_transitions</th>
        <th>visual_features</th>
        <th>phoneme_viseme_pairs</th>
        <th>av_transitions</th>
        <th>phoneme_coverage_gain</th>
        <th>special_mora_coverage_gain</th>
        <th>prosodic_coverage_gain</th>
        <th>phoneme_transition_gain</th>
        <th>viseme_coverage_gain</th>
        <th>viseme_transition_gain</th>
        <th>av_transition_gain</th>
        <th>audio_score</th>
        <th>vision_score</th>
        <th>joint_av_score</th>
        <th>audio_score_per_sec</th>
        <th>vision_score_per_sec</th>
        <th>joint_av_score_per_sec</th>
        <th>duration_measurement_status</th>
        <th>duration_model</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="line-num">1</td>
        <td>J001</td>
        <td>word</td>
        <td>朝</td>
        <td>あさ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>あさ</td>
        <td>あ-さ</td>
        <td>s</td>
        <td>a</td>
        <td></td>
        <td>a-s-a</td>
        <td></td>
        <td>0</td>
        <td>a,s</td>
        <td>a→s,s→a</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>open_vowel → coronal → open_vowel</td>
        <td>coronal,open_vowel</td>
        <td>open_vowel→coronal,coronal→open_vowel</td>
        <td>coronal; open_vowel</td>
        <td>a:open_vowel,s:coronal,a:open_vowel</td>
        <td>a:open_vowel→s:coronal,s:coronal→a:open_vowel</td>
        <td>0.06060606060606061</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.013157894736842105</td>
        <td>0.2</td>
        <td>0.047619047619047616</td>
        <td>0.013157894736842105</td>
        <td>0.018440988835725678</td>
        <td>0.12380952380952381</td>
        <td>0.04779155681411321</td>
        <td>0.03546344006870322</td>
        <td>0.23809523809523808</td>
        <td>0.0919068400271408</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">2</td>
        <td>J002</td>
        <td>word</td>
        <td>家</td>
        <td>いえ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>いえ</td>
        <td>い-え</td>
        <td></td>
        <td>e,i</td>
        <td></td>
        <td>i-e</td>
        <td></td>
        <td>0</td>
        <td>e,i</td>
        <td>i→e</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>spread_vowel → spread_vowel</td>
        <td>spread_vowel</td>
        <td>spread_vowel→spread_vowel</td>
        <td>spread_vowel</td>
        <td>i:spread_vowel,e:spread_vowel</td>
        <td>i:spread_vowel→e:spread_vowel</td>
        <td>0.06060606060606061</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.006578947368421052</td>
        <td>0.1</td>
        <td>0.023809523809523808</td>
        <td>0.006578947368421052</td>
        <td>0.016796251993620413</td>
        <td>0.06190476190476191</td>
        <td>0.02822478273606093</td>
        <td>0.03230048460311618</td>
        <td>0.11904761904761904</td>
        <td>0.05427842833857871</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">3</td>
        <td>J003</td>
        <td>word</td>
        <td>上</td>
        <td>うえ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>うえ</td>
        <td>う-え</td>
        <td></td>
        <td>e,u</td>
        <td></td>
        <td>u-e</td>
        <td></td>
        <td>0</td>
        <td>e,u</td>
        <td>u→e</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td>2</td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>MEDIUM</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>rounded → spread_vowel</td>
        <td>rounded,spread_vowel</td>
        <td>rounded→spread_vowel</td>
        <td>rounded; spread_vowel</td>
        <td>u:rounded,e:spread_vowel</td>
        <td>u:rounded→e:spread_vowel</td>
        <td>0.06060606060606061</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.006578947368421052</td>
        <td>0.2</td>
        <td>0.023809523809523808</td>
        <td>0.006578947368421052</td>
        <td>0.016796251993620413</td>
        <td>0.11190476190476191</td>
        <td>0.04251049702177522</td>
        <td>0.03230048460311618</td>
        <td>0.21520146520146521</td>
        <td>0.0817509558111062</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">4</td>
        <td>J004</td>
        <td>word</td>
        <td>駅</td>
        <td>えき</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>えき</td>
        <td>え-き</td>
        <td>k</td>
        <td>e,i</td>
        <td></td>
        <td>e-k-i</td>
        <td></td>
        <td>0</td>
        <td>e,i,k</td>
        <td>e→k,k→i</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>spread_vowel → low_visibility_velar → spread_vowel</td>
        <td>low_visibility_velar,spread_vowel</td>
        <td>spread_vowel→low_visibility_velar,low_visibility_velar→spread_vowel</td>
        <td>low_visibility_velar; spread_vowel</td>
        <td>e:spread_vowel,k:low_visibility_velar,i:spread_vowel</td>
        <td>e:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→i:spread_vowel</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.013157894736842105</td>
        <td>0.2</td>
        <td>0.047619047619047616</td>
        <td>0.013157894736842105</td>
        <td>0.026016746411483254</td>
        <td>0.12380952380952381</td>
        <td>0.052120561143117534</td>
        <td>0.0500322046374678</td>
        <td>0.23809523809523808</td>
        <td>0.1002318483521491</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">5</td>
        <td>J005</td>
        <td>word</td>
        <td>丘</td>
        <td>おか</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>おか</td>
        <td>お-か</td>
        <td>k</td>
        <td>a,o</td>
        <td></td>
        <td>o-k-a</td>
        <td></td>
        <td>0</td>
        <td>a,k,o</td>
        <td>o→k,k→a</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td>1</td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>MEDIUM</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>rounded → low_visibility_velar → open_vowel</td>
        <td>low_visibility_velar,open_vowel,rounded</td>
        <td>rounded→low_visibility_velar,low_visibility_velar→open_vowel</td>
        <td>low_visibility_velar; open_vowel; rounded</td>
        <td>o:rounded,k:low_visibility_velar,a:open_vowel</td>
        <td>o:rounded→k:low_visibility_velar,k:low_visibility_velar→a:open_vowel</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.013157894736842105</td>
        <td>0.3</td>
        <td>0.047619047619047616</td>
        <td>0.013157894736842105</td>
        <td>0.026016746411483254</td>
        <td>0.1738095238095238</td>
        <td>0.06640627542883182</td>
        <td>0.0500322046374678</td>
        <td>0.3342490842490842</td>
        <td>0.12770437582467656</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">6</td>
        <td>J006</td>
        <td>word</td>
        <td>柿</td>
        <td>かき</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>かき</td>
        <td>か-き</td>
        <td>k</td>
        <td>a,i</td>
        <td></td>
        <td>k-a-k-i</td>
        <td></td>
        <td>0</td>
        <td>a,i,k</td>
        <td>k→a,a→k,k→i</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → open_vowel → low_visibility_velar → spread_vowel</td>
        <td>low_visibility_velar,open_vowel,spread_vowel</td>
        <td>low_visibility_velar→open_vowel,open_vowel→low_visibility_velar,low_visibility_velar→spread_vowel</td>
        <td>low_visibility_velar; open_vowel; spread_vowel</td>
        <td>k:low_visibility_velar,a:open_vowel,k:low_visibility_velar,i:spread_vowel</td>
        <td>k:low_visibility_velar→a:open_vowel,a:open_vowel→k:low_visibility_velar,k:low_visibility_velar→i:spread_vowel</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.02766148325358852</td>
        <td>0.18571428571428572</td>
        <td>0.0716873352211698</td>
        <td>0.05319516010305484</td>
        <td>0.35714285714285715</td>
        <td>0.13786026004071114</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">7</td>
        <td>J007</td>
        <td>word</td>
        <td>鍵</td>
        <td>かぎ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>かぎ</td>
        <td>か-ぎ</td>
        <td>g,k</td>
        <td>a,i</td>
        <td></td>
        <td>k-a-g-i</td>
        <td></td>
        <td>0</td>
        <td>a,g,i,k</td>
        <td>k→a,a→g,g→i</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → open_vowel → low_visibility_velar → spread_vowel</td>
        <td>low_visibility_velar,open_vowel,spread_vowel</td>
        <td>low_visibility_velar→open_vowel,open_vowel→low_visibility_velar,low_visibility_velar→spread_vowel</td>
        <td>low_visibility_velar; open_vowel; spread_vowel</td>
        <td>k:low_visibility_velar,a:open_vowel,g:low_visibility_velar,i:spread_vowel</td>
        <td>k:low_visibility_velar→a:open_vowel,a:open_vowel→g:low_visibility_velar,g:low_visibility_velar→i:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.18571428571428572</td>
        <td>0.07601633955017414</td>
        <td>0.06776392467181941</td>
        <td>0.35714285714285715</td>
        <td>0.14618526836571952</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">8</td>
        <td>J008</td>
        <td>word</td>
        <td>傘</td>
        <td>かさ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>かさ</td>
        <td>か-さ</td>
        <td>k,s</td>
        <td>a</td>
        <td></td>
        <td>k-a-s-a</td>
        <td></td>
        <td>0</td>
        <td>a,k,s</td>
        <td>k→a,a→s,s→a</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → open_vowel → coronal → open_vowel</td>
        <td>coronal,low_visibility_velar,open_vowel</td>
        <td>low_visibility_velar→open_vowel,open_vowel→coronal,coronal→open_vowel</td>
        <td>coronal; low_visibility_velar; open_vowel</td>
        <td>k:low_visibility_velar,a:open_vowel,s:coronal,a:open_vowel</td>
        <td>k:low_visibility_velar→a:open_vowel,a:open_vowel→s:coronal,s:coronal→a:open_vowel</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.02766148325358852</td>
        <td>0.18571428571428572</td>
        <td>0.0716873352211698</td>
        <td>0.05319516010305484</td>
        <td>0.35714285714285715</td>
        <td>0.13786026004071114</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">9</td>
        <td>J009</td>
        <td>word</td>
        <td>風</td>
        <td>かぜ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>かぜ</td>
        <td>か-ぜ</td>
        <td>k,z</td>
        <td>a,e</td>
        <td></td>
        <td>k-a-z-e</td>
        <td></td>
        <td>0</td>
        <td>a,e,k,z</td>
        <td>k→a,a→z,z→e</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → open_vowel → coronal → spread_vowel</td>
        <td>coronal,low_visibility_velar,open_vowel,spread_vowel</td>
        <td>low_visibility_velar→open_vowel,open_vowel→coronal,coronal→spread_vowel</td>
        <td>coronal; low_visibility_velar; open_vowel; spread_vowel</td>
        <td>k:low_visibility_velar,a:open_vowel,z:coronal,e:spread_vowel</td>
        <td>k:low_visibility_velar→a:open_vowel,a:open_vowel→z:coronal,z:coronal→e:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">10</td>
        <td>J010</td>
        <td>word</td>
        <td>肩</td>
        <td>かた</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>かた</td>
        <td>か-た</td>
        <td>k,t</td>
        <td>a</td>
        <td></td>
        <td>k-a-t-a</td>
        <td></td>
        <td>0</td>
        <td>a,k,t</td>
        <td>k→a,a→t,t→a</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → open_vowel → coronal → open_vowel</td>
        <td>coronal,low_visibility_velar,open_vowel</td>
        <td>low_visibility_velar→open_vowel,open_vowel→coronal,coronal→open_vowel</td>
        <td>coronal; low_visibility_velar; open_vowel</td>
        <td>k:low_visibility_velar,a:open_vowel,t:coronal,a:open_vowel</td>
        <td>k:low_visibility_velar→a:open_vowel,a:open_vowel→t:coronal,t:coronal→a:open_vowel</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.02766148325358852</td>
        <td>0.18571428571428572</td>
        <td>0.0716873352211698</td>
        <td>0.05319516010305484</td>
        <td>0.35714285714285715</td>
        <td>0.13786026004071114</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">11</td>
        <td>J011</td>
        <td>word</td>
        <td>角</td>
        <td>かど</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>かど</td>
        <td>か-ど</td>
        <td>d,k</td>
        <td>a,o</td>
        <td></td>
        <td>k-a-d-o</td>
        <td></td>
        <td>0</td>
        <td>a,d,k,o</td>
        <td>k→a,a→d,d→o</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → open_vowel → coronal → rounded</td>
        <td>coronal,low_visibility_velar,open_vowel,rounded</td>
        <td>low_visibility_velar→open_vowel,open_vowel→coronal,coronal→rounded</td>
        <td>coronal; low_visibility_velar; open_vowel; rounded</td>
        <td>k:low_visibility_velar,a:open_vowel,d:coronal,o:rounded</td>
        <td>k:low_visibility_velar→a:open_vowel,a:open_vowel→d:coronal,d:coronal→o:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">12</td>
        <td>J012</td>
        <td>word</td>
        <td>壁</td>
        <td>かべ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>かべ</td>
        <td>か-べ</td>
        <td>b,k</td>
        <td>a,e</td>
        <td></td>
        <td>k-a-b-e</td>
        <td></td>
        <td>0</td>
        <td>a,b,e,k</td>
        <td>k→a,a→b,b→e</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → open_vowel → bilabial_closure → spread_vowel</td>
        <td>bilabial_closure,low_visibility_velar,open_vowel,spread_vowel</td>
        <td>low_visibility_velar→open_vowel,open_vowel→bilabial_closure,bilabial_closure→spread_vowel</td>
        <td>bilabial_closure; low_visibility_velar; open_vowel; spread_vowel</td>
        <td>k:low_visibility_velar,a:open_vowel,b:bilabial_closure,e:spread_vowel</td>
        <td>k:low_visibility_velar→a:open_vowel,a:open_vowel→b:bilabial_closure,b:bilabial_closure→e:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">13</td>
        <td>J013</td>
        <td>word</td>
        <td>紙</td>
        <td>かみ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>かみ</td>
        <td>か-み</td>
        <td>k,m</td>
        <td>a,i</td>
        <td></td>
        <td>k-a-m-i</td>
        <td></td>
        <td>0</td>
        <td>a,i,k,m</td>
        <td>k→a,a→m,m→i</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → open_vowel → bilabial_closure → spread_vowel</td>
        <td>bilabial_closure,low_visibility_velar,open_vowel,spread_vowel</td>
        <td>low_visibility_velar→open_vowel,open_vowel→bilabial_closure,bilabial_closure→spread_vowel</td>
        <td>bilabial_closure; low_visibility_velar; open_vowel; spread_vowel</td>
        <td>k:low_visibility_velar,a:open_vowel,m:bilabial_closure,i:spread_vowel</td>
        <td>k:low_visibility_velar→a:open_vowel,a:open_vowel→m:bilabial_closure,m:bilabial_closure→i:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">14</td>
        <td>J014</td>
        <td>word</td>
        <td>殻</td>
        <td>から</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>から</td>
        <td>か-ら</td>
        <td>k,r</td>
        <td>a</td>
        <td></td>
        <td>k-a-r-a</td>
        <td></td>
        <td>0</td>
        <td>a,k,r</td>
        <td>k→a,a→r,r→a</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → open_vowel → coronal → open_vowel</td>
        <td>coronal,low_visibility_velar,open_vowel</td>
        <td>low_visibility_velar→open_vowel,open_vowel→coronal,coronal→open_vowel</td>
        <td>coronal; low_visibility_velar; open_vowel</td>
        <td>k:low_visibility_velar,a:open_vowel,r:coronal,a:open_vowel</td>
        <td>k:low_visibility_velar→a:open_vowel,a:open_vowel→r:coronal,r:coronal→a:open_vowel</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.02766148325358852</td>
        <td>0.18571428571428572</td>
        <td>0.0716873352211698</td>
        <td>0.05319516010305484</td>
        <td>0.35714285714285715</td>
        <td>0.13786026004071114</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">15</td>
        <td>J015</td>
        <td>word</td>
        <td>川</td>
        <td>かわ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>かわ</td>
        <td>か-わ</td>
        <td>k,w</td>
        <td>a</td>
        <td></td>
        <td>k-a-w-a</td>
        <td></td>
        <td>0</td>
        <td>a,k,w</td>
        <td>k→a,a→w,w→a</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → open_vowel → rounded → open_vowel</td>
        <td>low_visibility_velar,open_vowel,rounded</td>
        <td>low_visibility_velar→open_vowel,open_vowel→rounded,rounded→open_vowel</td>
        <td>low_visibility_velar; open_vowel; rounded</td>
        <td>k:low_visibility_velar,a:open_vowel,w:rounded,a:open_vowel</td>
        <td>k:low_visibility_velar→a:open_vowel,a:open_vowel→w:rounded,w:rounded→a:open_vowel</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.02766148325358852</td>
        <td>0.18571428571428572</td>
        <td>0.0716873352211698</td>
        <td>0.05319516010305484</td>
        <td>0.35714285714285715</td>
        <td>0.13786026004071114</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">16</td>
        <td>J016</td>
        <td>word</td>
        <td>菊</td>
        <td>きく</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>きく</td>
        <td>き-く</td>
        <td>k</td>
        <td>i,u</td>
        <td></td>
        <td>k-i-k-u</td>
        <td></td>
        <td>0</td>
        <td>i,k,u</td>
        <td>k→i,i→k,k→u</td>
        <td></td>
        <td>high_vowel_devoicing_context</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td>0</td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>MEDIUM</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → spread_vowel → low_visibility_velar → rounded</td>
        <td>low_visibility_velar,rounded,spread_vowel</td>
        <td>low_visibility_velar→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→rounded</td>
        <td>low_visibility_velar; rounded; spread_vowel</td>
        <td>k:low_visibility_velar,i:spread_vowel,k:low_visibility_velar,u:rounded</td>
        <td>k:low_visibility_velar→i:spread_vowel,i:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→u:rounded</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.2</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.07766148325358851</td>
        <td>0.18571428571428572</td>
        <td>0.10025876379259838</td>
        <td>0.14934900625690098</td>
        <td>0.35714285714285715</td>
        <td>0.1928053149857661</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">17</td>
        <td>J017</td>
        <td>word</td>
        <td>靴</td>
        <td>くつ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>くつ</td>
        <td>く-つ</td>
        <td>k,ts</td>
        <td>u</td>
        <td></td>
        <td>k-u-ts-u</td>
        <td></td>
        <td>0</td>
        <td>k,ts,u</td>
        <td>k→u,u→ts,ts→u</td>
        <td></td>
        <td>high_vowel_devoicing_context</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → rounded → coronal → rounded</td>
        <td>coronal,low_visibility_velar,rounded</td>
        <td>low_visibility_velar→rounded,rounded→coronal,coronal→rounded</td>
        <td>coronal; low_visibility_velar; rounded</td>
        <td>k:low_visibility_velar,u:rounded,ts:coronal,u:rounded</td>
        <td>k:low_visibility_velar→u:rounded,u:rounded→ts:coronal,ts:coronal→u:rounded</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.2</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.07766148325358851</td>
        <td>0.18571428571428572</td>
        <td>0.10025876379259838</td>
        <td>0.14934900625690098</td>
        <td>0.35714285714285715</td>
        <td>0.1928053149857661</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">18</td>
        <td>J018</td>
        <td>word</td>
        <td>雲</td>
        <td>くも</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>くも</td>
        <td>く-も</td>
        <td>k,m</td>
        <td>o,u</td>
        <td></td>
        <td>k-u-m-o</td>
        <td></td>
        <td>0</td>
        <td>k,m,o,u</td>
        <td>k→u,u→m,m→o</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → rounded → bilabial_closure → rounded</td>
        <td>bilabial_closure,low_visibility_velar,rounded</td>
        <td>low_visibility_velar→rounded,rounded→bilabial_closure,bilabial_closure→rounded</td>
        <td>bilabial_closure; low_visibility_velar; rounded</td>
        <td>k:low_visibility_velar,u:rounded,m:bilabial_closure,o:rounded</td>
        <td>k:low_visibility_velar→u:rounded,u:rounded→m:bilabial_closure,m:bilabial_closure→o:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.18571428571428572</td>
        <td>0.07601633955017414</td>
        <td>0.06776392467181941</td>
        <td>0.35714285714285715</td>
        <td>0.14618526836571952</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">19</td>
        <td>J019</td>
        <td>word</td>
        <td>毛</td>
        <td>け</td>
        <td>1</td>
        <td>0.32</td>
        <td>0.33</td>
        <td>0.05</td>
        <td>け</td>
        <td>け</td>
        <td>k</td>
        <td>e</td>
        <td></td>
        <td>k-e</td>
        <td></td>
        <td>0</td>
        <td>e,k</td>
        <td>k→e</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → spread_vowel</td>
        <td>low_visibility_velar,spread_vowel</td>
        <td>low_visibility_velar→spread_vowel</td>
        <td>low_visibility_velar; spread_vowel</td>
        <td>k:low_visibility_velar,e:spread_vowel</td>
        <td>k:low_visibility_velar→e:spread_vowel</td>
        <td>0.06060606060606061</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.006578947368421052</td>
        <td>0.2</td>
        <td>0.023809523809523808</td>
        <td>0.006578947368421052</td>
        <td>0.016796251993620413</td>
        <td>0.11190476190476191</td>
        <td>0.04251049702177522</td>
        <td>0.05089773331400125</td>
        <td>0.33910533910533913</td>
        <td>0.1288196879447734</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">20</td>
        <td>J020</td>
        <td>word</td>
        <td>声</td>
        <td>こえ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>こえ</td>
        <td>こ-え</td>
        <td>k</td>
        <td>e,o</td>
        <td></td>
        <td>k-o-e</td>
        <td></td>
        <td>0</td>
        <td>e,k,o</td>
        <td>k→o,o→e</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → rounded → spread_vowel</td>
        <td>low_visibility_velar,rounded,spread_vowel</td>
        <td>low_visibility_velar→rounded,rounded→spread_vowel</td>
        <td>low_visibility_velar; rounded; spread_vowel</td>
        <td>k:low_visibility_velar,o:rounded,e:spread_vowel</td>
        <td>k:low_visibility_velar→o:rounded,o:rounded→e:spread_vowel</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.013157894736842105</td>
        <td>0.3</td>
        <td>0.047619047619047616</td>
        <td>0.013157894736842105</td>
        <td>0.026016746411483254</td>
        <td>0.1738095238095238</td>
        <td>0.06640627542883182</td>
        <td>0.0500322046374678</td>
        <td>0.3342490842490842</td>
        <td>0.12770437582467656</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">21</td>
        <td>J021</td>
        <td>word</td>
        <td>ここ</td>
        <td>ここ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>ここ</td>
        <td>こ-こ</td>
        <td>k</td>
        <td>o</td>
        <td></td>
        <td>k-o-k-o</td>
        <td></td>
        <td>0</td>
        <td>k,o</td>
        <td>k→o,o→k,k→o</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → rounded → low_visibility_velar → rounded</td>
        <td>low_visibility_velar,rounded</td>
        <td>low_visibility_velar→rounded,rounded→low_visibility_velar,low_visibility_velar→rounded</td>
        <td>low_visibility_velar; rounded</td>
        <td>k:low_visibility_velar,o:rounded,k:low_visibility_velar,o:rounded</td>
        <td>k:low_visibility_velar→o:rounded,o:rounded→k:low_visibility_velar,k:low_visibility_velar→o:rounded</td>
        <td>0.06060606060606061</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.013157894736842105</td>
        <td>0.2</td>
        <td>0.047619047619047616</td>
        <td>0.013157894736842105</td>
        <td>0.018440988835725678</td>
        <td>0.12380952380952381</td>
        <td>0.04779155681411321</td>
        <td>0.03546344006870322</td>
        <td>0.23809523809523808</td>
        <td>0.0919068400271408</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">22</td>
        <td>J022</td>
        <td>word</td>
        <td>坂</td>
        <td>さか</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>さか</td>
        <td>さ-か</td>
        <td>k,s</td>
        <td>a</td>
        <td></td>
        <td>s-a-k-a</td>
        <td></td>
        <td>0</td>
        <td>a,k,s</td>
        <td>s→a,a→k,k→a</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td>1</td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>MEDIUM</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → open_vowel → low_visibility_velar → open_vowel</td>
        <td>coronal,low_visibility_velar,open_vowel</td>
        <td>coronal→open_vowel,open_vowel→low_visibility_velar,low_visibility_velar→open_vowel</td>
        <td>coronal; low_visibility_velar; open_vowel</td>
        <td>s:coronal,a:open_vowel,k:low_visibility_velar,a:open_vowel</td>
        <td>s:coronal→a:open_vowel,a:open_vowel→k:low_visibility_velar,k:low_visibility_velar→a:open_vowel</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.02766148325358852</td>
        <td>0.18571428571428572</td>
        <td>0.0716873352211698</td>
        <td>0.05319516010305484</td>
        <td>0.35714285714285715</td>
        <td>0.13786026004071114</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">23</td>
        <td>J023</td>
        <td>word</td>
        <td>寿司</td>
        <td>すし</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>すし</td>
        <td>す-し</td>
        <td>s,sh</td>
        <td>i,u</td>
        <td></td>
        <td>s-u-sh-i</td>
        <td></td>
        <td>0</td>
        <td>i,s,sh,u</td>
        <td>s→u,u→sh,sh→i</td>
        <td></td>
        <td>high_vowel_devoicing_context</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td>1</td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>MEDIUM</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → rounded → coronal → spread_vowel</td>
        <td>coronal,rounded,spread_vowel</td>
        <td>coronal→rounded,rounded→coronal,coronal→spread_vowel</td>
        <td>coronal; rounded; spread_vowel</td>
        <td>s:coronal,u:rounded,sh:coronal,i:spread_vowel</td>
        <td>s:coronal→u:rounded,u:rounded→sh:coronal,sh:coronal→i:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.2</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.0852372408293461</td>
        <td>0.18571428571428572</td>
        <td>0.10458776812160271</td>
        <td>0.16391777082566555</td>
        <td>0.35714285714285715</td>
        <td>0.20113032331077443</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">24</td>
        <td>J024</td>
        <td>word</td>
        <td>外</td>
        <td>そと</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>そと</td>
        <td>そ-と</td>
        <td>s,t</td>
        <td>o</td>
        <td></td>
        <td>s-o-t-o</td>
        <td></td>
        <td>0</td>
        <td>o,s,t</td>
        <td>s→o,o→t,t→o</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → rounded → coronal → rounded</td>
        <td>coronal,rounded</td>
        <td>coronal→rounded,rounded→coronal,coronal→rounded</td>
        <td>coronal; rounded</td>
        <td>s:coronal,o:rounded,t:coronal,o:rounded</td>
        <td>s:coronal→o:rounded,o:rounded→t:coronal,t:coronal→o:rounded</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.2</td>
        <td>0.047619047619047616</td>
        <td>0.019736842105263157</td>
        <td>0.02766148325358852</td>
        <td>0.12380952380952381</td>
        <td>0.054000260391237835</td>
        <td>0.05319516010305484</td>
        <td>0.23809523809523808</td>
        <td>0.10384665459853429</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">25</td>
        <td>J025</td>
        <td>word</td>
        <td>滝</td>
        <td>たき</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>たき</td>
        <td>た-き</td>
        <td>k,t</td>
        <td>a,i</td>
        <td></td>
        <td>t-a-k-i</td>
        <td></td>
        <td>0</td>
        <td>a,i,k,t</td>
        <td>t→a,a→k,k→i</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → open_vowel → low_visibility_velar → spread_vowel</td>
        <td>coronal,low_visibility_velar,open_vowel,spread_vowel</td>
        <td>coronal→open_vowel,open_vowel→low_visibility_velar,low_visibility_velar→spread_vowel</td>
        <td>coronal; low_visibility_velar; open_vowel; spread_vowel</td>
        <td>t:coronal,a:open_vowel,k:low_visibility_velar,i:spread_vowel</td>
        <td>t:coronal→a:open_vowel,a:open_vowel→k:low_visibility_velar,k:low_visibility_velar→i:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">26</td>
        <td>J026</td>
        <td>word</td>
        <td>地図</td>
        <td>ちず</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>ちず</td>
        <td>ち-ず</td>
        <td>ch,z</td>
        <td>i,u</td>
        <td></td>
        <td>ch-i-z-u</td>
        <td></td>
        <td>0</td>
        <td>ch,i,u,z</td>
        <td>ch→i,i→z,z→u</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → spread_vowel → coronal → rounded</td>
        <td>coronal,rounded,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→coronal,coronal→rounded</td>
        <td>coronal; rounded; spread_vowel</td>
        <td>ch:coronal,i:spread_vowel,z:coronal,u:rounded</td>
        <td>ch:coronal→i:spread_vowel,i:spread_vowel→z:coronal,z:coronal→u:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.18571428571428572</td>
        <td>0.07601633955017414</td>
        <td>0.06776392467181941</td>
        <td>0.35714285714285715</td>
        <td>0.14618526836571952</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">27</td>
        <td>J027</td>
        <td>word</td>
        <td>月</td>
        <td>つき</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>つき</td>
        <td>つ-き</td>
        <td>k,ts</td>
        <td>i,u</td>
        <td></td>
        <td>ts-u-k-i</td>
        <td></td>
        <td>0</td>
        <td>i,k,ts,u</td>
        <td>ts→u,u→k,k→i</td>
        <td></td>
        <td>high_vowel_devoicing_context</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → rounded → low_visibility_velar → spread_vowel</td>
        <td>coronal,low_visibility_velar,rounded,spread_vowel</td>
        <td>coronal→rounded,rounded→low_visibility_velar,low_visibility_velar→spread_vowel</td>
        <td>coronal; low_visibility_velar; rounded; spread_vowel</td>
        <td>ts:coronal,u:rounded,k:low_visibility_velar,i:spread_vowel</td>
        <td>ts:coronal→u:rounded,u:rounded→k:low_visibility_velar,k:low_visibility_velar→i:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.2</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.0852372408293461</td>
        <td>0.2357142857142857</td>
        <td>0.118873482407317</td>
        <td>0.16391777082566555</td>
        <td>0.4532967032967033</td>
        <td>0.22860285078330192</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">28</td>
        <td>J028</td>
        <td>word</td>
        <td>手</td>
        <td>て</td>
        <td>1</td>
        <td>0.32</td>
        <td>0.33</td>
        <td>0.05</td>
        <td>て</td>
        <td>て</td>
        <td>t</td>
        <td>e</td>
        <td></td>
        <td>t-e</td>
        <td></td>
        <td>0</td>
        <td>e,t</td>
        <td>t→e</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → spread_vowel</td>
        <td>coronal,spread_vowel</td>
        <td>coronal→spread_vowel</td>
        <td>coronal; spread_vowel</td>
        <td>t:coronal,e:spread_vowel</td>
        <td>t:coronal→e:spread_vowel</td>
        <td>0.06060606060606061</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.006578947368421052</td>
        <td>0.2</td>
        <td>0.023809523809523808</td>
        <td>0.006578947368421052</td>
        <td>0.016796251993620413</td>
        <td>0.11190476190476191</td>
        <td>0.04251049702177522</td>
        <td>0.05089773331400125</td>
        <td>0.33910533910533913</td>
        <td>0.1288196879447734</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">29</td>
        <td>J029</td>
        <td>word</td>
        <td>音</td>
        <td>おと</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>おと</td>
        <td>お-と</td>
        <td>t</td>
        <td>o</td>
        <td></td>
        <td>o-t-o</td>
        <td></td>
        <td>0</td>
        <td>o,t</td>
        <td>o→t,t→o</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>rounded → coronal → rounded</td>
        <td>coronal,rounded</td>
        <td>rounded→coronal,coronal→rounded</td>
        <td>coronal; rounded</td>
        <td>o:rounded,t:coronal,o:rounded</td>
        <td>o:rounded→t:coronal,t:coronal→o:rounded</td>
        <td>0.06060606060606061</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.013157894736842105</td>
        <td>0.2</td>
        <td>0.047619047619047616</td>
        <td>0.013157894736842105</td>
        <td>0.018440988835725678</td>
        <td>0.12380952380952381</td>
        <td>0.04779155681411321</td>
        <td>0.03546344006870322</td>
        <td>0.23809523809523808</td>
        <td>0.0919068400271408</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">30</td>
        <td>J030</td>
        <td>word</td>
        <td>夏</td>
        <td>なつ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>なつ</td>
        <td>な-つ</td>
        <td>n,ts</td>
        <td>a,u</td>
        <td></td>
        <td>n-a-ts-u</td>
        <td></td>
        <td>0</td>
        <td>a,n,ts,u</td>
        <td>n→a,a→ts,ts→u</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → open_vowel → coronal → rounded</td>
        <td>coronal,open_vowel,rounded</td>
        <td>coronal→open_vowel,open_vowel→coronal,coronal→rounded</td>
        <td>coronal; open_vowel; rounded</td>
        <td>n:coronal,a:open_vowel,ts:coronal,u:rounded</td>
        <td>n:coronal→a:open_vowel,a:open_vowel→ts:coronal,ts:coronal→u:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.18571428571428572</td>
        <td>0.07601633955017414</td>
        <td>0.06776392467181941</td>
        <td>0.35714285714285715</td>
        <td>0.14618526836571952</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">31</td>
        <td>J031</td>
        <td>word</td>
        <td>庭</td>
        <td>にわ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>にわ</td>
        <td>に-わ</td>
        <td>n,w</td>
        <td>a,i</td>
        <td></td>
        <td>n-i-w-a</td>
        <td></td>
        <td>0</td>
        <td>a,i,n,w</td>
        <td>n→i,i→w,w→a</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → spread_vowel → rounded → open_vowel</td>
        <td>coronal,open_vowel,rounded,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→rounded,rounded→open_vowel</td>
        <td>coronal; open_vowel; rounded; spread_vowel</td>
        <td>n:coronal,i:spread_vowel,w:rounded,a:open_vowel</td>
        <td>n:coronal→i:spread_vowel,i:spread_vowel→w:rounded,w:rounded→a:open_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">32</td>
        <td>J032</td>
        <td>word</td>
        <td>布</td>
        <td>ぬの</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>ぬの</td>
        <td>ぬ-の</td>
        <td>n</td>
        <td>o,u</td>
        <td></td>
        <td>n-u-n-o</td>
        <td></td>
        <td>0</td>
        <td>n,o,u</td>
        <td>n→u,u→n,n→o</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → rounded → coronal → rounded</td>
        <td>coronal,rounded</td>
        <td>coronal→rounded,rounded→coronal,coronal→rounded</td>
        <td>coronal; rounded</td>
        <td>n:coronal,u:rounded,n:coronal,o:rounded</td>
        <td>n:coronal→u:rounded,u:rounded→n:coronal,n:coronal→o:rounded</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.2</td>
        <td>0.047619047619047616</td>
        <td>0.019736842105263157</td>
        <td>0.02766148325358852</td>
        <td>0.12380952380952381</td>
        <td>0.054000260391237835</td>
        <td>0.05319516010305484</td>
        <td>0.23809523809523808</td>
        <td>0.10384665459853429</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">33</td>
        <td>J033</td>
        <td>word</td>
        <td>猫</td>
        <td>ねこ</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>ねこ</td>
        <td>ね-こ</td>
        <td>k,n</td>
        <td>e,o</td>
        <td></td>
        <td>n-e-k-o</td>
        <td></td>
        <td>0</td>
        <td>e,k,n,o</td>
        <td>n→e,e→k,k→o</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → spread_vowel → low_visibility_velar → rounded</td>
        <td>coronal,low_visibility_velar,rounded,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→rounded</td>
        <td>coronal; low_visibility_velar; rounded; spread_vowel</td>
        <td>n:coronal,e:spread_vowel,k:low_visibility_velar,o:rounded</td>
        <td>n:coronal→e:spread_vowel,e:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→o:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">34</td>
        <td>J034</td>
        <td>word</td>
        <td>花</td>
        <td>はな</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>はな</td>
        <td>は-な</td>
        <td>h,n</td>
        <td>a</td>
        <td></td>
        <td>h-a-n-a</td>
        <td></td>
        <td>0</td>
        <td>a,h,n</td>
        <td>h→a,a→n,n→a</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatal_glottal → open_vowel → coronal → open_vowel</td>
        <td>coronal,open_vowel,palatal_glottal</td>
        <td>palatal_glottal→open_vowel,open_vowel→coronal,coronal→open_vowel</td>
        <td>coronal; open_vowel; palatal_glottal</td>
        <td>h:palatal_glottal,a:open_vowel,n:coronal,a:open_vowel</td>
        <td>h:palatal_glottal→a:open_vowel,a:open_vowel→n:coronal,n:coronal→a:open_vowel</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.02766148325358852</td>
        <td>0.18571428571428572</td>
        <td>0.0716873352211698</td>
        <td>0.05319516010305484</td>
        <td>0.35714285714285715</td>
        <td>0.13786026004071114</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">35</td>
        <td>J035</td>
        <td>word</td>
        <td>人</td>
        <td>ひと</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>ひと</td>
        <td>ひ-と</td>
        <td>h,t</td>
        <td>i,o</td>
        <td></td>
        <td>h-i-t-o</td>
        <td></td>
        <td>0</td>
        <td>h,i,o,t</td>
        <td>h→i,i→t,t→o</td>
        <td></td>
        <td>high_vowel_devoicing_context</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td>2</td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>MEDIUM</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatal_glottal → spread_vowel → coronal → rounded</td>
        <td>coronal,palatal_glottal,rounded,spread_vowel</td>
        <td>palatal_glottal→spread_vowel,spread_vowel→coronal,coronal→rounded</td>
        <td>coronal; palatal_glottal; rounded; spread_vowel</td>
        <td>h:palatal_glottal,i:spread_vowel,t:coronal,o:rounded</td>
        <td>h:palatal_glottal→i:spread_vowel,i:spread_vowel→t:coronal,t:coronal→o:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.2</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.0852372408293461</td>
        <td>0.2357142857142857</td>
        <td>0.118873482407317</td>
        <td>0.16391777082566555</td>
        <td>0.4532967032967033</td>
        <td>0.22860285078330192</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">36</td>
        <td>J036</td>
        <td>word</td>
        <td>船</td>
        <td>ふね</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>ふね</td>
        <td>ふ-ね</td>
        <td>f,n</td>
        <td>e,u</td>
        <td></td>
        <td>f-u-n-e</td>
        <td></td>
        <td>0</td>
        <td>e,f,n,u</td>
        <td>f→u,u→n,n→e</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>labiodental_like → rounded → coronal → spread_vowel</td>
        <td>coronal,labiodental_like,rounded,spread_vowel</td>
        <td>labiodental_like→rounded,rounded→coronal,coronal→spread_vowel</td>
        <td>coronal; labiodental_like; rounded; spread_vowel</td>
        <td>f:labiodental_like,u:rounded,n:coronal,e:spread_vowel</td>
        <td>f:labiodental_like→u:rounded,u:rounded→n:coronal,n:coronal→e:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">37</td>
        <td>J037</td>
        <td>word</td>
        <td>部屋</td>
        <td>へや</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>へや</td>
        <td>へ-や</td>
        <td>h,y</td>
        <td>a,e</td>
        <td></td>
        <td>h-e-y-a</td>
        <td></td>
        <td>0</td>
        <td>a,e,h,y</td>
        <td>h→e,e→y,y→a</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatal_glottal → spread_vowel → palatal_glottal → open_vowel</td>
        <td>open_vowel,palatal_glottal,spread_vowel</td>
        <td>palatal_glottal→spread_vowel,spread_vowel→palatal_glottal,palatal_glottal→open_vowel</td>
        <td>open_vowel; palatal_glottal; spread_vowel</td>
        <td>h:palatal_glottal,e:spread_vowel,y:palatal_glottal,a:open_vowel</td>
        <td>h:palatal_glottal→e:spread_vowel,e:spread_vowel→y:palatal_glottal,y:palatal_glottal→a:open_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.18571428571428572</td>
        <td>0.07601633955017414</td>
        <td>0.06776392467181941</td>
        <td>0.35714285714285715</td>
        <td>0.14618526836571952</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">38</td>
        <td>J038</td>
        <td>word</td>
        <td>星</td>
        <td>ほし</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>ほし</td>
        <td>ほ-し</td>
        <td>h,sh</td>
        <td>i,o</td>
        <td></td>
        <td>h-o-sh-i</td>
        <td></td>
        <td>0</td>
        <td>h,i,o,sh</td>
        <td>h→o,o→sh,sh→i</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatal_glottal → rounded → coronal → spread_vowel</td>
        <td>coronal,palatal_glottal,rounded,spread_vowel</td>
        <td>palatal_glottal→rounded,rounded→coronal,coronal→spread_vowel</td>
        <td>coronal; palatal_glottal; rounded; spread_vowel</td>
        <td>h:palatal_glottal,o:rounded,sh:coronal,i:spread_vowel</td>
        <td>h:palatal_glottal→o:rounded,o:rounded→sh:coronal,sh:coronal→i:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">39</td>
        <td>J039</td>
        <td>word</td>
        <td>窓</td>
        <td>まど</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>まど</td>
        <td>ま-ど</td>
        <td>d,m</td>
        <td>a,o</td>
        <td></td>
        <td>m-a-d-o</td>
        <td></td>
        <td>0</td>
        <td>a,d,m,o</td>
        <td>m→a,a→d,d→o</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>bilabial_closure → open_vowel → coronal → rounded</td>
        <td>bilabial_closure,coronal,open_vowel,rounded</td>
        <td>bilabial_closure→open_vowel,open_vowel→coronal,coronal→rounded</td>
        <td>bilabial_closure; coronal; open_vowel; rounded</td>
        <td>m:bilabial_closure,a:open_vowel,d:coronal,o:rounded</td>
        <td>m:bilabial_closure→a:open_vowel,a:open_vowel→d:coronal,d:coronal→o:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">40</td>
        <td>J040</td>
        <td>word</td>
        <td>水</td>
        <td>みず</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>みず</td>
        <td>み-ず</td>
        <td>m,z</td>
        <td>i,u</td>
        <td></td>
        <td>m-i-z-u</td>
        <td></td>
        <td>0</td>
        <td>i,m,u,z</td>
        <td>m→i,i→z,z→u</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>bilabial_closure → spread_vowel → coronal → rounded</td>
        <td>bilabial_closure,coronal,rounded,spread_vowel</td>
        <td>bilabial_closure→spread_vowel,spread_vowel→coronal,coronal→rounded</td>
        <td>bilabial_closure; coronal; rounded; spread_vowel</td>
        <td>m:bilabial_closure,i:spread_vowel,z:coronal,u:rounded</td>
        <td>m:bilabial_closure→i:spread_vowel,i:spread_vowel→z:coronal,z:coronal→u:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">41</td>
        <td>J041</td>
        <td>word</td>
        <td>胸</td>
        <td>むね</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>むね</td>
        <td>む-ね</td>
        <td>m,n</td>
        <td>e,u</td>
        <td></td>
        <td>m-u-n-e</td>
        <td></td>
        <td>0</td>
        <td>e,m,n,u</td>
        <td>m→u,u→n,n→e</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>bilabial_closure → rounded → coronal → spread_vowel</td>
        <td>bilabial_closure,coronal,rounded,spread_vowel</td>
        <td>bilabial_closure→rounded,rounded→coronal,coronal→spread_vowel</td>
        <td>bilabial_closure; coronal; rounded; spread_vowel</td>
        <td>m:bilabial_closure,u:rounded,n:coronal,e:spread_vowel</td>
        <td>m:bilabial_closure→u:rounded,u:rounded→n:coronal,n:coronal→e:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">42</td>
        <td>J042</td>
        <td>word</td>
        <td>目</td>
        <td>め</td>
        <td>1</td>
        <td>0.32</td>
        <td>0.33</td>
        <td>0.05</td>
        <td>め</td>
        <td>め</td>
        <td>m</td>
        <td>e</td>
        <td></td>
        <td>m-e</td>
        <td></td>
        <td>0</td>
        <td>e,m</td>
        <td>m→e</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>bilabial_closure → spread_vowel</td>
        <td>bilabial_closure,spread_vowel</td>
        <td>bilabial_closure→spread_vowel</td>
        <td>bilabial_closure; spread_vowel</td>
        <td>m:bilabial_closure,e:spread_vowel</td>
        <td>m:bilabial_closure→e:spread_vowel</td>
        <td>0.06060606060606061</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.006578947368421052</td>
        <td>0.2</td>
        <td>0.023809523809523808</td>
        <td>0.006578947368421052</td>
        <td>0.016796251993620413</td>
        <td>0.11190476190476191</td>
        <td>0.04251049702177522</td>
        <td>0.05089773331400125</td>
        <td>0.33910533910533913</td>
        <td>0.1288196879447734</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">43</td>
        <td>J043</td>
        <td>word</td>
        <td>森</td>
        <td>もり</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>もり</td>
        <td>も-り</td>
        <td>m,r</td>
        <td>i,o</td>
        <td></td>
        <td>m-o-r-i</td>
        <td></td>
        <td>0</td>
        <td>i,m,o,r</td>
        <td>m→o,o→r,r→i</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>bilabial_closure → rounded → coronal → spread_vowel</td>
        <td>bilabial_closure,coronal,rounded,spread_vowel</td>
        <td>bilabial_closure→rounded,rounded→coronal,coronal→spread_vowel</td>
        <td>bilabial_closure; coronal; rounded; spread_vowel</td>
        <td>m:bilabial_closure,o:rounded,r:coronal,i:spread_vowel</td>
        <td>m:bilabial_closure→o:rounded,o:rounded→r:coronal,r:coronal→i:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">44</td>
        <td>J044</td>
        <td>word</td>
        <td>山</td>
        <td>やま</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>やま</td>
        <td>や-ま</td>
        <td>m,y</td>
        <td>a</td>
        <td></td>
        <td>y-a-m-a</td>
        <td></td>
        <td>0</td>
        <td>a,m,y</td>
        <td>y→a,a→m,m→a</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatal_glottal → open_vowel → bilabial_closure → open_vowel</td>
        <td>bilabial_closure,open_vowel,palatal_glottal</td>
        <td>palatal_glottal→open_vowel,open_vowel→bilabial_closure,bilabial_closure→open_vowel</td>
        <td>bilabial_closure; open_vowel; palatal_glottal</td>
        <td>y:palatal_glottal,a:open_vowel,m:bilabial_closure,a:open_vowel</td>
        <td>y:palatal_glottal→a:open_vowel,a:open_vowel→m:bilabial_closure,m:bilabial_closure→a:open_vowel</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.02766148325358852</td>
        <td>0.18571428571428572</td>
        <td>0.0716873352211698</td>
        <td>0.05319516010305484</td>
        <td>0.35714285714285715</td>
        <td>0.13786026004071114</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">45</td>
        <td>J045</td>
        <td>word</td>
        <td>雪</td>
        <td>ゆき</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>ゆき</td>
        <td>ゆ-き</td>
        <td>k,y</td>
        <td>i,u</td>
        <td></td>
        <td>y-u-k-i</td>
        <td></td>
        <td>0</td>
        <td>i,k,u,y</td>
        <td>y→u,u→k,k→i</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td>1</td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>MEDIUM</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatal_glottal → rounded → low_visibility_velar → spread_vowel</td>
        <td>low_visibility_velar,palatal_glottal,rounded,spread_vowel</td>
        <td>palatal_glottal→rounded,rounded→low_visibility_velar,low_visibility_velar→spread_vowel</td>
        <td>low_visibility_velar; palatal_glottal; rounded; spread_vowel</td>
        <td>y:palatal_glottal,u:rounded,k:low_visibility_velar,i:spread_vowel</td>
        <td>y:palatal_glottal→u:rounded,u:rounded→k:low_visibility_velar,k:low_visibility_velar→i:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.2357142857142857</td>
        <td>0.09030205383588842</td>
        <td>0.06776392467181941</td>
        <td>0.4532967032967033</td>
        <td>0.17365779583824695</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">46</td>
        <td>J046</td>
        <td>word</td>
        <td>夜</td>
        <td>よる</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>よる</td>
        <td>よ-る</td>
        <td>r,y</td>
        <td>o,u</td>
        <td></td>
        <td>y-o-r-u</td>
        <td></td>
        <td>0</td>
        <td>o,r,u,y</td>
        <td>y→o,o→r,r→u</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatal_glottal → rounded → coronal → rounded</td>
        <td>coronal,palatal_glottal,rounded</td>
        <td>palatal_glottal→rounded,rounded→coronal,coronal→rounded</td>
        <td>coronal; palatal_glottal; rounded</td>
        <td>y:palatal_glottal,o:rounded,r:coronal,u:rounded</td>
        <td>y:palatal_glottal→o:rounded,o:rounded→r:coronal,r:coronal→u:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.18571428571428572</td>
        <td>0.07601633955017414</td>
        <td>0.06776392467181941</td>
        <td>0.35714285714285715</td>
        <td>0.14618526836571952</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">47</td>
        <td>J047</td>
        <td>word</td>
        <td>空</td>
        <td>そら</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>そら</td>
        <td>そ-ら</td>
        <td>r,s</td>
        <td>a,o</td>
        <td></td>
        <td>s-o-r-a</td>
        <td></td>
        <td>0</td>
        <td>a,o,r,s</td>
        <td>s→o,o→r,r→a</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → rounded → coronal → open_vowel</td>
        <td>coronal,open_vowel,rounded</td>
        <td>coronal→rounded,rounded→coronal,coronal→open_vowel</td>
        <td>coronal; open_vowel; rounded</td>
        <td>s:coronal,o:rounded,r:coronal,a:open_vowel</td>
        <td>s:coronal→o:rounded,o:rounded→r:coronal,r:coronal→a:open_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.035237240829346095</td>
        <td>0.18571428571428572</td>
        <td>0.07601633955017414</td>
        <td>0.06776392467181941</td>
        <td>0.35714285714285715</td>
        <td>0.14618526836571952</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">48</td>
        <td>J048</td>
        <td>word</td>
        <td>林檎</td>
        <td>りんご</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.74</td>
        <td>0.07</td>
        <td>りんご</td>
        <td>り-ん-ご</td>
        <td>g,r</td>
        <td>i,o</td>
        <td>N</td>
        <td>r-i-N-g-o</td>
        <td></td>
        <td>0</td>
        <td>N,g,i,o,r</td>
        <td>r→i,i→N,N→g,g→o</td>
        <td></td>
        <td>moraic_nasal</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → spread_vowel → special_mora → low_visibility_velar → rounded</td>
        <td>coronal,low_visibility_velar,rounded,special_mora,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→special_mora,special_mora→low_visibility_velar,low_visibility_velar→rounded</td>
        <td>coronal; low_visibility_velar; rounded; special_mora; spread_vowel</td>
        <td>r:coronal,i:spread_vowel,N:special_mora,g:low_visibility_velar,o:rounded</td>
        <td>r:coronal→i:spread_vowel,i:spread_vowel→N:special_mora,N:special_mora→g:low_visibility_velar,g:low_visibility_velar→o:rounded</td>
        <td>0.15151515151515152</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.02631578947368421</td>
        <td>0.5</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.17779106858054228</td>
        <td>0.2976190476190476</td>
        <td>0.19038830843342122</td>
        <td>0.2402582007845166</td>
        <td>0.4021879021879022</td>
        <td>0.25728149788300164</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">49</td>
        <td>J049</td>
        <td>word</td>
        <td>留守</td>
        <td>るす</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>るす</td>
        <td>る-す</td>
        <td>r,s</td>
        <td>u</td>
        <td></td>
        <td>r-u-s-u</td>
        <td></td>
        <td>0</td>
        <td>r,s,u</td>
        <td>r→u,u→s,s→u</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → rounded → coronal → rounded</td>
        <td>coronal,rounded</td>
        <td>coronal→rounded,rounded→coronal,coronal→rounded</td>
        <td>coronal; rounded</td>
        <td>r:coronal,u:rounded,s:coronal,u:rounded</td>
        <td>r:coronal→u:rounded,u:rounded→s:coronal,s:coronal→u:rounded</td>
        <td>0.09090909090909091</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.019736842105263157</td>
        <td>0.2</td>
        <td>0.047619047619047616</td>
        <td>0.019736842105263157</td>
        <td>0.02766148325358852</td>
        <td>0.12380952380952381</td>
        <td>0.054000260391237835</td>
        <td>0.05319516010305484</td>
        <td>0.23809523809523808</td>
        <td>0.10384665459853429</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">50</td>
        <td>J050</td>
        <td>word</td>
        <td>冷蔵庫</td>
        <td>れいぞうこ</td>
        <td>5</td>
        <td>1.12</td>
        <td>1.14</td>
        <td>0.09</td>
        <td>れいぞうこ</td>
        <td>れ-い-ぞ-う-こ</td>
        <td>k,r,z</td>
        <td>e,i,o,u</td>
        <td>R</td>
        <td>r-e-i-z-o-u-k-o</td>
        <td>e:1-2,o:3-4</td>
        <td>2</td>
        <td>e,i,k,o,r,u,z</td>
        <td>r→e,e→i,i→z,z→o,o→u,u→k,k→o</td>
        <td></td>
        <td>vowel_length</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>3</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → spread_vowel → spread_vowel → coronal → rounded → rounded → low_visibility_velar → rounded</td>
        <td>coronal,low_visibility_velar,rounded,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→spread_vowel,spread_vowel→coronal,coronal→rounded,rounded→rounded,rounded→low_visibility_velar,low_visibility_velar→rounded</td>
        <td>coronal; low_visibility_velar; rounded; spread_vowel</td>
        <td>r:coronal,e:spread_vowel,i:spread_vowel,z:coronal,o:rounded,u:rounded,k:low_visibility_velar,o:rounded</td>
        <td>r:coronal→e:spread_vowel,e:spread_vowel→i:spread_vowel,i:spread_vowel→z:coronal,z:coronal→o:rounded,o:rounded→u:rounded,u:rounded→k:low_visibility_velar,k:low_visibility_velar→o:rounded</td>
        <td>0.21212121212121213</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.046052631578947366</td>
        <td>0.4</td>
        <td>0.16666666666666666</td>
        <td>0.046052631578947366</td>
        <td>0.1978767942583732</td>
        <td>0.2833333333333333</td>
        <td>0.20060378218272956</td>
        <td>0.17357613531436247</td>
        <td>0.24853801169590645</td>
        <td>0.1759682299848505</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">51</td>
        <td>J051</td>
        <td>word</td>
        <td>廊下</td>
        <td>ろうか</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.74</td>
        <td>0.07</td>
        <td>ろうか</td>
        <td>ろ-う-か</td>
        <td>k,r</td>
        <td>a,o,u</td>
        <td>R</td>
        <td>r-o-u-k-a</td>
        <td>o:1-2</td>
        <td>1</td>
        <td>a,k,o,r,u</td>
        <td>r→o,o→u,u→k,k→a</td>
        <td></td>
        <td>vowel_length</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → rounded → rounded → low_visibility_velar → open_vowel</td>
        <td>coronal,low_visibility_velar,open_vowel,rounded</td>
        <td>coronal→rounded,rounded→rounded,rounded→low_visibility_velar,low_visibility_velar→open_vowel</td>
        <td>coronal; low_visibility_velar; open_vowel; rounded</td>
        <td>r:coronal,o:rounded,u:rounded,k:low_visibility_velar,a:open_vowel</td>
        <td>r:coronal→o:rounded,o:rounded→u:rounded,u:rounded→k:low_visibility_velar,k:low_visibility_velar→a:open_vowel</td>
        <td>0.15151515151515152</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.02631578947368421</td>
        <td>0.4</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.17779106858054228</td>
        <td>0.24761904761904763</td>
        <td>0.17610259414770693</td>
        <td>0.2402582007845166</td>
        <td>0.33462033462033464</td>
        <td>0.23797647857798235</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">52</td>
        <td>J052</td>
        <td>word</td>
        <td>私</td>
        <td>わたし</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.71</td>
        <td>0.07</td>
        <td>わたし</td>
        <td>わ-た-し</td>
        <td>sh,t,w</td>
        <td>a,i</td>
        <td></td>
        <td>w-a-t-a-sh-i</td>
        <td></td>
        <td>0</td>
        <td>a,i,sh,t,w</td>
        <td>w→a,a→t,t→a,a→sh,sh→i</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>rounded → open_vowel → coronal → open_vowel → coronal → spread_vowel</td>
        <td>coronal,open_vowel,rounded,spread_vowel</td>
        <td>rounded→open_vowel,open_vowel→coronal,coronal→open_vowel,open_vowel→coronal,coronal→spread_vowel</td>
        <td>coronal; open_vowel; rounded; spread_vowel</td>
        <td>w:rounded,a:open_vowel,t:coronal,a:open_vowel,sh:coronal,i:spread_vowel</td>
        <td>w:rounded→a:open_vowel,a:open_vowel→t:coronal,t:coronal→a:open_vowel,a:open_vowel→sh:coronal,sh:coronal→i:spread_vowel</td>
        <td>0.15151515151515152</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.03289473684210526</td>
        <td>0.4</td>
        <td>0.09523809523809523</td>
        <td>0.03289473684210526</td>
        <td>0.04610247208931419</td>
        <td>0.24761904761904763</td>
        <td>0.10179181720535103</td>
        <td>0.06493305928072422</td>
        <td>0.34875922199865866</td>
        <td>0.14336875662725498</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">53</td>
        <td>J053</td>
        <td>word</td>
        <td>銀行</td>
        <td>ぎんこう</td>
        <td>4</td>
        <td>0.92</td>
        <td>0.96</td>
        <td>0.08</td>
        <td>ぎんこう</td>
        <td>ぎ-ん-こ-う</td>
        <td>g,k</td>
        <td>i,o,u</td>
        <td>N,R</td>
        <td>g-i-N-k-o-u</td>
        <td>o:3-4</td>
        <td>1</td>
        <td>N,g,i,k,o,u</td>
        <td>g→i,i→N,N→k,k→o,o→u</td>
        <td></td>
        <td>moraic_nasal,vowel_length</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → spread_vowel → special_mora → low_visibility_velar → rounded → rounded</td>
        <td>low_visibility_velar,rounded,special_mora,spread_vowel</td>
        <td>low_visibility_velar→spread_vowel,spread_vowel→special_mora,special_mora→low_visibility_velar,low_visibility_velar→rounded,rounded→rounded</td>
        <td>low_visibility_velar; rounded; special_mora; spread_vowel</td>
        <td>g:low_visibility_velar,i:spread_vowel,N:special_mora,k:low_visibility_velar,o:rounded,u:rounded</td>
        <td>g:low_visibility_velar→i:spread_vowel,i:spread_vowel→N:special_mora,N:special_mora→k:low_visibility_velar,k:low_visibility_velar→o:rounded,o:rounded→u:rounded</td>
        <td>0.18181818181818182</td>
        <td>0.6666666666666666</td>
        <td>0.4</td>
        <td>0.03289473684210526</td>
        <td>0.4</td>
        <td>0.11904761904761904</td>
        <td>0.03289473684210526</td>
        <td>0.32034489633173846</td>
        <td>0.25952380952380955</td>
        <td>0.26190313445952546</td>
        <td>0.3336926003455609</td>
        <td>0.2703373015873016</td>
        <td>0.27281576506200567</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">54</td>
        <td>J054</td>
        <td>word</td>
        <td>午後</td>
        <td>ごご</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>ごご</td>
        <td>ご-ご</td>
        <td>g</td>
        <td>o</td>
        <td></td>
        <td>g-o-g-o</td>
        <td></td>
        <td>0</td>
        <td>g,o</td>
        <td>g→o,o→g,g→o</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → rounded → low_visibility_velar → rounded</td>
        <td>low_visibility_velar,rounded</td>
        <td>low_visibility_velar→rounded,rounded→low_visibility_velar,low_visibility_velar→rounded</td>
        <td>low_visibility_velar; rounded</td>
        <td>g:low_visibility_velar,o:rounded,g:low_visibility_velar,o:rounded</td>
        <td>g:low_visibility_velar→o:rounded,o:rounded→g:low_visibility_velar,g:low_visibility_velar→o:rounded</td>
        <td>0.06060606060606061</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.013157894736842105</td>
        <td>0.2</td>
        <td>0.047619047619047616</td>
        <td>0.013157894736842105</td>
        <td>0.018440988835725678</td>
        <td>0.12380952380952381</td>
        <td>0.04779155681411321</td>
        <td>0.03546344006870322</td>
        <td>0.23809523809523808</td>
        <td>0.0919068400271408</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">55</td>
        <td>J055</td>
        <td>word</td>
        <td>写真</td>
        <td>しゃしん</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.74</td>
        <td>0.07</td>
        <td>しゃしん</td>
        <td>しゃ-し-ん</td>
        <td>sh</td>
        <td>a,i</td>
        <td>N</td>
        <td>sh-a-sh-i-N</td>
        <td></td>
        <td>0</td>
        <td>N,a,i,sh</td>
        <td>sh→a,a→sh,sh→i,i→N</td>
        <td></td>
        <td>moraic_nasal,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → open_vowel → coronal → spread_vowel → special_mora</td>
        <td>coronal,open_vowel,special_mora,spread_vowel</td>
        <td>coronal→open_vowel,open_vowel→coronal,coronal→spread_vowel,spread_vowel→special_mora</td>
        <td>coronal; open_vowel; special_mora; spread_vowel</td>
        <td>sh:coronal,a:open_vowel,sh:coronal,i:spread_vowel,N:special_mora</td>
        <td>sh:coronal→a:open_vowel,a:open_vowel→sh:coronal,sh:coronal→i:spread_vowel,i:spread_vowel→N:special_mora</td>
        <td>0.12121212121212122</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.02631578947368421</td>
        <td>0.4</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.2202153110047847</td>
        <td>0.24761904761904763</td>
        <td>0.2003450183901312</td>
        <td>0.2975882581145739</td>
        <td>0.33462033462033464</td>
        <td>0.27073651133801513</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">56</td>
        <td>J056</td>
        <td>word</td>
        <td>主役</td>
        <td>しゅやく</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.71</td>
        <td>0.07</td>
        <td>しゅやく</td>
        <td>しゅ-や-く</td>
        <td>k,sh,y</td>
        <td>a,u</td>
        <td></td>
        <td>sh-u-y-a-k-u</td>
        <td></td>
        <td>0</td>
        <td>a,k,sh,u,y</td>
        <td>sh→u,u→y,y→a,a→k,k→u</td>
        <td></td>
        <td>palatalization</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → rounded → palatal_glottal → open_vowel → low_visibility_velar → rounded</td>
        <td>coronal,low_visibility_velar,open_vowel,palatal_glottal,rounded</td>
        <td>coronal→rounded,rounded→palatal_glottal,palatal_glottal→open_vowel,open_vowel→low_visibility_velar,low_visibility_velar→rounded</td>
        <td>coronal; low_visibility_velar; open_vowel; palatal_glottal; rounded</td>
        <td>sh:coronal,u:rounded,y:palatal_glottal,a:open_vowel,k:low_visibility_velar,u:rounded</td>
        <td>sh:coronal→u:rounded,u:rounded→y:palatal_glottal,y:palatal_glottal→a:open_vowel,a:open_vowel→k:low_visibility_velar,k:low_visibility_velar→u:rounded</td>
        <td>0.15151515151515152</td>
        <td>0.0</td>
        <td>0.2</td>
        <td>0.03289473684210526</td>
        <td>0.5</td>
        <td>0.11904761904761904</td>
        <td>0.03289473684210526</td>
        <td>0.0961024720893142</td>
        <td>0.30952380952380953</td>
        <td>0.14805032060671158</td>
        <td>0.13535559449199183</td>
        <td>0.4359490274983233</td>
        <td>0.2085215783193121</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">57</td>
        <td>J057</td>
        <td>word</td>
        <td>食事</td>
        <td>しょくじ</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.71</td>
        <td>0.07</td>
        <td>しょくじ</td>
        <td>しょ-く-じ</td>
        <td>j,k,sh</td>
        <td>i,o,u</td>
        <td></td>
        <td>sh-o-k-u-j-i</td>
        <td></td>
        <td>0</td>
        <td>i,j,k,o,sh,u</td>
        <td>sh→o,o→k,k→u,u→j,j→i</td>
        <td></td>
        <td>palatalization</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → rounded → low_visibility_velar → rounded → coronal → spread_vowel</td>
        <td>coronal,low_visibility_velar,rounded,spread_vowel</td>
        <td>coronal→rounded,rounded→low_visibility_velar,low_visibility_velar→rounded,rounded→coronal,coronal→spread_vowel</td>
        <td>coronal; low_visibility_velar; rounded; spread_vowel</td>
        <td>sh:coronal,o:rounded,k:low_visibility_velar,u:rounded,j:coronal,i:spread_vowel</td>
        <td>sh:coronal→o:rounded,o:rounded→k:low_visibility_velar,k:low_visibility_velar→u:rounded,u:rounded→j:coronal,j:coronal→i:spread_vowel</td>
        <td>0.18181818181818182</td>
        <td>0.0</td>
        <td>0.2</td>
        <td>0.03289473684210526</td>
        <td>0.4</td>
        <td>0.11904761904761904</td>
        <td>0.03289473684210526</td>
        <td>0.10367822966507177</td>
        <td>0.25952380952380955</td>
        <td>0.13809361065000164</td>
        <td>0.14602567558460813</td>
        <td>0.3655264922870557</td>
        <td>0.1944980431690164</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">58</td>
        <td>J058</td>
        <td>word</td>
        <td>茶碗</td>
        <td>ちゃわん</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.74</td>
        <td>0.07</td>
        <td>ちゃわん</td>
        <td>ちゃ-わ-ん</td>
        <td>ch,w</td>
        <td>a</td>
        <td>N</td>
        <td>ch-a-w-a-N</td>
        <td></td>
        <td>0</td>
        <td>N,a,ch,w</td>
        <td>ch→a,a→w,w→a,a→N</td>
        <td></td>
        <td>moraic_nasal,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → open_vowel → rounded → open_vowel → special_mora</td>
        <td>coronal,open_vowel,rounded,special_mora</td>
        <td>coronal→open_vowel,open_vowel→rounded,rounded→open_vowel,open_vowel→special_mora</td>
        <td>coronal; open_vowel; rounded; special_mora</td>
        <td>ch:coronal,a:open_vowel,w:rounded,a:open_vowel,N:special_mora</td>
        <td>ch:coronal→a:open_vowel,a:open_vowel→w:rounded,w:rounded→a:open_vowel,a:open_vowel→N:special_mora</td>
        <td>0.12121212121212122</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.02631578947368421</td>
        <td>0.4</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.2202153110047847</td>
        <td>0.24761904761904763</td>
        <td>0.2003450183901312</td>
        <td>0.2975882581145739</td>
        <td>0.33462033462033464</td>
        <td>0.27073651133801513</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">59</td>
        <td>J059</td>
        <td>word</td>
        <td>注意</td>
        <td>ちゅうい</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.74</td>
        <td>0.07</td>
        <td>ちゅうい</td>
        <td>ちゅ-う-い</td>
        <td>ch</td>
        <td>i,u</td>
        <td>R</td>
        <td>ch-u-u-i</td>
        <td>u:1-2</td>
        <td>1</td>
        <td>ch,i,u</td>
        <td>ch→u,u→u,u→i</td>
        <td></td>
        <td>vowel_length,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → rounded → rounded → spread_vowel</td>
        <td>coronal,rounded,spread_vowel</td>
        <td>coronal→rounded,rounded→rounded,rounded→spread_vowel</td>
        <td>coronal; rounded; spread_vowel</td>
        <td>ch:coronal,u:rounded,u:rounded,i:spread_vowel</td>
        <td>ch:coronal→u:rounded,u:rounded→u:rounded,u:rounded→i:spread_vowel</td>
        <td>0.09090909090909091</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.21099481658692185</td>
        <td>0.18571428571428572</td>
        <td>0.17644923998307457</td>
        <td>0.28512813052286734</td>
        <td>0.25096525096525096</td>
        <td>0.23844491889604671</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">60</td>
        <td>J060</td>
        <td>word</td>
        <td>貯金</td>
        <td>ちょきん</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.74</td>
        <td>0.07</td>
        <td>ちょきん</td>
        <td>ちょ-き-ん</td>
        <td>ch,k</td>
        <td>i,o</td>
        <td>N</td>
        <td>ch-o-k-i-N</td>
        <td></td>
        <td>0</td>
        <td>N,ch,i,k,o</td>
        <td>ch→o,o→k,k→i,i→N</td>
        <td></td>
        <td>moraic_nasal,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td>2</td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>MEDIUM</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → rounded → low_visibility_velar → spread_vowel → special_mora</td>
        <td>coronal,low_visibility_velar,rounded,special_mora,spread_vowel</td>
        <td>coronal→rounded,rounded→low_visibility_velar,low_visibility_velar→spread_vowel,spread_vowel→special_mora</td>
        <td>coronal; low_visibility_velar; rounded; special_mora; spread_vowel</td>
        <td>ch:coronal,o:rounded,k:low_visibility_velar,i:spread_vowel,N:special_mora</td>
        <td>ch:coronal→o:rounded,o:rounded→k:low_visibility_velar,k:low_visibility_velar→i:spread_vowel,i:spread_vowel→N:special_mora</td>
        <td>0.15151515151515152</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.02631578947368421</td>
        <td>0.5</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.22779106858054227</td>
        <td>0.2976190476190476</td>
        <td>0.21895973700484977</td>
        <td>0.30782576835208414</td>
        <td>0.4021879021879022</td>
        <td>0.29589153649304023</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">61</td>
        <td>J061</td>
        <td>word</td>
        <td>客</td>
        <td>きゃく</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>きゃく</td>
        <td>きゃ-く</td>
        <td>k,ky</td>
        <td>a,u</td>
        <td></td>
        <td>ky-a-k-u</td>
        <td></td>
        <td>0</td>
        <td>a,k,ky,u</td>
        <td>ky→a,a→k,k→u</td>
        <td></td>
        <td>palatalization</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → open_vowel → low_visibility_velar → rounded</td>
        <td>low_visibility_velar,open_vowel,rounded</td>
        <td>low_visibility_velar→open_vowel,open_vowel→low_visibility_velar,low_visibility_velar→rounded</td>
        <td>low_visibility_velar; open_vowel; rounded</td>
        <td>ky:low_visibility_velar,a:open_vowel,k:low_visibility_velar,u:rounded</td>
        <td>ky:low_visibility_velar→a:open_vowel,a:open_vowel→k:low_visibility_velar,k:low_visibility_velar→u:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.2</td>
        <td>0.019736842105263157</td>
        <td>0.3</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.0852372408293461</td>
        <td>0.18571428571428572</td>
        <td>0.10458776812160271</td>
        <td>0.16391777082566555</td>
        <td>0.35714285714285715</td>
        <td>0.20113032331077443</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">62</td>
        <td>J062</td>
        <td>word</td>
        <td>九</td>
        <td>きゅう</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.55</td>
        <td>0.07</td>
        <td>きゅう</td>
        <td>きゅ-う</td>
        <td>ky</td>
        <td>u</td>
        <td>R</td>
        <td>ky-u-u</td>
        <td>u:1-2</td>
        <td>1</td>
        <td>ky,u</td>
        <td>ky→u,u→u</td>
        <td></td>
        <td>vowel_length,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → rounded → rounded</td>
        <td>low_visibility_velar,rounded</td>
        <td>low_visibility_velar→rounded,rounded→rounded</td>
        <td>low_visibility_velar; rounded</td>
        <td>ky:low_visibility_velar,u:rounded,u:rounded</td>
        <td>ky:low_visibility_velar→u:rounded,u:rounded→u:rounded</td>
        <td>0.06060606060606061</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.013157894736842105</td>
        <td>0.2</td>
        <td>0.047619047619047616</td>
        <td>0.013157894736842105</td>
        <td>0.20177432216905902</td>
        <td>0.12380952380952381</td>
        <td>0.15255346157601798</td>
        <td>0.36686240394374364</td>
        <td>0.2251082251082251</td>
        <td>0.2773699301382145</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">63</td>
        <td>J063</td>
        <td>word</td>
        <td>今日</td>
        <td>きょう</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.55</td>
        <td>0.07</td>
        <td>きょう</td>
        <td>きょ-う</td>
        <td>ky</td>
        <td>o,u</td>
        <td>R</td>
        <td>ky-o-u</td>
        <td>o:1-2</td>
        <td>1</td>
        <td>ky,o,u</td>
        <td>ky→o,o→u</td>
        <td></td>
        <td>vowel_length,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → rounded → rounded</td>
        <td>low_visibility_velar,rounded</td>
        <td>low_visibility_velar→rounded,rounded→rounded</td>
        <td>low_visibility_velar; rounded</td>
        <td>ky:low_visibility_velar,o:rounded,u:rounded</td>
        <td>ky:low_visibility_velar→o:rounded,o:rounded→u:rounded</td>
        <td>0.09090909090909091</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.013157894736842105</td>
        <td>0.2</td>
        <td>0.047619047619047616</td>
        <td>0.013157894736842105</td>
        <td>0.2093500797448166</td>
        <td>0.12380952380952381</td>
        <td>0.1568824659050223</td>
        <td>0.3806365086269392</td>
        <td>0.2251082251082251</td>
        <td>0.28524084710004055</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">64</td>
        <td>J064</td>
        <td>word</td>
        <td>百</td>
        <td>ひゃく</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.06</td>
        <td>ひゃく</td>
        <td>ひゃ-く</td>
        <td>hy,k</td>
        <td>a,u</td>
        <td></td>
        <td>hy-a-k-u</td>
        <td></td>
        <td>0</td>
        <td>a,hy,k,u</td>
        <td>hy→a,a→k,k→u</td>
        <td></td>
        <td>palatalization</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatal_glottal → open_vowel → low_visibility_velar → rounded</td>
        <td>low_visibility_velar,open_vowel,palatal_glottal,rounded</td>
        <td>palatal_glottal→open_vowel,open_vowel→low_visibility_velar,low_visibility_velar→rounded</td>
        <td>low_visibility_velar; open_vowel; palatal_glottal; rounded</td>
        <td>hy:palatal_glottal,a:open_vowel,k:low_visibility_velar,u:rounded</td>
        <td>hy:palatal_glottal→a:open_vowel,a:open_vowel→k:low_visibility_velar,k:low_visibility_velar→u:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.2</td>
        <td>0.019736842105263157</td>
        <td>0.4</td>
        <td>0.07142857142857142</td>
        <td>0.019736842105263157</td>
        <td>0.0852372408293461</td>
        <td>0.2357142857142857</td>
        <td>0.118873482407317</td>
        <td>0.16391777082566555</td>
        <td>0.4532967032967033</td>
        <td>0.22860285078330192</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">65</td>
        <td>J065</td>
        <td>word</td>
        <td>表</td>
        <td>ひょう</td>
        <td>2</td>
        <td>0.52</td>
        <td>0.55</td>
        <td>0.07</td>
        <td>ひょう</td>
        <td>ひょ-う</td>
        <td>hy</td>
        <td>o,u</td>
        <td>R</td>
        <td>hy-o-u</td>
        <td>o:1-2</td>
        <td>1</td>
        <td>hy,o,u</td>
        <td>hy→o,o→u</td>
        <td></td>
        <td>vowel_length,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatal_glottal → rounded → rounded</td>
        <td>palatal_glottal,rounded</td>
        <td>palatal_glottal→rounded,rounded→rounded</td>
        <td>palatal_glottal; rounded</td>
        <td>hy:palatal_glottal,o:rounded,u:rounded</td>
        <td>hy:palatal_glottal→o:rounded,o:rounded→u:rounded</td>
        <td>0.09090909090909091</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.013157894736842105</td>
        <td>0.2</td>
        <td>0.047619047619047616</td>
        <td>0.013157894736842105</td>
        <td>0.2093500797448166</td>
        <td>0.12380952380952381</td>
        <td>0.1568824659050223</td>
        <td>0.3806365086269392</td>
        <td>0.2251082251082251</td>
        <td>0.28524084710004055</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">66</td>
        <td>J066</td>
        <td>word</td>
        <td>牛乳</td>
        <td>ぎゅうにゅう</td>
        <td>4</td>
        <td>0.92</td>
        <td>0.95</td>
        <td>0.08</td>
        <td>ぎゅうにゅう</td>
        <td>ぎゅ-う-にゅ-う</td>
        <td>gy,ny</td>
        <td>u</td>
        <td>R</td>
        <td>gy-u-u-ny-u-u</td>
        <td>u:1-2,u:3-4</td>
        <td>2</td>
        <td>gy,ny,u</td>
        <td>gy→u,u→u,u→ny,ny→u,u→u</td>
        <td></td>
        <td>vowel_length,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → rounded → rounded → palatal_glottal → rounded → rounded</td>
        <td>low_visibility_velar,palatal_glottal,rounded</td>
        <td>low_visibility_velar→rounded,rounded→rounded,rounded→palatal_glottal,palatal_glottal→rounded,rounded→rounded</td>
        <td>low_visibility_velar; palatal_glottal; rounded</td>
        <td>gy:low_visibility_velar,u:rounded,u:rounded,ny:palatal_glottal,u:rounded,u:rounded</td>
        <td>gy:low_visibility_velar→u:rounded,u:rounded→u:rounded,u:rounded→ny:palatal_glottal,ny:palatal_glottal→u:rounded,u:rounded→u:rounded</td>
        <td>0.09090909090909091</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.02631578947368421</td>
        <td>0.3</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.21263955342902713</td>
        <td>0.1976190476190476</td>
        <td>0.18173029977541258</td>
        <td>0.22383110887266014</td>
        <td>0.20802005012531327</td>
        <td>0.19129505239517114</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">67</td>
        <td>J067</td>
        <td>word</td>
        <td>料理</td>
        <td>りょうり</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.74</td>
        <td>0.07</td>
        <td>りょうり</td>
        <td>りょ-う-り</td>
        <td>r,ry</td>
        <td>i,o,u</td>
        <td>R</td>
        <td>ry-o-u-r-i</td>
        <td>o:1-2</td>
        <td>1</td>
        <td>i,o,r,ry,u</td>
        <td>ry→o,o→u,u→r,r→i</td>
        <td></td>
        <td>vowel_length,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatal_glottal → rounded → rounded → coronal → spread_vowel</td>
        <td>coronal,palatal_glottal,rounded,spread_vowel</td>
        <td>palatal_glottal→rounded,rounded→rounded,rounded→coronal,coronal→spread_vowel</td>
        <td>coronal; palatal_glottal; rounded; spread_vowel</td>
        <td>ry:palatal_glottal,o:rounded,u:rounded,r:coronal,i:spread_vowel</td>
        <td>ry:palatal_glottal→o:rounded,o:rounded→u:rounded,u:rounded→r:coronal,r:coronal→i:spread_vowel</td>
        <td>0.15151515151515152</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.02631578947368421</td>
        <td>0.4</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.22779106858054227</td>
        <td>0.24761904761904763</td>
        <td>0.2046740227191355</td>
        <td>0.30782576835208414</td>
        <td>0.33462033462033464</td>
        <td>0.27658651718802096</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">68</td>
        <td>J068</td>
        <td>word</td>
        <td>旅行</td>
        <td>りょこう</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.74</td>
        <td>0.07</td>
        <td>りょこう</td>
        <td>りょ-こ-う</td>
        <td>k,ry</td>
        <td>o,u</td>
        <td>R</td>
        <td>ry-o-k-o-u</td>
        <td>o:2-3</td>
        <td>1</td>
        <td>k,o,ry,u</td>
        <td>ry→o,o→k,k→o,o→u</td>
        <td></td>
        <td>vowel_length,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatal_glottal → rounded → low_visibility_velar → rounded → rounded</td>
        <td>low_visibility_velar,palatal_glottal,rounded</td>
        <td>palatal_glottal→rounded,rounded→low_visibility_velar,low_visibility_velar→rounded,rounded→rounded</td>
        <td>low_visibility_velar; palatal_glottal; rounded</td>
        <td>ry:palatal_glottal,o:rounded,k:low_visibility_velar,o:rounded,u:rounded</td>
        <td>ry:palatal_glottal→o:rounded,o:rounded→k:low_visibility_velar,k:low_visibility_velar→o:rounded,o:rounded→u:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.02631578947368421</td>
        <td>0.3</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.2202153110047847</td>
        <td>0.1976190476190476</td>
        <td>0.1860593041044169</td>
        <td>0.2975882581145739</td>
        <td>0.26705276705276704</td>
        <td>0.2514314920329958</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">69</td>
        <td>J069</td>
        <td>word</td>
        <td>病院</td>
        <td>びょういん</td>
        <td>4</td>
        <td>0.92</td>
        <td>0.96</td>
        <td>0.08</td>
        <td>びょういん</td>
        <td>びょ-う-い-ん</td>
        <td>by</td>
        <td>i,o,u</td>
        <td>N,R</td>
        <td>by-o-u-i-N</td>
        <td>o:1-2</td>
        <td>1</td>
        <td>N,by,i,o,u</td>
        <td>by→o,o→u,u→i,i→N</td>
        <td></td>
        <td>moraic_nasal,vowel_length,palatalization</td>
        <td>3</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatalized_labial → rounded → rounded → spread_vowel → special_mora</td>
        <td>palatalized_labial,rounded,special_mora,spread_vowel</td>
        <td>palatalized_labial→rounded,rounded→rounded,rounded→spread_vowel,spread_vowel→special_mora</td>
        <td>palatalized_labial; rounded; special_mora; spread_vowel</td>
        <td>by:palatalized_labial,o:rounded,u:rounded,i:spread_vowel,N:special_mora</td>
        <td>by:palatalized_labial→o:rounded,o:rounded→u:rounded,u:rounded→i:spread_vowel,i:spread_vowel→N:special_mora</td>
        <td>0.15151515151515152</td>
        <td>0.6666666666666666</td>
        <td>0.6</td>
        <td>0.02631578947368421</td>
        <td>0.4</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.36112440191387557</td>
        <td>0.24761904761904763</td>
        <td>0.2808644989096117</td>
        <td>0.3761712519936204</td>
        <td>0.25793650793650796</td>
        <td>0.29256718636417883</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">70</td>
        <td>J070</td>
        <td>word</td>
        <td>発表</td>
        <td>はっぴょう</td>
        <td>4</td>
        <td>0.92</td>
        <td>0.97</td>
        <td>0.08</td>
        <td>はっぴょう</td>
        <td>は-っ-ぴょ-う</td>
        <td>h,py</td>
        <td>a,o,u</td>
        <td>Q,R</td>
        <td>h-a-Q-py-o-u</td>
        <td>o:3-4</td>
        <td>1</td>
        <td>Q,a,h,o,py,u</td>
        <td>h→a,a→Q,Q→py,py→o,o→u</td>
        <td></td>
        <td>gemination,vowel_length,palatalization</td>
        <td>3</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>palatal_glottal → open_vowel → special_mora → palatalized_labial → rounded → rounded</td>
        <td>open_vowel,palatal_glottal,palatalized_labial,rounded,special_mora</td>
        <td>palatal_glottal→open_vowel,open_vowel→special_mora,special_mora→palatalized_labial,palatalized_labial→rounded,rounded→rounded</td>
        <td>open_vowel; palatal_glottal; palatalized_labial; rounded; special_mora</td>
        <td>h:palatal_glottal,a:open_vowel,Q:special_mora,py:palatalized_labial,o:rounded,u:rounded</td>
        <td>h:palatal_glottal→a:open_vowel,a:open_vowel→Q:special_mora,Q:special_mora→py:palatalized_labial,py:palatalized_labial→o:rounded,o:rounded→u:rounded</td>
        <td>0.18181818181818182</td>
        <td>0.6666666666666666</td>
        <td>0.6</td>
        <td>0.03289473684210526</td>
        <td>0.5</td>
        <td>0.11904761904761904</td>
        <td>0.03289473684210526</td>
        <td>0.37034489633173845</td>
        <td>0.30952380952380953</td>
        <td>0.30476027731666827</td>
        <td>0.3817988621976685</td>
        <td>0.3190967108492882</td>
        <td>0.3141858529037817</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">71</td>
        <td>J071</td>
        <td>word</td>
        <td>学校</td>
        <td>がっこう</td>
        <td>4</td>
        <td>0.92</td>
        <td>0.97</td>
        <td>0.08</td>
        <td>がっこう</td>
        <td>が-っ-こ-う</td>
        <td>g,k</td>
        <td>a,o,u</td>
        <td>Q,R</td>
        <td>g-a-Q-k-o-u</td>
        <td>o:3-4</td>
        <td>1</td>
        <td>Q,a,g,k,o,u</td>
        <td>g→a,a→Q,Q→k,k→o,o→u</td>
        <td></td>
        <td>gemination,vowel_length</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → open_vowel → special_mora → low_visibility_velar → rounded → rounded</td>
        <td>low_visibility_velar,open_vowel,rounded,special_mora</td>
        <td>low_visibility_velar→open_vowel,open_vowel→special_mora,special_mora→low_visibility_velar,low_visibility_velar→rounded,rounded→rounded</td>
        <td>low_visibility_velar; open_vowel; rounded; special_mora</td>
        <td>g:low_visibility_velar,a:open_vowel,Q:special_mora,k:low_visibility_velar,o:rounded,u:rounded</td>
        <td>g:low_visibility_velar→a:open_vowel,a:open_vowel→Q:special_mora,Q:special_mora→k:low_visibility_velar,k:low_visibility_velar→o:rounded,o:rounded→u:rounded</td>
        <td>0.18181818181818182</td>
        <td>0.6666666666666666</td>
        <td>0.4</td>
        <td>0.03289473684210526</td>
        <td>0.4</td>
        <td>0.11904761904761904</td>
        <td>0.03289473684210526</td>
        <td>0.32034489633173846</td>
        <td>0.25952380952380955</td>
        <td>0.26190313445952546</td>
        <td>0.3302524704450912</td>
        <td>0.2675503190967109</td>
        <td>0.2700032314015726</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">72</td>
        <td>J072</td>
        <td>word</td>
        <td>切手</td>
        <td>きって</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>きって</td>
        <td>き-っ-て</td>
        <td>k,t</td>
        <td>e,i</td>
        <td>Q</td>
        <td>k-i-Q-t-e</td>
        <td></td>
        <td>0</td>
        <td>Q,e,i,k,t</td>
        <td>k→i,i→Q,Q→t,t→e</td>
        <td></td>
        <td>gemination</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td>3</td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>MEDIUM</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>low_visibility_velar → spread_vowel → special_mora → coronal → spread_vowel</td>
        <td>coronal,low_visibility_velar,special_mora,spread_vowel</td>
        <td>low_visibility_velar→spread_vowel,spread_vowel→special_mora,special_mora→coronal,coronal→spread_vowel</td>
        <td>coronal; low_visibility_velar; special_mora; spread_vowel</td>
        <td>k:low_visibility_velar,i:spread_vowel,Q:special_mora,t:coronal,e:spread_vowel</td>
        <td>k:low_visibility_velar→i:spread_vowel,i:spread_vowel→Q:special_mora,Q:special_mora→t:coronal,t:coronal→e:spread_vowel</td>
        <td>0.15151515151515152</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.02631578947368421</td>
        <td>0.4</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.17779106858054228</td>
        <td>0.24761904761904763</td>
        <td>0.17610259414770693</td>
        <td>0.2339356165533451</td>
        <td>0.3258145363408521</td>
        <td>0.23171393966803544</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">73</td>
        <td>J073</td>
        <td>word</td>
        <td>雑誌</td>
        <td>ざっし</td>
        <td>3</td>
        <td>0.72</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>ざっし</td>
        <td>ざ-っ-し</td>
        <td>sh,z</td>
        <td>a,i</td>
        <td>Q</td>
        <td>z-a-Q-sh-i</td>
        <td></td>
        <td>0</td>
        <td>Q,a,i,sh,z</td>
        <td>z→a,a→Q,Q→sh,sh→i</td>
        <td></td>
        <td>gemination</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → open_vowel → special_mora → coronal → spread_vowel</td>
        <td>coronal,open_vowel,special_mora,spread_vowel</td>
        <td>coronal→open_vowel,open_vowel→special_mora,special_mora→coronal,coronal→spread_vowel</td>
        <td>coronal; open_vowel; special_mora; spread_vowel</td>
        <td>z:coronal,a:open_vowel,Q:special_mora,sh:coronal,i:spread_vowel</td>
        <td>z:coronal→a:open_vowel,a:open_vowel→Q:special_mora,Q:special_mora→sh:coronal,sh:coronal→i:spread_vowel</td>
        <td>0.15151515151515152</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.02631578947368421</td>
        <td>0.4</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.17779106858054228</td>
        <td>0.24761904761904763</td>
        <td>0.17610259414770693</td>
        <td>0.2339356165533451</td>
        <td>0.3258145363408521</td>
        <td>0.23171393966803544</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">74</td>
        <td>J074</td>
        <td>word</td>
        <td>一杯</td>
        <td>いっぱい</td>
        <td>4</td>
        <td>0.92</td>
        <td>0.95</td>
        <td>0.08</td>
        <td>いっぱい</td>
        <td>い-っ-ぱ-い</td>
        <td>p</td>
        <td>a,i</td>
        <td>Q</td>
        <td>i-Q-p-a-i</td>
        <td></td>
        <td>0</td>
        <td>Q,a,i,p</td>
        <td>i→Q,Q→p,p→a,a→i</td>
        <td></td>
        <td>gemination</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1</td>
        <td>0</td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>MEDIUM</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>spread_vowel → special_mora → bilabial_closure → open_vowel → spread_vowel</td>
        <td>bilabial_closure,open_vowel,special_mora,spread_vowel</td>
        <td>spread_vowel→special_mora,special_mora→bilabial_closure,bilabial_closure→open_vowel,open_vowel→spread_vowel</td>
        <td>bilabial_closure; open_vowel; special_mora; spread_vowel</td>
        <td>i:spread_vowel,Q:special_mora,p:bilabial_closure,a:open_vowel,i:spread_vowel</td>
        <td>i:spread_vowel→Q:special_mora,Q:special_mora→p:bilabial_closure,p:bilabial_closure→a:open_vowel,a:open_vowel→i:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.02631578947368421</td>
        <td>0.4</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.17021531100478468</td>
        <td>0.24761904761904763</td>
        <td>0.17177358981870258</td>
        <td>0.17917401158398388</td>
        <td>0.26065162907268175</td>
        <td>0.18081430507231852</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">75</td>
        <td>J075</td>
        <td>word</td>
        <td>新聞</td>
        <td>しんぶん</td>
        <td>4</td>
        <td>0.92</td>
        <td>0.93</td>
        <td>0.08</td>
        <td>しんぶん</td>
        <td>し-ん-ぶ-ん</td>
        <td>b,sh</td>
        <td>i,u</td>
        <td>N</td>
        <td>sh-i-N-b-u-N</td>
        <td></td>
        <td>0</td>
        <td>N,b,i,sh,u</td>
        <td>sh→i,i→N,N→b,b→u,u→N</td>
        <td></td>
        <td>moraic_nasal</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → spread_vowel → special_mora → bilabial_closure → rounded → special_mora</td>
        <td>bilabial_closure,coronal,rounded,special_mora,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→special_mora,special_mora→bilabial_closure,bilabial_closure→rounded,rounded→special_mora</td>
        <td>bilabial_closure; coronal; rounded; special_mora; spread_vowel</td>
        <td>sh:coronal,i:spread_vowel,N:special_mora,b:bilabial_closure,u:rounded,N:special_mora</td>
        <td>sh:coronal→i:spread_vowel,i:spread_vowel→N:special_mora,N:special_mora→b:bilabial_closure,b:bilabial_closure→u:rounded,u:rounded→N:special_mora</td>
        <td>0.15151515151515152</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.03289473684210526</td>
        <td>0.5</td>
        <td>0.11904761904761904</td>
        <td>0.03289473684210526</td>
        <td>0.17943580542264753</td>
        <td>0.30952380952380953</td>
        <td>0.19566936822575923</td>
        <td>0.19294172626091133</td>
        <td>0.33282130056323606</td>
        <td>0.21039717013522496</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">76</td>
        <td>J076</td>
        <td>word</td>
        <td>安全</td>
        <td>あんぜん</td>
        <td>4</td>
        <td>0.92</td>
        <td>0.93</td>
        <td>0.08</td>
        <td>あんぜん</td>
        <td>あ-ん-ぜ-ん</td>
        <td>z</td>
        <td>a,e</td>
        <td>N</td>
        <td>a-N-z-e-N</td>
        <td></td>
        <td>0</td>
        <td>N,a,e,z</td>
        <td>a→N,N→z,z→e,e→N</td>
        <td></td>
        <td>moraic_nasal</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>open_vowel → special_mora → coronal → spread_vowel → special_mora</td>
        <td>coronal,open_vowel,special_mora,spread_vowel</td>
        <td>open_vowel→special_mora,special_mora→coronal,coronal→spread_vowel,spread_vowel→special_mora</td>
        <td>coronal; open_vowel; special_mora; spread_vowel</td>
        <td>a:open_vowel,N:special_mora,z:coronal,e:spread_vowel,N:special_mora</td>
        <td>a:open_vowel→N:special_mora,N:special_mora→z:coronal,z:coronal→e:spread_vowel,e:spread_vowel→N:special_mora</td>
        <td>0.12121212121212122</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.02631578947368421</td>
        <td>0.4</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.17021531100478468</td>
        <td>0.24761904761904763</td>
        <td>0.17177358981870258</td>
        <td>0.18302721613417708</td>
        <td>0.26625704045058884</td>
        <td>0.1847027847512931</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">77</td>
        <td>J077</td>
        <td>word</td>
        <td>案内</td>
        <td>あんない</td>
        <td>4</td>
        <td>0.92</td>
        <td>0.93</td>
        <td>0.08</td>
        <td>あんない</td>
        <td>あ-ん-な-い</td>
        <td>n</td>
        <td>a,i</td>
        <td>N</td>
        <td>a-N-n-a-i</td>
        <td></td>
        <td>0</td>
        <td>N,a,i,n</td>
        <td>a→N,N→n,n→a,a→i</td>
        <td></td>
        <td>moraic_nasal</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>3</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>open_vowel → special_mora → coronal → open_vowel → spread_vowel</td>
        <td>coronal,open_vowel,special_mora,spread_vowel</td>
        <td>open_vowel→special_mora,special_mora→coronal,coronal→open_vowel,open_vowel→spread_vowel</td>
        <td>coronal; open_vowel; special_mora; spread_vowel</td>
        <td>a:open_vowel,N:special_mora,n:coronal,a:open_vowel,i:spread_vowel</td>
        <td>a:open_vowel→N:special_mora,N:special_mora→n:coronal,n:coronal→a:open_vowel,a:open_vowel→i:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.02631578947368421</td>
        <td>0.4</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.17021531100478468</td>
        <td>0.24761904761904763</td>
        <td>0.17177358981870258</td>
        <td>0.18302721613417708</td>
        <td>0.26625704045058884</td>
        <td>0.1847027847512931</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">78</td>
        <td>J078</td>
        <td>word</td>
        <td>温泉</td>
        <td>おんせん</td>
        <td>4</td>
        <td>0.92</td>
        <td>0.93</td>
        <td>0.08</td>
        <td>おんせん</td>
        <td>お-ん-せ-ん</td>
        <td>s</td>
        <td>e,o</td>
        <td>N</td>
        <td>o-N-s-e-N</td>
        <td></td>
        <td>0</td>
        <td>N,e,o,s</td>
        <td>o→N,N→s,s→e,e→N</td>
        <td></td>
        <td>moraic_nasal</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>rounded → special_mora → coronal → spread_vowel → special_mora</td>
        <td>coronal,rounded,special_mora,spread_vowel</td>
        <td>rounded→special_mora,special_mora→coronal,coronal→spread_vowel,spread_vowel→special_mora</td>
        <td>coronal; rounded; special_mora; spread_vowel</td>
        <td>o:rounded,N:special_mora,s:coronal,e:spread_vowel,N:special_mora</td>
        <td>o:rounded→N:special_mora,N:special_mora→s:coronal,s:coronal→e:spread_vowel,e:spread_vowel→N:special_mora</td>
        <td>0.12121212121212122</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.02631578947368421</td>
        <td>0.4</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.17021531100478468</td>
        <td>0.24761904761904763</td>
        <td>0.17177358981870258</td>
        <td>0.18302721613417708</td>
        <td>0.26625704045058884</td>
        <td>0.1847027847512931</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">79</td>
        <td>J079</td>
        <td>word</td>
        <td>先生</td>
        <td>せんせい</td>
        <td>4</td>
        <td>0.92</td>
        <td>0.96</td>
        <td>0.08</td>
        <td>せんせい</td>
        <td>せ-ん-せ-い</td>
        <td>s</td>
        <td>e,i</td>
        <td>N,R</td>
        <td>s-e-N-s-e-i</td>
        <td>e:3-4</td>
        <td>1</td>
        <td>N,e,i,s</td>
        <td>s→e,e→N,N→s,s→e,e→i</td>
        <td></td>
        <td>moraic_nasal,vowel_length</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>3</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → spread_vowel → special_mora → coronal → spread_vowel → spread_vowel</td>
        <td>coronal,special_mora,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→special_mora,special_mora→coronal,coronal→spread_vowel,spread_vowel→spread_vowel</td>
        <td>coronal; special_mora; spread_vowel</td>
        <td>s:coronal,e:spread_vowel,N:special_mora,s:coronal,e:spread_vowel,i:spread_vowel</td>
        <td>s:coronal→e:spread_vowel,e:spread_vowel→N:special_mora,N:special_mora→s:coronal,s:coronal→e:spread_vowel,e:spread_vowel→i:spread_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.6666666666666666</td>
        <td>0.4</td>
        <td>0.02631578947368421</td>
        <td>0.3</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.303548644338118</td>
        <td>0.1976190476190476</td>
        <td>0.2336783517234645</td>
        <td>0.31619650451887293</td>
        <td>0.2058531746031746</td>
        <td>0.2434149497119422</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">80</td>
        <td>J080</td>
        <td>word</td>
        <td>東京</td>
        <td>とうきょう</td>
        <td>4</td>
        <td>0.92</td>
        <td>0.95</td>
        <td>0.08</td>
        <td>とうきょう</td>
        <td>と-う-きょ-う</td>
        <td>ky,t</td>
        <td>o,u</td>
        <td>R</td>
        <td>t-o-u-ky-o-u</td>
        <td>o:1-2,o:3-4</td>
        <td>2</td>
        <td>ky,o,t,u</td>
        <td>t→o,o→u,u→ky,ky→o,o→u</td>
        <td></td>
        <td>vowel_length,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0</td>
        <td></td>
        <td>lexical_nucleus</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>HIGH</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>DICTIONARY_VERIFIED</td>
        <td></td>
        <td>coronal → rounded → rounded → low_visibility_velar → rounded → rounded</td>
        <td>coronal,low_visibility_velar,rounded</td>
        <td>coronal→rounded,rounded→rounded,rounded→low_visibility_velar,low_visibility_velar→rounded,rounded→rounded</td>
        <td>coronal; low_visibility_velar; rounded</td>
        <td>t:coronal,o:rounded,u:rounded,ky:low_visibility_velar,o:rounded,u:rounded</td>
        <td>t:coronal→o:rounded,o:rounded→u:rounded,u:rounded→ky:low_visibility_velar,ky:low_visibility_velar→o:rounded,o:rounded→u:rounded</td>
        <td>0.12121212121212122</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.02631578947368421</td>
        <td>0.3</td>
        <td>0.09523809523809523</td>
        <td>0.02631578947368421</td>
        <td>0.2202153110047847</td>
        <td>0.1976190476190476</td>
        <td>0.1860593041044169</td>
        <td>0.23180559053135233</td>
        <td>0.20802005012531327</td>
        <td>0.19585189905728095</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">81</td>
        <td>J081</td>
        <td>phrase</td>
        <td>青い空</td>
        <td>あおい そら</td>
        <td>5</td>
        <td>1.15</td>
        <td>1.17</td>
        <td>0.09</td>
        <td>あおいそら</td>
        <td>あ-お-い-そ-ら</td>
        <td>r,s</td>
        <td>a,i,o</td>
        <td></td>
        <td>a-o-i-s-o-r-a</td>
        <td></td>
        <td>0</td>
        <td>a,i,o,r,s</td>
        <td>a→o,o→i,i→s,s→o,o→r,r→a</td>
        <td>i→s</td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2+1</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>open_vowel → rounded → spread_vowel → coronal → rounded → coronal → open_vowel</td>
        <td>coronal,open_vowel,rounded,spread_vowel</td>
        <td>open_vowel→rounded,rounded→spread_vowel,spread_vowel→coronal,coronal→rounded,rounded→coronal,coronal→open_vowel</td>
        <td>coronal; open_vowel; rounded; spread_vowel</td>
        <td>a:open_vowel,o:rounded,i:spread_vowel,s:coronal,o:rounded,r:coronal,a:open_vowel</td>
        <td>a:open_vowel→o:rounded,o:rounded→i:spread_vowel,i:spread_vowel→s:coronal,s:coronal→o:rounded,o:rounded→r:coronal,r:coronal→a:open_vowel</td>
        <td>0.15151515151515152</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.039473684210526314</td>
        <td>0.4</td>
        <td>0.14285714285714285</td>
        <td>0.039473684210526314</td>
        <td>0.047747208931419455</td>
        <td>0.27142857142857146</td>
        <td>0.1104742375419067</td>
        <td>0.04080958028326449</td>
        <td>0.23199023199023203</td>
        <td>0.09442242524949292</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">82</td>
        <td>J082</td>
        <td>phrase</td>
        <td>赤い傘</td>
        <td>あかい かさ</td>
        <td>5</td>
        <td>1.15</td>
        <td>1.17</td>
        <td>0.09</td>
        <td>あかいかさ</td>
        <td>あ-か-い-か-さ</td>
        <td>k,s</td>
        <td>a,i</td>
        <td></td>
        <td>a-k-a-i-k-a-s-a</td>
        <td></td>
        <td>0</td>
        <td>a,i,k,s</td>
        <td>a→k,k→a,a→i,i→k,k→a,a→s,s→a</td>
        <td>i→k</td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0+1</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>open_vowel → low_visibility_velar → open_vowel → spread_vowel → low_visibility_velar → open_vowel → coronal → open_vowel</td>
        <td>coronal,low_visibility_velar,open_vowel,spread_vowel</td>
        <td>open_vowel→low_visibility_velar,low_visibility_velar→open_vowel,open_vowel→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→open_vowel,open_vowel→coronal,coronal→open_vowel</td>
        <td>coronal; low_visibility_velar; open_vowel; spread_vowel</td>
        <td>a:open_vowel,k:low_visibility_velar,a:open_vowel,i:spread_vowel,k:low_visibility_velar,a:open_vowel,s:coronal,a:open_vowel</td>
        <td>a:open_vowel→k:low_visibility_velar,k:low_visibility_velar→a:open_vowel,a:open_vowel→i:spread_vowel,i:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→a:open_vowel,a:open_vowel→s:coronal,s:coronal→a:open_vowel</td>
        <td>0.12121212121212122</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.039473684210526314</td>
        <td>0.4</td>
        <td>0.14285714285714285</td>
        <td>0.039473684210526314</td>
        <td>0.040171451355661886</td>
        <td>0.27142857142857146</td>
        <td>0.10614523321290238</td>
        <td>0.03433457380825802</td>
        <td>0.23199023199023203</td>
        <td>0.09072242154948922</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">83</td>
        <td>J083</td>
        <td>phrase</td>
        <td>大きな木</td>
        <td>おおきな き</td>
        <td>5</td>
        <td>1.15</td>
        <td>1.19</td>
        <td>0.09</td>
        <td>おおきなき</td>
        <td>お-お-き-な-き</td>
        <td>k,n</td>
        <td>a,i,o</td>
        <td>R</td>
        <td>o-o-k-i-n-a-k-i</td>
        <td>o:1-2</td>
        <td>1</td>
        <td>a,i,k,n,o</td>
        <td>o→o,o→k,k→i,i→n,n→a,a→k,k→i</td>
        <td>a→k</td>
        <td>vowel_length</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1+1</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>rounded → rounded → low_visibility_velar → spread_vowel → coronal → open_vowel → low_visibility_velar → spread_vowel</td>
        <td>coronal,low_visibility_velar,open_vowel,rounded,spread_vowel</td>
        <td>rounded→rounded,rounded→low_visibility_velar,low_visibility_velar→spread_vowel,spread_vowel→coronal,coronal→open_vowel,open_vowel→low_visibility_velar,low_visibility_velar→spread_vowel</td>
        <td>coronal; low_visibility_velar; open_vowel; rounded; spread_vowel</td>
        <td>o:rounded,o:rounded,k:low_visibility_velar,i:spread_vowel,n:coronal,a:open_vowel,k:low_visibility_velar,i:spread_vowel</td>
        <td>o:rounded→o:rounded,o:rounded→k:low_visibility_velar,k:low_visibility_velar→i:spread_vowel,i:spread_vowel→n:coronal,n:coronal→a:open_vowel,a:open_vowel→k:low_visibility_velar,k:low_visibility_velar→i:spread_vowel</td>
        <td>0.15151515151515152</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.039473684210526314</td>
        <td>0.5</td>
        <td>0.14285714285714285</td>
        <td>0.039473684210526314</td>
        <td>0.1810805422647528</td>
        <td>0.3214285714285714</td>
        <td>0.20095042801809718</td>
        <td>0.15216852291155697</td>
        <td>0.2701080432172869</td>
        <td>0.16886590589756065</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">84</td>
        <td>J084</td>
        <td>phrase</td>
        <td>小さな猫</td>
        <td>ちいさな ねこ</td>
        <td>6</td>
        <td>1.33</td>
        <td>1.39</td>
        <td>0.1</td>
        <td>ちいさなねこ</td>
        <td>ち-い-さ-な-ね-こ</td>
        <td>ch,k,n,s</td>
        <td>a,e,i,o</td>
        <td>R</td>
        <td>ch-i-i-s-a-n-a-n-e-k-o</td>
        <td>i:1-2</td>
        <td>1</td>
        <td>a,ch,e,i,k,n,o,s</td>
        <td>ch→i,i→i,i→s,s→a,a→n,n→a,a→n,n→e,e→k,k→o</td>
        <td>a→n</td>
        <td>vowel_length</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1+1</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>coronal → spread_vowel → spread_vowel → coronal → open_vowel → coronal → open_vowel → coronal → spread_vowel → low_visibility_velar → rounded</td>
        <td>coronal,low_visibility_velar,open_vowel,rounded,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→spread_vowel,spread_vowel→coronal,coronal→open_vowel,open_vowel→coronal,coronal→open_vowel,open_vowel→coronal,coronal→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→rounded</td>
        <td>coronal; low_visibility_velar; open_vowel; rounded; spread_vowel</td>
        <td>ch:coronal,i:spread_vowel,i:spread_vowel,s:coronal,a:open_vowel,n:coronal,a:open_vowel,n:coronal,e:spread_vowel,k:low_visibility_velar,o:rounded</td>
        <td>ch:coronal→i:spread_vowel,i:spread_vowel→i:spread_vowel,i:spread_vowel→s:coronal,s:coronal→a:open_vowel,a:open_vowel→n:coronal,n:coronal→a:open_vowel,a:open_vowel→n:coronal,n:coronal→e:spread_vowel,e:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→o:rounded</td>
        <td>0.24242424242424243</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.05921052631578947</td>
        <td>0.5</td>
        <td>0.16666666666666666</td>
        <td>0.05921052631578947</td>
        <td>0.2087420255183413</td>
        <td>0.3333333333333333</td>
        <td>0.22297789929368877</td>
        <td>0.1501741190779434</td>
        <td>0.23980815347721823</td>
        <td>0.1604157548875459</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">85</td>
        <td>J085</td>
        <td>phrase</td>
        <td>白い雲</td>
        <td>しろい くも</td>
        <td>5</td>
        <td>1.15</td>
        <td>1.17</td>
        <td>0.09</td>
        <td>しろいくも</td>
        <td>し-ろ-い-く-も</td>
        <td>k,m,r,sh</td>
        <td>i,o,u</td>
        <td></td>
        <td>sh-i-r-o-i-k-u-m-o</td>
        <td></td>
        <td>0</td>
        <td>i,k,m,o,r,sh,u</td>
        <td>sh→i,i→r,r→o,o→i,i→k,k→u,u→m,m→o</td>
        <td>i→k</td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2+1</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>coronal → spread_vowel → coronal → rounded → spread_vowel → low_visibility_velar → rounded → bilabial_closure → rounded</td>
        <td>bilabial_closure,coronal,low_visibility_velar,rounded,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→coronal,coronal→rounded,rounded→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→rounded,rounded→bilabial_closure,bilabial_closure→rounded</td>
        <td>bilabial_closure; coronal; low_visibility_velar; rounded; spread_vowel</td>
        <td>sh:coronal,i:spread_vowel,r:coronal,o:rounded,i:spread_vowel,k:low_visibility_velar,u:rounded,m:bilabial_closure,o:rounded</td>
        <td>sh:coronal→i:spread_vowel,i:spread_vowel→r:coronal,r:coronal→o:rounded,o:rounded→i:spread_vowel,i:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→u:rounded,u:rounded→m:bilabial_closure,m:bilabial_closure→o:rounded</td>
        <td>0.21212121212121213</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.05263157894736842</td>
        <td>0.5</td>
        <td>0.19047619047619047</td>
        <td>0.05263157894736842</td>
        <td>0.06618819776714513</td>
        <td>0.34523809523809523</td>
        <td>0.14398008007030563</td>
        <td>0.056571109202688145</td>
        <td>0.29507529507529506</td>
        <td>0.12305989749598772</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">86</td>
        <td>J086</td>
        <td>phrase</td>
        <td>黒い靴</td>
        <td>くろい くつ</td>
        <td>5</td>
        <td>1.15</td>
        <td>1.17</td>
        <td>0.09</td>
        <td>くろいくつ</td>
        <td>く-ろ-い-く-つ</td>
        <td>k,r,ts</td>
        <td>i,o,u</td>
        <td></td>
        <td>k-u-r-o-i-k-u-ts-u</td>
        <td></td>
        <td>0</td>
        <td>i,k,o,r,ts,u</td>
        <td>k→u,u→r,r→o,o→i,i→k,k→u,u→ts,ts→u</td>
        <td>i→k</td>
        <td>high_vowel_devoicing_context</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>2+2</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>low_visibility_velar → rounded → coronal → rounded → spread_vowel → low_visibility_velar → rounded → coronal → rounded</td>
        <td>coronal,low_visibility_velar,rounded,spread_vowel</td>
        <td>low_visibility_velar→rounded,rounded→coronal,coronal→rounded,rounded→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→rounded,rounded→coronal,coronal→rounded</td>
        <td>coronal; low_visibility_velar; rounded; spread_vowel</td>
        <td>k:low_visibility_velar,u:rounded,r:coronal,o:rounded,i:spread_vowel,k:low_visibility_velar,u:rounded,ts:coronal,u:rounded</td>
        <td>k:low_visibility_velar→u:rounded,u:rounded→r:coronal,r:coronal→o:rounded,o:rounded→i:spread_vowel,i:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→u:rounded,u:rounded→ts:coronal,ts:coronal→u:rounded</td>
        <td>0.18181818181818182</td>
        <td>0.0</td>
        <td>0.2</td>
        <td>0.046052631578947366</td>
        <td>0.4</td>
        <td>0.11904761904761904</td>
        <td>0.046052631578947366</td>
        <td>0.1069677033492823</td>
        <td>0.25952380952380955</td>
        <td>0.14185300914624224</td>
        <td>0.09142538747801907</td>
        <td>0.22181522181522184</td>
        <td>0.12124188815918141</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">87</td>
        <td>J087</td>
        <td>phrase</td>
        <td>新しい地図</td>
        <td>あたらしい ちず</td>
        <td>7</td>
        <td>1.51</td>
        <td>1.58</td>
        <td>0.1</td>
        <td>あたらしいちず</td>
        <td>あ-た-ら-し-い-ち-ず</td>
        <td>ch,r,sh,t,z</td>
        <td>a,i,u</td>
        <td>R</td>
        <td>a-t-a-r-a-sh-i-i-ch-i-z-u</td>
        <td>i:4-5</td>
        <td>1</td>
        <td>a,ch,i,r,sh,t,u,z</td>
        <td>a→t,t→a,a→r,r→a,a→sh,sh→i,i→i,i→ch,ch→i,i→z,z→u</td>
        <td>i→ch</td>
        <td>vowel_length</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>4+1</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>open_vowel → coronal → open_vowel → coronal → open_vowel → coronal → spread_vowel → spread_vowel → coronal → spread_vowel → coronal → rounded</td>
        <td>coronal,open_vowel,rounded,spread_vowel</td>
        <td>open_vowel→coronal,coronal→open_vowel,open_vowel→coronal,coronal→open_vowel,open_vowel→coronal,coronal→spread_vowel,spread_vowel→spread_vowel,spread_vowel→coronal,coronal→spread_vowel,spread_vowel→coronal,coronal→rounded</td>
        <td>coronal; open_vowel; rounded; spread_vowel</td>
        <td>a:open_vowel,t:coronal,a:open_vowel,r:coronal,a:open_vowel,sh:coronal,i:spread_vowel,i:spread_vowel,ch:coronal,i:spread_vowel,z:coronal,u:rounded</td>
        <td>a:open_vowel→t:coronal,t:coronal→a:open_vowel,a:open_vowel→r:coronal,r:coronal→a:open_vowel,a:open_vowel→sh:coronal,sh:coronal→i:spread_vowel,i:spread_vowel→i:spread_vowel,i:spread_vowel→ch:coronal,ch:coronal→i:spread_vowel,i:spread_vowel→z:coronal,z:coronal→u:rounded</td>
        <td>0.24242424242424243</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.07236842105263158</td>
        <td>0.4</td>
        <td>0.14285714285714285</td>
        <td>0.07236842105263158</td>
        <td>0.21203149920255182</td>
        <td>0.27142857142857146</td>
        <td>0.2090502229599974</td>
        <td>0.13419715139402014</td>
        <td>0.17179023508137434</td>
        <td>0.13231026769620088</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">88</td>
        <td>J088</td>
        <td>phrase</td>
        <td>静かな部屋</td>
        <td>しずかな へや</td>
        <td>6</td>
        <td>1.33</td>
        <td>1.36</td>
        <td>0.09</td>
        <td>しずかなへや</td>
        <td>し-ず-か-な-へ-や</td>
        <td>h,k,n,sh,y,z</td>
        <td>a,e,i,u</td>
        <td></td>
        <td>sh-i-z-u-k-a-n-a-h-e-y-a</td>
        <td></td>
        <td>0</td>
        <td>a,e,h,i,k,n,sh,u,y,z</td>
        <td>sh→i,i→z,z→u,u→k,k→a,a→n,n→a,a→h,h→e,e→y,y→a</td>
        <td>a→h</td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1+2</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>coronal → spread_vowel → coronal → rounded → low_visibility_velar → open_vowel → coronal → open_vowel → palatal_glottal → spread_vowel → palatal_glottal → open_vowel</td>
        <td>coronal,low_visibility_velar,open_vowel,palatal_glottal,rounded,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→coronal,coronal→rounded,rounded→low_visibility_velar,low_visibility_velar→open_vowel,open_vowel→coronal,coronal→open_vowel,open_vowel→palatal_glottal,palatal_glottal→spread_vowel,spread_vowel→palatal_glottal,palatal_glottal→open_vowel</td>
        <td>coronal; low_visibility_velar; open_vowel; palatal_glottal; rounded; spread_vowel</td>
        <td>sh:coronal,i:spread_vowel,z:coronal,u:rounded,k:low_visibility_velar,a:open_vowel,n:coronal,a:open_vowel,h:palatal_glottal,e:spread_vowel,y:palatal_glottal,a:open_vowel</td>
        <td>sh:coronal→i:spread_vowel,i:spread_vowel→z:coronal,z:coronal→u:rounded,u:rounded→k:low_visibility_velar,k:low_visibility_velar→a:open_vowel,a:open_vowel→n:coronal,n:coronal→a:open_vowel,a:open_vowel→h:palatal_glottal,h:palatal_glottal→e:spread_vowel,e:spread_vowel→y:palatal_glottal,y:palatal_glottal→a:open_vowel</td>
        <td>0.30303030303030304</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.07236842105263158</td>
        <td>0.6</td>
        <td>0.2619047619047619</td>
        <td>0.07236842105263158</td>
        <td>0.09384968102073366</td>
        <td>0.430952380952381</td>
        <td>0.18709598672004685</td>
        <td>0.06900711839759827</td>
        <td>0.3168767507002801</td>
        <td>0.13757057847062268</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">89</td>
        <td>J089</td>
        <td>phrase</td>
        <td>きれいな花</td>
        <td>きれいな はな</td>
        <td>6</td>
        <td>1.33</td>
        <td>1.39</td>
        <td>0.1</td>
        <td>きれいなはな</td>
        <td>き-れ-い-な-は-な</td>
        <td>h,k,n,r</td>
        <td>a,e,i</td>
        <td>R</td>
        <td>k-i-r-e-i-n-a-h-a-n-a</td>
        <td>e:2-3</td>
        <td>1</td>
        <td>a,e,h,i,k,n,r</td>
        <td>k→i,i→r,r→e,e→i,i→n,n→a,a→h,h→a,a→n,n→a</td>
        <td>a→h</td>
        <td>vowel_length</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1+2</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>low_visibility_velar → spread_vowel → coronal → spread_vowel → spread_vowel → coronal → open_vowel → palatal_glottal → open_vowel → coronal → open_vowel</td>
        <td>coronal,low_visibility_velar,open_vowel,palatal_glottal,spread_vowel</td>
        <td>low_visibility_velar→spread_vowel,spread_vowel→coronal,coronal→spread_vowel,spread_vowel→spread_vowel,spread_vowel→coronal,coronal→open_vowel,open_vowel→palatal_glottal,palatal_glottal→open_vowel,open_vowel→coronal,coronal→open_vowel</td>
        <td>coronal; low_visibility_velar; open_vowel; palatal_glottal; spread_vowel</td>
        <td>k:low_visibility_velar,i:spread_vowel,r:coronal,e:spread_vowel,i:spread_vowel,n:coronal,a:open_vowel,h:palatal_glottal,a:open_vowel,n:coronal,a:open_vowel</td>
        <td>k:low_visibility_velar→i:spread_vowel,i:spread_vowel→r:coronal,r:coronal→e:spread_vowel,e:spread_vowel→i:spread_vowel,i:spread_vowel→n:coronal,n:coronal→a:open_vowel,a:open_vowel→h:palatal_glottal,h:palatal_glottal→a:open_vowel,a:open_vowel→n:coronal,n:coronal→a:open_vowel</td>
        <td>0.21212121212121213</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.05921052631578947</td>
        <td>0.5</td>
        <td>0.19047619047619047</td>
        <td>0.05921052631578947</td>
        <td>0.20116626794258374</td>
        <td>0.34523809523809523</td>
        <td>0.22205025550890212</td>
        <td>0.144723933771643</td>
        <td>0.24837273038711888</td>
        <td>0.15974838525820298</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">90</td>
        <td>J090</td>
        <td>phrase</td>
        <td>冷たい水</td>
        <td>つめたい みず</td>
        <td>6</td>
        <td>1.33</td>
        <td>1.36</td>
        <td>0.09</td>
        <td>つめたいみず</td>
        <td>つ-め-た-い-み-ず</td>
        <td>m,t,ts,z</td>
        <td>a,e,i,u</td>
        <td></td>
        <td>ts-u-m-e-t-a-i-m-i-z-u</td>
        <td></td>
        <td>0</td>
        <td>a,e,i,m,t,ts,u,z</td>
        <td>ts→u,u→m,m→e,e→t,t→a,a→i,i→m,m→i,i→z,z→u</td>
        <td>i→m</td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0+0</td>
        <td>3+0</td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>coronal → rounded → bilabial_closure → spread_vowel → coronal → open_vowel → spread_vowel → bilabial_closure → spread_vowel → coronal → rounded</td>
        <td>bilabial_closure,coronal,open_vowel,rounded,spread_vowel</td>
        <td>coronal→rounded,rounded→bilabial_closure,bilabial_closure→spread_vowel,spread_vowel→coronal,coronal→open_vowel,open_vowel→spread_vowel,spread_vowel→bilabial_closure,bilabial_closure→spread_vowel,spread_vowel→coronal,coronal→rounded</td>
        <td>bilabial_closure; coronal; open_vowel; rounded; spread_vowel</td>
        <td>ts:coronal,u:rounded,m:bilabial_closure,e:spread_vowel,t:coronal,a:open_vowel,i:spread_vowel,m:bilabial_closure,i:spread_vowel,z:coronal,u:rounded</td>
        <td>ts:coronal→u:rounded,u:rounded→m:bilabial_closure,m:bilabial_closure→e:spread_vowel,e:spread_vowel→t:coronal,t:coronal→a:open_vowel,a:open_vowel→i:spread_vowel,i:spread_vowel→m:bilabial_closure,m:bilabial_closure→i:spread_vowel,i:spread_vowel→z:coronal,z:coronal→u:rounded</td>
        <td>0.24242424242424243</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.06578947368421052</td>
        <td>0.5</td>
        <td>0.16666666666666666</td>
        <td>0.06578947368421052</td>
        <td>0.07705342902711323</td>
        <td>0.3333333333333333</td>
        <td>0.1486671223513329</td>
        <td>0.05665693310817149</td>
        <td>0.24509803921568624</td>
        <td>0.10931406055245065</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">91</td>
        <td>J091</td>
        <td>phrase</td>
        <td>温かいお茶</td>
        <td>あたたかい おちゃ</td>
        <td>7</td>
        <td>1.51</td>
        <td>1.55</td>
        <td>0.09</td>
        <td>あたたかいおちゃ</td>
        <td>あ-た-た-か-い-お-ちゃ</td>
        <td>ch,k,t</td>
        <td>a,i,o</td>
        <td></td>
        <td>a-t-a-t-a-k-a-i-o-ch-a</td>
        <td></td>
        <td>0</td>
        <td>a,ch,i,k,o,t</td>
        <td>a→t,t→a,a→t,t→a,a→k,k→a,a→i,i→o,o→ch,ch→a</td>
        <td>i→o</td>
        <td>palatalization</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>4+0</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>open_vowel → coronal → open_vowel → coronal → open_vowel → low_visibility_velar → open_vowel → spread_vowel → rounded → coronal → open_vowel</td>
        <td>coronal,low_visibility_velar,open_vowel,rounded,spread_vowel</td>
        <td>open_vowel→coronal,coronal→open_vowel,open_vowel→coronal,coronal→open_vowel,open_vowel→low_visibility_velar,low_visibility_velar→open_vowel,open_vowel→spread_vowel,spread_vowel→rounded,rounded→coronal,coronal→open_vowel</td>
        <td>coronal; low_visibility_velar; open_vowel; rounded; spread_vowel</td>
        <td>a:open_vowel,t:coronal,a:open_vowel,t:coronal,a:open_vowel,k:low_visibility_velar,a:open_vowel,i:spread_vowel,o:rounded,ch:coronal,a:open_vowel</td>
        <td>a:open_vowel→t:coronal,t:coronal→a:open_vowel,a:open_vowel→t:coronal,t:coronal→a:open_vowel,a:open_vowel→k:low_visibility_velar,k:low_visibility_velar→a:open_vowel,a:open_vowel→i:spread_vowel,i:spread_vowel→o:rounded,o:rounded→ch:coronal,ch:coronal→a:open_vowel</td>
        <td>0.18181818181818182</td>
        <td>0.0</td>
        <td>0.2</td>
        <td>0.05263157894736842</td>
        <td>0.5</td>
        <td>0.16666666666666666</td>
        <td>0.05263157894736842</td>
        <td>0.10861244019138756</td>
        <td>0.3333333333333333</td>
        <td>0.16482114376851217</td>
        <td>0.07007254205895971</td>
        <td>0.2150537634408602</td>
        <td>0.10633622178613689</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">92</td>
        <td>J092</td>
        <td>phrase</td>
        <td>切符を買う</td>
        <td>きっぷを かう</td>
        <td>6</td>
        <td>1.33</td>
        <td>1.41</td>
        <td>0.1</td>
        <td>きっぷをかう</td>
        <td>き-っ-ぷ-を-か-う</td>
        <td>k,p</td>
        <td>a,i,o,u</td>
        <td>Q</td>
        <td>k-i-Q-p-u-o-k-a-u</td>
        <td></td>
        <td>0</td>
        <td>Q,a,i,k,o,p,u</td>
        <td>k→i,i→Q,Q→p,p→u,u→o,o→k,k→a,a→u</td>
        <td>o→k</td>
        <td>gemination</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0+0</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>low_visibility_velar → spread_vowel → special_mora → bilabial_closure → rounded → rounded → low_visibility_velar → open_vowel → rounded</td>
        <td>bilabial_closure,low_visibility_velar,open_vowel,rounded,special_mora,spread_vowel</td>
        <td>low_visibility_velar→spread_vowel,spread_vowel→special_mora,special_mora→bilabial_closure,bilabial_closure→rounded,rounded→rounded,rounded→low_visibility_velar,low_visibility_velar→open_vowel,open_vowel→rounded</td>
        <td>bilabial_closure; low_visibility_velar; open_vowel; rounded; special_mora; spread_vowel</td>
        <td>k:low_visibility_velar,i:spread_vowel,Q:special_mora,p:bilabial_closure,u:rounded,o:rounded,k:low_visibility_velar,a:open_vowel,u:rounded</td>
        <td>k:low_visibility_velar→i:spread_vowel,i:spread_vowel→Q:special_mora,Q:special_mora→p:bilabial_closure,p:bilabial_closure→u:rounded,u:rounded→o:rounded,o:rounded→k:low_visibility_velar,k:low_visibility_velar→a:open_vowel,a:open_vowel→u:rounded</td>
        <td>0.21212121212121213</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.05263157894736842</td>
        <td>0.6</td>
        <td>0.19047619047619047</td>
        <td>0.05263157894736842</td>
        <td>0.19952153110047846</td>
        <td>0.3952380952380952</td>
        <td>0.2344562705464961</td>
        <td>0.14150463198615496</td>
        <td>0.28031070584262074</td>
        <td>0.1662810429407774</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">93</td>
        <td>J093</td>
        <td>phrase</td>
        <td>写真を撮る</td>
        <td>しゃしんを とる</td>
        <td>6</td>
        <td>1.33</td>
        <td>1.39</td>
        <td>0.1</td>
        <td>しゃしんをとる</td>
        <td>しゃ-し-ん-を-と-る</td>
        <td>r,sh,t</td>
        <td>a,i,o,u</td>
        <td>N</td>
        <td>sh-a-sh-i-N-o-t-o-r-u</td>
        <td></td>
        <td>0</td>
        <td>N,a,i,o,r,sh,t,u</td>
        <td>sh→a,a→sh,sh→i,i→N,N→o,o→t,t→o,o→r,r→u</td>
        <td>o→t</td>
        <td>moraic_nasal,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>0+1</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>coronal → open_vowel → coronal → spread_vowel → special_mora → rounded → coronal → rounded → coronal → rounded</td>
        <td>coronal,open_vowel,rounded,special_mora,spread_vowel</td>
        <td>coronal→open_vowel,open_vowel→coronal,coronal→spread_vowel,spread_vowel→special_mora,special_mora→rounded,rounded→coronal,coronal→rounded,rounded→coronal,coronal→rounded</td>
        <td>coronal; open_vowel; rounded; special_mora; spread_vowel</td>
        <td>sh:coronal,a:open_vowel,sh:coronal,i:spread_vowel,N:special_mora,o:rounded,t:coronal,o:rounded,r:coronal,u:rounded</td>
        <td>sh:coronal→a:open_vowel,a:open_vowel→sh:coronal,sh:coronal→i:spread_vowel,i:spread_vowel→N:special_mora,N:special_mora→o:rounded,o:rounded→t:coronal,t:coronal→o:rounded,o:rounded→r:coronal,r:coronal→u:rounded</td>
        <td>0.24242424242424243</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.05921052631578947</td>
        <td>0.5</td>
        <td>0.16666666666666666</td>
        <td>0.05921052631578947</td>
        <td>0.2587420255183413</td>
        <td>0.3333333333333333</td>
        <td>0.25154932786511736</td>
        <td>0.18614534209952613</td>
        <td>0.23980815347721823</td>
        <td>0.18097073947130746</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">94</td>
        <td>J094</td>
        <td>phrase</td>
        <td>ゆっくり話す</td>
        <td>ゆっくり はなす</td>
        <td>7</td>
        <td>1.51</td>
        <td>1.6</td>
        <td>0.1</td>
        <td>ゆっくりはなす</td>
        <td>ゆ-っ-く-り-は-な-す</td>
        <td>h,k,n,r,s,y</td>
        <td>a,i,u</td>
        <td>Q</td>
        <td>y-u-Q-k-u-r-i-h-a-n-a-s-u</td>
        <td></td>
        <td>0</td>
        <td>Q,a,h,i,k,n,r,s,u,y</td>
        <td>y→u,u→Q,Q→k,k→u,u→r,r→i,i→h,h→a,a→n,n→a,a→s,s→u</td>
        <td>i→h</td>
        <td>gemination</td>
        <td>1</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>3+2</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>palatal_glottal → rounded → special_mora → low_visibility_velar → rounded → coronal → spread_vowel → palatal_glottal → open_vowel → coronal → open_vowel → coronal → rounded</td>
        <td>coronal,low_visibility_velar,open_vowel,palatal_glottal,rounded,special_mora,spread_vowel</td>
        <td>palatal_glottal→rounded,rounded→special_mora,special_mora→low_visibility_velar,low_visibility_velar→rounded,rounded→coronal,coronal→spread_vowel,spread_vowel→palatal_glottal,palatal_glottal→open_vowel,open_vowel→coronal,coronal→open_vowel,open_vowel→coronal,coronal→rounded</td>
        <td>coronal; low_visibility_velar; open_vowel; palatal_glottal; rounded; special_mora; spread_vowel</td>
        <td>y:palatal_glottal,u:rounded,Q:special_mora,k:low_visibility_velar,u:rounded,r:coronal,i:spread_vowel,h:palatal_glottal,a:open_vowel,n:coronal,a:open_vowel,s:coronal,u:rounded</td>
        <td>y:palatal_glottal→u:rounded,u:rounded→Q:special_mora,Q:special_mora→k:low_visibility_velar,k:low_visibility_velar→u:rounded,u:rounded→r:coronal,r:coronal→i:spread_vowel,i:spread_vowel→h:palatal_glottal,h:palatal_glottal→a:open_vowel,a:open_vowel→n:coronal,n:coronal→a:open_vowel,a:open_vowel→s:coronal,s:coronal→u:rounded</td>
        <td>0.30303030303030304</td>
        <td>0.3333333333333333</td>
        <td>0.2</td>
        <td>0.07894736842105263</td>
        <td>0.7</td>
        <td>0.2619047619047619</td>
        <td>0.07894736842105263</td>
        <td>0.22882775119617224</td>
        <td>0.4809523809523809</td>
        <td>0.27945187644435765</td>
        <td>0.14301734449760764</td>
        <td>0.300595238095238</td>
        <td>0.17465742277772353</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">95</td>
        <td>J095</td>
        <td>phrase</td>
        <td>駅まで歩く</td>
        <td>えきまで あるく</td>
        <td>7</td>
        <td>1.51</td>
        <td>1.55</td>
        <td>0.09</td>
        <td>えきまであるく</td>
        <td>え-き-ま-で-あ-る-く</td>
        <td>d,k,m,r</td>
        <td>a,e,i,u</td>
        <td></td>
        <td>e-k-i-m-a-d-e-a-r-u-k-u</td>
        <td></td>
        <td>0</td>
        <td>a,d,e,i,k,m,r,u</td>
        <td>e→k,k→i,i→m,m→a,a→d,d→e,e→a,a→r,r→u,u→k,k→u</td>
        <td>e→a</td>
        <td></td>
        <td>0</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1+2</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Pitch pattern lists lexical components in order.</td>
        <td>spread_vowel → low_visibility_velar → spread_vowel → bilabial_closure → open_vowel → coronal → spread_vowel → open_vowel → coronal → rounded → low_visibility_velar → rounded</td>
        <td>bilabial_closure,coronal,low_visibility_velar,open_vowel,rounded,spread_vowel</td>
        <td>spread_vowel→low_visibility_velar,low_visibility_velar→spread_vowel,spread_vowel→bilabial_closure,bilabial_closure→open_vowel,open_vowel→coronal,coronal→spread_vowel,spread_vowel→open_vowel,open_vowel→coronal,coronal→rounded,rounded→low_visibility_velar,low_visibility_velar→rounded</td>
        <td>bilabial_closure; coronal; low_visibility_velar; open_vowel; rounded; spread_vowel</td>
        <td>e:spread_vowel,k:low_visibility_velar,i:spread_vowel,m:bilabial_closure,a:open_vowel,d:coronal,e:spread_vowel,a:open_vowel,r:coronal,u:rounded,k:low_visibility_velar,u:rounded</td>
        <td>e:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→i:spread_vowel,i:spread_vowel→m:bilabial_closure,m:bilabial_closure→a:open_vowel,a:open_vowel→d:coronal,d:coronal→e:spread_vowel,e:spread_vowel→a:open_vowel,a:open_vowel→r:coronal,r:coronal→u:rounded,u:rounded→k:low_visibility_velar,k:low_visibility_velar→u:rounded</td>
        <td>0.24242424242424243</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>0.07236842105263158</td>
        <td>0.6</td>
        <td>0.23809523809523808</td>
        <td>0.07236842105263158</td>
        <td>0.0786981658692185</td>
        <td>0.419047619047619</td>
        <td>0.17503661751782054</td>
        <td>0.050773010238205483</td>
        <td>0.2703533026113671</td>
        <td>0.11292685001149712</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
      <tr>
        <td class="line-num">96</td>
        <td>J096</td>
        <td>phrase</td>
        <td>今日は晴れです</td>
        <td>きょうわ はれです</td>
        <td>7</td>
        <td>1.51</td>
        <td>1.58</td>
        <td>0.1</td>
        <td>きょうわはれです</td>
        <td>きょ-う-わ-は-れ-で-す</td>
        <td>d,h,ky,r,s,w</td>
        <td>a,e,o,u</td>
        <td>R</td>
        <td>ky-o-u-w-a-h-a-r-e-d-e-s-u</td>
        <td>o:1-2</td>
        <td>1</td>
        <td>a,d,e,h,ky,o,r,s,u,w</td>
        <td>ky→o,o→u,u→w,w→a,a→h,h→a,a→r,r→e,e→d,d→e,e→s,s→u</td>
        <td>a→h</td>
        <td>vowel_length,palatalization</td>
        <td>2</td>
        <td>mora_timed;pitch_accent_relevant</td>
        <td>1+2+1</td>
        <td></td>
        <td>lexical_component_sequence</td>
        <td>Accent Jiten aggregation: OJAD; NHK; Wiktionary; Kanjium; Kishimoto Tsuneyo</td>
        <td>COMPONENT_LEVEL</td>
        <td>RULE_REVIEWED</td>
        <td>RULE_REVIEWED</td>
        <td>COMPONENTS_VERIFIED; UTTERANCE_F0_NOT_MEASURED</td>
        <td>Phrase pronunciation uses surface particle reading; pitch pattern lists lexical components.</td>
        <td>low_visibility_velar → rounded → rounded → rounded → open_vowel → palatal_glottal → open_vowel → coronal → spread_vowel → coronal → spread_vowel → coronal → rounded</td>
        <td>coronal,low_visibility_velar,open_vowel,palatal_glottal,rounded,spread_vowel</td>
        <td>low_visibility_velar→rounded,rounded→rounded,rounded→rounded,rounded→open_vowel,open_vowel→palatal_glottal,palatal_glottal→open_vowel,open_vowel→coronal,coronal→spread_vowel,spread_vowel→coronal,coronal→spread_vowel,spread_vowel→coronal,coronal→rounded</td>
        <td>coronal; low_visibility_velar; open_vowel; palatal_glottal; rounded; spread_vowel</td>
        <td>ky:low_visibility_velar,o:rounded,u:rounded,w:rounded,a:open_vowel,h:palatal_glottal,a:open_vowel,r:coronal,e:spread_vowel,d:coronal,e:spread_vowel,s:coronal,u:rounded</td>
        <td>ky:low_visibility_velar→o:rounded,o:rounded→u:rounded,u:rounded→w:rounded,w:rounded→a:open_vowel,a:open_vowel→h:palatal_glottal,h:palatal_glottal→a:open_vowel,a:open_vowel→r:coronal,r:coronal→e:spread_vowel,e:spread_vowel→d:coronal,d:coronal→e:spread_vowel,e:spread_vowel→s:coronal,s:coronal→u:rounded</td>
        <td>0.30303030303030304</td>
        <td>0.3333333333333333</td>
        <td>0.4</td>
        <td>0.07894736842105263</td>
        <td>0.6</td>
        <td>0.21428571428571427</td>
        <td>0.07894736842105263</td>
        <td>0.27882775119617226</td>
        <td>0.40714285714285714</td>
        <td>0.28693486964163656</td>
        <td>0.17647326025074192</td>
        <td>0.2576853526220615</td>
        <td>0.1816043478744535</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.14 + 0.19*mora + 0.03*N + 0.045*Q + 0.025*long_mora + 0.08*phrase; SD=0.035+0.018*sqrt(mora)+0.012*phrase+0.005*special</td>
      </tr>
    </tbody>
  </table>
</div>

</div>

### Vietnamese