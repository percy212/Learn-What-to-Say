# Learn What to Say: Generalizable Active Enrollment for Few-Shot Voice Personalization

This repository contains the lexicon files used in **LEAP** (**L**anguage-Transferable **E**nrollment via **A**ctive **P**olicy Learning).

## Overview

To support the methodology proposed in **LEAP**, we provide lexicon CSV files across four languages:
- Korean
- Japanese
- Vietnamese
- English

All lexicon files can be found in the `csv/` directory.

## Preview
Below is a preview of the lexicon CSV data used in our framework.

| Language | Path |
| :--- | :--- |
| **Korean** | `csv/korean.csv` |
| **Japanese** | `csv/japanese.csv` |
| **Vietnamese** | `csv/vietnamese.csv` |
| **English** | `csv/english.csv` |

> **Note:** For more implementation and experiment details, please refer to our main paper.

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
        <th>dialect</th>
        <th>syllable_count</th>
        <th>estimated_duration</th>
        <th>actual_duration_mean</th>
        <th>standard_deviation</th>
        <th>duration_measurement_status</th>
        <th>duration_model</th>
        <th>pronunciation_ipa</th>
        <th>syllable_sequence</th>
        <th>initials</th>
        <th>nuclei</th>
        <th>codas</th>
        <th>phoneme_sequence</th>
        <th>phoneme_set</th>
        <th>phoneme_transitions</th>
        <th>cross_word_transition</th>
        <th>tone_sequence</th>
        <th>tone_set</th>
        <th>tone_transitions</th>
        <th>checked_syllables</th>
        <th>checked_syllable_count</th>
        <th>phonological_features</th>
        <th>viseme_sequence</th>
        <th>viseme_set</th>
        <th>viseme_transitions</th>
        <th>visual_features</th>
        <th>phoneme_viseme_pairs</th>
        <th>av_transitions</th>
        <th>phoneme_coverage_gain</th>
        <th>coda_coverage_gain</th>
        <th>tone_coverage_gain</th>
        <th>phoneme_transition_gain</th>
        <th>tone_transition_gain</th>
        <th>combined_transition_gain</th>
        <th>viseme_coverage_gain</th>
        <th>viseme_transition_gain</th>
        <th>av_transition_gain</th>
        <th>audio_score</th>
        <th>vision_score</th>
        <th>joint_av_score</th>
        <th>audio_score_per_sec</th>
        <th>vision_score_per_sec</th>
        <th>joint_av_score_per_sec</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="line-num">1</td>
        <td>V001</td>
        <td>word</td>
        <td>ba</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɓaː/</td>
        <td>ba</td>
        <td>b</td>
        <td>a</td>
        <td>∅</td>
        <td>ɓ-aː</td>
        <td>aː,ɓ</td>
        <td>ɓ→aː</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>bilabial_closure → open_vowel</td>
        <td>bilabial_closure,open_vowel</td>
        <td>bilabial_closure→open_vowel</td>
        <td>bilabial_closure,open_vowel</td>
        <td>ɓ:bilabial_closure,aː:open_vowel</td>
        <td>ɓ:bilabial_closure→aː:open_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">2</td>
        <td>V002</td>
        <td>word</td>
        <td>bà</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɓaː/</td>
        <td>bà</td>
        <td>b</td>
        <td>a</td>
        <td>∅</td>
        <td>ɓ-aː</td>
        <td>aː,ɓ</td>
        <td>ɓ→aː</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>bilabial_closure → open_vowel</td>
        <td>bilabial_closure,open_vowel</td>
        <td>bilabial_closure→open_vowel</td>
        <td>bilabial_closure,open_vowel</td>
        <td>ɓ:bilabial_closure,aː:open_vowel</td>
        <td>ɓ:bilabial_closure→aː:open_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">3</td>
        <td>V003</td>
        <td>word</td>
        <td>cá</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/kaː/</td>
        <td>cá</td>
        <td>c</td>
        <td>a</td>
        <td>∅</td>
        <td>k-aː</td>
        <td>aː,k</td>
        <td>k→aː</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>low_visibility_velar → open_vowel</td>
        <td>low_visibility_velar,open_vowel</td>
        <td>low_visibility_velar→open_vowel</td>
        <td>low_visibility_velar,open_vowel</td>
        <td>k:low_visibility_velar,aː:open_vowel</td>
        <td>k:low_visibility_velar→aː:open_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">4</td>
        <td>V004</td>
        <td>word</td>
        <td>cả</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/kaː/</td>
        <td>cả</td>
        <td>c</td>
        <td>a</td>
        <td>∅</td>
        <td>k-aː</td>
        <td>aː,k</td>
        <td>k→aː</td>
        <td></td>
        <td>hỏi</td>
        <td>hỏi</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>low_visibility_velar → open_vowel</td>
        <td>low_visibility_velar,open_vowel</td>
        <td>low_visibility_velar→open_vowel</td>
        <td>low_visibility_velar,open_vowel</td>
        <td>k:low_visibility_velar,aː:open_vowel</td>
        <td>k:low_visibility_velar→aː:open_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">5</td>
        <td>V005</td>
        <td>word</td>
        <td>mã</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/maː/</td>
        <td>mã</td>
        <td>m</td>
        <td>a</td>
        <td>∅</td>
        <td>m-aː</td>
        <td>aː,m</td>
        <td>m→aː</td>
        <td></td>
        <td>ngã</td>
        <td>ngã</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast</td>
        <td>bilabial_closure → open_vowel</td>
        <td>bilabial_closure,open_vowel</td>
        <td>bilabial_closure→open_vowel</td>
        <td>bilabial_closure,open_vowel</td>
        <td>m:bilabial_closure,aː:open_vowel</td>
        <td>m:bilabial_closure→aː:open_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">6</td>
        <td>V006</td>
        <td>word</td>
        <td>bạn</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɓaːn/</td>
        <td>bạn</td>
        <td>b</td>
        <td>a</td>
        <td>n</td>
        <td>ɓ-aː-n</td>
        <td>aː,n,ɓ</td>
        <td>ɓ→aː,aː→n</td>
        <td></td>
        <td>nặng</td>
        <td>nặng</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast</td>
        <td>bilabial_closure → open_vowel → coronal</td>
        <td>bilabial_closure,coronal,open_vowel</td>
        <td>bilabial_closure→open_vowel,open_vowel→coronal</td>
        <td>bilabial_closure,coronal,open_vowel</td>
        <td>ɓ:bilabial_closure,aː:open_vowel,n:coronal</td>
        <td>ɓ:bilabial_closure→aː:open_vowel,aː:open_vowel→n:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">7</td>
        <td>V007</td>
        <td>word</td>
        <td>nhà</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɲaː/</td>
        <td>nhà</td>
        <td>nh</td>
        <td>a</td>
        <td>∅</td>
        <td>ɲ-aː</td>
        <td>aː,ɲ</td>
        <td>ɲ→aː</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>palatal → open_vowel</td>
        <td>open_vowel,palatal</td>
        <td>palatal→open_vowel</td>
        <td>open_vowel,palatal</td>
        <td>ɲ:palatal,aː:open_vowel</td>
        <td>ɲ:palatal→aː:open_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">8</td>
        <td>V008</td>
        <td>word</td>
        <td>hoa</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/hwaː/</td>
        <td>hoa</td>
        <td>h</td>
        <td>oa</td>
        <td>∅</td>
        <td>h-waː</td>
        <td>h,waː</td>
        <td>h→waː</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>glottal → rounded</td>
        <td>glottal,rounded</td>
        <td>glottal→rounded</td>
        <td>glottal,rounded</td>
        <td>h:glottal,waː:rounded</td>
        <td>h:glottal→waː:rounded</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">9</td>
        <td>V009</td>
        <td>word</td>
        <td>xe</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/sɛ/</td>
        <td>xe</td>
        <td>x</td>
        <td>e</td>
        <td>∅</td>
        <td>s-ɛ</td>
        <td>s,ɛ</td>
        <td>s→ɛ</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → spread_vowel</td>
        <td>coronal,spread_vowel</td>
        <td>coronal→spread_vowel</td>
        <td>coronal,spread_vowel</td>
        <td>s:coronal,ɛ:spread_vowel</td>
        <td>s:coronal→ɛ:spread_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">10</td>
        <td>V010</td>
        <td>word</td>
        <td>đi</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɗi/</td>
        <td>đi</td>
        <td>đ</td>
        <td>i</td>
        <td>∅</td>
        <td>ɗ-i</td>
        <td>i,ɗ</td>
        <td>ɗ→i</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>central_vowel → spread_vowel</td>
        <td>central_vowel,spread_vowel</td>
        <td>central_vowel→spread_vowel</td>
        <td>central_vowel,spread_vowel</td>
        <td>ɗ:central_vowel,i:spread_vowel</td>
        <td>ɗ:central_vowel→i:spread_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">11</td>
        <td>V011</td>
        <td>word</td>
        <td>về</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ve/</td>
        <td>về</td>
        <td>v</td>
        <td>ê</td>
        <td>∅</td>
        <td>v-e</td>
        <td>e,v</td>
        <td>v→e</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>labiodental → spread_vowel</td>
        <td>labiodental,spread_vowel</td>
        <td>labiodental→spread_vowel</td>
        <td>labiodental,spread_vowel</td>
        <td>v:labiodental,e:spread_vowel</td>
        <td>v:labiodental→e:spread_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">12</td>
        <td>V012</td>
        <td>word</td>
        <td>ăn</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/an/</td>
        <td>ăn</td>
        <td>∅</td>
        <td>ă</td>
        <td>n</td>
        <td>a-n</td>
        <td>a,n</td>
        <td>a→n</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>open_vowel → coronal</td>
        <td>coronal,open_vowel</td>
        <td>open_vowel→coronal</td>
        <td>coronal,open_vowel</td>
        <td>a:open_vowel,n:coronal</td>
        <td>a:open_vowel→n:coronal</td>
        <td>0.046511627906976744</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.07491407049875676</td>
        <td>0.1090909090909091</td>
        <td>0.07487534405042083</td>
        <td>0.14406552018991683</td>
        <td>0.2097902097902098</td>
        <td>0.14399104625080927</td>
      </tr>
      <tr>
        <td class="line-num">13</td>
        <td>V013</td>
        <td>word</td>
        <td>cơm</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/kɤm/</td>
        <td>cơm</td>
        <td>c</td>
        <td>ơ</td>
        <td>m</td>
        <td>k-ɤ-m</td>
        <td>k,m,ɤ</td>
        <td>k→ɤ,ɤ→m</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>low_visibility_velar → central_vowel → bilabial_closure</td>
        <td>bilabial_closure,central_vowel,low_visibility_velar</td>
        <td>low_visibility_velar→central_vowel,central_vowel→bilabial_closure</td>
        <td>bilabial_closure,central_vowel,low_visibility_velar</td>
        <td>k:low_visibility_velar,ɤ:central_vowel,m:bilabial_closure</td>
        <td>k:low_visibility_velar→ɤ:central_vowel,ɤ:central_vowel→m:bilabial_closure</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">14</td>
        <td>V014</td>
        <td>word</td>
        <td>nước</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/nɯək̚/</td>
        <td>nước</td>
        <td>n</td>
        <td>ươ</td>
        <td>c</td>
        <td>n-ɯə-k̚</td>
        <td>k̚,n,ɯə</td>
        <td>n→ɯə,ɯə→k̚</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td>nước</td>
        <td>1</td>
        <td>checked_syllable</td>
        <td>coronal → central_vowel → low_visibility_velar</td>
        <td>central_vowel,coronal,low_visibility_velar</td>
        <td>coronal→central_vowel,central_vowel→low_visibility_velar</td>
        <td>central_vowel,coronal,low_visibility_velar</td>
        <td>n:coronal,ɯə:central_vowel,k̚:low_visibility_velar</td>
        <td>n:coronal→ɯə:central_vowel,ɯə:central_vowel→k̚:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.16635548471253356</td>
        <td>0.3432282003710575</td>
        <td>0.19679271217271233</td>
      </tr>
      <tr>
        <td class="line-num">15</td>
        <td>V015</td>
        <td>word</td>
        <td>trà</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ʈaː/</td>
        <td>trà</td>
        <td>tr</td>
        <td>a</td>
        <td>∅</td>
        <td>ʈ-aː</td>
        <td>aː,ʈ</td>
        <td>ʈ→aː</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → open_vowel</td>
        <td>coronal,open_vowel</td>
        <td>coronal→open_vowel</td>
        <td>coronal,open_vowel</td>
        <td>ʈ:coronal,aː:open_vowel</td>
        <td>ʈ:coronal→aː:open_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">16</td>
        <td>V016</td>
        <td>word</td>
        <td>sữa</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ʂɯə/</td>
        <td>sữa</td>
        <td>s</td>
        <td>ưa</td>
        <td>∅</td>
        <td>ʂ-ɯə</td>
        <td>ɯə,ʂ</td>
        <td>ʂ→ɯə</td>
        <td></td>
        <td>ngã</td>
        <td>ngã</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast</td>
        <td>coronal → central_vowel</td>
        <td>central_vowel,coronal</td>
        <td>coronal→central_vowel</td>
        <td>central_vowel,coronal</td>
        <td>ʂ:coronal,ɯə:central_vowel</td>
        <td>ʂ:coronal→ɯə:central_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">17</td>
        <td>V017</td>
        <td>word</td>
        <td>sách</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ʂaːc̚/</td>
        <td>sách</td>
        <td>s</td>
        <td>a</td>
        <td>ch</td>
        <td>ʂ-aː-c̚</td>
        <td>aː,c̚,ʂ</td>
        <td>ʂ→aː,aː→c̚</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td>sách</td>
        <td>1</td>
        <td>checked_syllable</td>
        <td>coronal → open_vowel → palatal</td>
        <td>coronal,open_vowel,palatal</td>
        <td>coronal→open_vowel,open_vowel→palatal</td>
        <td>coronal,open_vowel,palatal</td>
        <td>ʂ:coronal,aː:open_vowel,c̚:palatal</td>
        <td>ʂ:coronal→aː:open_vowel,aː:open_vowel→c̚:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.16635548471253356</td>
        <td>0.3432282003710575</td>
        <td>0.19679271217271233</td>
      </tr>
      <tr>
        <td class="line-num">18</td>
        <td>V018</td>
        <td>word</td>
        <td>bút</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɓut̚/</td>
        <td>bút</td>
        <td>b</td>
        <td>u</td>
        <td>t</td>
        <td>ɓ-u-t̚</td>
        <td>t̚,u,ɓ</td>
        <td>ɓ→u,u→t̚</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td>bút</td>
        <td>1</td>
        <td>checked_syllable</td>
        <td>bilabial_closure → rounded → coronal</td>
        <td>bilabial_closure,coronal,rounded</td>
        <td>bilabial_closure→rounded,rounded→coronal</td>
        <td>bilabial_closure,coronal,rounded</td>
        <td>ɓ:bilabial_closure,u:rounded,t̚:coronal</td>
        <td>ɓ:bilabial_closure→u:rounded,u:rounded→t̚:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.16635548471253356</td>
        <td>0.3432282003710575</td>
        <td>0.19679271217271233</td>
      </tr>
      <tr>
        <td class="line-num">19</td>
        <td>V019</td>
        <td>word</td>
        <td>bàn</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɓaːn/</td>
        <td>bàn</td>
        <td>b</td>
        <td>a</td>
        <td>n</td>
        <td>ɓ-aː-n</td>
        <td>aː,n,ɓ</td>
        <td>ɓ→aː,aː→n</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>bilabial_closure → open_vowel → coronal</td>
        <td>bilabial_closure,coronal,open_vowel</td>
        <td>bilabial_closure→open_vowel,open_vowel→coronal</td>
        <td>bilabial_closure,coronal,open_vowel</td>
        <td>ɓ:bilabial_closure,aː:open_vowel,n:coronal</td>
        <td>ɓ:bilabial_closure→aː:open_vowel,aː:open_vowel→n:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">20</td>
        <td>V020</td>
        <td>word</td>
        <td>ghế</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɣe/</td>
        <td>ghế</td>
        <td>gh</td>
        <td>ê</td>
        <td>∅</td>
        <td>ɣ-e</td>
        <td>e,ɣ</td>
        <td>ɣ→e</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>low_visibility_velar → spread_vowel</td>
        <td>low_visibility_velar,spread_vowel</td>
        <td>low_visibility_velar→spread_vowel</td>
        <td>low_visibility_velar,spread_vowel</td>
        <td>ɣ:low_visibility_velar,e:spread_vowel</td>
        <td>ɣ:low_visibility_velar→e:spread_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">21</td>
        <td>V021</td>
        <td>word</td>
        <td>cửa</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/kɯə/</td>
        <td>cửa</td>
        <td>c</td>
        <td>ưa</td>
        <td>∅</td>
        <td>k-ɯə</td>
        <td>k,ɯə</td>
        <td>k→ɯə</td>
        <td></td>
        <td>hỏi</td>
        <td>hỏi</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>low_visibility_velar → central_vowel</td>
        <td>central_vowel,low_visibility_velar</td>
        <td>low_visibility_velar→central_vowel</td>
        <td>central_vowel,low_visibility_velar</td>
        <td>k:low_visibility_velar,ɯə:central_vowel</td>
        <td>k:low_visibility_velar→ɯə:central_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">22</td>
        <td>V022</td>
        <td>word</td>
        <td>biển</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɓiən/</td>
        <td>biển</td>
        <td>b</td>
        <td>iê</td>
        <td>n</td>
        <td>ɓ-iə-n</td>
        <td>iə,n,ɓ</td>
        <td>ɓ→iə,iə→n</td>
        <td></td>
        <td>hỏi</td>
        <td>hỏi</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>bilabial_closure → spread_vowel → coronal</td>
        <td>bilabial_closure,coronal,spread_vowel</td>
        <td>bilabial_closure→spread_vowel,spread_vowel→coronal</td>
        <td>bilabial_closure,coronal,spread_vowel</td>
        <td>ɓ:bilabial_closure,iə:spread_vowel,n:coronal</td>
        <td>ɓ:bilabial_closure→iə:spread_vowel,iə:spread_vowel→n:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">23</td>
        <td>V023</td>
        <td>word</td>
        <td>trời</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ʈɤj/</td>
        <td>trời</td>
        <td>tr</td>
        <td>ơ</td>
        <td>i</td>
        <td>ʈ-ɤ-j</td>
        <td>j,ɤ,ʈ</td>
        <td>ʈ→ɤ,ɤ→j</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → central_vowel → palatal</td>
        <td>central_vowel,coronal,palatal</td>
        <td>coronal→central_vowel,central_vowel→palatal</td>
        <td>central_vowel,coronal,palatal</td>
        <td>ʈ:coronal,ɤ:central_vowel,j:palatal</td>
        <td>ʈ:coronal→ɤ:central_vowel,ɤ:central_vowel→j:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">24</td>
        <td>V024</td>
        <td>word</td>
        <td>đất</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɗət̚/</td>
        <td>đất</td>
        <td>đ</td>
        <td>â</td>
        <td>t</td>
        <td>ɗ-ə-t̚</td>
        <td>t̚,ɗ,ə</td>
        <td>ɗ→ə,ə→t̚</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td>đất</td>
        <td>1</td>
        <td>checked_syllable</td>
        <td>central_vowel → central_vowel → coronal</td>
        <td>central_vowel,coronal</td>
        <td>central_vowel→central_vowel,central_vowel→coronal</td>
        <td>central_vowel,coronal</td>
        <td>ɗ:central_vowel,ə:central_vowel,t̚:coronal</td>
        <td>ɗ:central_vowel→ə:central_vowel,ə:central_vowel→t̚:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.2</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.1181818181818182</td>
        <td>0.08214271467891478</td>
        <td>0.16635548471253356</td>
        <td>0.24118738404452694</td>
        <td>0.16763819322227505</td>
      </tr>
      <tr>
        <td class="line-num">25</td>
        <td>V025</td>
        <td>word</td>
        <td>núi</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/nuj/</td>
        <td>núi</td>
        <td>n</td>
        <td>u</td>
        <td>i</td>
        <td>n-u-j</td>
        <td>j,n,u</td>
        <td>n→u,u→j</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → rounded → palatal</td>
        <td>coronal,palatal,rounded</td>
        <td>coronal→rounded,rounded→palatal</td>
        <td>coronal,palatal,rounded</td>
        <td>n:coronal,u:rounded,j:palatal</td>
        <td>n:coronal→u:rounded,u:rounded→j:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">26</td>
        <td>V026</td>
        <td>word</td>
        <td>sông</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ʂoŋ/</td>
        <td>sông</td>
        <td>s</td>
        <td>ô</td>
        <td>ng</td>
        <td>ʂ-o-ŋ</td>
        <td>o,ŋ,ʂ</td>
        <td>ʂ→o,o→ŋ</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → rounded → low_visibility_velar</td>
        <td>coronal,low_visibility_velar,rounded</td>
        <td>coronal→rounded,rounded→low_visibility_velar</td>
        <td>coronal,low_visibility_velar,rounded</td>
        <td>ʂ:coronal,o:rounded,ŋ:low_visibility_velar</td>
        <td>ʂ:coronal→o:rounded,o:rounded→ŋ:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">27</td>
        <td>V027</td>
        <td>word</td>
        <td>cây</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/kəj/</td>
        <td>cây</td>
        <td>c</td>
        <td>â</td>
        <td>y</td>
        <td>k-ə-j</td>
        <td>j,k,ə</td>
        <td>k→ə,ə→j</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>low_visibility_velar → central_vowel → palatal</td>
        <td>central_vowel,low_visibility_velar,palatal</td>
        <td>low_visibility_velar→central_vowel,central_vowel→palatal</td>
        <td>central_vowel,low_visibility_velar,palatal</td>
        <td>k:low_visibility_velar,ə:central_vowel,j:palatal</td>
        <td>k:low_visibility_velar→ə:central_vowel,ə:central_vowel→j:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">28</td>
        <td>V028</td>
        <td>word</td>
        <td>quả</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/kwaː/</td>
        <td>quả</td>
        <td>qu</td>
        <td>a</td>
        <td>∅</td>
        <td>kw-aː</td>
        <td>aː,kw</td>
        <td>kw→aː</td>
        <td></td>
        <td>hỏi</td>
        <td>hỏi</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>rounded → open_vowel</td>
        <td>open_vowel,rounded</td>
        <td>rounded→open_vowel</td>
        <td>open_vowel,rounded</td>
        <td>kw:rounded,aː:open_vowel</td>
        <td>kw:rounded→aː:open_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">29</td>
        <td>V029</td>
        <td>word</td>
        <td>áo</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/aːw/</td>
        <td>áo</td>
        <td>∅</td>
        <td>a</td>
        <td>o</td>
        <td>aː-w</td>
        <td>aː,w</td>
        <td>aː→w</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>open_vowel → rounded</td>
        <td>open_vowel,rounded</td>
        <td>open_vowel→rounded</td>
        <td>open_vowel,rounded</td>
        <td>aː:open_vowel,w:rounded</td>
        <td>aː:open_vowel→w:rounded</td>
        <td>0.046511627906976744</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.07491407049875676</td>
        <td>0.1090909090909091</td>
        <td>0.07487534405042083</td>
        <td>0.14406552018991683</td>
        <td>0.2097902097902098</td>
        <td>0.14399104625080927</td>
      </tr>
      <tr>
        <td class="line-num">30</td>
        <td>V030</td>
        <td>word</td>
        <td>quần</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/kwən/</td>
        <td>quần</td>
        <td>qu</td>
        <td>â</td>
        <td>n</td>
        <td>kw-ə-n</td>
        <td>kw,n,ə</td>
        <td>kw→ə,ə→n</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>rounded → central_vowel → coronal</td>
        <td>central_vowel,coronal,rounded</td>
        <td>rounded→central_vowel,central_vowel→coronal</td>
        <td>central_vowel,coronal,rounded</td>
        <td>kw:rounded,ə:central_vowel,n:coronal</td>
        <td>kw:rounded→ə:central_vowel,ə:central_vowel→n:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">31</td>
        <td>V031</td>
        <td>word</td>
        <td>mắt</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/mat̚/</td>
        <td>mắt</td>
        <td>m</td>
        <td>ă</td>
        <td>t</td>
        <td>m-a-t̚</td>
        <td>a,m,t̚</td>
        <td>m→a,a→t̚</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td>mắt</td>
        <td>1</td>
        <td>checked_syllable</td>
        <td>bilabial_closure → open_vowel → coronal</td>
        <td>bilabial_closure,coronal,open_vowel</td>
        <td>bilabial_closure→open_vowel,open_vowel→coronal</td>
        <td>bilabial_closure,coronal,open_vowel</td>
        <td>m:bilabial_closure,a:open_vowel,t̚:coronal</td>
        <td>m:bilabial_closure→a:open_vowel,a:open_vowel→t̚:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.16635548471253356</td>
        <td>0.3432282003710575</td>
        <td>0.19679271217271233</td>
      </tr>
      <tr>
        <td class="line-num">32</td>
        <td>V032</td>
        <td>word</td>
        <td>mũi</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/muj/</td>
        <td>mũi</td>
        <td>m</td>
        <td>u</td>
        <td>i</td>
        <td>m-u-j</td>
        <td>j,m,u</td>
        <td>m→u,u→j</td>
        <td></td>
        <td>ngã</td>
        <td>ngã</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast</td>
        <td>bilabial_closure → rounded → palatal</td>
        <td>bilabial_closure,palatal,rounded</td>
        <td>bilabial_closure→rounded,rounded→palatal</td>
        <td>bilabial_closure,palatal,rounded</td>
        <td>m:bilabial_closure,u:rounded,j:palatal</td>
        <td>m:bilabial_closure→u:rounded,u:rounded→j:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">33</td>
        <td>V033</td>
        <td>word</td>
        <td>tóc</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/tɔk̚/</td>
        <td>tóc</td>
        <td>t</td>
        <td>o</td>
        <td>c</td>
        <td>t-ɔ-k̚</td>
        <td>k̚,t,ɔ</td>
        <td>t→ɔ,ɔ→k̚</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td>tóc</td>
        <td>1</td>
        <td>checked_syllable</td>
        <td>coronal → rounded → low_visibility_velar</td>
        <td>coronal,low_visibility_velar,rounded</td>
        <td>coronal→rounded,rounded→low_visibility_velar</td>
        <td>coronal,low_visibility_velar,rounded</td>
        <td>t:coronal,ɔ:rounded,k̚:low_visibility_velar</td>
        <td>t:coronal→ɔ:rounded,ɔ:rounded→k̚:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.16635548471253356</td>
        <td>0.3432282003710575</td>
        <td>0.19679271217271233</td>
      </tr>
      <tr>
        <td class="line-num">34</td>
        <td>V034</td>
        <td>word</td>
        <td>tay</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/taːj/</td>
        <td>tay</td>
        <td>t</td>
        <td>a</td>
        <td>y</td>
        <td>t-aː-j</td>
        <td>aː,j,t</td>
        <td>t→aː,aː→j</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → open_vowel → palatal</td>
        <td>coronal,open_vowel,palatal</td>
        <td>coronal→open_vowel,open_vowel→palatal</td>
        <td>coronal,open_vowel,palatal</td>
        <td>t:coronal,aː:open_vowel,j:palatal</td>
        <td>t:coronal→aː:open_vowel,aː:open_vowel→j:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">35</td>
        <td>V035</td>
        <td>word</td>
        <td>chân</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/cən/</td>
        <td>chân</td>
        <td>ch</td>
        <td>â</td>
        <td>n</td>
        <td>c-ə-n</td>
        <td>c,n,ə</td>
        <td>c→ə,ə→n</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>palatal → central_vowel → coronal</td>
        <td>central_vowel,coronal,palatal</td>
        <td>palatal→central_vowel,central_vowel→coronal</td>
        <td>central_vowel,coronal,palatal</td>
        <td>c:palatal,ə:central_vowel,n:coronal</td>
        <td>c:palatal→ə:central_vowel,ə:central_vowel→n:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">36</td>
        <td>V036</td>
        <td>word</td>
        <td>mặt</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/mat̚/</td>
        <td>mặt</td>
        <td>m</td>
        <td>ă</td>
        <td>t</td>
        <td>m-a-t̚</td>
        <td>a,m,t̚</td>
        <td>m→a,a→t̚</td>
        <td></td>
        <td>nặng</td>
        <td>nặng</td>
        <td></td>
        <td>mặt</td>
        <td>1</td>
        <td>checked_syllable,phonation_contrast</td>
        <td>bilabial_closure → open_vowel → coronal</td>
        <td>bilabial_closure,coronal,open_vowel</td>
        <td>bilabial_closure→open_vowel,open_vowel→coronal</td>
        <td>bilabial_closure,coronal,open_vowel</td>
        <td>m:bilabial_closure,a:open_vowel,t̚:coronal</td>
        <td>m:bilabial_closure→a:open_vowel,a:open_vowel→t̚:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.16635548471253356</td>
        <td>0.3432282003710575</td>
        <td>0.19679271217271233</td>
      </tr>
      <tr>
        <td class="line-num">37</td>
        <td>V037</td>
        <td>word</td>
        <td>miệng</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/miəŋ/</td>
        <td>miệng</td>
        <td>m</td>
        <td>iê</td>
        <td>ng</td>
        <td>m-iə-ŋ</td>
        <td>iə,m,ŋ</td>
        <td>m→iə,iə→ŋ</td>
        <td></td>
        <td>nặng</td>
        <td>nặng</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast</td>
        <td>bilabial_closure → spread_vowel → low_visibility_velar</td>
        <td>bilabial_closure,low_visibility_velar,spread_vowel</td>
        <td>bilabial_closure→spread_vowel,spread_vowel→low_visibility_velar</td>
        <td>bilabial_closure,low_visibility_velar,spread_vowel</td>
        <td>m:bilabial_closure,iə:spread_vowel,ŋ:low_visibility_velar</td>
        <td>m:bilabial_closure→iə:spread_vowel,iə:spread_vowel→ŋ:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">38</td>
        <td>V038</td>
        <td>word</td>
        <td>tai</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/taːj/</td>
        <td>tai</td>
        <td>t</td>
        <td>a</td>
        <td>i</td>
        <td>t-aː-j</td>
        <td>aː,j,t</td>
        <td>t→aː,aː→j</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → open_vowel → palatal</td>
        <td>coronal,open_vowel,palatal</td>
        <td>coronal→open_vowel,open_vowel→palatal</td>
        <td>coronal,open_vowel,palatal</td>
        <td>t:coronal,aː:open_vowel,j:palatal</td>
        <td>t:coronal→aː:open_vowel,aː:open_vowel→j:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">39</td>
        <td>V039</td>
        <td>word</td>
        <td>mẹ</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/mɛ/</td>
        <td>mẹ</td>
        <td>m</td>
        <td>e</td>
        <td>∅</td>
        <td>m-ɛ</td>
        <td>m,ɛ</td>
        <td>m→ɛ</td>
        <td></td>
        <td>nặng</td>
        <td>nặng</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast</td>
        <td>bilabial_closure → spread_vowel</td>
        <td>bilabial_closure,spread_vowel</td>
        <td>bilabial_closure→spread_vowel</td>
        <td>bilabial_closure,spread_vowel</td>
        <td>m:bilabial_closure,ɛ:spread_vowel</td>
        <td>m:bilabial_closure→ɛ:spread_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">40</td>
        <td>V040</td>
        <td>word</td>
        <td>bố</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɓo/</td>
        <td>bố</td>
        <td>b</td>
        <td>ô</td>
        <td>∅</td>
        <td>ɓ-o</td>
        <td>o,ɓ</td>
        <td>ɓ→o</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>bilabial_closure → rounded</td>
        <td>bilabial_closure,rounded</td>
        <td>bilabial_closure→rounded</td>
        <td>bilabial_closure,rounded</td>
        <td>ɓ:bilabial_closure,o:rounded</td>
        <td>ɓ:bilabial_closure→o:rounded</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">41</td>
        <td>V041</td>
        <td>word</td>
        <td>anh</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/aːɲ/</td>
        <td>anh</td>
        <td>∅</td>
        <td>a</td>
        <td>nh</td>
        <td>aː-ɲ</td>
        <td>aː,ɲ</td>
        <td>aː→ɲ</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>open_vowel → palatal</td>
        <td>open_vowel,palatal</td>
        <td>open_vowel→palatal</td>
        <td>open_vowel,palatal</td>
        <td>aː:open_vowel,ɲ:palatal</td>
        <td>aː:open_vowel→ɲ:palatal</td>
        <td>0.046511627906976744</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.07491407049875676</td>
        <td>0.1090909090909091</td>
        <td>0.07487534405042083</td>
        <td>0.14406552018991683</td>
        <td>0.2097902097902098</td>
        <td>0.14399104625080927</td>
      </tr>
      <tr>
        <td class="line-num">42</td>
        <td>V042</td>
        <td>word</td>
        <td>chị</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ci/</td>
        <td>chị</td>
        <td>ch</td>
        <td>i</td>
        <td>∅</td>
        <td>c-i</td>
        <td>c,i</td>
        <td>c→i</td>
        <td></td>
        <td>nặng</td>
        <td>nặng</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast</td>
        <td>palatal → spread_vowel</td>
        <td>palatal,spread_vowel</td>
        <td>palatal→spread_vowel</td>
        <td>palatal,spread_vowel</td>
        <td>c:palatal,i:spread_vowel</td>
        <td>c:palatal→i:spread_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">43</td>
        <td>V043</td>
        <td>word</td>
        <td>em</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɛm/</td>
        <td>em</td>
        <td>∅</td>
        <td>e</td>
        <td>m</td>
        <td>ɛ-m</td>
        <td>m,ɛ</td>
        <td>ɛ→m</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>spread_vowel → bilabial_closure</td>
        <td>bilabial_closure,spread_vowel</td>
        <td>spread_vowel→bilabial_closure</td>
        <td>bilabial_closure,spread_vowel</td>
        <td>ɛ:spread_vowel,m:bilabial_closure</td>
        <td>ɛ:spread_vowel→m:bilabial_closure</td>
        <td>0.046511627906976744</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.07491407049875676</td>
        <td>0.1090909090909091</td>
        <td>0.07487534405042083</td>
        <td>0.14406552018991683</td>
        <td>0.2097902097902098</td>
        <td>0.14399104625080927</td>
      </tr>
      <tr>
        <td class="line-num">44</td>
        <td>V044</td>
        <td>word</td>
        <td>người</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ŋɯəj/</td>
        <td>người</td>
        <td>ng</td>
        <td>ươ</td>
        <td>i</td>
        <td>ŋ-ɯə-j</td>
        <td>j,ŋ,ɯə</td>
        <td>ŋ→ɯə,ɯə→j</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>low_visibility_velar → central_vowel → palatal</td>
        <td>central_vowel,low_visibility_velar,palatal</td>
        <td>low_visibility_velar→central_vowel,central_vowel→palatal</td>
        <td>central_vowel,low_visibility_velar,palatal</td>
        <td>ŋ:low_visibility_velar,ɯə:central_vowel,j:palatal</td>
        <td>ŋ:low_visibility_velar→ɯə:central_vowel,ɯə:central_vowel→j:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">45</td>
        <td>V045</td>
        <td>word</td>
        <td>trẻ</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ʈɛ/</td>
        <td>trẻ</td>
        <td>tr</td>
        <td>e</td>
        <td>∅</td>
        <td>ʈ-ɛ</td>
        <td>ɛ,ʈ</td>
        <td>ʈ→ɛ</td>
        <td></td>
        <td>hỏi</td>
        <td>hỏi</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → spread_vowel</td>
        <td>coronal,spread_vowel</td>
        <td>coronal→spread_vowel</td>
        <td>coronal,spread_vowel</td>
        <td>ʈ:coronal,ɛ:spread_vowel</td>
        <td>ʈ:coronal→ɛ:spread_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">46</td>
        <td>V046</td>
        <td>word</td>
        <td>nhỏ</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɲɔ/</td>
        <td>nhỏ</td>
        <td>nh</td>
        <td>o</td>
        <td>∅</td>
        <td>ɲ-ɔ</td>
        <td>ɔ,ɲ</td>
        <td>ɲ→ɔ</td>
        <td></td>
        <td>hỏi</td>
        <td>hỏi</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>palatal → rounded</td>
        <td>palatal,rounded</td>
        <td>palatal→rounded</td>
        <td>palatal,rounded</td>
        <td>ɲ:palatal,ɔ:rounded</td>
        <td>ɲ:palatal→ɔ:rounded</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">47</td>
        <td>V047</td>
        <td>word</td>
        <td>lớn</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/lɤn/</td>
        <td>lớn</td>
        <td>l</td>
        <td>ơ</td>
        <td>n</td>
        <td>l-ɤ-n</td>
        <td>l,n,ɤ</td>
        <td>l→ɤ,ɤ→n</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → central_vowel → coronal</td>
        <td>central_vowel,coronal</td>
        <td>coronal→central_vowel,central_vowel→coronal</td>
        <td>central_vowel,coronal</td>
        <td>l:coronal,ɤ:central_vowel,n:coronal</td>
        <td>l:coronal→ɤ:central_vowel,ɤ:central_vowel→n:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.2</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.1181818181818182</td>
        <td>0.08214271467891478</td>
        <td>0.15675805290219508</td>
        <td>0.2272727272727273</td>
        <td>0.15796675899791301</td>
      </tr>
      <tr>
        <td class="line-num">48</td>
        <td>V048</td>
        <td>word</td>
        <td>đẹp</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɗɛp̚/</td>
        <td>đẹp</td>
        <td>đ</td>
        <td>e</td>
        <td>p</td>
        <td>ɗ-ɛ-p̚</td>
        <td>p̚,ɗ,ɛ</td>
        <td>ɗ→ɛ,ɛ→p̚</td>
        <td></td>
        <td>nặng</td>
        <td>nặng</td>
        <td></td>
        <td>đẹp</td>
        <td>1</td>
        <td>checked_syllable,phonation_contrast</td>
        <td>central_vowel → spread_vowel → bilabial_closure</td>
        <td>bilabial_closure,central_vowel,spread_vowel</td>
        <td>central_vowel→spread_vowel,spread_vowel→bilabial_closure</td>
        <td>bilabial_closure,central_vowel,spread_vowel</td>
        <td>ɗ:central_vowel,ɛ:spread_vowel,p̚:bilabial_closure</td>
        <td>ɗ:central_vowel→ɛ:spread_vowel,ɛ:spread_vowel→p̚:bilabial_closure</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.16635548471253356</td>
        <td>0.3432282003710575</td>
        <td>0.19679271217271233</td>
      </tr>
      <tr>
        <td class="line-num">49</td>
        <td>V049</td>
        <td>word</td>
        <td>khỏe</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/xwɛ/</td>
        <td>khỏe</td>
        <td>kh</td>
        <td>oe</td>
        <td>∅</td>
        <td>x-wɛ</td>
        <td>wɛ,x</td>
        <td>x→wɛ</td>
        <td></td>
        <td>hỏi</td>
        <td>hỏi</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>low_visibility_velar → rounded</td>
        <td>low_visibility_velar,rounded</td>
        <td>low_visibility_velar→rounded</td>
        <td>low_visibility_velar,rounded</td>
        <td>x:low_visibility_velar,wɛ:rounded</td>
        <td>x:low_visibility_velar→wɛ:rounded</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">50</td>
        <td>V050</td>
        <td>word</td>
        <td>lạnh</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/laːɲ/</td>
        <td>lạnh</td>
        <td>l</td>
        <td>a</td>
        <td>nh</td>
        <td>l-aː-ɲ</td>
        <td>aː,l,ɲ</td>
        <td>l→aː,aː→ɲ</td>
        <td></td>
        <td>nặng</td>
        <td>nặng</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast</td>
        <td>coronal → open_vowel → palatal</td>
        <td>coronal,open_vowel,palatal</td>
        <td>coronal→open_vowel,open_vowel→palatal</td>
        <td>coronal,open_vowel,palatal</td>
        <td>l:coronal,aː:open_vowel,ɲ:palatal</td>
        <td>l:coronal→aː:open_vowel,aː:open_vowel→ɲ:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">51</td>
        <td>V051</td>
        <td>word</td>
        <td>nóng</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/nɔŋ/</td>
        <td>nóng</td>
        <td>n</td>
        <td>o</td>
        <td>ng</td>
        <td>n-ɔ-ŋ</td>
        <td>n,ŋ,ɔ</td>
        <td>n→ɔ,ɔ→ŋ</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → rounded → low_visibility_velar</td>
        <td>coronal,low_visibility_velar,rounded</td>
        <td>coronal→rounded,rounded→low_visibility_velar</td>
        <td>coronal,low_visibility_velar,rounded</td>
        <td>n:coronal,ɔ:rounded,ŋ:low_visibility_velar</td>
        <td>n:coronal→ɔ:rounded,ɔ:rounded→ŋ:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">52</td>
        <td>V052</td>
        <td>word</td>
        <td>sáng</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ʂaːŋ/</td>
        <td>sáng</td>
        <td>s</td>
        <td>a</td>
        <td>ng</td>
        <td>ʂ-aː-ŋ</td>
        <td>aː,ŋ,ʂ</td>
        <td>ʂ→aː,aː→ŋ</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → open_vowel → low_visibility_velar</td>
        <td>coronal,low_visibility_velar,open_vowel</td>
        <td>coronal→open_vowel,open_vowel→low_visibility_velar</td>
        <td>coronal,low_visibility_velar,open_vowel</td>
        <td>ʂ:coronal,aː:open_vowel,ŋ:low_visibility_velar</td>
        <td>ʂ:coronal→aː:open_vowel,aː:open_vowel→ŋ:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">53</td>
        <td>V053</td>
        <td>word</td>
        <td>tối</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/toj/</td>
        <td>tối</td>
        <td>t</td>
        <td>ô</td>
        <td>i</td>
        <td>t-o-j</td>
        <td>j,o,t</td>
        <td>t→o,o→j</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → rounded → palatal</td>
        <td>coronal,palatal,rounded</td>
        <td>coronal→rounded,rounded→palatal</td>
        <td>coronal,palatal,rounded</td>
        <td>t:coronal,o:rounded,j:palatal</td>
        <td>t:coronal→o:rounded,o:rounded→j:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">54</td>
        <td>V054</td>
        <td>word</td>
        <td>đỏ</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɗɔ/</td>
        <td>đỏ</td>
        <td>đ</td>
        <td>o</td>
        <td>∅</td>
        <td>ɗ-ɔ</td>
        <td>ɔ,ɗ</td>
        <td>ɗ→ɔ</td>
        <td></td>
        <td>hỏi</td>
        <td>hỏi</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>central_vowel → rounded</td>
        <td>central_vowel,rounded</td>
        <td>central_vowel→rounded</td>
        <td>central_vowel,rounded</td>
        <td>ɗ:central_vowel,ɔ:rounded</td>
        <td>ɗ:central_vowel→ɔ:rounded</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">55</td>
        <td>V055</td>
        <td>word</td>
        <td>trắng</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ʈaŋ/</td>
        <td>trắng</td>
        <td>tr</td>
        <td>ă</td>
        <td>ng</td>
        <td>ʈ-a-ŋ</td>
        <td>a,ŋ,ʈ</td>
        <td>ʈ→a,a→ŋ</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → open_vowel → low_visibility_velar</td>
        <td>coronal,low_visibility_velar,open_vowel</td>
        <td>coronal→open_vowel,open_vowel→low_visibility_velar</td>
        <td>coronal,low_visibility_velar,open_vowel</td>
        <td>ʈ:coronal,a:open_vowel,ŋ:low_visibility_velar</td>
        <td>ʈ:coronal→a:open_vowel,a:open_vowel→ŋ:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">56</td>
        <td>V056</td>
        <td>word</td>
        <td>xanh</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/saːɲ/</td>
        <td>xanh</td>
        <td>x</td>
        <td>a</td>
        <td>nh</td>
        <td>s-aː-ɲ</td>
        <td>aː,s,ɲ</td>
        <td>s→aː,aː→ɲ</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → open_vowel → palatal</td>
        <td>coronal,open_vowel,palatal</td>
        <td>coronal→open_vowel,open_vowel→palatal</td>
        <td>coronal,open_vowel,palatal</td>
        <td>s:coronal,aː:open_vowel,ɲ:palatal</td>
        <td>s:coronal→aː:open_vowel,aː:open_vowel→ɲ:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">57</td>
        <td>V057</td>
        <td>word</td>
        <td>vàng</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/vaːŋ/</td>
        <td>vàng</td>
        <td>v</td>
        <td>a</td>
        <td>ng</td>
        <td>v-aː-ŋ</td>
        <td>aː,v,ŋ</td>
        <td>v→aː,aː→ŋ</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>labiodental → open_vowel → low_visibility_velar</td>
        <td>labiodental,low_visibility_velar,open_vowel</td>
        <td>labiodental→open_vowel,open_vowel→low_visibility_velar</td>
        <td>labiodental,low_visibility_velar,open_vowel</td>
        <td>v:labiodental,aː:open_vowel,ŋ:low_visibility_velar</td>
        <td>v:labiodental→aː:open_vowel,aː:open_vowel→ŋ:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">58</td>
        <td>V058</td>
        <td>word</td>
        <td>đen</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɗɛn/</td>
        <td>đen</td>
        <td>đ</td>
        <td>e</td>
        <td>n</td>
        <td>ɗ-ɛ-n</td>
        <td>n,ɗ,ɛ</td>
        <td>ɗ→ɛ,ɛ→n</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>central_vowel → spread_vowel → coronal</td>
        <td>central_vowel,coronal,spread_vowel</td>
        <td>central_vowel→spread_vowel,spread_vowel→coronal</td>
        <td>central_vowel,coronal,spread_vowel</td>
        <td>ɗ:central_vowel,ɛ:spread_vowel,n:coronal</td>
        <td>ɗ:central_vowel→ɛ:spread_vowel,ɛ:spread_vowel→n:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">59</td>
        <td>V059</td>
        <td>word</td>
        <td>hỏi</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/hɔj/</td>
        <td>hỏi</td>
        <td>h</td>
        <td>o</td>
        <td>i</td>
        <td>h-ɔ-j</td>
        <td>h,j,ɔ</td>
        <td>h→ɔ,ɔ→j</td>
        <td></td>
        <td>hỏi</td>
        <td>hỏi</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>glottal → rounded → palatal</td>
        <td>glottal,palatal,rounded</td>
        <td>glottal→rounded,rounded→palatal</td>
        <td>glottal,palatal,rounded</td>
        <td>h:glottal,ɔ:rounded,j:palatal</td>
        <td>h:glottal→ɔ:rounded,ɔ:rounded→j:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">60</td>
        <td>V060</td>
        <td>word</td>
        <td>nghĩ</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ŋi/</td>
        <td>nghĩ</td>
        <td>ngh</td>
        <td>i</td>
        <td>∅</td>
        <td>ŋ-i</td>
        <td>i,ŋ</td>
        <td>ŋ→i</td>
        <td></td>
        <td>ngã</td>
        <td>ngã</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast</td>
        <td>low_visibility_velar → spread_vowel</td>
        <td>low_visibility_velar,spread_vowel</td>
        <td>low_visibility_velar→spread_vowel</td>
        <td>low_visibility_velar,spread_vowel</td>
        <td>ŋ:low_visibility_velar,i:spread_vowel</td>
        <td>ŋ:low_visibility_velar→i:spread_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">61</td>
        <td>V061</td>
        <td>word</td>
        <td>giữ</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/zɯ/</td>
        <td>giữ</td>
        <td>gi</td>
        <td>ư</td>
        <td>∅</td>
        <td>z-ɯ</td>
        <td>z,ɯ</td>
        <td>z→ɯ</td>
        <td></td>
        <td>ngã</td>
        <td>ngã</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast</td>
        <td>coronal → central_vowel</td>
        <td>central_vowel,coronal</td>
        <td>coronal→central_vowel</td>
        <td>central_vowel,coronal</td>
        <td>z:coronal,ɯ:central_vowel</td>
        <td>z:coronal→ɯ:central_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">62</td>
        <td>V062</td>
        <td>word</td>
        <td>đọc</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɗɔk̚/</td>
        <td>đọc</td>
        <td>đ</td>
        <td>o</td>
        <td>c</td>
        <td>ɗ-ɔ-k̚</td>
        <td>k̚,ɔ,ɗ</td>
        <td>ɗ→ɔ,ɔ→k̚</td>
        <td></td>
        <td>nặng</td>
        <td>nặng</td>
        <td></td>
        <td>đọc</td>
        <td>1</td>
        <td>checked_syllable,phonation_contrast</td>
        <td>central_vowel → rounded → low_visibility_velar</td>
        <td>central_vowel,low_visibility_velar,rounded</td>
        <td>central_vowel→rounded,rounded→low_visibility_velar</td>
        <td>central_vowel,low_visibility_velar,rounded</td>
        <td>ɗ:central_vowel,ɔ:rounded,k̚:low_visibility_velar</td>
        <td>ɗ:central_vowel→ɔ:rounded,ɔ:rounded→k̚:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.16635548471253356</td>
        <td>0.3432282003710575</td>
        <td>0.19679271217271233</td>
      </tr>
      <tr>
        <td class="line-num">63</td>
        <td>V063</td>
        <td>word</td>
        <td>viết</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/viət̚/</td>
        <td>viết</td>
        <td>v</td>
        <td>iê</td>
        <td>t</td>
        <td>v-iə-t̚</td>
        <td>iə,t̚,v</td>
        <td>v→iə,iə→t̚</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td>viết</td>
        <td>1</td>
        <td>checked_syllable</td>
        <td>labiodental → spread_vowel → coronal</td>
        <td>coronal,labiodental,spread_vowel</td>
        <td>labiodental→spread_vowel,spread_vowel→coronal</td>
        <td>coronal,labiodental,spread_vowel</td>
        <td>v:labiodental,iə:spread_vowel,t̚:coronal</td>
        <td>v:labiodental→iə:spread_vowel,iə:spread_vowel→t̚:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.16635548471253356</td>
        <td>0.3432282003710575</td>
        <td>0.19679271217271233</td>
      </tr>
      <tr>
        <td class="line-num">64</td>
        <td>V064</td>
        <td>word</td>
        <td>nói</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/nɔj/</td>
        <td>nói</td>
        <td>n</td>
        <td>o</td>
        <td>i</td>
        <td>n-ɔ-j</td>
        <td>j,n,ɔ</td>
        <td>n→ɔ,ɔ→j</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → rounded → palatal</td>
        <td>coronal,palatal,rounded</td>
        <td>coronal→rounded,rounded→palatal</td>
        <td>coronal,palatal,rounded</td>
        <td>n:coronal,ɔ:rounded,j:palatal</td>
        <td>n:coronal→ɔ:rounded,ɔ:rounded→j:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">65</td>
        <td>V065</td>
        <td>word</td>
        <td>nghe</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ŋɛ/</td>
        <td>nghe</td>
        <td>ngh</td>
        <td>e</td>
        <td>∅</td>
        <td>ŋ-ɛ</td>
        <td>ŋ,ɛ</td>
        <td>ŋ→ɛ</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>low_visibility_velar → spread_vowel</td>
        <td>low_visibility_velar,spread_vowel</td>
        <td>low_visibility_velar→spread_vowel</td>
        <td>low_visibility_velar,spread_vowel</td>
        <td>ŋ:low_visibility_velar,ɛ:spread_vowel</td>
        <td>ŋ:low_visibility_velar→ɛ:spread_vowel</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">66</td>
        <td>V066</td>
        <td>word</td>
        <td>nhìn</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɲin/</td>
        <td>nhìn</td>
        <td>nh</td>
        <td>i</td>
        <td>n</td>
        <td>ɲ-i-n</td>
        <td>i,n,ɲ</td>
        <td>ɲ→i,i→n</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>palatal → spread_vowel → coronal</td>
        <td>coronal,palatal,spread_vowel</td>
        <td>palatal→spread_vowel,spread_vowel→coronal</td>
        <td>coronal,palatal,spread_vowel</td>
        <td>ɲ:palatal,i:spread_vowel,n:coronal</td>
        <td>ɲ:palatal→i:spread_vowel,i:spread_vowel→n:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">67</td>
        <td>V067</td>
        <td>word</td>
        <td>học</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/hɔk̚/</td>
        <td>học</td>
        <td>h</td>
        <td>o</td>
        <td>c</td>
        <td>h-ɔ-k̚</td>
        <td>h,k̚,ɔ</td>
        <td>h→ɔ,ɔ→k̚</td>
        <td></td>
        <td>nặng</td>
        <td>nặng</td>
        <td></td>
        <td>học</td>
        <td>1</td>
        <td>checked_syllable,phonation_contrast</td>
        <td>glottal → rounded → low_visibility_velar</td>
        <td>glottal,low_visibility_velar,rounded</td>
        <td>glottal→rounded,rounded→low_visibility_velar</td>
        <td>glottal,low_visibility_velar,rounded</td>
        <td>h:glottal,ɔ:rounded,k̚:low_visibility_velar</td>
        <td>h:glottal→ɔ:rounded,ɔ:rounded→k̚:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.16635548471253356</td>
        <td>0.3432282003710575</td>
        <td>0.19679271217271233</td>
      </tr>
      <tr>
        <td class="line-num">68</td>
        <td>V068</td>
        <td>word</td>
        <td>làm</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/laːm/</td>
        <td>làm</td>
        <td>l</td>
        <td>a</td>
        <td>m</td>
        <td>l-aː-m</td>
        <td>aː,l,m</td>
        <td>l→aː,aː→m</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → open_vowel → bilabial_closure</td>
        <td>bilabial_closure,coronal,open_vowel</td>
        <td>coronal→open_vowel,open_vowel→bilabial_closure</td>
        <td>bilabial_closure,coronal,open_vowel</td>
        <td>l:coronal,aː:open_vowel,m:bilabial_closure</td>
        <td>l:coronal→aː:open_vowel,aː:open_vowel→m:bilabial_closure</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">69</td>
        <td>V069</td>
        <td>word</td>
        <td>chơi</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/cɤj/</td>
        <td>chơi</td>
        <td>ch</td>
        <td>ơ</td>
        <td>i</td>
        <td>c-ɤ-j</td>
        <td>c,j,ɤ</td>
        <td>c→ɤ,ɤ→j</td>
        <td></td>
        <td>ngang</td>
        <td>ngang</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>palatal → central_vowel → palatal</td>
        <td>central_vowel,palatal</td>
        <td>palatal→central_vowel,central_vowel→palatal</td>
        <td>central_vowel,palatal</td>
        <td>c:palatal,ɤ:central_vowel,j:palatal</td>
        <td>c:palatal→ɤ:central_vowel,ɤ:central_vowel→j:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.2</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.1181818181818182</td>
        <td>0.08214271467891478</td>
        <td>0.15675805290219508</td>
        <td>0.2272727272727273</td>
        <td>0.15796675899791301</td>
      </tr>
      <tr>
        <td class="line-num">70</td>
        <td>V070</td>
        <td>word</td>
        <td>ngủ</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ŋu/</td>
        <td>ngủ</td>
        <td>ng</td>
        <td>u</td>
        <td>∅</td>
        <td>ŋ-u</td>
        <td>u,ŋ</td>
        <td>ŋ→u</td>
        <td></td>
        <td>hỏi</td>
        <td>hỏi</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>low_visibility_velar → rounded</td>
        <td>low_visibility_velar,rounded</td>
        <td>low_visibility_velar→rounded</td>
        <td>low_visibility_velar,rounded</td>
        <td>ŋ:low_visibility_velar,u:rounded</td>
        <td>ŋ:low_visibility_velar→u:rounded</td>
        <td>0.046511627906976744</td>
        <td>0</td>
        <td>0.16666666666666666</td>
        <td>0.006289308176100629</td>
        <td>0</td>
        <td>0.0031446540880503146</td>
        <td>0.2</td>
        <td>0.01818181818181818</td>
        <td>0.006289308176100629</td>
        <td>0.05408073716542343</td>
        <td>0.1090909090909091</td>
        <td>0.06297058214565894</td>
        <td>0.10400141762581429</td>
        <td>0.2097902097902098</td>
        <td>0.12109727335703642</td>
      </tr>
      <tr>
        <td class="line-num">71</td>
        <td>V071</td>
        <td>word</td>
        <td>trường</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ʈɯəŋ/</td>
        <td>trường</td>
        <td>tr</td>
        <td>ươ</td>
        <td>ng</td>
        <td>ʈ-ɯə-ŋ</td>
        <td>ŋ,ɯə,ʈ</td>
        <td>ʈ→ɯə,ɯə→ŋ</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → central_vowel → low_visibility_velar</td>
        <td>central_vowel,coronal,low_visibility_velar</td>
        <td>coronal→central_vowel,central_vowel→low_visibility_velar</td>
        <td>central_vowel,coronal,low_visibility_velar</td>
        <td>ʈ:coronal,ɯə:central_vowel,ŋ:low_visibility_velar</td>
        <td>ʈ:coronal→ɯə:central_vowel,ɯə:central_vowel→ŋ:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">72</td>
        <td>V072</td>
        <td>word</td>
        <td>lớp</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/lɤp̚/</td>
        <td>lớp</td>
        <td>l</td>
        <td>ơ</td>
        <td>p</td>
        <td>l-ɤ-p̚</td>
        <td>l,p̚,ɤ</td>
        <td>l→ɤ,ɤ→p̚</td>
        <td></td>
        <td>sắc</td>
        <td>sắc</td>
        <td></td>
        <td>lớp</td>
        <td>1</td>
        <td>checked_syllable</td>
        <td>coronal → central_vowel → bilabial_closure</td>
        <td>bilabial_closure,central_vowel,coronal</td>
        <td>coronal→central_vowel,central_vowel→bilabial_closure</td>
        <td>bilabial_closure,central_vowel,coronal</td>
        <td>l:coronal,ɤ:central_vowel,p̚:bilabial_closure</td>
        <td>l:coronal→ɤ:central_vowel,ɤ:central_vowel→p̚:bilabial_closure</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.16635548471253356</td>
        <td>0.3432282003710575</td>
        <td>0.19679271217271233</td>
      </tr>
      <tr>
        <td class="line-num">73</td>
        <td>V073</td>
        <td>word</td>
        <td>việc</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.49</td>
        <td>0.49</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/viək̚/</td>
        <td>việc</td>
        <td>v</td>
        <td>iê</td>
        <td>c</td>
        <td>v-iə-k̚</td>
        <td>iə,k̚,v</td>
        <td>v→iə,iə→k̚</td>
        <td></td>
        <td>nặng</td>
        <td>nặng</td>
        <td></td>
        <td>việc</td>
        <td>1</td>
        <td>checked_syllable,phonation_contrast</td>
        <td>labiodental → spread_vowel → low_visibility_velar</td>
        <td>labiodental,low_visibility_velar,spread_vowel</td>
        <td>labiodental→spread_vowel,spread_vowel→low_visibility_velar</td>
        <td>labiodental,low_visibility_velar,spread_vowel</td>
        <td>v:labiodental,iə:spread_vowel,k̚:low_visibility_velar</td>
        <td>v:labiodental→iə:spread_vowel,iə:spread_vowel→k̚:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.16635548471253356</td>
        <td>0.3432282003710575</td>
        <td>0.19679271217271233</td>
      </tr>
      <tr>
        <td class="line-num">74</td>
        <td>V074</td>
        <td>word</td>
        <td>bệnh</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɓeɲ/</td>
        <td>bệnh</td>
        <td>b</td>
        <td>ê</td>
        <td>nh</td>
        <td>ɓ-e-ɲ</td>
        <td>e,ɓ,ɲ</td>
        <td>ɓ→e,e→ɲ</td>
        <td></td>
        <td>nặng</td>
        <td>nặng</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast</td>
        <td>bilabial_closure → spread_vowel → palatal</td>
        <td>bilabial_closure,palatal,spread_vowel</td>
        <td>bilabial_closure→spread_vowel,spread_vowel→palatal</td>
        <td>bilabial_closure,palatal,spread_vowel</td>
        <td>ɓ:bilabial_closure,e:spread_vowel,ɲ:palatal</td>
        <td>ɓ:bilabial_closure→e:spread_vowel,e:spread_vowel→ɲ:palatal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.3</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.16818181818181818</td>
        <td>0.09642842896462904</td>
        <td>0.15675805290219508</td>
        <td>0.32342657342657344</td>
        <td>0.18543928647044045</td>
      </tr>
      <tr>
        <td class="line-num">75</td>
        <td>V075</td>
        <td>word</td>
        <td>tiền</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/tiən/</td>
        <td>tiền</td>
        <td>t</td>
        <td>iê</td>
        <td>n</td>
        <td>t-iə-n</td>
        <td>iə,n,t</td>
        <td>t→iə,iə→n</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>coronal → spread_vowel → coronal</td>
        <td>coronal,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→coronal</td>
        <td>coronal,spread_vowel</td>
        <td>t:coronal,iə:spread_vowel,n:coronal</td>
        <td>t:coronal→iə:spread_vowel,iə:spread_vowel→n:coronal</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.2</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.1181818181818182</td>
        <td>0.08214271467891478</td>
        <td>0.15675805290219508</td>
        <td>0.2272727272727273</td>
        <td>0.15796675899791301</td>
      </tr>
      <tr>
        <td class="line-num">76</td>
        <td>V076</td>
        <td>word</td>
        <td>đường</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>1</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɗɯəŋ/</td>
        <td>đường</td>
        <td>đ</td>
        <td>ươ</td>
        <td>ng</td>
        <td>ɗ-ɯə-ŋ</td>
        <td>ŋ,ɗ,ɯə</td>
        <td>ɗ→ɯə,ɯə→ŋ</td>
        <td></td>
        <td>huyền</td>
        <td>huyền</td>
        <td></td>
        <td></td>
        <td>0</td>
        <td></td>
        <td>central_vowel → central_vowel → low_visibility_velar</td>
        <td>central_vowel,low_visibility_velar</td>
        <td>central_vowel→central_vowel,central_vowel→low_visibility_velar</td>
        <td>central_vowel,low_visibility_velar</td>
        <td>ɗ:central_vowel,ɯə:central_vowel,ŋ:low_visibility_velar</td>
        <td>ɗ:central_vowel→ɯə:central_vowel,ɯə:central_vowel→ŋ:low_visibility_velar</td>
        <td>0.06976744186046512</td>
        <td>0.08333333333333333</td>
        <td>0.16666666666666666</td>
        <td>0.012578616352201259</td>
        <td>0</td>
        <td>0.006289308176100629</td>
        <td>0.2</td>
        <td>0.03636363636363636</td>
        <td>0.012578616352201259</td>
        <td>0.08151418750914144</td>
        <td>0.1181818181818182</td>
        <td>0.08214271467891478</td>
        <td>0.15675805290219508</td>
        <td>0.2272727272727273</td>
        <td>0.15796675899791301</td>
      </tr>
      <tr>
        <td class="line-num">77</td>
        <td>V077</td>
        <td>phrase</td>
        <td>thành phố</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>2</td>
        <td>0.94</td>
        <td>0.94</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/tʰaːɲ/ /fo/</td>
        <td>thành-phố</td>
        <td>ph,th</td>
        <td>a,ô</td>
        <td>nh,∅</td>
        <td>tʰ-aː-ɲ-f-o</td>
        <td>aː,f,o,tʰ,ɲ</td>
        <td>tʰ→aː,aː→ɲ,ɲ→f,f→o</td>
        <td>ɲ→f</td>
        <td>huyền-sắc</td>
        <td>huyền,sắc</td>
        <td>huyền→sắc</td>
        <td></td>
        <td>0</td>
        <td>tonal_coarticulation_context</td>
        <td>coronal → open_vowel → palatal → labiodental → rounded</td>
        <td>coronal,labiodental,open_vowel,palatal,rounded</td>
        <td>coronal→open_vowel,open_vowel→palatal,palatal→labiodental,labiodental→rounded</td>
        <td>coronal,labiodental,open_vowel,palatal,rounded</td>
        <td>tʰ:coronal,aː:open_vowel,ɲ:palatal,f:labiodental,o:rounded</td>
        <td>tʰ:coronal→aː:open_vowel,aː:open_vowel→ɲ:palatal,ɲ:palatal→f:labiodental,f:labiodental→o:rounded</td>
        <td>0.11627906976744186</td>
        <td>0.08333333333333333</td>
        <td>0.3333333333333333</td>
        <td>0.025157232704402517</td>
        <td>0.0625</td>
        <td>0.043828616352201255</td>
        <td>0.5</td>
        <td>0.07272727272727272</td>
        <td>0.025157232704402517</td>
        <td>0.14419358819657743</td>
        <td>0.2863636363636364</td>
        <td>0.167808408316855</td>
        <td>0.15339743425167812</td>
        <td>0.30464216634429403</td>
        <td>0.1785195833158032</td>
      </tr>
      <tr>
        <td class="line-num">78</td>
        <td>V078</td>
        <td>phrase</td>
        <td>gia đình</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>2</td>
        <td>0.94</td>
        <td>0.94</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/zaː/ /ɗiɲ/</td>
        <td>gia-đình</td>
        <td>gi,đ</td>
        <td>a,i</td>
        <td>nh,∅</td>
        <td>z-aː-ɗ-i-ɲ</td>
        <td>aː,i,z,ɗ,ɲ</td>
        <td>z→aː,aː→ɗ,ɗ→i,i→ɲ</td>
        <td>aː→ɗ</td>
        <td>ngang-huyền</td>
        <td>huyền,ngang</td>
        <td>ngang→huyền</td>
        <td></td>
        <td>0</td>
        <td>tonal_coarticulation_context</td>
        <td>coronal → open_vowel → central_vowel → spread_vowel → palatal</td>
        <td>central_vowel,coronal,open_vowel,palatal,spread_vowel</td>
        <td>coronal→open_vowel,open_vowel→central_vowel,central_vowel→spread_vowel,spread_vowel→palatal</td>
        <td>central_vowel,coronal,open_vowel,palatal,spread_vowel</td>
        <td>z:coronal,aː:open_vowel,ɗ:central_vowel,i:spread_vowel,ɲ:palatal</td>
        <td>z:coronal→aː:open_vowel,aː:open_vowel→ɗ:central_vowel,ɗ:central_vowel→i:spread_vowel,i:spread_vowel→ɲ:palatal</td>
        <td>0.11627906976744186</td>
        <td>0.08333333333333333</td>
        <td>0.3333333333333333</td>
        <td>0.025157232704402517</td>
        <td>0.0625</td>
        <td>0.043828616352201255</td>
        <td>0.5</td>
        <td>0.07272727272727272</td>
        <td>0.025157232704402517</td>
        <td>0.14419358819657743</td>
        <td>0.2863636363636364</td>
        <td>0.167808408316855</td>
        <td>0.15339743425167812</td>
        <td>0.30464216634429403</td>
        <td>0.1785195833158032</td>
      </tr>
      <tr>
        <td class="line-num">79</td>
        <td>V079</td>
        <td>phrase</td>
        <td>điện thoại</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>2</td>
        <td>0.94</td>
        <td>0.94</td>
        <td>0.08</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɗiən/ /tʰwaːj/</td>
        <td>điện-thoại</td>
        <td>th,đ</td>
        <td>iê,oa</td>
        <td>i,n</td>
        <td>ɗ-iə-n-tʰ-waː-j</td>
        <td>iə,j,n,tʰ,waː,ɗ</td>
        <td>ɗ→iə,iə→n,n→tʰ,tʰ→waː,waː→j</td>
        <td>n→tʰ</td>
        <td>nặng-nặng</td>
        <td>nặng</td>
        <td>nặng→nặng</td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast,tonal_coarticulation_context</td>
        <td>central_vowel → spread_vowel → coronal → coronal → rounded → palatal</td>
        <td>central_vowel,coronal,palatal,rounded,spread_vowel</td>
        <td>central_vowel→spread_vowel,spread_vowel→coronal,coronal→coronal,coronal→rounded,rounded→palatal</td>
        <td>central_vowel,coronal,palatal,rounded,spread_vowel</td>
        <td>ɗ:central_vowel,iə:spread_vowel,n:coronal,tʰ:coronal,waː:rounded,j:palatal</td>
        <td>ɗ:central_vowel→iə:spread_vowel,iə:spread_vowel→n:coronal,n:coronal→tʰ:coronal,tʰ:coronal→waː:rounded,waː:rounded→j:palatal</td>
        <td>0.13953488372093023</td>
        <td>0.16666666666666666</td>
        <td>0.16666666666666666</td>
        <td>0.031446540880503145</td>
        <td>0.0625</td>
        <td>0.04697327044025157</td>
        <td>0.5</td>
        <td>0.09090909090909091</td>
        <td>0.031446540880503145</td>
        <td>0.12996037187362877</td>
        <td>0.29545454545454547</td>
        <td>0.16317101704058698</td>
        <td>0.13825571475917955</td>
        <td>0.31431334622823986</td>
        <td>0.17358618834105</td>
      </tr>
      <tr>
        <td class="line-num">80</td>
        <td>V080</td>
        <td>phrase</td>
        <td>máy tính</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>2</td>
        <td>0.94</td>
        <td>0.94</td>
        <td>0.08</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/maːj/ /tiɲ/</td>
        <td>máy-tính</td>
        <td>m,t</td>
        <td>a,i</td>
        <td>nh,y</td>
        <td>m-aː-j-t-i-ɲ</td>
        <td>aː,i,j,m,t,ɲ</td>
        <td>m→aː,aː→j,j→t,t→i,i→ɲ</td>
        <td>j→t</td>
        <td>sắc-sắc</td>
        <td>sắc</td>
        <td>sắc→sắc</td>
        <td></td>
        <td>0</td>
        <td>tonal_coarticulation_context</td>
        <td>bilabial_closure → open_vowel → palatal → coronal → spread_vowel → palatal</td>
        <td>bilabial_closure,coronal,open_vowel,palatal,spread_vowel</td>
        <td>bilabial_closure→open_vowel,open_vowel→palatal,palatal→coronal,coronal→spread_vowel,spread_vowel→palatal</td>
        <td>bilabial_closure,coronal,open_vowel,palatal,spread_vowel</td>
        <td>m:bilabial_closure,aː:open_vowel,j:palatal,t:coronal,i:spread_vowel,ɲ:palatal</td>
        <td>m:bilabial_closure→aː:open_vowel,aː:open_vowel→j:palatal,j:palatal→t:coronal,t:coronal→i:spread_vowel,i:spread_vowel→ɲ:palatal</td>
        <td>0.13953488372093023</td>
        <td>0.16666666666666666</td>
        <td>0.16666666666666666</td>
        <td>0.031446540880503145</td>
        <td>0.0625</td>
        <td>0.04697327044025157</td>
        <td>0.5</td>
        <td>0.09090909090909091</td>
        <td>0.031446540880503145</td>
        <td>0.12996037187362877</td>
        <td>0.29545454545454547</td>
        <td>0.16317101704058698</td>
        <td>0.13825571475917955</td>
        <td>0.31431334622823986</td>
        <td>0.17358618834105</td>
      </tr>
      <tr>
        <td class="line-num">81</td>
        <td>V081</td>
        <td>phrase</td>
        <td>xin chào</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>2</td>
        <td>0.94</td>
        <td>0.94</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/sin/ /caːw/</td>
        <td>xin-chào</td>
        <td>ch,x</td>
        <td>a,i</td>
        <td>n,o</td>
        <td>s-i-n-c-aː-w</td>
        <td>aː,c,i,n,s,w</td>
        <td>s→i,i→n,n→c,c→aː,aː→w</td>
        <td>n→c</td>
        <td>ngang-huyền</td>
        <td>huyền,ngang</td>
        <td>ngang→huyền</td>
        <td></td>
        <td>0</td>
        <td>tonal_coarticulation_context</td>
        <td>coronal → spread_vowel → coronal → palatal → open_vowel → rounded</td>
        <td>coronal,open_vowel,palatal,rounded,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→coronal,coronal→palatal,palatal→open_vowel,open_vowel→rounded</td>
        <td>coronal,open_vowel,palatal,rounded,spread_vowel</td>
        <td>s:coronal,i:spread_vowel,n:coronal,c:palatal,aː:open_vowel,w:rounded</td>
        <td>s:coronal→i:spread_vowel,i:spread_vowel→n:coronal,n:coronal→c:palatal,c:palatal→aː:open_vowel,aː:open_vowel→w:rounded</td>
        <td>0.13953488372093023</td>
        <td>0.16666666666666666</td>
        <td>0.3333333333333333</td>
        <td>0.031446540880503145</td>
        <td>0.0625</td>
        <td>0.04697327044025157</td>
        <td>0.5</td>
        <td>0.09090909090909091</td>
        <td>0.031446540880503145</td>
        <td>0.17162703854029546</td>
        <td>0.29545454545454547</td>
        <td>0.18698054085011084</td>
        <td>0.18258195589393134</td>
        <td>0.31431334622823986</td>
        <td>0.19891546898947962</td>
      </tr>
      <tr>
        <td class="line-num">82</td>
        <td>V082</td>
        <td>phrase</td>
        <td>cảm ơn</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>2</td>
        <td>0.94</td>
        <td>0.94</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/kaːm/ /ɤn/</td>
        <td>cảm-ơn</td>
        <td>c,∅</td>
        <td>a,ơ</td>
        <td>m,n</td>
        <td>k-aː-m-ɤ-n</td>
        <td>aː,k,m,n,ɤ</td>
        <td>k→aː,aː→m,m→ɤ,ɤ→n</td>
        <td>m→ɤ</td>
        <td>hỏi-ngang</td>
        <td>hỏi,ngang</td>
        <td>hỏi→ngang</td>
        <td></td>
        <td>0</td>
        <td>tonal_coarticulation_context</td>
        <td>low_visibility_velar → open_vowel → bilabial_closure → central_vowel → coronal</td>
        <td>bilabial_closure,central_vowel,coronal,low_visibility_velar,open_vowel</td>
        <td>low_visibility_velar→open_vowel,open_vowel→bilabial_closure,bilabial_closure→central_vowel,central_vowel→coronal</td>
        <td>bilabial_closure,central_vowel,coronal,low_visibility_velar,open_vowel</td>
        <td>k:low_visibility_velar,aː:open_vowel,m:bilabial_closure,ɤ:central_vowel,n:coronal</td>
        <td>k:low_visibility_velar→aː:open_vowel,aː:open_vowel→m:bilabial_closure,m:bilabial_closure→ɤ:central_vowel,ɤ:central_vowel→n:coronal</td>
        <td>0.11627906976744186</td>
        <td>0.16666666666666666</td>
        <td>0.3333333333333333</td>
        <td>0.025157232704402517</td>
        <td>0.0625</td>
        <td>0.043828616352201255</td>
        <td>0.5</td>
        <td>0.07272727272727272</td>
        <td>0.025157232704402517</td>
        <td>0.16502692152991078</td>
        <td>0.2863636363636364</td>
        <td>0.1797131702216169</td>
        <td>0.17556055481905403</td>
        <td>0.30464216634429403</td>
        <td>0.191184223640018</td>
      </tr>
      <tr>
        <td class="line-num">83</td>
        <td>V083</td>
        <td>phrase</td>
        <td>chào buổi sáng</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>3</td>
        <td>1.28</td>
        <td>1.28</td>
        <td>0.1</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/caːw/ /ɓuəj/ /ʂaːŋ/</td>
        <td>chào-buổi-sáng</td>
        <td>b,ch,s</td>
        <td>a,uô</td>
        <td>i,ng,o</td>
        <td>c-aː-w-ɓ-uə-j-ʂ-aː-ŋ</td>
        <td>aː,c,j,uə,w,ŋ,ɓ,ʂ</td>
        <td>c→aː,aː→w,w→ɓ,ɓ→uə,uə→j,j→ʂ,ʂ→aː,aː→ŋ</td>
        <td>w→ɓ,j→ʂ</td>
        <td>huyền-hỏi-sắc</td>
        <td>huyền,hỏi,sắc</td>
        <td>huyền→hỏi,hỏi→sắc</td>
        <td></td>
        <td>0</td>
        <td>tonal_coarticulation_context</td>
        <td>palatal → open_vowel → rounded → bilabial_closure → rounded → palatal → coronal → open_vowel → low_visibility_velar</td>
        <td>bilabial_closure,coronal,low_visibility_velar,open_vowel,palatal,rounded</td>
        <td>palatal→open_vowel,open_vowel→rounded,rounded→bilabial_closure,bilabial_closure→rounded,rounded→palatal,palatal→coronal,coronal→open_vowel,open_vowel→low_visibility_velar</td>
        <td>bilabial_closure,coronal,low_visibility_velar,open_vowel,palatal,rounded</td>
        <td>c:palatal,aː:open_vowel,w:rounded,ɓ:bilabial_closure,uə:rounded,j:palatal,ʂ:coronal,aː:open_vowel,ŋ:low_visibility_velar</td>
        <td>c:palatal→aː:open_vowel,aː:open_vowel→w:rounded,w:rounded→ɓ:bilabial_closure,ɓ:bilabial_closure→uə:rounded,uə:rounded→j:palatal,j:palatal→ʂ:coronal,ʂ:coronal→aː:open_vowel,aː:open_vowel→ŋ:low_visibility_velar</td>
        <td>0.18604651162790697</td>
        <td>0.25</td>
        <td>0.5</td>
        <td>0.050314465408805034</td>
        <td>0.125</td>
        <td>0.08765723270440251</td>
        <td>0.6</td>
        <td>0.14545454545454545</td>
        <td>0.050314465408805034</td>
        <td>0.25592593608307734</td>
        <td>0.3727272727272727</td>
        <td>0.2599246793136657</td>
        <td>0.19994213756490417</td>
        <td>0.29119318181818177</td>
        <td>0.20306615571380132</td>
      </tr>
      <tr>
        <td class="line-num">84</td>
        <td>V084</td>
        <td>phrase</td>
        <td>tôi tên là Lan</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>4</td>
        <td>1.62</td>
        <td>1.62</td>
        <td>0.1</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/toj/ /ten/ /laː/ /laːn/</td>
        <td>tôi-tên-là-Lan</td>
        <td>l,t</td>
        <td>a,ê,ô</td>
        <td>i,n,∅</td>
        <td>t-o-j-t-e-n-l-aː-l-aː-n</td>
        <td>aː,e,j,l,n,o,t</td>
        <td>t→o,o→j,j→t,t→e,e→n,n→l,l→aː,aː→l,l→aː,aː→n</td>
        <td>j→t,n→l,aː→l</td>
        <td>ngang-ngang-huyền-ngang</td>
        <td>huyền,ngang</td>
        <td>ngang→ngang,ngang→huyền,huyền→ngang</td>
        <td></td>
        <td>0</td>
        <td>tonal_coarticulation_context</td>
        <td>coronal → rounded → palatal → coronal → spread_vowel → coronal → coronal → open_vowel → coronal → open_vowel → coronal</td>
        <td>coronal,open_vowel,palatal,rounded,spread_vowel</td>
        <td>coronal→rounded,rounded→palatal,palatal→coronal,coronal→spread_vowel,spread_vowel→coronal,coronal→coronal,coronal→open_vowel,open_vowel→coronal,coronal→open_vowel,open_vowel→coronal</td>
        <td>coronal,open_vowel,palatal,rounded,spread_vowel</td>
        <td>t:coronal,o:rounded,j:palatal,t:coronal,e:spread_vowel,n:coronal,l:coronal,aː:open_vowel,l:coronal,aː:open_vowel,n:coronal</td>
        <td>t:coronal→o:rounded,o:rounded→j:palatal,j:palatal→t:coronal,t:coronal→e:spread_vowel,e:spread_vowel→n:coronal,n:coronal→l:coronal,l:coronal→aː:open_vowel,aː:open_vowel→l:coronal,l:coronal→aː:open_vowel,aː:open_vowel→n:coronal</td>
        <td>0.16279069767441862</td>
        <td>0.16666666666666666</td>
        <td>0.3333333333333333</td>
        <td>0.05660377358490566</td>
        <td>0.1875</td>
        <td>0.12205188679245282</td>
        <td>0.5</td>
        <td>0.14545454545454545</td>
        <td>0.05660377358490566</td>
        <td>0.19621064611671787</td>
        <td>0.32272727272727275</td>
        <td>0.21241441478661754</td>
        <td>0.12111768278809744</td>
        <td>0.19921436588103256</td>
        <td>0.13112000912754168</td>
      </tr>
      <tr>
        <td class="line-num">85</td>
        <td>V085</td>
        <td>phrase</td>
        <td>bạn khỏe không</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>3</td>
        <td>1.28</td>
        <td>1.28</td>
        <td>0.1</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɓaːn/ /xwɛ/ /xoŋ/</td>
        <td>bạn-khỏe-không</td>
        <td>b,kh</td>
        <td>a,oe,ô</td>
        <td>n,ng,∅</td>
        <td>ɓ-aː-n-x-wɛ-x-o-ŋ</td>
        <td>aː,n,o,wɛ,x,ŋ,ɓ</td>
        <td>ɓ→aː,aː→n,n→x,x→wɛ,wɛ→x,x→o,o→ŋ</td>
        <td>n→x,wɛ→x</td>
        <td>nặng-hỏi-ngang</td>
        <td>hỏi,ngang,nặng</td>
        <td>nặng→hỏi,hỏi→ngang</td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast,tonal_coarticulation_context</td>
        <td>bilabial_closure → open_vowel → coronal → low_visibility_velar → rounded → low_visibility_velar → rounded → low_visibility_velar</td>
        <td>bilabial_closure,coronal,low_visibility_velar,open_vowel,rounded</td>
        <td>bilabial_closure→open_vowel,open_vowel→coronal,coronal→low_visibility_velar,low_visibility_velar→rounded,rounded→low_visibility_velar,low_visibility_velar→rounded,rounded→low_visibility_velar</td>
        <td>bilabial_closure,coronal,low_visibility_velar,open_vowel,rounded</td>
        <td>ɓ:bilabial_closure,aː:open_vowel,n:coronal,x:low_visibility_velar,wɛ:rounded,x:low_visibility_velar,o:rounded,ŋ:low_visibility_velar</td>
        <td>ɓ:bilabial_closure→aː:open_vowel,aː:open_vowel→n:coronal,n:coronal→x:low_visibility_velar,x:low_visibility_velar→wɛ:rounded,wɛ:rounded→x:low_visibility_velar,x:low_visibility_velar→o:rounded,o:rounded→ŋ:low_visibility_velar</td>
        <td>0.16279069767441862</td>
        <td>0.16666666666666666</td>
        <td>0.5</td>
        <td>0.0440251572327044</td>
        <td>0.125</td>
        <td>0.0845125786163522</td>
        <td>0.5</td>
        <td>0.09090909090909091</td>
        <td>0.0440251572327044</td>
        <td>0.22849248573935937</td>
        <td>0.29545454545454547</td>
        <td>0.2212720272998904</td>
        <td>0.17850975448387452</td>
        <td>0.23082386363636365</td>
        <td>0.17286877132803938</td>
      </tr>
      <tr>
        <td class="line-num">86</td>
        <td>V086</td>
        <td>phrase</td>
        <td>tôi uống nước</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>3</td>
        <td>1.25</td>
        <td>1.25</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/toj/ /uəŋ/ /nɯək̚/</td>
        <td>tôi-uống-nước</td>
        <td>n,t,∅</td>
        <td>uô,ô,ươ</td>
        <td>c,i,ng</td>
        <td>t-o-j-uə-ŋ-n-ɯə-k̚</td>
        <td>j,k̚,n,o,t,uə,ŋ,ɯə</td>
        <td>t→o,o→j,j→uə,uə→ŋ,ŋ→n,n→ɯə,ɯə→k̚</td>
        <td>j→uə,ŋ→n</td>
        <td>ngang-sắc-sắc</td>
        <td>ngang,sắc</td>
        <td>ngang→sắc,sắc→sắc</td>
        <td>nước</td>
        <td>1</td>
        <td>checked_syllable,tonal_coarticulation_context</td>
        <td>coronal → rounded → palatal → rounded → low_visibility_velar → coronal → central_vowel → low_visibility_velar</td>
        <td>central_vowel,coronal,low_visibility_velar,palatal,rounded</td>
        <td>coronal→rounded,rounded→palatal,palatal→rounded,rounded→low_visibility_velar,low_visibility_velar→coronal,coronal→central_vowel,central_vowel→low_visibility_velar</td>
        <td>central_vowel,coronal,low_visibility_velar,palatal,rounded</td>
        <td>t:coronal,o:rounded,j:palatal,uə:rounded,ŋ:low_visibility_velar,n:coronal,ɯə:central_vowel,k̚:low_visibility_velar</td>
        <td>t:coronal→o:rounded,o:rounded→j:palatal,j:palatal→uə:rounded,uə:rounded→ŋ:low_visibility_velar,ŋ:low_visibility_velar→n:coronal,n:coronal→ɯə:central_vowel,ɯə:central_vowel→k̚:low_visibility_velar</td>
        <td>0.18604651162790697</td>
        <td>0.25</td>
        <td>0.3333333333333333</td>
        <td>0.0440251572327044</td>
        <td>0.125</td>
        <td>0.0845125786163522</td>
        <td>0.5</td>
        <td>0.12727272727272726</td>
        <td>0.0440251572327044</td>
        <td>0.21347310589439814</td>
        <td>0.3136363636363636</td>
        <td>0.21788432972614633</td>
        <td>0.1707784847155185</td>
        <td>0.25090909090909086</td>
        <td>0.17430746378091705</td>
      </tr>
      <tr>
        <td class="line-num">87</td>
        <td>V087</td>
        <td>phrase</td>
        <td>em đọc sách</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>3</td>
        <td>1.22</td>
        <td>1.22</td>
        <td>0.1</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɛm/ /ɗɔk̚/ /ʂaːc̚/</td>
        <td>em-đọc-sách</td>
        <td>s,đ,∅</td>
        <td>a,e,o</td>
        <td>c,ch,m</td>
        <td>ɛ-m-ɗ-ɔ-k̚-ʂ-aː-c̚</td>
        <td>aː,c̚,k̚,m,ɔ,ɗ,ɛ,ʂ</td>
        <td>ɛ→m,m→ɗ,ɗ→ɔ,ɔ→k̚,k̚→ʂ,ʂ→aː,aː→c̚</td>
        <td>m→ɗ,k̚→ʂ</td>
        <td>ngang-nặng-sắc</td>
        <td>ngang,nặng,sắc</td>
        <td>ngang→nặng,nặng→sắc</td>
        <td>đọc,sách</td>
        <td>2</td>
        <td>checked_syllable,phonation_contrast,tonal_coarticulation_context</td>
        <td>spread_vowel → bilabial_closure → central_vowel → rounded → low_visibility_velar → coronal → open_vowel → palatal</td>
        <td>bilabial_closure,central_vowel,coronal,low_visibility_velar,open_vowel,palatal,rounded,spread_vowel</td>
        <td>spread_vowel→bilabial_closure,bilabial_closure→central_vowel,central_vowel→rounded,rounded→low_visibility_velar,low_visibility_velar→coronal,coronal→open_vowel,open_vowel→palatal</td>
        <td>bilabial_closure,central_vowel,coronal,low_visibility_velar,open_vowel,palatal,rounded,spread_vowel</td>
        <td>ɛ:spread_vowel,m:bilabial_closure,ɗ:central_vowel,ɔ:rounded,k̚:low_visibility_velar,ʂ:coronal,aː:open_vowel,c̚:palatal</td>
        <td>ɛ:spread_vowel→m:bilabial_closure,m:bilabial_closure→ɗ:central_vowel,ɗ:central_vowel→ɔ:rounded,ɔ:rounded→k̚:low_visibility_velar,k̚:low_visibility_velar→ʂ:coronal,ʂ:coronal→aː:open_vowel,aː:open_vowel→c̚:palatal</td>
        <td>0.18604651162790697</td>
        <td>0.25</td>
        <td>0.5</td>
        <td>0.0440251572327044</td>
        <td>0.125</td>
        <td>0.0845125786163522</td>
        <td>0.8</td>
        <td>0.12727272727272726</td>
        <td>0.0440251572327044</td>
        <td>0.2551397725610648</td>
        <td>0.4636363636363636</td>
        <td>0.28455099639281295</td>
        <td>0.20913096111562687</td>
        <td>0.38002980625931443</td>
        <td>0.23323852163345324</td>
      </tr>
      <tr>
        <td class="line-num">88</td>
        <td>V088</td>
        <td>phrase</td>
        <td>mẹ nấu cơm</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>3</td>
        <td>1.28</td>
        <td>1.28</td>
        <td>0.1</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/mɛ/ /nəw/ /kɤm/</td>
        <td>mẹ-nấu-cơm</td>
        <td>c,m,n</td>
        <td>e,â,ơ</td>
        <td>m,u,∅</td>
        <td>m-ɛ-n-ə-w-k-ɤ-m</td>
        <td>k,m,n,w,ə,ɛ,ɤ</td>
        <td>m→ɛ,ɛ→n,n→ə,ə→w,w→k,k→ɤ,ɤ→m</td>
        <td>ɛ→n,w→k</td>
        <td>nặng-sắc-ngang</td>
        <td>ngang,nặng,sắc</td>
        <td>nặng→sắc,sắc→ngang</td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast,tonal_coarticulation_context</td>
        <td>bilabial_closure → spread_vowel → coronal → central_vowel → rounded → low_visibility_velar → central_vowel → bilabial_closure</td>
        <td>bilabial_closure,central_vowel,coronal,low_visibility_velar,rounded,spread_vowel</td>
        <td>bilabial_closure→spread_vowel,spread_vowel→coronal,coronal→central_vowel,central_vowel→rounded,rounded→low_visibility_velar,low_visibility_velar→central_vowel,central_vowel→bilabial_closure</td>
        <td>bilabial_closure,central_vowel,coronal,low_visibility_velar,rounded,spread_vowel</td>
        <td>m:bilabial_closure,ɛ:spread_vowel,n:coronal,ə:central_vowel,w:rounded,k:low_visibility_velar,ɤ:central_vowel,m:bilabial_closure</td>
        <td>m:bilabial_closure→ɛ:spread_vowel,ɛ:spread_vowel→n:coronal,n:coronal→ə:central_vowel,ə:central_vowel→w:rounded,w:rounded→k:low_visibility_velar,k:low_visibility_velar→ɤ:central_vowel,ɤ:central_vowel→m:bilabial_closure</td>
        <td>0.16279069767441862</td>
        <td>0.16666666666666666</td>
        <td>0.5</td>
        <td>0.0440251572327044</td>
        <td>0.125</td>
        <td>0.0845125786163522</td>
        <td>0.6</td>
        <td>0.12727272727272726</td>
        <td>0.0440251572327044</td>
        <td>0.22849248573935937</td>
        <td>0.36363636363636365</td>
        <td>0.24075254678040986</td>
        <td>0.17850975448387452</td>
        <td>0.2840909090909091</td>
        <td>0.1880879271721952</td>
      </tr>
      <tr>
        <td class="line-num">89</td>
        <td>V089</td>
        <td>phrase</td>
        <td>bố đi làm</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>3</td>
        <td>1.28</td>
        <td>1.28</td>
        <td>0.1</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɓo/ /ɗi/ /laːm/</td>
        <td>bố-đi-làm</td>
        <td>b,l,đ</td>
        <td>a,i,ô</td>
        <td>m,∅</td>
        <td>ɓ-o-ɗ-i-l-aː-m</td>
        <td>aː,i,l,m,o,ɓ,ɗ</td>
        <td>ɓ→o,o→ɗ,ɗ→i,i→l,l→aː,aː→m</td>
        <td>o→ɗ,i→l</td>
        <td>sắc-ngang-huyền</td>
        <td>huyền,ngang,sắc</td>
        <td>sắc→ngang,ngang→huyền</td>
        <td></td>
        <td>0</td>
        <td>tonal_coarticulation_context</td>
        <td>bilabial_closure → rounded → central_vowel → spread_vowel → coronal → open_vowel → bilabial_closure</td>
        <td>bilabial_closure,central_vowel,coronal,open_vowel,rounded,spread_vowel</td>
        <td>bilabial_closure→rounded,rounded→central_vowel,central_vowel→spread_vowel,spread_vowel→coronal,coronal→open_vowel,open_vowel→bilabial_closure</td>
        <td>bilabial_closure,central_vowel,coronal,open_vowel,rounded,spread_vowel</td>
        <td>ɓ:bilabial_closure,o:rounded,ɗ:central_vowel,i:spread_vowel,l:coronal,aː:open_vowel,m:bilabial_closure</td>
        <td>ɓ:bilabial_closure→o:rounded,o:rounded→ɗ:central_vowel,ɗ:central_vowel→i:spread_vowel,i:spread_vowel→l:coronal,l:coronal→aː:open_vowel,aː:open_vowel→m:bilabial_closure</td>
        <td>0.16279069767441862</td>
        <td>0.08333333333333333</td>
        <td>0.5</td>
        <td>0.03773584905660377</td>
        <td>0.125</td>
        <td>0.08136792452830188</td>
        <td>0.6</td>
        <td>0.10909090909090909</td>
        <td>0.03773584905660377</td>
        <td>0.20687298888401345</td>
        <td>0.35454545454545455</td>
        <td>0.22490267338336664</td>
        <td>0.1616195225656355</td>
        <td>0.27698863636363635</td>
        <td>0.1757052135807552</td>
      </tr>
      <tr>
        <td class="line-num">90</td>
        <td>V090</td>
        <td>phrase</td>
        <td>trẻ em chơi</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>3</td>
        <td>1.28</td>
        <td>1.28</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ʈɛ/ /ɛm/ /cɤj/</td>
        <td>trẻ-em-chơi</td>
        <td>ch,tr,∅</td>
        <td>e,ơ</td>
        <td>i,m,∅</td>
        <td>ʈ-ɛ-ɛ-m-c-ɤ-j</td>
        <td>c,j,m,ɛ,ɤ,ʈ</td>
        <td>ʈ→ɛ,ɛ→ɛ,ɛ→m,m→c,c→ɤ,ɤ→j</td>
        <td>ɛ→ɛ,m→c</td>
        <td>hỏi-ngang-ngang</td>
        <td>hỏi,ngang</td>
        <td>hỏi→ngang,ngang→ngang</td>
        <td></td>
        <td>0</td>
        <td>tonal_coarticulation_context</td>
        <td>coronal → spread_vowel → spread_vowel → bilabial_closure → palatal → central_vowel → palatal</td>
        <td>bilabial_closure,central_vowel,coronal,palatal,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→spread_vowel,spread_vowel→bilabial_closure,bilabial_closure→palatal,palatal→central_vowel,central_vowel→palatal</td>
        <td>bilabial_closure,central_vowel,coronal,palatal,spread_vowel</td>
        <td>ʈ:coronal,ɛ:spread_vowel,ɛ:spread_vowel,m:bilabial_closure,c:palatal,ɤ:central_vowel,j:palatal</td>
        <td>ʈ:coronal→ɛ:spread_vowel,ɛ:spread_vowel→ɛ:spread_vowel,ɛ:spread_vowel→m:bilabial_closure,m:bilabial_closure→c:palatal,c:palatal→ɤ:central_vowel,ɤ:central_vowel→j:palatal</td>
        <td>0.13953488372093023</td>
        <td>0.16666666666666666</td>
        <td>0.3333333333333333</td>
        <td>0.03773584905660377</td>
        <td>0.125</td>
        <td>0.08136792452830188</td>
        <td>0.5</td>
        <td>0.10909090909090909</td>
        <td>0.03773584905660377</td>
        <td>0.18022570206230804</td>
        <td>0.30454545454545456</td>
        <td>0.19538993805667787</td>
        <td>0.14080132973617815</td>
        <td>0.23792613636363638</td>
        <td>0.15264838910677958</td>
      </tr>
      <tr>
        <td class="line-num">91</td>
        <td>V091</td>
        <td>phrase</td>
        <td>nhà ở đây</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>3</td>
        <td>1.28</td>
        <td>1.28</td>
        <td>0.1</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ɲaː/ /ɤ/ /ɗəj/</td>
        <td>nhà-ở-đây</td>
        <td>nh,đ,∅</td>
        <td>a,â,ơ</td>
        <td>y,∅</td>
        <td>ɲ-aː-ɤ-ɗ-ə-j</td>
        <td>aː,j,ɗ,ə,ɤ,ɲ</td>
        <td>ɲ→aː,aː→ɤ,ɤ→ɗ,ɗ→ə,ə→j</td>
        <td>aː→ɤ,ɤ→ɗ</td>
        <td>huyền-hỏi-ngang</td>
        <td>huyền,hỏi,ngang</td>
        <td>huyền→hỏi,hỏi→ngang</td>
        <td></td>
        <td>0</td>
        <td>tonal_coarticulation_context</td>
        <td>palatal → open_vowel → central_vowel → central_vowel → central_vowel → palatal</td>
        <td>central_vowel,open_vowel,palatal</td>
        <td>palatal→open_vowel,open_vowel→central_vowel,central_vowel→central_vowel,central_vowel→central_vowel,central_vowel→palatal</td>
        <td>central_vowel,open_vowel,palatal</td>
        <td>ɲ:palatal,aː:open_vowel,ɤ:central_vowel,ɗ:central_vowel,ə:central_vowel,j:palatal</td>
        <td>ɲ:palatal→aː:open_vowel,aː:open_vowel→ɤ:central_vowel,ɤ:central_vowel→ɗ:central_vowel,ɗ:central_vowel→ə:central_vowel,ə:central_vowel→j:palatal</td>
        <td>0.13953488372093023</td>
        <td>0.08333333333333333</td>
        <td>0.5</td>
        <td>0.031446540880503145</td>
        <td>0.125</td>
        <td>0.07822327044025157</td>
        <td>0.3</td>
        <td>0.07272727272727272</td>
        <td>0.031446540880503145</td>
        <td>0.20027287187362877</td>
        <td>0.18636363636363634</td>
        <td>0.17218075730032728</td>
        <td>0.15646318115127247</td>
        <td>0.14559659090909088</td>
        <td>0.13451621664088068</td>
      </tr>
      <tr>
        <td class="line-num">92</td>
        <td>V092</td>
        <td>phrase</td>
        <td>trời hôm nay đẹp</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>4</td>
        <td>1.59</td>
        <td>1.59</td>
        <td>0.11</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/ʈɤj/ /hom/ /naːj/ /ɗɛp̚/</td>
        <td>trời-hôm-nay-đẹp</td>
        <td>h,n,tr,đ</td>
        <td>a,e,ô,ơ</td>
        <td>i,m,p,y</td>
        <td>ʈ-ɤ-j-h-o-m-n-aː-j-ɗ-ɛ-p̚</td>
        <td>aː,h,j,m,n,o,p̚,ɗ,ɛ,ɤ,ʈ</td>
        <td>ʈ→ɤ,ɤ→j,j→h,h→o,o→m,m→n,n→aː,aː→j,j→ɗ,ɗ→ɛ,ɛ→p̚</td>
        <td>j→h,m→n,j→ɗ</td>
        <td>huyền-ngang-ngang-nặng</td>
        <td>huyền,ngang,nặng</td>
        <td>huyền→ngang,ngang→ngang,ngang→nặng</td>
        <td>đẹp</td>
        <td>1</td>
        <td>checked_syllable,phonation_contrast,tonal_coarticulation_context</td>
        <td>coronal → central_vowel → palatal → glottal → rounded → bilabial_closure → coronal → open_vowel → palatal → central_vowel → spread_vowel → bilabial_closure</td>
        <td>bilabial_closure,central_vowel,coronal,glottal,open_vowel,palatal,rounded,spread_vowel</td>
        <td>coronal→central_vowel,central_vowel→palatal,palatal→glottal,glottal→rounded,rounded→bilabial_closure,bilabial_closure→coronal,coronal→open_vowel,open_vowel→palatal,palatal→central_vowel,central_vowel→spread_vowel,spread_vowel→bilabial_closure</td>
        <td>bilabial_closure,central_vowel,coronal,glottal,open_vowel,palatal,rounded,spread_vowel</td>
        <td>ʈ:coronal,ɤ:central_vowel,j:palatal,h:glottal,o:rounded,m:bilabial_closure,n:coronal,aː:open_vowel,j:palatal,ɗ:central_vowel,ɛ:spread_vowel,p̚:bilabial_closure</td>
        <td>ʈ:coronal→ɤ:central_vowel,ɤ:central_vowel→j:palatal,j:palatal→h:glottal,h:glottal→o:rounded,o:rounded→m:bilabial_closure,m:bilabial_closure→n:coronal,n:coronal→aː:open_vowel,aː:open_vowel→j:palatal,j:palatal→ɗ:central_vowel,ɗ:central_vowel→ɛ:spread_vowel,ɛ:spread_vowel→p̚:bilabial_closure</td>
        <td>0.2558139534883721</td>
        <td>0.3333333333333333</td>
        <td>0.5</td>
        <td>0.06918238993710692</td>
        <td>0.1875</td>
        <td>0.12834119496855345</td>
        <td>0.8</td>
        <td>0.2</td>
        <td>0.06918238993710692</td>
        <td>0.3043721204475647</td>
        <td>0.5</td>
        <td>0.3266672673896237</td>
        <td>0.1914290065707954</td>
        <td>0.31446540880503143</td>
        <td>0.20545111156580106</td>
      </tr>
      <tr>
        <td class="line-num">93</td>
        <td>V093</td>
        <td>phrase</td>
        <td>tôi thích âm nhạc</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>4</td>
        <td>1.56</td>
        <td>1.56</td>
        <td>0.11</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/toj/ /tʰic̚/ /əm/ /ɲaːk̚/</td>
        <td>tôi-thích-âm-nhạc</td>
        <td>nh,t,th,∅</td>
        <td>a,i,â,ô</td>
        <td>c,ch,i,m</td>
        <td>t-o-j-tʰ-i-c̚-ə-m-ɲ-aː-k̚</td>
        <td>aː,c̚,i,j,k̚,m,o,t,tʰ,ə,ɲ</td>
        <td>t→o,o→j,j→tʰ,tʰ→i,i→c̚,c̚→ə,ə→m,m→ɲ,ɲ→aː,aː→k̚</td>
        <td>j→tʰ,c̚→ə,m→ɲ</td>
        <td>ngang-sắc-ngang-nặng</td>
        <td>ngang,nặng,sắc</td>
        <td>ngang→sắc,sắc→ngang,ngang→nặng</td>
        <td>thích,nhạc</td>
        <td>2</td>
        <td>checked_syllable,phonation_contrast,tonal_coarticulation_context</td>
        <td>coronal → rounded → palatal → coronal → spread_vowel → palatal → central_vowel → bilabial_closure → palatal → open_vowel → low_visibility_velar</td>
        <td>bilabial_closure,central_vowel,coronal,low_visibility_velar,open_vowel,palatal,rounded,spread_vowel</td>
        <td>coronal→rounded,rounded→palatal,palatal→coronal,coronal→spread_vowel,spread_vowel→palatal,palatal→central_vowel,central_vowel→bilabial_closure,bilabial_closure→palatal,palatal→open_vowel,open_vowel→low_visibility_velar</td>
        <td>bilabial_closure,central_vowel,coronal,low_visibility_velar,open_vowel,palatal,rounded,spread_vowel</td>
        <td>t:coronal,o:rounded,j:palatal,tʰ:coronal,i:spread_vowel,c̚:palatal,ə:central_vowel,m:bilabial_closure,ɲ:palatal,aː:open_vowel,k̚:low_visibility_velar</td>
        <td>t:coronal→o:rounded,o:rounded→j:palatal,j:palatal→tʰ:coronal,tʰ:coronal→i:spread_vowel,i:spread_vowel→c̚:palatal,c̚:palatal→ə:central_vowel,ə:central_vowel→m:bilabial_closure,m:bilabial_closure→ɲ:palatal,ɲ:palatal→aː:open_vowel,aː:open_vowel→k̚:low_visibility_velar</td>
        <td>0.2558139534883721</td>
        <td>0.3333333333333333</td>
        <td>0.5</td>
        <td>0.06289308176100629</td>
        <td>0.1875</td>
        <td>0.12519654088050314</td>
        <td>0.8</td>
        <td>0.18181818181818182</td>
        <td>0.06289308176100629</td>
        <td>0.3035859569255521</td>
        <td>0.49090909090909096</td>
        <td>0.3227221558973423</td>
        <td>0.19460638264458469</td>
        <td>0.3146853146853147</td>
        <td>0.20687317685727072</td>
      </tr>
      <tr>
        <td class="line-num">94</td>
        <td>V094</td>
        <td>phrase</td>
        <td>xin nói chậm</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>3</td>
        <td>1.28</td>
        <td>1.28</td>
        <td>0.1</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/sin/ /nɔj/ /cəm/</td>
        <td>xin-nói-chậm</td>
        <td>ch,n,x</td>
        <td>i,o,â</td>
        <td>i,m,n</td>
        <td>s-i-n-n-ɔ-j-c-ə-m</td>
        <td>c,i,j,m,n,s,ɔ,ə</td>
        <td>s→i,i→n,n→n,n→ɔ,ɔ→j,j→c,c→ə,ə→m</td>
        <td>n→n,j→c</td>
        <td>ngang-sắc-nặng</td>
        <td>ngang,nặng,sắc</td>
        <td>ngang→sắc,sắc→nặng</td>
        <td></td>
        <td>0</td>
        <td>phonation_contrast,tonal_coarticulation_context</td>
        <td>coronal → spread_vowel → coronal → coronal → rounded → palatal → palatal → central_vowel → bilabial_closure</td>
        <td>bilabial_closure,central_vowel,coronal,palatal,rounded,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→coronal,coronal→coronal,coronal→rounded,rounded→palatal,palatal→palatal,palatal→central_vowel,central_vowel→bilabial_closure</td>
        <td>bilabial_closure,central_vowel,coronal,palatal,rounded,spread_vowel</td>
        <td>s:coronal,i:spread_vowel,n:coronal,n:coronal,ɔ:rounded,j:palatal,c:palatal,ə:central_vowel,m:bilabial_closure</td>
        <td>s:coronal→i:spread_vowel,i:spread_vowel→n:coronal,n:coronal→n:coronal,n:coronal→ɔ:rounded,ɔ:rounded→j:palatal,j:palatal→c:palatal,c:palatal→ə:central_vowel,ə:central_vowel→m:bilabial_closure</td>
        <td>0.18604651162790697</td>
        <td>0.25</td>
        <td>0.5</td>
        <td>0.050314465408805034</td>
        <td>0.125</td>
        <td>0.08765723270440251</td>
        <td>0.6</td>
        <td>0.14545454545454545</td>
        <td>0.050314465408805034</td>
        <td>0.25592593608307734</td>
        <td>0.3727272727272727</td>
        <td>0.2599246793136657</td>
        <td>0.19994213756490417</td>
        <td>0.29119318181818177</td>
        <td>0.20306615571380132</td>
      </tr>
      <tr>
        <td class="line-num">95</td>
        <td>V095</td>
        <td>phrase</td>
        <td>hẹn gặp lại</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>3</td>
        <td>1.25</td>
        <td>1.25</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/hɛn/ /ɣap̚/ /laːj/</td>
        <td>hẹn-gặp-lại</td>
        <td>g,h,l</td>
        <td>a,e,ă</td>
        <td>i,n,p</td>
        <td>h-ɛ-n-ɣ-a-p̚-l-aː-j</td>
        <td>a,aː,h,j,l,n,p̚,ɛ,ɣ</td>
        <td>h→ɛ,ɛ→n,n→ɣ,ɣ→a,a→p̚,p̚→l,l→aː,aː→j</td>
        <td>n→ɣ,p̚→l</td>
        <td>nặng-nặng-nặng</td>
        <td>nặng</td>
        <td>nặng→nặng,nặng→nặng</td>
        <td>gặp</td>
        <td>1</td>
        <td>checked_syllable,phonation_contrast,tonal_coarticulation_context</td>
        <td>glottal → spread_vowel → coronal → low_visibility_velar → open_vowel → bilabial_closure → coronal → open_vowel → palatal</td>
        <td>bilabial_closure,coronal,glottal,low_visibility_velar,open_vowel,palatal,spread_vowel</td>
        <td>glottal→spread_vowel,spread_vowel→coronal,coronal→low_visibility_velar,low_visibility_velar→open_vowel,open_vowel→bilabial_closure,bilabial_closure→coronal,coronal→open_vowel,open_vowel→palatal</td>
        <td>bilabial_closure,coronal,glottal,low_visibility_velar,open_vowel,palatal,spread_vowel</td>
        <td>h:glottal,ɛ:spread_vowel,n:coronal,ɣ:low_visibility_velar,a:open_vowel,p̚:bilabial_closure,l:coronal,aː:open_vowel,j:palatal</td>
        <td>h:glottal→ɛ:spread_vowel,ɛ:spread_vowel→n:coronal,n:coronal→ɣ:low_visibility_velar,ɣ:low_visibility_velar→a:open_vowel,a:open_vowel→p̚:bilabial_closure,p̚:bilabial_closure→l:coronal,l:coronal→aː:open_vowel,aː:open_vowel→j:palatal</td>
        <td>0.20930232558139536</td>
        <td>0.25</td>
        <td>0.16666666666666666</td>
        <td>0.050314465408805034</td>
        <td>0.0625</td>
        <td>0.05640723270440252</td>
        <td>0.7</td>
        <td>0.14545454545454545</td>
        <td>0.050314465408805034</td>
        <td>0.17059405623811613</td>
        <td>0.42272727272727273</td>
        <td>0.2254493194022593</td>
        <td>0.1364752449904929</td>
        <td>0.3381818181818182</td>
        <td>0.18035945552180743</td>
      </tr>
      <tr>
        <td class="line-num">96</td>
        <td>V096</td>
        <td>phrase</td>
        <td>Việt Nam rất đẹp</td>
        <td>Northern Vietnamese (Hanoi)</td>
        <td>4</td>
        <td>1.53</td>
        <td>1.53</td>
        <td>0.11</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.18 + 0.34*syllables - 0.03*checked + 0.08*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*tone_types</td>
        <td>/viət̚/ /naːm/ /zət̚/ /ɗɛp̚/</td>
        <td>Việt-Nam-rất-đẹp</td>
        <td>n,r,v,đ</td>
        <td>a,e,iê,â</td>
        <td>m,p,t</td>
        <td>v-iə-t̚-n-aː-m-z-ə-t̚-ɗ-ɛ-p̚</td>
        <td>aː,iə,m,n,p̚,t̚,v,z,ɗ,ə,ɛ</td>
        <td>v→iə,iə→t̚,t̚→n,n→aː,aː→m,m→z,z→ə,ə→t̚,t̚→ɗ,ɗ→ɛ,ɛ→p̚</td>
        <td>t̚→n,m→z,t̚→ɗ</td>
        <td>nặng-ngang-sắc-nặng</td>
        <td>ngang,nặng,sắc</td>
        <td>nặng→ngang,ngang→sắc,sắc→nặng</td>
        <td>Việt,rất,đẹp</td>
        <td>3</td>
        <td>checked_syllable,phonation_contrast,tonal_coarticulation_context</td>
        <td>labiodental → spread_vowel → coronal → coronal → open_vowel → bilabial_closure → coronal → central_vowel → coronal → central_vowel → spread_vowel → bilabial_closure</td>
        <td>bilabial_closure,central_vowel,coronal,labiodental,open_vowel,spread_vowel</td>
        <td>labiodental→spread_vowel,spread_vowel→coronal,coronal→coronal,coronal→open_vowel,open_vowel→bilabial_closure,bilabial_closure→coronal,coronal→central_vowel,central_vowel→coronal,coronal→central_vowel,central_vowel→spread_vowel,spread_vowel→bilabial_closure</td>
        <td>bilabial_closure,central_vowel,coronal,labiodental,open_vowel,spread_vowel</td>
        <td>v:labiodental,iə:spread_vowel,t̚:coronal,n:coronal,aː:open_vowel,m:bilabial_closure,z:coronal,ə:central_vowel,t̚:coronal,ɗ:central_vowel,ɛ:spread_vowel,p̚:bilabial_closure</td>
        <td>v:labiodental→iə:spread_vowel,iə:spread_vowel→t̚:coronal,t̚:coronal→n:coronal,n:coronal→aː:open_vowel,aː:open_vowel→m:bilabial_closure,m:bilabial_closure→z:coronal,z:coronal→ə:central_vowel,ə:central_vowel→t̚:coronal,t̚:coronal→ɗ:central_vowel,ɗ:central_vowel→ɛ:spread_vowel,ɛ:spread_vowel→p̚:bilabial_closure</td>
        <td>0.2558139534883721</td>
        <td>0.25</td>
        <td>0.5</td>
        <td>0.06918238993710692</td>
        <td>0.1875</td>
        <td>0.12834119496855345</td>
        <td>0.6</td>
        <td>0.18181818181818182</td>
        <td>0.06918238993710692</td>
        <td>0.2835387871142314</td>
        <td>0.3909090909090909</td>
        <td>0.28359367431603066</td>
        <td>0.18531946870211202</td>
        <td>0.255496137849079</td>
        <td>0.1853553426902161</td>
      </tr>
    </tbody>
  </table>
</div>

</div>

### English

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
        <th>dialect</th>
        <th>syllable_count</th>
        <th>stress_pattern</th>
        <th>stress_features</th>
        <th>estimated_duration</th>
        <th>actual_duration_mean</th>
        <th>standard_deviation</th>
        <th>duration_measurement_status</th>
        <th>duration_model</th>
        <th>pronunciation_phonemic_ipa</th>
        <th>surface_pronunciation_ipa</th>
        <th>phoneme_sequence</th>
        <th>phoneme_set</th>
        <th>consonants</th>
        <th>nuclei</th>
        <th>word_final_codas</th>
        <th>cross_word_transition</th>
        <th>phoneme_transitions</th>
        <th>consonant_clusters</th>
        <th>phonological_processes</th>
        <th>reduced_vowels_and_weak_forms</th>
        <th>pronunciation_review_status</th>
        <th>review_notes</th>
        <th>viseme_sequence</th>
        <th>viseme_set</th>
        <th>viseme_transitions</th>
        <th>phoneme_viseme_pairs</th>
        <th>av_transitions</th>
        <th>score_weighting_status</th>
        <th>standalone_phoneme_coverage</th>
        <th>standalone_coda_coverage</th>
        <th>standalone_stress_feature_coverage</th>
        <th>standalone_reduction_coverage</th>
        <th>standalone_cluster_coverage</th>
        <th>standalone_process_coverage</th>
        <th>standalone_phoneme_transition_coverage</th>
        <th>standalone_viseme_coverage</th>
        <th>standalone_viseme_transition_coverage</th>
        <th>standalone_av_transition_coverage</th>
        <th>standalone_audio_score</th>
        <th>standalone_vision_score</th>
        <th>standalone_joint_av_score</th>
        <th>standalone_audio_score_per_sec</th>
        <th>standalone_vision_score_per_sec</th>
        <th>standalone_joint_av_score_per_sec</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="line-num">1</td>
        <td>E001</td>
        <td>word</td>
        <td>cat</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/kæt/</td>
        <td>[kæt]</td>
        <td>k-æ-t</td>
        <td>k,t,æ</td>
        <td>k,t</td>
        <td>æ</td>
        <td>t</td>
        <td></td>
        <td>k→æ,æ→t</td>
        <td></td>
        <td>aspiration</td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → open_vowel → coronal</td>
        <td>low_visibility_velar,open_vowel,coronal</td>
        <td>low_visibility_velar→open_vowel,open_vowel→coronal</td>
        <td>k:low_visibility_velar,æ:open_vowel,t:coronal</td>
        <td>k:low_visibility_velar→æ:open_vowel,æ:open_vowel→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.083587893</td>
        <td>0.084174312</td>
        <td>0.076186723</td>
        <td>0.174141443</td>
        <td>0.17536315</td>
        <td>0.15872234</td>
      </tr>
      <tr>
        <td class="line-num">2</td>
        <td>E002</td>
        <td>word</td>
        <td>dog</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/dɔɡ/</td>
        <td>[dɔɡ]</td>
        <td>d-ɔ-ɡ</td>
        <td>d,ɔ,ɡ</td>
        <td>d,ɡ</td>
        <td>ɔ</td>
        <td>ɡ</td>
        <td></td>
        <td>d→ɔ,ɔ→ɡ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → rounded_open_vowel → low_visibility_velar</td>
        <td>coronal,rounded_open_vowel,low_visibility_velar</td>
        <td>coronal→rounded_open_vowel,rounded_open_vowel→low_visibility_velar</td>
        <td>d:coronal,ɔ:rounded_open_vowel,ɡ:low_visibility_velar</td>
        <td>d:coronal→ɔ:rounded_open_vowel,ɔ:rounded_open_vowel→ɡ:low_visibility_velar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.067714877</td>
        <td>0.084174312</td>
        <td>0.065075612</td>
        <td>0.14107266</td>
        <td>0.17536315</td>
        <td>0.135574192</td>
      </tr>
      <tr>
        <td class="line-num">3</td>
        <td>E003</td>
        <td>word</td>
        <td>sheep</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ʃiːp/</td>
        <td>[ʃiːp]</td>
        <td>ʃ-iː-p</td>
        <td>iː,p,ʃ</td>
        <td>ʃ,p</td>
        <td>iː</td>
        <td>p</td>
        <td></td>
        <td>ʃ→iː,iː→p</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>postalveolar → spread_vowel → bilabial_closure</td>
        <td>postalveolar,spread_vowel,bilabial_closure</td>
        <td>postalveolar→spread_vowel,spread_vowel→bilabial_closure</td>
        <td>ʃ:postalveolar,iː:spread_vowel,p:bilabial_closure</td>
        <td>ʃ:postalveolar→iː:spread_vowel,iː:spread_vowel→p:bilabial_closure</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.067714877</td>
        <td>0.084174312</td>
        <td>0.065075612</td>
        <td>0.14107266</td>
        <td>0.17536315</td>
        <td>0.135574192</td>
      </tr>
      <tr>
        <td class="line-num">4</td>
        <td>E004</td>
        <td>word</td>
        <td>fish</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/fɪʃ/</td>
        <td>[fɪʃ]</td>
        <td>f-ɪ-ʃ</td>
        <td>f,ɪ,ʃ</td>
        <td>f,ʃ</td>
        <td>ɪ</td>
        <td>ʃ</td>
        <td></td>
        <td>f→ɪ,ɪ→ʃ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>labiodental → spread_vowel → postalveolar</td>
        <td>labiodental,spread_vowel,postalveolar</td>
        <td>labiodental→spread_vowel,spread_vowel→postalveolar</td>
        <td>f:labiodental,ɪ:spread_vowel,ʃ:postalveolar</td>
        <td>f:labiodental→ɪ:spread_vowel,ɪ:spread_vowel→ʃ:postalveolar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.067714877</td>
        <td>0.084174312</td>
        <td>0.065075612</td>
        <td>0.14107266</td>
        <td>0.17536315</td>
        <td>0.135574192</td>
      </tr>
      <tr>
        <td class="line-num">5</td>
        <td>E005</td>
        <td>word</td>
        <td>bird</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/bɝd/</td>
        <td>[bɝd]</td>
        <td>b-ɝ-d</td>
        <td>b,d,ɝ</td>
        <td>b,d</td>
        <td>ɝ</td>
        <td>d</td>
        <td></td>
        <td>b→ɝ,ɝ→d</td>
        <td></td>
        <td>r_coloring</td>
        <td>ɝ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → rhotic_vowel → coronal</td>
        <td>bilabial_closure,rhotic_vowel,coronal</td>
        <td>bilabial_closure→rhotic_vowel,rhotic_vowel→coronal</td>
        <td>b:bilabial_closure,ɝ:rhotic_vowel,d:coronal</td>
        <td>b:bilabial_closure→ɝ:rhotic_vowel,ɝ:rhotic_vowel→d:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.097873607</td>
        <td>0.084174312</td>
        <td>0.086186723</td>
        <td>0.203903348</td>
        <td>0.17536315</td>
        <td>0.179555674</td>
      </tr>
      <tr>
        <td class="line-num">6</td>
        <td>E006</td>
        <td>word</td>
        <td>mouse</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/maʊs/</td>
        <td>[maʊs]</td>
        <td>m-aʊ-s</td>
        <td>aʊ,m,s</td>
        <td>m,s</td>
        <td>aʊ</td>
        <td>s</td>
        <td></td>
        <td>m→aʊ,aʊ→s</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → open_to_rounded → coronal</td>
        <td>bilabial_closure,open_to_rounded,coronal</td>
        <td>bilabial_closure→open_to_rounded,open_to_rounded→coronal</td>
        <td>m:bilabial_closure,aʊ:open_to_rounded,s:coronal</td>
        <td>m:bilabial_closure→aʊ:open_to_rounded,aʊ:open_to_rounded→s:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.067714877</td>
        <td>0.084174312</td>
        <td>0.065075612</td>
        <td>0.14107266</td>
        <td>0.17536315</td>
        <td>0.135574192</td>
      </tr>
      <tr>
        <td class="line-num">7</td>
        <td>E007</td>
        <td>word</td>
        <td>goat</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɡoʊt/</td>
        <td>[ɡoʊt]</td>
        <td>ɡ-oʊ-t</td>
        <td>oʊ,t,ɡ</td>
        <td>ɡ,t</td>
        <td>oʊ</td>
        <td>t</td>
        <td></td>
        <td>ɡ→oʊ,oʊ→t</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → rounded_vowel → coronal</td>
        <td>low_visibility_velar,rounded_vowel,coronal</td>
        <td>low_visibility_velar→rounded_vowel,rounded_vowel→coronal</td>
        <td>ɡ:low_visibility_velar,oʊ:rounded_vowel,t:coronal</td>
        <td>ɡ:low_visibility_velar→oʊ:rounded_vowel,oʊ:rounded_vowel→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.067714877</td>
        <td>0.084174312</td>
        <td>0.065075612</td>
        <td>0.14107266</td>
        <td>0.17536315</td>
        <td>0.135574192</td>
      </tr>
      <tr>
        <td class="line-num">8</td>
        <td>E008</td>
        <td>word</td>
        <td>zebra</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.8</td>
        <td>0.8</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ziːbɹə/</td>
        <td>[ziːbɹə]</td>
        <td>z-iː-b-ɹ-ə</td>
        <td>b,iː,z,ə,ɹ</td>
        <td>z,b,ɹ</td>
        <td>iː,ə</td>
        <td></td>
        <td></td>
        <td>z→iː,iː→b,b→ɹ,ɹ→ə</td>
        <td>bɹ</td>
        <td>vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → spread_vowel → bilabial_closure → rhotic → neutral_vowel</td>
        <td>coronal,spread_vowel,bilabial_closure,rhotic,neutral_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→bilabial_closure,bilabial_closure→rhotic,rhotic→neutral_vowel</td>
        <td>z:coronal,iː:spread_vowel,b:bilabial_closure,ɹ:rhotic,ə:neutral_vowel</td>
        <td>z:coronal→iː:spread_vowel,iː:spread_vowel→b:bilabial_closure,b:bilabial_closure→ɹ:rhotic,ɹ:rhotic→ə:neutral_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.111111111</td>
        <td>0.016806723</td>
        <td>0.25</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.149170986</td>
        <td>0.143348624</td>
        <td>0.134770087</td>
        <td>0.186463733</td>
        <td>0.17918578</td>
        <td>0.168462609</td>
      </tr>
      <tr>
        <td class="line-num">9</td>
        <td>E009</td>
        <td>word</td>
        <td>chair</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/tʃɛɹ/</td>
        <td>[tʃɛɹ]</td>
        <td>tʃ-ɛɹ</td>
        <td>tʃ,ɛɹ</td>
        <td>tʃ</td>
        <td>ɛɹ</td>
        <td></td>
        <td></td>
        <td>tʃ→ɛɹ</td>
        <td></td>
        <td>r_coloring</td>
        <td>ɛɹ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>postalveolar → rhotic_vowel</td>
        <td>postalveolar,rhotic_vowel</td>
        <td>postalveolar→rhotic_vowel</td>
        <td>tʃ:postalveolar,ɛɹ:rhotic_vowel</td>
        <td>tʃ:postalveolar→ɛɹ:rhotic_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.046511628</td>
        <td>0</td>
        <td>0.333333333</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.004201681</td>
        <td>0.1</td>
        <td>0.009174312</td>
        <td>0.004201681</td>
        <td>0.085022536</td>
        <td>0.054587156</td>
        <td>0.070853375</td>
        <td>0.177130284</td>
        <td>0.113723242</td>
        <td>0.147611197</td>
      </tr>
      <tr>
        <td class="line-num">10</td>
        <td>E010</td>
        <td>word</td>
        <td>judge</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/dʒʌdʒ/</td>
        <td>[dʒʌdʒ]</td>
        <td>dʒ-ʌ-dʒ</td>
        <td>dʒ,ʌ</td>
        <td>dʒ</td>
        <td>ʌ</td>
        <td>dʒ</td>
        <td></td>
        <td>dʒ→ʌ,ʌ→dʒ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>postalveolar → central_open_vowel → postalveolar</td>
        <td>postalveolar,central_open_vowel</td>
        <td>postalveolar→central_open_vowel,central_open_vowel→postalveolar</td>
        <td>dʒ:postalveolar,ʌ:central_open_vowel,dʒ:postalveolar</td>
        <td>dʒ:postalveolar→ʌ:central_open_vowel,ʌ:central_open_vowel→dʒ:postalveolar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.046511628</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.1</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.064392618</td>
        <td>0.059174312</td>
        <td>0.057750031</td>
        <td>0.134151286</td>
        <td>0.123279817</td>
        <td>0.120312564</td>
      </tr>
      <tr>
        <td class="line-num">11</td>
        <td>E011</td>
        <td>word</td>
        <td>van</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/væn/</td>
        <td>[væn]</td>
        <td>v-æ-n</td>
        <td>n,v,æ</td>
        <td>v,n</td>
        <td>æ</td>
        <td>n</td>
        <td></td>
        <td>v→æ,æ→n</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>labiodental → open_vowel → coronal</td>
        <td>labiodental,open_vowel,coronal</td>
        <td>labiodental→open_vowel,open_vowel→coronal</td>
        <td>v:labiodental,æ:open_vowel,n:coronal</td>
        <td>v:labiodental→æ:open_vowel,æ:open_vowel→n:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.067714877</td>
        <td>0.084174312</td>
        <td>0.065075612</td>
        <td>0.14107266</td>
        <td>0.17536315</td>
        <td>0.135574192</td>
      </tr>
      <tr>
        <td class="line-num">12</td>
        <td>E012</td>
        <td>word</td>
        <td>think</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/θɪŋk/</td>
        <td>[θɪŋk]</td>
        <td>θ-ɪ-ŋ-k</td>
        <td>k,ŋ,ɪ,θ</td>
        <td>θ,ŋ,k</td>
        <td>ɪ</td>
        <td>k</td>
        <td></td>
        <td>θ→ɪ,ɪ→ŋ,ŋ→k</td>
        <td>ŋk</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>dental → spread_vowel → low_visibility_velar → low_visibility_velar</td>
        <td>dental,spread_vowel,low_visibility_velar</td>
        <td>dental→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→low_visibility_velar</td>
        <td>θ:dental,ɪ:spread_vowel,ŋ:low_visibility_velar,k:low_visibility_velar</td>
        <td>θ:dental→ɪ:spread_vowel,ɪ:spread_vowel→ŋ:low_visibility_velar,ŋ:low_visibility_velar→k:low_visibility_velar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.012605042</td>
        <td>0.15</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.076399281</td>
        <td>0.088761468</td>
        <td>0.072492294</td>
        <td>0.146921694</td>
        <td>0.170695131</td>
        <td>0.139408258</td>
      </tr>
      <tr>
        <td class="line-num">13</td>
        <td>E013</td>
        <td>word</td>
        <td>this</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ðɪs/</td>
        <td>[ðɪs]</td>
        <td>ð-ɪ-s</td>
        <td>s,ð,ɪ</td>
        <td>ð,s</td>
        <td>ɪ</td>
        <td>s</td>
        <td></td>
        <td>ð→ɪ,ɪ→s</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>dental → spread_vowel → coronal</td>
        <td>dental,spread_vowel,coronal</td>
        <td>dental→spread_vowel,spread_vowel→coronal</td>
        <td>ð:dental,ɪ:spread_vowel,s:coronal</td>
        <td>ð:dental→ɪ:spread_vowel,ɪ:spread_vowel→s:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.067714877</td>
        <td>0.084174312</td>
        <td>0.065075612</td>
        <td>0.14107266</td>
        <td>0.17536315</td>
        <td>0.135574192</td>
      </tr>
      <tr>
        <td class="line-num">14</td>
        <td>E014</td>
        <td>word</td>
        <td>red</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɹɛd/</td>
        <td>[ɹɛd]</td>
        <td>ɹ-ɛ-d</td>
        <td>d,ɛ,ɹ</td>
        <td>ɹ,d</td>
        <td>ɛ</td>
        <td>d</td>
        <td></td>
        <td>ɹ→ɛ,ɛ→d</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>rhotic → front_open_vowel → coronal</td>
        <td>rhotic,front_open_vowel,coronal</td>
        <td>rhotic→front_open_vowel,front_open_vowel→coronal</td>
        <td>ɹ:rhotic,ɛ:front_open_vowel,d:coronal</td>
        <td>ɹ:rhotic→ɛ:front_open_vowel,ɛ:front_open_vowel→d:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.067714877</td>
        <td>0.084174312</td>
        <td>0.065075612</td>
        <td>0.14107266</td>
        <td>0.17536315</td>
        <td>0.135574192</td>
      </tr>
      <tr>
        <td class="line-num">15</td>
        <td>E015</td>
        <td>word</td>
        <td>light</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/laɪt/</td>
        <td>[laɪt]</td>
        <td>l-aɪ-t</td>
        <td>aɪ,l,t</td>
        <td>l,t</td>
        <td>aɪ</td>
        <td>t</td>
        <td></td>
        <td>l→aɪ,aɪ→t</td>
        <td></td>
        <td>dark_l</td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → open_to_spread → coronal</td>
        <td>coronal,open_to_spread</td>
        <td>coronal→open_to_spread,open_to_spread→coronal</td>
        <td>l:coronal,aɪ:open_to_spread,t:coronal</td>
        <td>l:coronal→aɪ:open_to_spread,aɪ:open_to_spread→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.008403361</td>
        <td>0.1</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.083587893</td>
        <td>0.059174312</td>
        <td>0.071186723</td>
        <td>0.174141443</td>
        <td>0.123279817</td>
        <td>0.148305674</td>
      </tr>
      <tr>
        <td class="line-num">16</td>
        <td>E016</td>
        <td>word</td>
        <td>yellow</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/jɛloʊ/</td>
        <td>[jɛloʊ]</td>
        <td>j-ɛ-l-oʊ</td>
        <td>j,l,oʊ,ɛ</td>
        <td>j,l</td>
        <td>ɛ,oʊ</td>
        <td></td>
        <td></td>
        <td>j→ɛ,ɛ→l,l→oʊ</td>
        <td></td>
        <td>dark_l</td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>palatal_glide → front_open_vowel → coronal → rounded_vowel</td>
        <td>palatal_glide,front_open_vowel,coronal,rounded_vowel</td>
        <td>palatal_glide→front_open_vowel,front_open_vowel→coronal,coronal→rounded_vowel</td>
        <td>j:palatal_glide,ɛ:front_open_vowel,l:coronal,oʊ:rounded_vowel</td>
        <td>j:palatal_glide→ɛ:front_open_vowel,ɛ:front_open_vowel→l:coronal,l:coronal→oʊ:rounded_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.126200868</td>
        <td>0.113761468</td>
        <td>0.112353405</td>
        <td>0.166053774</td>
        <td>0.149686142</td>
        <td>0.147833428</td>
      </tr>
      <tr>
        <td class="line-num">17</td>
        <td>E017</td>
        <td>word</td>
        <td>water</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/wɔtɚ/</td>
        <td>[wɔɾɚ]</td>
        <td>w-ɔ-t-ɚ</td>
        <td>t,w,ɔ,ɚ</td>
        <td>w,t</td>
        <td>ɔ,ɚ</td>
        <td></td>
        <td></td>
        <td>w→ɔ,ɔ→t,t→ɚ</td>
        <td></td>
        <td>flapping;r_coloring</td>
        <td>ɚ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>rounded_glide → rounded_open_vowel → coronal → rhotic_vowel</td>
        <td>rounded_glide,rounded_open_vowel,coronal,rhotic_vowel</td>
        <td>rounded_glide→rounded_open_vowel,rounded_open_vowel→coronal,coronal→rhotic_vowel</td>
        <td>w:rounded_glide,ɔ:rounded_open_vowel,t:coronal,ɚ:rhotic_vowel</td>
        <td>w:rounded_glide→ɔ:rounded_open_vowel,ɔ:rounded_open_vowel→t:coronal,t:coronal→ɚ:rhotic_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.156359598</td>
        <td>0.113761468</td>
        <td>0.133464516</td>
        <td>0.205736313</td>
        <td>0.149686142</td>
        <td>0.175611206</td>
      </tr>
      <tr>
        <td class="line-num">18</td>
        <td>E018</td>
        <td>word</td>
        <td>happy</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/hæpi/</td>
        <td>[hæpi]</td>
        <td>h-æ-p-i</td>
        <td>h,i,p,æ</td>
        <td>h,p</td>
        <td>æ,i</td>
        <td></td>
        <td></td>
        <td>h→æ,æ→p,p→i</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>glottal → open_vowel → bilabial_closure → spread_vowel</td>
        <td>glottal,open_vowel,bilabial_closure,spread_vowel</td>
        <td>glottal→open_vowel,open_vowel→bilabial_closure,bilabial_closure→spread_vowel</td>
        <td>h:glottal,æ:open_vowel,p:bilabial_closure,i:spread_vowel</td>
        <td>h:glottal→æ:open_vowel,æ:open_vowel→p:bilabial_closure,p:bilabial_closure→i:spread_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.110327852</td>
        <td>0.113761468</td>
        <td>0.101242294</td>
        <td>0.145168226</td>
        <td>0.149686142</td>
        <td>0.133213545</td>
      </tr>
      <tr>
        <td class="line-num">19</td>
        <td>E019</td>
        <td>word</td>
        <td>pen</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/pɛn/</td>
        <td>[pɛn]</td>
        <td>p-ɛ-n</td>
        <td>n,p,ɛ</td>
        <td>p,n</td>
        <td>ɛ</td>
        <td>n</td>
        <td></td>
        <td>p→ɛ,ɛ→n</td>
        <td></td>
        <td>aspiration</td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → front_open_vowel → coronal</td>
        <td>bilabial_closure,front_open_vowel,coronal</td>
        <td>bilabial_closure→front_open_vowel,front_open_vowel→coronal</td>
        <td>p:bilabial_closure,ɛ:front_open_vowel,n:coronal</td>
        <td>p:bilabial_closure→ɛ:front_open_vowel,ɛ:front_open_vowel→n:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.083587893</td>
        <td>0.084174312</td>
        <td>0.076186723</td>
        <td>0.174141443</td>
        <td>0.17536315</td>
        <td>0.15872234</td>
      </tr>
      <tr>
        <td class="line-num">20</td>
        <td>E020</td>
        <td>word</td>
        <td>book</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/bʊk/</td>
        <td>[bʊk]</td>
        <td>b-ʊ-k</td>
        <td>b,k,ʊ</td>
        <td>b,k</td>
        <td>ʊ</td>
        <td>k</td>
        <td></td>
        <td>b→ʊ,ʊ→k</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → rounded_vowel → low_visibility_velar</td>
        <td>bilabial_closure,rounded_vowel,low_visibility_velar</td>
        <td>bilabial_closure→rounded_vowel,rounded_vowel→low_visibility_velar</td>
        <td>b:bilabial_closure,ʊ:rounded_vowel,k:low_visibility_velar</td>
        <td>b:bilabial_closure→ʊ:rounded_vowel,ʊ:rounded_vowel→k:low_visibility_velar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.067714877</td>
        <td>0.084174312</td>
        <td>0.065075612</td>
        <td>0.14107266</td>
        <td>0.17536315</td>
        <td>0.135574192</td>
      </tr>
      <tr>
        <td class="line-num">21</td>
        <td>E021</td>
        <td>word</td>
        <td>cup</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/kʌp/</td>
        <td>[kʌp]</td>
        <td>k-ʌ-p</td>
        <td>k,p,ʌ</td>
        <td>k,p</td>
        <td>ʌ</td>
        <td>p</td>
        <td></td>
        <td>k→ʌ,ʌ→p</td>
        <td></td>
        <td>aspiration</td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → central_open_vowel → bilabial_closure</td>
        <td>low_visibility_velar,central_open_vowel,bilabial_closure</td>
        <td>low_visibility_velar→central_open_vowel,central_open_vowel→bilabial_closure</td>
        <td>k:low_visibility_velar,ʌ:central_open_vowel,p:bilabial_closure</td>
        <td>k:low_visibility_velar→ʌ:central_open_vowel,ʌ:central_open_vowel→p:bilabial_closure</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.083587893</td>
        <td>0.084174312</td>
        <td>0.076186723</td>
        <td>0.174141443</td>
        <td>0.17536315</td>
        <td>0.15872234</td>
      </tr>
      <tr>
        <td class="line-num">22</td>
        <td>E022</td>
        <td>word</td>
        <td>key</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/kiː/</td>
        <td>[kiː]</td>
        <td>k-iː</td>
        <td>iː,k</td>
        <td>k</td>
        <td>iː</td>
        <td></td>
        <td></td>
        <td>k→iː</td>
        <td></td>
        <td>aspiration</td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → spread_vowel</td>
        <td>low_visibility_velar,spread_vowel</td>
        <td>low_visibility_velar→spread_vowel</td>
        <td>k:low_visibility_velar,iː:spread_vowel</td>
        <td>k:low_visibility_velar→iː:spread_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.046511628</td>
        <td>0</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.004201681</td>
        <td>0.1</td>
        <td>0.009174312</td>
        <td>0.004201681</td>
        <td>0.070736822</td>
        <td>0.054587156</td>
        <td>0.060853375</td>
        <td>0.147368379</td>
        <td>0.113723242</td>
        <td>0.126777864</td>
      </tr>
      <tr>
        <td class="line-num">23</td>
        <td>E023</td>
        <td>word</td>
        <td>phone</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/foʊn/</td>
        <td>[foʊn]</td>
        <td>f-oʊ-n</td>
        <td>f,n,oʊ</td>
        <td>f,n</td>
        <td>oʊ</td>
        <td>n</td>
        <td></td>
        <td>f→oʊ,oʊ→n</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>labiodental → rounded_vowel → coronal</td>
        <td>labiodental,rounded_vowel,coronal</td>
        <td>labiodental→rounded_vowel,rounded_vowel→coronal</td>
        <td>f:labiodental,oʊ:rounded_vowel,n:coronal</td>
        <td>f:labiodental→oʊ:rounded_vowel,oʊ:rounded_vowel→n:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.067714877</td>
        <td>0.084174312</td>
        <td>0.065075612</td>
        <td>0.14107266</td>
        <td>0.17536315</td>
        <td>0.135574192</td>
      </tr>
      <tr>
        <td class="line-num">24</td>
        <td>E024</td>
        <td>word</td>
        <td>mirror</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/mɪɹɚ/</td>
        <td>[mɪɹɚ]</td>
        <td>m-ɪ-ɹ-ɚ</td>
        <td>m,ɚ,ɪ,ɹ</td>
        <td>m,ɹ</td>
        <td>ɪ,ɚ</td>
        <td></td>
        <td></td>
        <td>m→ɪ,ɪ→ɹ,ɹ→ɚ</td>
        <td></td>
        <td>r_coloring</td>
        <td>ɚ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → spread_vowel → rhotic → rhotic_vowel</td>
        <td>bilabial_closure,spread_vowel,rhotic,rhotic_vowel</td>
        <td>bilabial_closure→spread_vowel,spread_vowel→rhotic,rhotic→rhotic_vowel</td>
        <td>m:bilabial_closure,ɪ:spread_vowel,ɹ:rhotic,ɚ:rhotic_vowel</td>
        <td>m:bilabial_closure→ɪ:spread_vowel,ɪ:spread_vowel→ɹ:rhotic,ɹ:rhotic→ɚ:rhotic_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.140486582</td>
        <td>0.113761468</td>
        <td>0.122353405</td>
        <td>0.184850766</td>
        <td>0.149686142</td>
        <td>0.160991323</td>
      </tr>
      <tr>
        <td class="line-num">25</td>
        <td>E025</td>
        <td>word</td>
        <td>spoon</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/spuːn/</td>
        <td>[spuːn]</td>
        <td>s-p-uː-n</td>
        <td>n,p,s,uː</td>
        <td>s,p,n</td>
        <td>uː</td>
        <td>n</td>
        <td></td>
        <td>s→p,p→uː,uː→n</td>
        <td>sp</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → bilabial_closure → rounded_vowel → coronal</td>
        <td>coronal,bilabial_closure,rounded_vowel</td>
        <td>coronal→bilabial_closure,bilabial_closure→rounded_vowel,rounded_vowel→coronal</td>
        <td>s:coronal,p:bilabial_closure,uː:rounded_vowel,n:coronal</td>
        <td>s:coronal→p:bilabial_closure,p:bilabial_closure→uː:rounded_vowel,uː:rounded_vowel→n:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.012605042</td>
        <td>0.15</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.076399281</td>
        <td>0.088761468</td>
        <td>0.072492294</td>
        <td>0.146921694</td>
        <td>0.170695131</td>
        <td>0.139408258</td>
      </tr>
      <tr>
        <td class="line-num">26</td>
        <td>E026</td>
        <td>word</td>
        <td>plate</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/pleɪt/</td>
        <td>[pleɪt]</td>
        <td>p-l-eɪ-t</td>
        <td>eɪ,l,p,t</td>
        <td>p,l,t</td>
        <td>eɪ</td>
        <td>t</td>
        <td></td>
        <td>p→l,l→eɪ,eɪ→t</td>
        <td>pl</td>
        <td>aspiration</td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → coronal → spread_vowel → coronal</td>
        <td>bilabial_closure,coronal,spread_vowel</td>
        <td>bilabial_closure→coronal,coronal→spread_vowel,spread_vowel→coronal</td>
        <td>p:bilabial_closure,l:coronal,eɪ:spread_vowel,t:coronal</td>
        <td>p:bilabial_closure→l:coronal,l:coronal→eɪ:spread_vowel,eɪ:spread_vowel→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0.111111111</td>
        <td>0.012605042</td>
        <td>0.15</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.092272297</td>
        <td>0.088761468</td>
        <td>0.083603405</td>
        <td>0.177446724</td>
        <td>0.170695131</td>
        <td>0.16077578</td>
      </tr>
      <tr>
        <td class="line-num">27</td>
        <td>E027</td>
        <td>word</td>
        <td>glass</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɡlæs/</td>
        <td>[ɡlæs]</td>
        <td>ɡ-l-æ-s</td>
        <td>l,s,æ,ɡ</td>
        <td>ɡ,l,s</td>
        <td>æ</td>
        <td>s</td>
        <td></td>
        <td>ɡ→l,l→æ,æ→s</td>
        <td>ɡl</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → coronal → open_vowel → coronal</td>
        <td>low_visibility_velar,coronal,open_vowel</td>
        <td>low_visibility_velar→coronal,coronal→open_vowel,open_vowel→coronal</td>
        <td>ɡ:low_visibility_velar,l:coronal,æ:open_vowel,s:coronal</td>
        <td>ɡ:low_visibility_velar→l:coronal,l:coronal→æ:open_vowel,æ:open_vowel→s:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.012605042</td>
        <td>0.15</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.076399281</td>
        <td>0.088761468</td>
        <td>0.072492294</td>
        <td>0.146921694</td>
        <td>0.170695131</td>
        <td>0.139408258</td>
      </tr>
      <tr>
        <td class="line-num">28</td>
        <td>E028</td>
        <td>word</td>
        <td>bread</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/bɹɛd/</td>
        <td>[bɹɛd]</td>
        <td>b-ɹ-ɛ-d</td>
        <td>b,d,ɛ,ɹ</td>
        <td>b,ɹ,d</td>
        <td>ɛ</td>
        <td>d</td>
        <td></td>
        <td>b→ɹ,ɹ→ɛ,ɛ→d</td>
        <td>bɹ</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → rhotic → front_open_vowel → coronal</td>
        <td>bilabial_closure,rhotic,front_open_vowel,coronal</td>
        <td>bilabial_closure→rhotic,rhotic→front_open_vowel,front_open_vowel→coronal</td>
        <td>b:bilabial_closure,ɹ:rhotic,ɛ:front_open_vowel,d:coronal</td>
        <td>b:bilabial_closure→ɹ:rhotic,ɹ:rhotic→ɛ:front_open_vowel,ɛ:front_open_vowel→d:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.076399281</td>
        <td>0.113761468</td>
        <td>0.077492294</td>
        <td>0.146921694</td>
        <td>0.218772054</td>
        <td>0.149023643</td>
      </tr>
      <tr>
        <td class="line-num">29</td>
        <td>E029</td>
        <td>word</td>
        <td>cheese</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/tʃiːz/</td>
        <td>[tʃiːz]</td>
        <td>tʃ-iː-z</td>
        <td>iː,tʃ,z</td>
        <td>tʃ,z</td>
        <td>iː</td>
        <td>z</td>
        <td></td>
        <td>tʃ→iː,iː→z</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>postalveolar → spread_vowel → coronal</td>
        <td>postalveolar,spread_vowel,coronal</td>
        <td>postalveolar→spread_vowel,spread_vowel→coronal</td>
        <td>tʃ:postalveolar,iː:spread_vowel,z:coronal</td>
        <td>tʃ:postalveolar→iː:spread_vowel,iː:spread_vowel→z:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.067714877</td>
        <td>0.084174312</td>
        <td>0.065075612</td>
        <td>0.14107266</td>
        <td>0.17536315</td>
        <td>0.135574192</td>
      </tr>
      <tr>
        <td class="line-num">30</td>
        <td>E030</td>
        <td>word</td>
        <td>fruit</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/fɹuːt/</td>
        <td>[fɹuːt]</td>
        <td>f-ɹ-uː-t</td>
        <td>f,t,uː,ɹ</td>
        <td>f,ɹ,t</td>
        <td>uː</td>
        <td>t</td>
        <td></td>
        <td>f→ɹ,ɹ→uː,uː→t</td>
        <td>fɹ</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>labiodental → rhotic → rounded_vowel → coronal</td>
        <td>labiodental,rhotic,rounded_vowel,coronal</td>
        <td>labiodental→rhotic,rhotic→rounded_vowel,rounded_vowel→coronal</td>
        <td>f:labiodental,ɹ:rhotic,uː:rounded_vowel,t:coronal</td>
        <td>f:labiodental→ɹ:rhotic,ɹ:rhotic→uː:rounded_vowel,uː:rounded_vowel→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.076399281</td>
        <td>0.113761468</td>
        <td>0.077492294</td>
        <td>0.146921694</td>
        <td>0.218772054</td>
        <td>0.149023643</td>
      </tr>
      <tr>
        <td class="line-num">31</td>
        <td>E031</td>
        <td>word</td>
        <td>milk</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/mɪlk/</td>
        <td>[mɪlk]</td>
        <td>m-ɪ-l-k</td>
        <td>k,l,m,ɪ</td>
        <td>m,l,k</td>
        <td>ɪ</td>
        <td>k</td>
        <td></td>
        <td>m→ɪ,ɪ→l,l→k</td>
        <td>lk</td>
        <td>dark_l</td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → spread_vowel → coronal → low_visibility_velar</td>
        <td>bilabial_closure,spread_vowel,coronal,low_visibility_velar</td>
        <td>bilabial_closure→spread_vowel,spread_vowel→coronal,coronal→low_visibility_velar</td>
        <td>m:bilabial_closure,ɪ:spread_vowel,l:coronal,k:low_visibility_velar</td>
        <td>m:bilabial_closure→ɪ:spread_vowel,ɪ:spread_vowel→l:coronal,l:coronal→k:low_visibility_velar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0.111111111</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.092272297</td>
        <td>0.113761468</td>
        <td>0.088603405</td>
        <td>0.177446724</td>
        <td>0.218772054</td>
        <td>0.170391164</td>
      </tr>
      <tr>
        <td class="line-num">32</td>
        <td>E032</td>
        <td>word</td>
        <td>egg</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.48</td>
        <td>0.48</td>
        <td>0.06</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɛɡ/</td>
        <td>[ɛɡ]</td>
        <td>ɛ-ɡ</td>
        <td>ɛ,ɡ</td>
        <td>ɡ</td>
        <td>ɛ</td>
        <td>ɡ</td>
        <td></td>
        <td>ɛ→ɡ</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>front_open_vowel → low_visibility_velar</td>
        <td>front_open_vowel,low_visibility_velar</td>
        <td>front_open_vowel→low_visibility_velar</td>
        <td>ɛ:front_open_vowel,ɡ:low_visibility_velar</td>
        <td>ɛ:front_open_vowel→ɡ:low_visibility_velar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.046511628</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.004201681</td>
        <td>0.1</td>
        <td>0.009174312</td>
        <td>0.004201681</td>
        <td>0.063792377</td>
        <td>0.054587156</td>
        <td>0.055992263</td>
        <td>0.132900786</td>
        <td>0.113723242</td>
        <td>0.116650549</td>
      </tr>
      <tr>
        <td class="line-num">33</td>
        <td>E033</td>
        <td>word</td>
        <td>orange</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.8</td>
        <td>0.8</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɔɹɪndʒ/</td>
        <td>[ɔɹɪndʒ]</td>
        <td>ɔɹ-ɪ-n-dʒ</td>
        <td>dʒ,n,ɔɹ,ɪ</td>
        <td>n,dʒ</td>
        <td>ɔɹ,ɪ</td>
        <td>dʒ</td>
        <td></td>
        <td>ɔɹ→ɪ,ɪ→n,n→dʒ</td>
        <td>ndʒ</td>
        <td>r_coloring</td>
        <td>ɔɹ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>rhotic_vowel → spread_vowel → coronal → postalveolar</td>
        <td>rhotic_vowel,spread_vowel,coronal,postalveolar</td>
        <td>rhotic_vowel→spread_vowel,spread_vowel→coronal,coronal→postalveolar</td>
        <td>ɔɹ:rhotic_vowel,ɪ:spread_vowel,n:coronal,dʒ:postalveolar</td>
        <td>ɔɹ:rhotic_vowel→ɪ:spread_vowel,ɪ:spread_vowel→n:coronal,n:coronal→dʒ:postalveolar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.111111111</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.154177058</td>
        <td>0.113761468</td>
        <td>0.131936739</td>
        <td>0.192721323</td>
        <td>0.142201835</td>
        <td>0.164920923</td>
      </tr>
      <tr>
        <td class="line-num">34</td>
        <td>E034</td>
        <td>word</td>
        <td>banana</td>
        <td>General American English</td>
        <td>3</td>
        <td>010</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;stress_alternation</td>
        <td>1.04</td>
        <td>1.04</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/bənænə/</td>
        <td>[bənænə]</td>
        <td>b-ə-n-æ-n-ə</td>
        <td>b,n,æ,ə</td>
        <td>b,n</td>
        <td>ə,æ</td>
        <td></td>
        <td></td>
        <td>b→ə,ə→n,n→æ,æ→n,n→ə</td>
        <td></td>
        <td>vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → neutral_vowel → coronal → open_vowel → coronal → neutral_vowel</td>
        <td>bilabial_closure,neutral_vowel,coronal,open_vowel</td>
        <td>bilabial_closure→neutral_vowel,neutral_vowel→coronal,coronal→open_vowel,open_vowel→coronal,coronal→neutral_vowel</td>
        <td>b:bilabial_closure,ə:neutral_vowel,n:coronal,æ:open_vowel,n:coronal,ə:neutral_vowel</td>
        <td>b:bilabial_closure→ə:neutral_vowel,ə:neutral_vowel→n:coronal,n:coronal→æ:open_vowel,æ:open_vowel→n:coronal,n:coronal→ə:neutral_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.021008403</td>
        <td>0.2</td>
        <td>0.04587156</td>
        <td>0.021008403</td>
        <td>0.141687062</td>
        <td>0.12293578</td>
        <td>0.12586894</td>
        <td>0.13623756</td>
        <td>0.118207481</td>
        <td>0.121027827</td>
      </tr>
      <tr>
        <td class="line-num">35</td>
        <td>E035</td>
        <td>word</td>
        <td>tomato</td>
        <td>General American English</td>
        <td>3</td>
        <td>010</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;stress_alternation</td>
        <td>1.04</td>
        <td>1.04</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/təmeɪtoʊ/</td>
        <td>[təmeɪɾoʊ]</td>
        <td>t-ə-m-eɪ-t-oʊ</td>
        <td>eɪ,m,oʊ,t,ə</td>
        <td>t,m</td>
        <td>ə,eɪ,oʊ</td>
        <td></td>
        <td></td>
        <td>t→ə,ə→m,m→eɪ,eɪ→t,t→oʊ</td>
        <td></td>
        <td>vowel_reduction;flapping</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → neutral_vowel → bilabial_closure → spread_vowel → coronal → rounded_vowel</td>
        <td>coronal,neutral_vowel,bilabial_closure,spread_vowel,rounded_vowel</td>
        <td>coronal→neutral_vowel,neutral_vowel→bilabial_closure,bilabial_closure→spread_vowel,spread_vowel→coronal,coronal→rounded_vowel</td>
        <td>t:coronal,ə:neutral_vowel,m:bilabial_closure,eɪ:spread_vowel,t:coronal,oʊ:rounded_vowel</td>
        <td>t:coronal→ə:neutral_vowel,ə:neutral_vowel→m:bilabial_closure,m:bilabial_closure→eɪ:spread_vowel,eɪ:spread_vowel→t:coronal,t:coronal→oʊ:rounded_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.021008403</td>
        <td>0.25</td>
        <td>0.04587156</td>
        <td>0.021008403</td>
        <td>0.160882337</td>
        <td>0.14793578</td>
        <td>0.144305633</td>
        <td>0.154694555</td>
        <td>0.142245942</td>
        <td>0.138755416</td>
      </tr>
      <tr>
        <td class="line-num">36</td>
        <td>E036</td>
        <td>word</td>
        <td>potato</td>
        <td>General American English</td>
        <td>3</td>
        <td>010</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;stress_alternation</td>
        <td>1.04</td>
        <td>1.04</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/pəteɪtoʊ/</td>
        <td>[pəteɪɾoʊ]</td>
        <td>p-ə-t-eɪ-t-oʊ</td>
        <td>eɪ,oʊ,p,t,ə</td>
        <td>p,t</td>
        <td>ə,eɪ,oʊ</td>
        <td></td>
        <td></td>
        <td>p→ə,ə→t,t→eɪ,eɪ→t,t→oʊ</td>
        <td></td>
        <td>vowel_reduction;flapping</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → neutral_vowel → coronal → spread_vowel → coronal → rounded_vowel</td>
        <td>bilabial_closure,neutral_vowel,coronal,spread_vowel,rounded_vowel</td>
        <td>bilabial_closure→neutral_vowel,neutral_vowel→coronal,coronal→spread_vowel,spread_vowel→coronal,coronal→rounded_vowel</td>
        <td>p:bilabial_closure,ə:neutral_vowel,t:coronal,eɪ:spread_vowel,t:coronal,oʊ:rounded_vowel</td>
        <td>p:bilabial_closure→ə:neutral_vowel,ə:neutral_vowel→t:coronal,t:coronal→eɪ:spread_vowel,eɪ:spread_vowel→t:coronal,t:coronal→oʊ:rounded_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.021008403</td>
        <td>0.25</td>
        <td>0.04587156</td>
        <td>0.021008403</td>
        <td>0.160882337</td>
        <td>0.14793578</td>
        <td>0.144305633</td>
        <td>0.154694555</td>
        <td>0.142245942</td>
        <td>0.138755416</td>
      </tr>
      <tr>
        <td class="line-num">37</td>
        <td>E037</td>
        <td>word</td>
        <td>coffee</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/kɔfi/</td>
        <td>[kɔfi]</td>
        <td>k-ɔ-f-i</td>
        <td>f,i,k,ɔ</td>
        <td>k,f</td>
        <td>ɔ,i</td>
        <td></td>
        <td></td>
        <td>k→ɔ,ɔ→f,f→i</td>
        <td></td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → rounded_open_vowel → labiodental → spread_vowel</td>
        <td>low_visibility_velar,rounded_open_vowel,labiodental,spread_vowel</td>
        <td>low_visibility_velar→rounded_open_vowel,rounded_open_vowel→labiodental,labiodental→spread_vowel</td>
        <td>k:low_visibility_velar,ɔ:rounded_open_vowel,f:labiodental,i:spread_vowel</td>
        <td>k:low_visibility_velar→ɔ:rounded_open_vowel,ɔ:rounded_open_vowel→f:labiodental,f:labiodental→i:spread_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.110327852</td>
        <td>0.113761468</td>
        <td>0.101242294</td>
        <td>0.145168226</td>
        <td>0.149686142</td>
        <td>0.133213545</td>
      </tr>
      <tr>
        <td class="line-num">38</td>
        <td>E038</td>
        <td>word</td>
        <td>teacher</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/tiːtʃɚ/</td>
        <td>[tiːtʃɚ]</td>
        <td>t-iː-tʃ-ɚ</td>
        <td>iː,t,tʃ,ɚ</td>
        <td>t,tʃ</td>
        <td>iː,ɚ</td>
        <td></td>
        <td></td>
        <td>t→iː,iː→tʃ,tʃ→ɚ</td>
        <td></td>
        <td>r_coloring</td>
        <td>ɚ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → spread_vowel → postalveolar → rhotic_vowel</td>
        <td>coronal,spread_vowel,postalveolar,rhotic_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→postalveolar,postalveolar→rhotic_vowel</td>
        <td>t:coronal,iː:spread_vowel,tʃ:postalveolar,ɚ:rhotic_vowel</td>
        <td>t:coronal→iː:spread_vowel,iː:spread_vowel→tʃ:postalveolar,tʃ:postalveolar→ɚ:rhotic_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.140486582</td>
        <td>0.113761468</td>
        <td>0.122353405</td>
        <td>0.184850766</td>
        <td>0.149686142</td>
        <td>0.160991323</td>
      </tr>
      <tr>
        <td class="line-num">39</td>
        <td>E039</td>
        <td>word</td>
        <td>student</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.8</td>
        <td>0.8</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/stuːdənt/</td>
        <td>[stuːdənt]</td>
        <td>s-t-uː-d-ə-n-t</td>
        <td>d,n,s,t,uː,ə</td>
        <td>s,t,d,n</td>
        <td>uː,ə</td>
        <td>t</td>
        <td></td>
        <td>s→t,t→uː,uː→d,d→ə,ə→n,n→t</td>
        <td>st</td>
        <td>vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → coronal → rounded_vowel → coronal → neutral_vowel → coronal → coronal</td>
        <td>coronal,rounded_vowel,neutral_vowel</td>
        <td>coronal→coronal,coronal→rounded_vowel,rounded_vowel→coronal,coronal→neutral_vowel,neutral_vowel→coronal,coronal→coronal</td>
        <td>s:coronal,t:coronal,uː:rounded_vowel,d:coronal,ə:neutral_vowel,n:coronal,t:coronal</td>
        <td>s:coronal→t:coronal,t:coronal→uː:rounded_vowel,uː:rounded_vowel→d:coronal,d:coronal→ə:neutral_vowel,ə:neutral_vowel→n:coronal,n:coronal→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.139534884</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.111111111</td>
        <td>0.025210084</td>
        <td>0.15</td>
        <td>0.04587156</td>
        <td>0.025210084</td>
        <td>0.162622297</td>
        <td>0.09793578</td>
        <td>0.135943772</td>
        <td>0.203277871</td>
        <td>0.122419725</td>
        <td>0.169929715</td>
      </tr>
      <tr>
        <td class="line-num">40</td>
        <td>E040</td>
        <td>word</td>
        <td>doctor</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.8</td>
        <td>0.8</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/dɔktɚ/</td>
        <td>[dɔktɚ]</td>
        <td>d-ɔ-k-t-ɚ</td>
        <td>d,k,t,ɔ,ɚ</td>
        <td>d,k,t</td>
        <td>ɔ,ɚ</td>
        <td></td>
        <td></td>
        <td>d→ɔ,ɔ→k,k→t,t→ɚ</td>
        <td>kt</td>
        <td>r_coloring</td>
        <td>ɚ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → rounded_open_vowel → low_visibility_velar → coronal → rhotic_vowel</td>
        <td>coronal,rounded_open_vowel,low_visibility_velar,rhotic_vowel</td>
        <td>coronal→rounded_open_vowel,rounded_open_vowel→low_visibility_velar,low_visibility_velar→coronal,coronal→rhotic_vowel</td>
        <td>d:coronal,ɔ:rounded_open_vowel,k:low_visibility_velar,t:coronal,ɚ:rhotic_vowel</td>
        <td>d:coronal→ɔ:rounded_open_vowel,ɔ:rounded_open_vowel→k:low_visibility_velar,k:low_visibility_velar→t:coronal,t:coronal→ɚ:rhotic_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.111111111</td>
        <td>0.016806723</td>
        <td>0.2</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.149170986</td>
        <td>0.118348624</td>
        <td>0.129770087</td>
        <td>0.186463733</td>
        <td>0.14793578</td>
        <td>0.162212609</td>
      </tr>
      <tr>
        <td class="line-num">41</td>
        <td>E041</td>
        <td>word</td>
        <td>singer</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/sɪŋɚ/</td>
        <td>[sɪŋɚ]</td>
        <td>s-ɪ-ŋ-ɚ</td>
        <td>s,ŋ,ɚ,ɪ</td>
        <td>s,ŋ</td>
        <td>ɪ,ɚ</td>
        <td></td>
        <td></td>
        <td>s→ɪ,ɪ→ŋ,ŋ→ɚ</td>
        <td></td>
        <td>r_coloring</td>
        <td>ɚ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → spread_vowel → low_visibility_velar → rhotic_vowel</td>
        <td>coronal,spread_vowel,low_visibility_velar,rhotic_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→rhotic_vowel</td>
        <td>s:coronal,ɪ:spread_vowel,ŋ:low_visibility_velar,ɚ:rhotic_vowel</td>
        <td>s:coronal→ɪ:spread_vowel,ɪ:spread_vowel→ŋ:low_visibility_velar,ŋ:low_visibility_velar→ɚ:rhotic_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.140486582</td>
        <td>0.113761468</td>
        <td>0.122353405</td>
        <td>0.184850766</td>
        <td>0.149686142</td>
        <td>0.160991323</td>
      </tr>
      <tr>
        <td class="line-num">42</td>
        <td>E042</td>
        <td>word</td>
        <td>music</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.8</td>
        <td>0.8</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/mjuːzɪk/</td>
        <td>[mjuːzɪk]</td>
        <td>m-j-uː-z-ɪ-k</td>
        <td>j,k,m,uː,z,ɪ</td>
        <td>m,j,z,k</td>
        <td>uː,ɪ</td>
        <td>k</td>
        <td></td>
        <td>m→j,j→uː,uː→z,z→ɪ,ɪ→k</td>
        <td>mj</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → palatal_glide → rounded_vowel → coronal → spread_vowel → low_visibility_velar</td>
        <td>bilabial_closure,palatal_glide,rounded_vowel,coronal,spread_vowel,low_visibility_velar</td>
        <td>bilabial_closure→palatal_glide,palatal_glide→rounded_vowel,rounded_vowel→coronal,coronal→spread_vowel,spread_vowel→low_visibility_velar</td>
        <td>m:bilabial_closure,j:palatal_glide,uː:rounded_vowel,z:coronal,ɪ:spread_vowel,k:low_visibility_velar</td>
        <td>m:bilabial_closure→j:palatal_glide,j:palatal_glide→uː:rounded_vowel,uː:rounded_vowel→z:coronal,z:coronal→ɪ:spread_vowel,ɪ:spread_vowel→k:low_visibility_velar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.139534884</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.021008403</td>
        <td>0.3</td>
        <td>0.04587156</td>
        <td>0.021008403</td>
        <td>0.131863327</td>
        <td>0.17293578</td>
        <td>0.128992325</td>
        <td>0.164829158</td>
        <td>0.216169725</td>
        <td>0.161240406</td>
      </tr>
      <tr>
        <td class="line-num">43</td>
        <td>E043</td>
        <td>word</td>
        <td>paper</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/peɪpɚ/</td>
        <td>[peɪpɚ]</td>
        <td>p-eɪ-p-ɚ</td>
        <td>eɪ,p,ɚ</td>
        <td>p</td>
        <td>eɪ,ɚ</td>
        <td></td>
        <td></td>
        <td>p→eɪ,eɪ→p,p→ɚ</td>
        <td></td>
        <td>aspiration;r_coloring</td>
        <td>ɚ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → spread_vowel → bilabial_closure → rhotic_vowel</td>
        <td>bilabial_closure,spread_vowel,rhotic_vowel</td>
        <td>bilabial_closure→spread_vowel,spread_vowel→bilabial_closure,bilabial_closure→rhotic_vowel</td>
        <td>p:bilabial_closure,eɪ:spread_vowel,p:bilabial_closure,ɚ:rhotic_vowel</td>
        <td>p:bilabial_closure→eɪ:spread_vowel,eɪ:spread_vowel→p:bilabial_closure,p:bilabial_closure→ɚ:rhotic_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.012605042</td>
        <td>0.15</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.153037339</td>
        <td>0.088761468</td>
        <td>0.126138935</td>
        <td>0.20136492</td>
        <td>0.116791405</td>
        <td>0.165972283</td>
      </tr>
      <tr>
        <td class="line-num">44</td>
        <td>E044</td>
        <td>word</td>
        <td>pencil</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.8</td>
        <td>0.8</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/pɛnsəl/</td>
        <td>[pɛnsəl]</td>
        <td>p-ɛ-n-s-ə-l</td>
        <td>l,n,p,s,ə,ɛ</td>
        <td>p,n,s,l</td>
        <td>ɛ,ə</td>
        <td>l</td>
        <td></td>
        <td>p→ɛ,ɛ→n,n→s,s→ə,ə→l</td>
        <td>ns</td>
        <td>vowel_reduction;dark_l</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → front_open_vowel → coronal → coronal → neutral_vowel → coronal</td>
        <td>bilabial_closure,front_open_vowel,coronal,neutral_vowel</td>
        <td>bilabial_closure→front_open_vowel,front_open_vowel→coronal,coronal→coronal,coronal→neutral_vowel,neutral_vowel→coronal</td>
        <td>p:bilabial_closure,ɛ:front_open_vowel,n:coronal,s:coronal,ə:neutral_vowel,l:coronal</td>
        <td>p:bilabial_closure→ɛ:front_open_vowel,ɛ:front_open_vowel→n:coronal,n:coronal→s:coronal,s:coronal→ə:neutral_vowel,ə:neutral_vowel→l:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.139534884</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.222222222</td>
        <td>0.021008403</td>
        <td>0.2</td>
        <td>0.04587156</td>
        <td>0.021008403</td>
        <td>0.177895073</td>
        <td>0.12293578</td>
        <td>0.151214547</td>
        <td>0.222368841</td>
        <td>0.153669725</td>
        <td>0.189018184</td>
      </tr>
      <tr>
        <td class="line-num">45</td>
        <td>E045</td>
        <td>word</td>
        <td>window</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.8</td>
        <td>0.8</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/wɪndoʊ/</td>
        <td>[wɪndoʊ]</td>
        <td>w-ɪ-n-d-oʊ</td>
        <td>d,n,oʊ,w,ɪ</td>
        <td>w,n,d</td>
        <td>ɪ,oʊ</td>
        <td></td>
        <td></td>
        <td>w→ɪ,ɪ→n,n→d,d→oʊ</td>
        <td>nd</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>rounded_glide → spread_vowel → coronal → coronal → rounded_vowel</td>
        <td>rounded_glide,spread_vowel,coronal,rounded_vowel</td>
        <td>rounded_glide→spread_vowel,spread_vowel→coronal,coronal→coronal,coronal→rounded_vowel</td>
        <td>w:rounded_glide,ɪ:spread_vowel,n:coronal,d:coronal,oʊ:rounded_vowel</td>
        <td>w:rounded_glide→ɪ:spread_vowel,ɪ:spread_vowel→n:coronal,n:coronal→d:coronal,d:coronal→oʊ:rounded_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.016806723</td>
        <td>0.2</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.119012256</td>
        <td>0.118348624</td>
        <td>0.108658976</td>
        <td>0.14876532</td>
        <td>0.14793578</td>
        <td>0.13582372</td>
      </tr>
      <tr>
        <td class="line-num">46</td>
        <td>E046</td>
        <td>word</td>
        <td>garden</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɡɑɹdən/</td>
        <td>[ɡɑɹdən]</td>
        <td>ɡ-ɑɹ-d-ə-n</td>
        <td>d,n,ɑɹ,ə,ɡ</td>
        <td>ɡ,d,n</td>
        <td>ɑɹ,ə</td>
        <td>n</td>
        <td></td>
        <td>ɡ→ɑɹ,ɑɹ→d,d→ə,ə→n</td>
        <td></td>
        <td>vowel_reduction;r_coloring</td>
        <td>ɑɹ;ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → rhotic_vowel → coronal → neutral_vowel → coronal</td>
        <td>low_visibility_velar,rhotic_vowel,coronal,neutral_vowel</td>
        <td>low_visibility_velar→rhotic_vowel,rhotic_vowel→coronal,coronal→neutral_vowel,neutral_vowel→coronal</td>
        <td>ɡ:low_visibility_velar,ɑɹ:rhotic_vowel,d:coronal,ə:neutral_vowel,n:coronal</td>
        <td>ɡ:low_visibility_velar→ɑɹ:rhotic_vowel,ɑɹ:rhotic_vowel→d:coronal,d:coronal→ə:neutral_vowel,ə:neutral_vowel→n:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0.2</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.016806723</td>
        <td>0.2</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.183496383</td>
        <td>0.118348624</td>
        <td>0.153797865</td>
        <td>0.241442609</td>
        <td>0.155721873</td>
        <td>0.202365612</td>
      </tr>
      <tr>
        <td class="line-num">47</td>
        <td>E047</td>
        <td>word</td>
        <td>button</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/bʌtən/</td>
        <td>[bʌʔən]</td>
        <td>b-ʌ-t-ə-n</td>
        <td>b,n,t,ə,ʌ</td>
        <td>b,t,n</td>
        <td>ʌ,ə</td>
        <td>n</td>
        <td></td>
        <td>b→ʌ,ʌ→t,t→ə,ə→n</td>
        <td></td>
        <td>glottalization;vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → central_open_vowel → coronal → neutral_vowel → coronal</td>
        <td>bilabial_closure,central_open_vowel,coronal,neutral_vowel</td>
        <td>bilabial_closure→central_open_vowel,central_open_vowel→coronal,coronal→neutral_vowel,neutral_vowel→coronal</td>
        <td>b:bilabial_closure,ʌ:central_open_vowel,t:coronal,ə:neutral_vowel,n:coronal</td>
        <td>b:bilabial_closure→ʌ:central_open_vowel,ʌ:central_open_vowel→t:coronal,t:coronal→ə:neutral_vowel,ə:neutral_vowel→n:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.016806723</td>
        <td>0.2</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.169210669</td>
        <td>0.118348624</td>
        <td>0.143797865</td>
        <td>0.222645617</td>
        <td>0.155721873</td>
        <td>0.189207717</td>
      </tr>
      <tr>
        <td class="line-num">48</td>
        <td>E048</td>
        <td>word</td>
        <td>little</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/lɪtəl/</td>
        <td>[lɪɾəl]</td>
        <td>l-ɪ-t-ə-l</td>
        <td>l,t,ə,ɪ</td>
        <td>l,t</td>
        <td>ɪ,ə</td>
        <td>l</td>
        <td></td>
        <td>l→ɪ,ɪ→t,t→ə,ə→l</td>
        <td></td>
        <td>flapping;vowel_reduction;dark_l</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → spread_vowel → coronal → neutral_vowel → coronal</td>
        <td>coronal,spread_vowel,neutral_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→coronal,coronal→neutral_vowel,neutral_vowel→coronal</td>
        <td>l:coronal,ɪ:spread_vowel,t:coronal,ə:neutral_vowel,l:coronal</td>
        <td>l:coronal→ɪ:spread_vowel,ɪ:spread_vowel→t:coronal,t:coronal→ə:neutral_vowel,ə:neutral_vowel→l:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.333333333</td>
        <td>0.016806723</td>
        <td>0.15</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.181761426</td>
        <td>0.093348624</td>
        <td>0.147583395</td>
        <td>0.23915977</td>
        <td>0.122827137</td>
        <td>0.194188677</td>
      </tr>
      <tr>
        <td class="line-num">49</td>
        <td>E049</td>
        <td>word</td>
        <td>city</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/sɪti/</td>
        <td>[sɪɾi]</td>
        <td>s-ɪ-t-i</td>
        <td>i,s,t,ɪ</td>
        <td>s,t</td>
        <td>ɪ,i</td>
        <td></td>
        <td></td>
        <td>s→ɪ,ɪ→t,t→i</td>
        <td></td>
        <td>flapping</td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → spread_vowel → coronal → spread_vowel</td>
        <td>coronal,spread_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→coronal,coronal→spread_vowel</td>
        <td>s:coronal,ɪ:spread_vowel,t:coronal,i:spread_vowel</td>
        <td>s:coronal→ɪ:spread_vowel,ɪ:spread_vowel→t:coronal,t:coronal→i:spread_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.012605042</td>
        <td>0.1</td>
        <td>0.018348624</td>
        <td>0.012605042</td>
        <td>0.126200868</td>
        <td>0.059174312</td>
        <td>0.101435974</td>
        <td>0.166053774</td>
        <td>0.077860937</td>
        <td>0.133468387</td>
      </tr>
      <tr>
        <td class="line-num">50</td>
        <td>E050</td>
        <td>word</td>
        <td>better</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/bɛtɚ/</td>
        <td>[bɛɾɚ]</td>
        <td>b-ɛ-t-ɚ</td>
        <td>b,t,ɚ,ɛ</td>
        <td>b,t</td>
        <td>ɛ,ɚ</td>
        <td></td>
        <td></td>
        <td>b→ɛ,ɛ→t,t→ɚ</td>
        <td></td>
        <td>flapping;r_coloring</td>
        <td>ɚ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → front_open_vowel → coronal → rhotic_vowel</td>
        <td>bilabial_closure,front_open_vowel,coronal,rhotic_vowel</td>
        <td>bilabial_closure→front_open_vowel,front_open_vowel→coronal,coronal→rhotic_vowel</td>
        <td>b:bilabial_closure,ɛ:front_open_vowel,t:coronal,ɚ:rhotic_vowel</td>
        <td>b:bilabial_closure→ɛ:front_open_vowel,ɛ:front_open_vowel→t:coronal,t:coronal→ɚ:rhotic_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.156359598</td>
        <td>0.113761468</td>
        <td>0.133464516</td>
        <td>0.205736313</td>
        <td>0.149686142</td>
        <td>0.175611206</td>
      </tr>
      <tr>
        <td class="line-num">51</td>
        <td>E051</td>
        <td>word</td>
        <td>writer</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɹaɪtɚ/</td>
        <td>[ɹaɪɾɚ]</td>
        <td>ɹ-aɪ-t-ɚ</td>
        <td>aɪ,t,ɚ,ɹ</td>
        <td>ɹ,t</td>
        <td>aɪ,ɚ</td>
        <td></td>
        <td></td>
        <td>ɹ→aɪ,aɪ→t,t→ɚ</td>
        <td></td>
        <td>flapping;r_coloring</td>
        <td>ɚ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>rhotic → open_to_spread → coronal → rhotic_vowel</td>
        <td>rhotic,open_to_spread,coronal,rhotic_vowel</td>
        <td>rhotic→open_to_spread,open_to_spread→coronal,coronal→rhotic_vowel</td>
        <td>ɹ:rhotic,aɪ:open_to_spread,t:coronal,ɚ:rhotic_vowel</td>
        <td>ɹ:rhotic→aɪ:open_to_spread,aɪ:open_to_spread→t:coronal,t:coronal→ɚ:rhotic_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.156359598</td>
        <td>0.113761468</td>
        <td>0.133464516</td>
        <td>0.205736313</td>
        <td>0.149686142</td>
        <td>0.175611206</td>
      </tr>
      <tr>
        <td class="line-num">52</td>
        <td>E052</td>
        <td>word</td>
        <td>winter</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.8</td>
        <td>0.8</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/wɪntɚ/</td>
        <td>[wɪntɚ]</td>
        <td>w-ɪ-n-t-ɚ</td>
        <td>n,t,w,ɚ,ɪ</td>
        <td>w,n,t</td>
        <td>ɪ,ɚ</td>
        <td></td>
        <td></td>
        <td>w→ɪ,ɪ→n,n→t,t→ɚ</td>
        <td>nt</td>
        <td>r_coloring</td>
        <td>ɚ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>rounded_glide → spread_vowel → coronal → coronal → rhotic_vowel</td>
        <td>rounded_glide,spread_vowel,coronal,rhotic_vowel</td>
        <td>rounded_glide→spread_vowel,spread_vowel→coronal,coronal→coronal,coronal→rhotic_vowel</td>
        <td>w:rounded_glide,ɪ:spread_vowel,n:coronal,t:coronal,ɚ:rhotic_vowel</td>
        <td>w:rounded_glide→ɪ:spread_vowel,ɪ:spread_vowel→n:coronal,n:coronal→t:coronal,t:coronal→ɚ:rhotic_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.111111111</td>
        <td>0.016806723</td>
        <td>0.2</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.149170986</td>
        <td>0.118348624</td>
        <td>0.129770087</td>
        <td>0.186463733</td>
        <td>0.14793578</td>
        <td>0.162212609</td>
      </tr>
      <tr>
        <td class="line-num">53</td>
        <td>E053</td>
        <td>word</td>
        <td>spring</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/spɹɪŋ/</td>
        <td>[spɹɪŋ]</td>
        <td>s-p-ɹ-ɪ-ŋ</td>
        <td>p,s,ŋ,ɪ,ɹ</td>
        <td>s,p,ɹ,ŋ</td>
        <td>ɪ</td>
        <td>ŋ</td>
        <td></td>
        <td>s→p,p→ɹ,ɹ→ɪ,ɪ→ŋ</td>
        <td>spɹ</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → bilabial_closure → rhotic → spread_vowel → low_visibility_velar</td>
        <td>coronal,bilabial_closure,rhotic,spread_vowel,low_visibility_velar</td>
        <td>coronal→bilabial_closure,bilabial_closure→rhotic,rhotic→spread_vowel,spread_vowel→low_visibility_velar</td>
        <td>s:coronal,p:bilabial_closure,ɹ:rhotic,ɪ:spread_vowel,ŋ:low_visibility_velar</td>
        <td>s:coronal→p:bilabial_closure,p:bilabial_closure→ɹ:rhotic,ɹ:rhotic→ɪ:spread_vowel,ɪ:spread_vowel→ŋ:low_visibility_velar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.016806723</td>
        <td>0.25</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.08032178</td>
        <td>0.143348624</td>
        <td>0.086575643</td>
        <td>0.154464961</td>
        <td>0.27567043</td>
        <td>0.166491621</td>
      </tr>
      <tr>
        <td class="line-num">54</td>
        <td>E054</td>
        <td>word</td>
        <td>street</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/stɹiːt/</td>
        <td>[stɹiːt]</td>
        <td>s-t-ɹ-iː-t</td>
        <td>iː,s,t,ɹ</td>
        <td>s,t,ɹ</td>
        <td>iː</td>
        <td>t</td>
        <td></td>
        <td>s→t,t→ɹ,ɹ→iː,iː→t</td>
        <td>stɹ</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → coronal → rhotic → spread_vowel → coronal</td>
        <td>coronal,rhotic,spread_vowel</td>
        <td>coronal→coronal,coronal→rhotic,rhotic→spread_vowel,spread_vowel→coronal</td>
        <td>s:coronal,t:coronal,ɹ:rhotic,iː:spread_vowel,t:coronal</td>
        <td>s:coronal→t:coronal,t:coronal→ɹ:rhotic,ɹ:rhotic→iː:spread_vowel,iː:spread_vowel→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.016806723</td>
        <td>0.15</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.076999521</td>
        <td>0.093348624</td>
        <td>0.074250062</td>
        <td>0.148076001</td>
        <td>0.179516584</td>
        <td>0.14278858</td>
      </tr>
      <tr>
        <td class="line-num">55</td>
        <td>E055</td>
        <td>word</td>
        <td>strong</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/stɹɔŋ/</td>
        <td>[stɹɔŋ]</td>
        <td>s-t-ɹ-ɔ-ŋ</td>
        <td>s,t,ŋ,ɔ,ɹ</td>
        <td>s,t,ɹ,ŋ</td>
        <td>ɔ</td>
        <td>ŋ</td>
        <td></td>
        <td>s→t,t→ɹ,ɹ→ɔ,ɔ→ŋ</td>
        <td>stɹ</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → coronal → rhotic → rounded_open_vowel → low_visibility_velar</td>
        <td>coronal,rhotic,rounded_open_vowel,low_visibility_velar</td>
        <td>coronal→coronal,coronal→rhotic,rhotic→rounded_open_vowel,rounded_open_vowel→low_visibility_velar</td>
        <td>s:coronal,t:coronal,ɹ:rhotic,ɔ:rounded_open_vowel,ŋ:low_visibility_velar</td>
        <td>s:coronal→t:coronal,t:coronal→ɹ:rhotic,ɹ:rhotic→ɔ:rounded_open_vowel,ɔ:rounded_open_vowel→ŋ:low_visibility_velar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.016806723</td>
        <td>0.2</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.08032178</td>
        <td>0.118348624</td>
        <td>0.081575643</td>
        <td>0.154464961</td>
        <td>0.227593507</td>
        <td>0.156876236</td>
      </tr>
      <tr>
        <td class="line-num">56</td>
        <td>E056</td>
        <td>word</td>
        <td>world</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/wɝld/</td>
        <td>[wɝld]</td>
        <td>w-ɝ-l-d</td>
        <td>d,l,w,ɝ</td>
        <td>w,l,d</td>
        <td>ɝ</td>
        <td>d</td>
        <td></td>
        <td>w→ɝ,ɝ→l,l→d</td>
        <td>ld</td>
        <td>r_coloring;dark_l</td>
        <td>ɝ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>rounded_glide → rhotic_vowel → coronal → coronal</td>
        <td>rounded_glide,rhotic_vowel,coronal</td>
        <td>rounded_glide→rhotic_vowel,rhotic_vowel→coronal,coronal→coronal</td>
        <td>w:rounded_glide,ɝ:rhotic_vowel,l:coronal,d:coronal</td>
        <td>w:rounded_glide→ɝ:rhotic_vowel,ɝ:rhotic_vowel→l:coronal,l:coronal→d:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.222222222</td>
        <td>0.012605042</td>
        <td>0.15</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.122431027</td>
        <td>0.088761468</td>
        <td>0.104714516</td>
        <td>0.235444282</td>
        <td>0.170695131</td>
        <td>0.20137407</td>
      </tr>
      <tr>
        <td class="line-num">57</td>
        <td>E057</td>
        <td>word</td>
        <td>help</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/hɛlp/</td>
        <td>[hɛlp]</td>
        <td>h-ɛ-l-p</td>
        <td>h,l,p,ɛ</td>
        <td>h,l,p</td>
        <td>ɛ</td>
        <td>p</td>
        <td></td>
        <td>h→ɛ,ɛ→l,l→p</td>
        <td>lp</td>
        <td>dark_l</td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>glottal → front_open_vowel → coronal → bilabial_closure</td>
        <td>glottal,front_open_vowel,coronal,bilabial_closure</td>
        <td>glottal→front_open_vowel,front_open_vowel→coronal,coronal→bilabial_closure</td>
        <td>h:glottal,ɛ:front_open_vowel,l:coronal,p:bilabial_closure</td>
        <td>h:glottal→ɛ:front_open_vowel,ɛ:front_open_vowel→l:coronal,l:coronal→p:bilabial_closure</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0.111111111</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.092272297</td>
        <td>0.113761468</td>
        <td>0.088603405</td>
        <td>0.177446724</td>
        <td>0.218772054</td>
        <td>0.170391164</td>
      </tr>
      <tr>
        <td class="line-num">58</td>
        <td>E058</td>
        <td>word</td>
        <td>desk</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/dɛsk/</td>
        <td>[dɛsk]</td>
        <td>d-ɛ-s-k</td>
        <td>d,k,s,ɛ</td>
        <td>d,s,k</td>
        <td>ɛ</td>
        <td>k</td>
        <td></td>
        <td>d→ɛ,ɛ→s,s→k</td>
        <td>sk</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → front_open_vowel → coronal → low_visibility_velar</td>
        <td>coronal,front_open_vowel,low_visibility_velar</td>
        <td>coronal→front_open_vowel,front_open_vowel→coronal,coronal→low_visibility_velar</td>
        <td>d:coronal,ɛ:front_open_vowel,s:coronal,k:low_visibility_velar</td>
        <td>d:coronal→ɛ:front_open_vowel,ɛ:front_open_vowel→s:coronal,s:coronal→k:low_visibility_velar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.012605042</td>
        <td>0.15</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.076399281</td>
        <td>0.088761468</td>
        <td>0.072492294</td>
        <td>0.146921694</td>
        <td>0.170695131</td>
        <td>0.139408258</td>
      </tr>
      <tr>
        <td class="line-num">59</td>
        <td>E059</td>
        <td>word</td>
        <td>next</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/nɛkst/</td>
        <td>[nɛkst]</td>
        <td>n-ɛ-k-s-t</td>
        <td>k,n,s,t,ɛ</td>
        <td>n,k,s,t</td>
        <td>ɛ</td>
        <td>t</td>
        <td></td>
        <td>n→ɛ,ɛ→k,k→s,s→t</td>
        <td>kst</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → front_open_vowel → low_visibility_velar → coronal → coronal</td>
        <td>coronal,front_open_vowel,low_visibility_velar</td>
        <td>coronal→front_open_vowel,front_open_vowel→low_visibility_velar,low_visibility_velar→coronal,coronal→coronal</td>
        <td>n:coronal,ɛ:front_open_vowel,k:low_visibility_velar,s:coronal,t:coronal</td>
        <td>n:coronal→ɛ:front_open_vowel,ɛ:front_open_vowel→k:low_visibility_velar,k:low_visibility_velar→s:coronal,s:coronal→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.016806723</td>
        <td>0.15</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.08032178</td>
        <td>0.093348624</td>
        <td>0.076575643</td>
        <td>0.154464961</td>
        <td>0.179516584</td>
        <td>0.147260852</td>
      </tr>
      <tr>
        <td class="line-num">60</td>
        <td>E060</td>
        <td>word</td>
        <td>asked</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/æskt/</td>
        <td>[æskt]</td>
        <td>æ-s-k-t</td>
        <td>k,s,t,æ</td>
        <td>s,k,t</td>
        <td>æ</td>
        <td>t</td>
        <td></td>
        <td>æ→s,s→k,k→t</td>
        <td>skt</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>open_vowel → coronal → low_visibility_velar → coronal</td>
        <td>open_vowel,coronal,low_visibility_velar</td>
        <td>open_vowel→coronal,coronal→low_visibility_velar,low_visibility_velar→coronal</td>
        <td>æ:open_vowel,s:coronal,k:low_visibility_velar,t:coronal</td>
        <td>æ:open_vowel→s:coronal,s:coronal→k:low_visibility_velar,k:low_visibility_velar→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.012605042</td>
        <td>0.15</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.076399281</td>
        <td>0.088761468</td>
        <td>0.072492294</td>
        <td>0.146921694</td>
        <td>0.170695131</td>
        <td>0.139408258</td>
      </tr>
      <tr>
        <td class="line-num">61</td>
        <td>E061</td>
        <td>word</td>
        <td>sixth</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/sɪksθ/</td>
        <td>[sɪksθ]</td>
        <td>s-ɪ-k-s-θ</td>
        <td>k,s,ɪ,θ</td>
        <td>s,k,θ</td>
        <td>ɪ</td>
        <td>θ</td>
        <td></td>
        <td>s→ɪ,ɪ→k,k→s,s→θ</td>
        <td>ksθ</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → spread_vowel → low_visibility_velar → coronal → dental</td>
        <td>coronal,spread_vowel,low_visibility_velar,dental</td>
        <td>coronal→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→coronal,coronal→dental</td>
        <td>s:coronal,ɪ:spread_vowel,k:low_visibility_velar,s:coronal,θ:dental</td>
        <td>s:coronal→ɪ:spread_vowel,ɪ:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→s:coronal,s:coronal→θ:dental</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.016806723</td>
        <td>0.2</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.076999521</td>
        <td>0.118348624</td>
        <td>0.079250062</td>
        <td>0.148076001</td>
        <td>0.227593507</td>
        <td>0.152403965</td>
      </tr>
      <tr>
        <td class="line-num">62</td>
        <td>E062</td>
        <td>word</td>
        <td>texts</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/tɛksts/</td>
        <td>[tɛksts]</td>
        <td>t-ɛ-k-s-t-s</td>
        <td>k,s,t,ɛ</td>
        <td>t,k,s</td>
        <td>ɛ</td>
        <td>s</td>
        <td></td>
        <td>t→ɛ,ɛ→k,k→s,s→t,t→s</td>
        <td>ksts</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → front_open_vowel → low_visibility_velar → coronal → coronal → coronal</td>
        <td>coronal,front_open_vowel,low_visibility_velar</td>
        <td>coronal→front_open_vowel,front_open_vowel→low_visibility_velar,low_visibility_velar→coronal,coronal→coronal,coronal→coronal</td>
        <td>t:coronal,ɛ:front_open_vowel,k:low_visibility_velar,s:coronal,t:coronal,s:coronal</td>
        <td>t:coronal→ɛ:front_open_vowel,ɛ:front_open_vowel→k:low_visibility_velar,k:low_visibility_velar→s:coronal,s:coronal→t:coronal,t:coronal→s:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.021008403</td>
        <td>0.15</td>
        <td>0.036697248</td>
        <td>0.021008403</td>
        <td>0.077599761</td>
        <td>0.093348624</td>
        <td>0.075090398</td>
        <td>0.149230309</td>
        <td>0.179516584</td>
        <td>0.144404611</td>
      </tr>
      <tr>
        <td class="line-num">63</td>
        <td>E063</td>
        <td>word</td>
        <td>blue</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/bluː/</td>
        <td>[bluː]</td>
        <td>b-l-uː</td>
        <td>b,l,uː</td>
        <td>b,l</td>
        <td>uː</td>
        <td></td>
        <td></td>
        <td>b→l,l→uː</td>
        <td>bl</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → coronal → rounded_vowel</td>
        <td>bilabial_closure,coronal,rounded_vowel</td>
        <td>bilabial_closure→coronal,coronal→rounded_vowel</td>
        <td>b:bilabial_closure,l:coronal,uː:rounded_vowel</td>
        <td>b:bilabial_closure→l:coronal,l:coronal→uː:rounded_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.06354821</td>
        <td>0.084174312</td>
        <td>0.062158946</td>
        <td>0.122208096</td>
        <td>0.161873677</td>
        <td>0.119536434</td>
      </tr>
      <tr>
        <td class="line-num">64</td>
        <td>E064</td>
        <td>word</td>
        <td>green</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɡɹiːn/</td>
        <td>[ɡɹiːn]</td>
        <td>ɡ-ɹ-iː-n</td>
        <td>iː,n,ɡ,ɹ</td>
        <td>ɡ,ɹ,n</td>
        <td>iː</td>
        <td>n</td>
        <td></td>
        <td>ɡ→ɹ,ɹ→iː,iː→n</td>
        <td>ɡɹ</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → rhotic → spread_vowel → coronal</td>
        <td>low_visibility_velar,rhotic,spread_vowel,coronal</td>
        <td>low_visibility_velar→rhotic,rhotic→spread_vowel,spread_vowel→coronal</td>
        <td>ɡ:low_visibility_velar,ɹ:rhotic,iː:spread_vowel,n:coronal</td>
        <td>ɡ:low_visibility_velar→ɹ:rhotic,ɹ:rhotic→iː:spread_vowel,iː:spread_vowel→n:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.076399281</td>
        <td>0.113761468</td>
        <td>0.077492294</td>
        <td>0.146921694</td>
        <td>0.218772054</td>
        <td>0.149023643</td>
      </tr>
      <tr>
        <td class="line-num">65</td>
        <td>E065</td>
        <td>word</td>
        <td>brown</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/bɹaʊn/</td>
        <td>[bɹaʊn]</td>
        <td>b-ɹ-aʊ-n</td>
        <td>aʊ,b,n,ɹ</td>
        <td>b,ɹ,n</td>
        <td>aʊ</td>
        <td>n</td>
        <td></td>
        <td>b→ɹ,ɹ→aʊ,aʊ→n</td>
        <td>bɹ</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → rhotic → open_to_rounded → coronal</td>
        <td>bilabial_closure,rhotic,open_to_rounded,coronal</td>
        <td>bilabial_closure→rhotic,rhotic→open_to_rounded,open_to_rounded→coronal</td>
        <td>b:bilabial_closure,ɹ:rhotic,aʊ:open_to_rounded,n:coronal</td>
        <td>b:bilabial_closure→ɹ:rhotic,ɹ:rhotic→aʊ:open_to_rounded,aʊ:open_to_rounded→n:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.076399281</td>
        <td>0.113761468</td>
        <td>0.077492294</td>
        <td>0.146921694</td>
        <td>0.218772054</td>
        <td>0.149023643</td>
      </tr>
      <tr>
        <td class="line-num">66</td>
        <td>E066</td>
        <td>word</td>
        <td>quick</td>
        <td>General American English</td>
        <td>1</td>
        <td>1</td>
        <td>has_primary_stress;initial_primary_stress</td>
        <td>0.52</td>
        <td>0.52</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/kwɪk/</td>
        <td>[kwɪk]</td>
        <td>k-w-ɪ-k</td>
        <td>k,w,ɪ</td>
        <td>k,w</td>
        <td>ɪ</td>
        <td>k</td>
        <td></td>
        <td>k→w,w→ɪ,ɪ→k</td>
        <td>kw</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → rounded_glide → spread_vowel → low_visibility_velar</td>
        <td>low_visibility_velar,rounded_glide,spread_vowel</td>
        <td>low_visibility_velar→rounded_glide,rounded_glide→spread_vowel,spread_vowel→low_visibility_velar</td>
        <td>k:low_visibility_velar,w:rounded_glide,ɪ:spread_vowel,k:low_visibility_velar</td>
        <td>k:low_visibility_velar→w:rounded_glide,w:rounded_glide→ɪ:spread_vowel,ɪ:spread_vowel→k:low_visibility_velar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0.0625</td>
        <td>0.333333333</td>
        <td>0</td>
        <td>0.033333333</td>
        <td>0</td>
        <td>0.012605042</td>
        <td>0.15</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.073077022</td>
        <td>0.088761468</td>
        <td>0.070166713</td>
        <td>0.140532734</td>
        <td>0.170695131</td>
        <td>0.134935986</td>
      </tr>
      <tr>
        <td class="line-num">67</td>
        <td>E067</td>
        <td>word</td>
        <td>quiet</td>
        <td>General American English</td>
        <td>2</td>
        <td>10</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>0.8</td>
        <td>0.8</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/kwaɪət/</td>
        <td>[kwaɪət]</td>
        <td>k-w-aɪ-ə-t</td>
        <td>aɪ,k,t,w,ə</td>
        <td>k,w,t</td>
        <td>aɪ,ə</td>
        <td>t</td>
        <td></td>
        <td>k→w,w→aɪ,aɪ→ə,ə→t</td>
        <td>kw</td>
        <td>vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → rounded_glide → open_to_spread → neutral_vowel → coronal</td>
        <td>low_visibility_velar,rounded_glide,open_to_spread,neutral_vowel,coronal</td>
        <td>low_visibility_velar→rounded_glide,rounded_glide→open_to_spread,open_to_spread→neutral_vowel,neutral_vowel→coronal</td>
        <td>k:low_visibility_velar,w:rounded_glide,aɪ:open_to_spread,ə:neutral_vowel,t:coronal</td>
        <td>k:low_visibility_velar→w:rounded_glide,w:rounded_glide→aɪ:open_to_spread,aɪ:open_to_spread→ə:neutral_vowel,ə:neutral_vowel→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.111111111</td>
        <td>0.016806723</td>
        <td>0.25</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.158099558</td>
        <td>0.143348624</td>
        <td>0.141020087</td>
        <td>0.197624447</td>
        <td>0.17918578</td>
        <td>0.176275109</td>
      </tr>
      <tr>
        <td class="line-num">68</td>
        <td>E068</td>
        <td>word</td>
        <td>around</td>
        <td>General American English</td>
        <td>2</td>
        <td>01</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;stress_alternation</td>
        <td>0.8</td>
        <td>0.8</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/əɹaʊnd/</td>
        <td>[əɹaʊnd]</td>
        <td>ə-ɹ-aʊ-n-d</td>
        <td>aʊ,d,n,ə,ɹ</td>
        <td>ɹ,n,d</td>
        <td>ə,aʊ</td>
        <td>d</td>
        <td></td>
        <td>ə→ɹ,ɹ→aʊ,aʊ→n,n→d</td>
        <td>nd</td>
        <td>vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>neutral_vowel → rhotic → open_to_rounded → coronal → coronal</td>
        <td>neutral_vowel,rhotic,open_to_rounded,coronal</td>
        <td>neutral_vowel→rhotic,rhotic→open_to_rounded,open_to_rounded→coronal,coronal→coronal</td>
        <td>ə:neutral_vowel,ɹ:rhotic,aʊ:open_to_rounded,n:coronal,d:coronal</td>
        <td>ə:neutral_vowel→ɹ:rhotic,ɹ:rhotic→aʊ:open_to_rounded,aʊ:open_to_rounded→n:coronal,n:coronal→d:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.111111111</td>
        <td>0.016806723</td>
        <td>0.2</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.158099558</td>
        <td>0.118348624</td>
        <td>0.136020087</td>
        <td>0.197624447</td>
        <td>0.14793578</td>
        <td>0.170025109</td>
      </tr>
      <tr>
        <td class="line-num">69</td>
        <td>E069</td>
        <td>word</td>
        <td>away</td>
        <td>General American English</td>
        <td>2</td>
        <td>01</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/əweɪ/</td>
        <td>[əweɪ]</td>
        <td>ə-w-eɪ</td>
        <td>eɪ,w,ə</td>
        <td>w</td>
        <td>ə,eɪ</td>
        <td></td>
        <td></td>
        <td>ə→w,w→eɪ</td>
        <td></td>
        <td>vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>neutral_vowel → rounded_glide → spread_vowel</td>
        <td>neutral_vowel,rounded_glide,spread_vowel</td>
        <td>neutral_vowel→rounded_glide,rounded_glide→spread_vowel</td>
        <td>ə:neutral_vowel,w:rounded_glide,eɪ:spread_vowel</td>
        <td>ə:neutral_vowel→w:rounded_glide,w:rounded_glide→eɪ:spread_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.069767442</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.008403361</td>
        <td>0.15</td>
        <td>0.018348624</td>
        <td>0.008403361</td>
        <td>0.136564083</td>
        <td>0.084174312</td>
        <td>0.113270057</td>
        <td>0.179689583</td>
        <td>0.110755674</td>
        <td>0.149039548</td>
      </tr>
      <tr>
        <td class="line-num">70</td>
        <td>E070</td>
        <td>word</td>
        <td>about</td>
        <td>General American English</td>
        <td>2</td>
        <td>01</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/əbaʊt/</td>
        <td>[əbaʊt]</td>
        <td>ə-b-aʊ-t</td>
        <td>aʊ,b,t,ə</td>
        <td>b,t</td>
        <td>ə,aʊ</td>
        <td>t</td>
        <td></td>
        <td>ə→b,b→aʊ,aʊ→t</td>
        <td></td>
        <td>vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>neutral_vowel → bilabial_closure → open_to_rounded → coronal</td>
        <td>neutral_vowel,bilabial_closure,open_to_rounded,coronal</td>
        <td>neutral_vowel→bilabial_closure,bilabial_closure→open_to_rounded,open_to_rounded→coronal</td>
        <td>ə:neutral_vowel,b:bilabial_closure,aʊ:open_to_rounded,t:coronal</td>
        <td>ə:neutral_vowel→b:bilabial_closure,b:bilabial_closure→aʊ:open_to_rounded,aʊ:open_to_rounded→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.149415154</td>
        <td>0.113761468</td>
        <td>0.128603405</td>
        <td>0.196598886</td>
        <td>0.149686142</td>
        <td>0.169215007</td>
      </tr>
      <tr>
        <td class="line-num">71</td>
        <td>E071</td>
        <td>word</td>
        <td>today</td>
        <td>General American English</td>
        <td>2</td>
        <td>01</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/tədeɪ/</td>
        <td>[tədeɪ]</td>
        <td>t-ə-d-eɪ</td>
        <td>d,eɪ,t,ə</td>
        <td>t,d</td>
        <td>ə,eɪ</td>
        <td></td>
        <td></td>
        <td>t→ə,ə→d,d→eɪ</td>
        <td></td>
        <td>vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → neutral_vowel → coronal → spread_vowel</td>
        <td>coronal,neutral_vowel,spread_vowel</td>
        <td>coronal→neutral_vowel,neutral_vowel→coronal,coronal→spread_vowel</td>
        <td>t:coronal,ə:neutral_vowel,d:coronal,eɪ:spread_vowel</td>
        <td>t:coronal→ə:neutral_vowel,ə:neutral_vowel→d:coronal,d:coronal→eɪ:spread_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.012605042</td>
        <td>0.15</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.140486582</td>
        <td>0.088761468</td>
        <td>0.117353405</td>
        <td>0.184850766</td>
        <td>0.116791405</td>
        <td>0.154412375</td>
      </tr>
      <tr>
        <td class="line-num">72</td>
        <td>E072</td>
        <td>word</td>
        <td>again</td>
        <td>General American English</td>
        <td>2</td>
        <td>01</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/əɡɛn/</td>
        <td>[əɡɛn]</td>
        <td>ə-ɡ-ɛ-n</td>
        <td>n,ə,ɛ,ɡ</td>
        <td>ɡ,n</td>
        <td>ə,ɛ</td>
        <td>n</td>
        <td></td>
        <td>ə→ɡ,ɡ→ɛ,ɛ→n</td>
        <td></td>
        <td>vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>neutral_vowel → low_visibility_velar → front_open_vowel → coronal</td>
        <td>neutral_vowel,low_visibility_velar,front_open_vowel,coronal</td>
        <td>neutral_vowel→low_visibility_velar,low_visibility_velar→front_open_vowel,front_open_vowel→coronal</td>
        <td>ə:neutral_vowel,ɡ:low_visibility_velar,ɛ:front_open_vowel,n:coronal</td>
        <td>ə:neutral_vowel→ɡ:low_visibility_velar,ɡ:low_visibility_velar→ɛ:front_open_vowel,ɛ:front_open_vowel→n:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.093023256</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.012605042</td>
        <td>0.2</td>
        <td>0.027522936</td>
        <td>0.012605042</td>
        <td>0.149415154</td>
        <td>0.113761468</td>
        <td>0.128603405</td>
        <td>0.196598886</td>
        <td>0.149686142</td>
        <td>0.169215007</td>
      </tr>
      <tr>
        <td class="line-num">73</td>
        <td>E073</td>
        <td>word</td>
        <td>machine</td>
        <td>General American English</td>
        <td>2</td>
        <td>01</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;stress_alternation</td>
        <td>0.76</td>
        <td>0.76</td>
        <td>0.07</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/məʃiːn/</td>
        <td>[məʃiːn]</td>
        <td>m-ə-ʃ-iː-n</td>
        <td>iː,m,n,ə,ʃ</td>
        <td>m,ʃ,n</td>
        <td>ə,iː</td>
        <td>n</td>
        <td></td>
        <td>m→ə,ə→ʃ,ʃ→iː,iː→n</td>
        <td></td>
        <td>vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → neutral_vowel → postalveolar → spread_vowel → coronal</td>
        <td>bilabial_closure,neutral_vowel,postalveolar,spread_vowel,coronal</td>
        <td>bilabial_closure→neutral_vowel,neutral_vowel→postalveolar,postalveolar→spread_vowel,spread_vowel→coronal</td>
        <td>m:bilabial_closure,ə:neutral_vowel,ʃ:postalveolar,iː:spread_vowel,n:coronal</td>
        <td>m:bilabial_closure→ə:neutral_vowel,ə:neutral_vowel→ʃ:postalveolar,ʃ:postalveolar→iː:spread_vowel,iː:spread_vowel→n:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.016806723</td>
        <td>0.25</td>
        <td>0.036697248</td>
        <td>0.016806723</td>
        <td>0.153337653</td>
        <td>0.143348624</td>
        <td>0.137686754</td>
        <td>0.20176007</td>
        <td>0.18861661</td>
        <td>0.181166782</td>
      </tr>
      <tr>
        <td class="line-num">74</td>
        <td>E074</td>
        <td>word</td>
        <td>photograph</td>
        <td>General American English</td>
        <td>3</td>
        <td>100</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;stress_alternation</td>
        <td>1.08</td>
        <td>1.08</td>
        <td>0.08</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/foʊtəɡɹæf/</td>
        <td>[foʊɾəɡɹæf]</td>
        <td>f-oʊ-t-ə-ɡ-ɹ-æ-f</td>
        <td>f,oʊ,t,æ,ə,ɡ,ɹ</td>
        <td>f,t,ɡ,ɹ</td>
        <td>oʊ,ə,æ</td>
        <td>f</td>
        <td></td>
        <td>f→oʊ,oʊ→t,t→ə,ə→ɡ,ɡ→ɹ,ɹ→æ,æ→f</td>
        <td>ɡɹ</td>
        <td>flapping;vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>labiodental → rounded_vowel → coronal → neutral_vowel → low_visibility_velar → rhotic → open_vowel → labiodental</td>
        <td>labiodental,rounded_vowel,coronal,neutral_vowel,low_visibility_velar,rhotic,open_vowel</td>
        <td>labiodental→rounded_vowel,rounded_vowel→coronal,coronal→neutral_vowel,neutral_vowel→low_visibility_velar,low_visibility_velar→rhotic,rhotic→open_vowel,open_vowel→labiodental</td>
        <td>f:labiodental,oʊ:rounded_vowel,t:coronal,ə:neutral_vowel,ɡ:low_visibility_velar,ɹ:rhotic,æ:open_vowel,f:labiodental</td>
        <td>f:labiodental→oʊ:rounded_vowel,oʊ:rounded_vowel→t:coronal,t:coronal→ə:neutral_vowel,ə:neutral_vowel→ɡ:low_visibility_velar,ɡ:low_visibility_velar→ɹ:rhotic,ɹ:rhotic→æ:open_vowel,æ:open_vowel→f:labiodental</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.162790698</td>
        <td>0.0625</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.222222222</td>
        <td>0.029411765</td>
        <td>0.35</td>
        <td>0.064220183</td>
        <td>0.029411765</td>
        <td>0.182417812</td>
        <td>0.207110092</td>
        <td>0.172055663</td>
        <td>0.168905382</td>
        <td>0.191768603</td>
        <td>0.159310799</td>
      </tr>
      <tr>
        <td class="line-num">75</td>
        <td>E075</td>
        <td>word</td>
        <td>photography</td>
        <td>General American English</td>
        <td>4</td>
        <td>0100</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;stress_alternation</td>
        <td>1.36</td>
        <td>1.36</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/fətɔɡɹəfi/</td>
        <td>[fətɔɡɹəfi]</td>
        <td>f-ə-t-ɔ-ɡ-ɹ-ə-f-i</td>
        <td>f,i,t,ɔ,ə,ɡ,ɹ</td>
        <td>f,t,ɡ,ɹ</td>
        <td>ə,ɔ,i</td>
        <td></td>
        <td></td>
        <td>f→ə,ə→t,t→ɔ,ɔ→ɡ,ɡ→ɹ,ɹ→ə,ə→f,f→i</td>
        <td>ɡɹ</td>
        <td>vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>labiodental → neutral_vowel → coronal → rounded_open_vowel → low_visibility_velar → rhotic → neutral_vowel → labiodental → spread_vowel</td>
        <td>labiodental,neutral_vowel,coronal,rounded_open_vowel,low_visibility_velar,rhotic,spread_vowel</td>
        <td>labiodental→neutral_vowel,neutral_vowel→coronal,coronal→rounded_open_vowel,rounded_open_vowel→low_visibility_velar,low_visibility_velar→rhotic,rhotic→neutral_vowel,neutral_vowel→labiodental,labiodental→spread_vowel</td>
        <td>f:labiodental,ə:neutral_vowel,t:coronal,ɔ:rounded_open_vowel,ɡ:low_visibility_velar,ɹ:rhotic,ə:neutral_vowel,f:labiodental,i:spread_vowel</td>
        <td>f:labiodental→ə:neutral_vowel,ə:neutral_vowel→t:coronal,t:coronal→ɔ:rounded_open_vowel,ɔ:rounded_open_vowel→ɡ:low_visibility_velar,ɡ:low_visibility_velar→ɹ:rhotic,ɹ:rhotic→ə:neutral_vowel,ə:neutral_vowel→f:labiodental,f:labiodental→i:spread_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.162790698</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.111111111</td>
        <td>0.033613445</td>
        <td>0.35</td>
        <td>0.073394495</td>
        <td>0.033613445</td>
        <td>0.158216465</td>
        <td>0.211697248</td>
        <td>0.156452319</td>
        <td>0.116335636</td>
        <td>0.155659741</td>
        <td>0.11503847</td>
      </tr>
      <tr>
        <td class="line-num">76</td>
        <td>E076</td>
        <td>word</td>
        <td>electricity</td>
        <td>General American English</td>
        <td>5</td>
        <td>01000</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;stress_alternation</td>
        <td>1.64</td>
        <td>1.64</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɪlɛktɹɪsəti/</td>
        <td>[ɪlɛktɹɪsəɾi]</td>
        <td>ɪ-l-ɛ-k-t-ɹ-ɪ-s-ə-t-i</td>
        <td>i,k,l,s,t,ə,ɛ,ɪ,ɹ</td>
        <td>l,k,t,ɹ,s</td>
        <td>ɪ,ɛ,ə,i</td>
        <td></td>
        <td></td>
        <td>ɪ→l,l→ɛ,ɛ→k,k→t,t→ɹ,ɹ→ɪ,ɪ→s,s→ə,ə→t,t→i</td>
        <td>ktɹ</td>
        <td>flapping;vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>spread_vowel → coronal → front_open_vowel → low_visibility_velar → coronal → rhotic → spread_vowel → coronal → neutral_vowel → coronal → spread_vowel</td>
        <td>spread_vowel,coronal,front_open_vowel,low_visibility_velar,rhotic,neutral_vowel</td>
        <td>spread_vowel→coronal,coronal→front_open_vowel,front_open_vowel→low_visibility_velar,low_visibility_velar→coronal,coronal→rhotic,rhotic→spread_vowel,spread_vowel→coronal,coronal→neutral_vowel,neutral_vowel→coronal,coronal→spread_vowel</td>
        <td>ɪ:spread_vowel,l:coronal,ɛ:front_open_vowel,k:low_visibility_velar,t:coronal,ɹ:rhotic,ɪ:spread_vowel,s:coronal,ə:neutral_vowel,t:coronal,i:spread_vowel</td>
        <td>ɪ:spread_vowel→l:coronal,l:coronal→ɛ:front_open_vowel,ɛ:front_open_vowel→k:low_visibility_velar,k:low_visibility_velar→t:coronal,t:coronal→ɹ:rhotic,ɹ:rhotic→ɪ:spread_vowel,ɪ:spread_vowel→s:coronal,s:coronal→ə:neutral_vowel,ə:neutral_vowel→t:coronal,t:coronal→i:spread_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.209302326</td>
        <td>0</td>
        <td>0.666666667</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.222222222</td>
        <td>0.042016807</td>
        <td>0.3</td>
        <td>0.082568807</td>
        <td>0.042016807</td>
        <td>0.181934479</td>
        <td>0.191284404</td>
        <td>0.169812697</td>
        <td>0.110935658</td>
        <td>0.116636832</td>
        <td>0.103544327</td>
      </tr>
      <tr>
        <td class="line-num">77</td>
        <td>E077</td>
        <td>phrase</td>
        <td>pick it up</td>
        <td>General American English</td>
        <td>3</td>
        <td>111</td>
        <td>has_primary_stress;initial_primary_stress;multiple_lexical_stresses</td>
        <td>1.1</td>
        <td>1.1</td>
        <td>0.08</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/pɪk ɪt ʌp/</td>
        <td>[pɪk ɪt ʌp]</td>
        <td>p-ɪ-k | ɪ-t | ʌ-p</td>
        <td>k,p,t,ɪ,ʌ</td>
        <td>p,k,t</td>
        <td>ɪ,ʌ</td>
        <td>k,t,p</td>
        <td>k→ɪ,t→ʌ</td>
        <td>p→ɪ,ɪ→k,ɪ→t,ʌ→p</td>
        <td></td>
        <td>linking</td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → spread_vowel → low_visibility_velar → spread_vowel → coronal → central_open_vowel → bilabial_closure</td>
        <td>bilabial_closure,spread_vowel,low_visibility_velar,coronal,central_open_vowel</td>
        <td>bilabial_closure→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→spread_vowel,spread_vowel→coronal,coronal→central_open_vowel,central_open_vowel→bilabial_closure</td>
        <td>p:bilabial_closure,ɪ:spread_vowel,k:low_visibility_velar,ɪ:spread_vowel,t:coronal,ʌ:central_open_vowel,p:bilabial_closure</td>
        <td>p:bilabial_closure→ɪ:spread_vowel,ɪ:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→ɪ:spread_vowel,ɪ:spread_vowel→t:coronal,t:coronal→ʌ:central_open_vowel,ʌ:central_open_vowel→p:bilabial_closure</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0.1875</td>
        <td>0.5</td>
        <td>0</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.025210084</td>
        <td>0.25</td>
        <td>0.055045872</td>
        <td>0.025210084</td>
        <td>0.134300038</td>
        <td>0.152522936</td>
        <td>0.127035622</td>
        <td>0.122090943</td>
        <td>0.138657214</td>
        <td>0.115486929</td>
      </tr>
      <tr>
        <td class="line-num">78</td>
        <td>E078</td>
        <td>phrase</td>
        <td>turn it on</td>
        <td>General American English</td>
        <td>3</td>
        <td>111</td>
        <td>has_primary_stress;initial_primary_stress;multiple_lexical_stresses</td>
        <td>1.1</td>
        <td>1.1</td>
        <td>0.08</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/tɝn ɪt ɑn/</td>
        <td>[tɝn ɪɾ ɑn]</td>
        <td>t-ɝ-n | ɪ-t | ɑ-n</td>
        <td>n,t,ɑ,ɝ,ɪ</td>
        <td>t,n</td>
        <td>ɝ,ɪ,ɑ</td>
        <td>n,t</td>
        <td>n→ɪ,t→ɑ</td>
        <td>t→ɝ,ɝ→n,ɪ→t,ɑ→n</td>
        <td></td>
        <td>linking;flapping;r_coloring</td>
        <td>ɝ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → rhotic_vowel → coronal → spread_vowel → coronal → open_vowel → coronal</td>
        <td>coronal,rhotic_vowel,spread_vowel,open_vowel</td>
        <td>coronal→rhotic_vowel,rhotic_vowel→coronal,coronal→spread_vowel,spread_vowel→coronal,coronal→open_vowel,open_vowel→coronal</td>
        <td>t:coronal,ɝ:rhotic_vowel,n:coronal,ɪ:spread_vowel,t:coronal,ɑ:open_vowel,n:coronal</td>
        <td>t:coronal→ɝ:rhotic_vowel,ɝ:rhotic_vowel→n:coronal,n:coronal→ɪ:spread_vowel,ɪ:spread_vowel→t:coronal,t:coronal→ɑ:open_vowel,ɑ:open_vowel→n:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.11627907</td>
        <td>0.125</td>
        <td>0.5</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.333333333</td>
        <td>0.025210084</td>
        <td>0.2</td>
        <td>0.055045872</td>
        <td>0.025210084</td>
        <td>0.171403212</td>
        <td>0.127522936</td>
        <td>0.148007844</td>
        <td>0.155821102</td>
        <td>0.115929942</td>
        <td>0.134552586</td>
      </tr>
      <tr>
        <td class="line-num">79</td>
        <td>E079</td>
        <td>phrase</td>
        <td>take a seat</td>
        <td>General American English</td>
        <td>3</td>
        <td>101</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.1</td>
        <td>1.1</td>
        <td>0.08</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/teɪk ə siːt/</td>
        <td>[teɪk ə siːt]</td>
        <td>t-eɪ-k | ə | s-iː-t</td>
        <td>eɪ,iː,k,s,t,ə</td>
        <td>t,k,s</td>
        <td>eɪ,ə,iː</td>
        <td>k,t</td>
        <td>k→ə,ə→s</td>
        <td>t→eɪ,eɪ→k,s→iː,iː→t</td>
        <td></td>
        <td>linking;weak_form_reduction</td>
        <td>weak_a;ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → spread_vowel → low_visibility_velar → neutral_vowel → coronal → spread_vowel → coronal</td>
        <td>coronal,spread_vowel,low_visibility_velar,neutral_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→neutral_vowel,neutral_vowel→coronal,coronal→spread_vowel,spread_vowel→coronal</td>
        <td>t:coronal,eɪ:spread_vowel,k:low_visibility_velar,ə:neutral_vowel,s:coronal,iː:spread_vowel,t:coronal</td>
        <td>t:coronal→eɪ:spread_vowel,eɪ:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→ə:neutral_vowel,ə:neutral_vowel→s:coronal,s:coronal→iː:spread_vowel,iː:spread_vowel→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.139534884</td>
        <td>0.125</td>
        <td>0.833333333</td>
        <td>0.2</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.025210084</td>
        <td>0.2</td>
        <td>0.04587156</td>
        <td>0.025210084</td>
        <td>0.220757218</td>
        <td>0.12293578</td>
        <td>0.181638217</td>
        <td>0.20068838</td>
        <td>0.1117598</td>
        <td>0.165125652</td>
      </tr>
      <tr>
        <td class="line-num">80</td>
        <td>E080</td>
        <td>phrase</td>
        <td>read it aloud</td>
        <td>General American English</td>
        <td>4</td>
        <td>1101</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.38</td>
        <td>1.66</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɹiːd ɪt əlaʊd/</td>
        <td>[ɹiːd ɪɾ əlaʊd]</td>
        <td>ɹ-iː-d | ɪ-t | ə-l-aʊ-d</td>
        <td>aʊ,d,iː,l,t,ə,ɪ,ɹ</td>
        <td>ɹ,d,t,l</td>
        <td>iː,ɪ,ə,aʊ</td>
        <td>d,t</td>
        <td>d→ɪ,t→ə</td>
        <td>ɹ→iː,iː→d,ɪ→t,ə→l,l→aʊ,aʊ→d</td>
        <td></td>
        <td>linking;flapping;vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>rhotic → spread_vowel → coronal → spread_vowel → coronal → neutral_vowel → coronal → open_to_rounded → coronal</td>
        <td>rhotic,spread_vowel,coronal,neutral_vowel,open_to_rounded</td>
        <td>rhotic→spread_vowel,spread_vowel→coronal,coronal→spread_vowel,spread_vowel→coronal,coronal→neutral_vowel,neutral_vowel→coronal,coronal→open_to_rounded,open_to_rounded→coronal</td>
        <td>ɹ:rhotic,iː:spread_vowel,d:coronal,ɪ:spread_vowel,t:coronal,ə:neutral_vowel,l:coronal,aʊ:open_to_rounded,d:coronal</td>
        <td>ɹ:rhotic→iː:spread_vowel,iː:spread_vowel→d:coronal,d:coronal→ɪ:spread_vowel,ɪ:spread_vowel→t:coronal,t:coronal→ə:neutral_vowel,ə:neutral_vowel→l:coronal,l:coronal→aʊ:open_to_rounded,aʊ:open_to_rounded→d:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.186046512</td>
        <td>0.125</td>
        <td>0.833333333</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.333333333</td>
        <td>0.033613445</td>
        <td>0.25</td>
        <td>0.064220183</td>
        <td>0.033613445</td>
        <td>0.230189518</td>
        <td>0.157110092</td>
        <td>0.195916025</td>
        <td>0.166803998</td>
        <td>0.113847893</td>
        <td>0.141968134</td>
      </tr>
      <tr>
        <td class="line-num">81</td>
        <td>E081</td>
        <td>phrase</td>
        <td>put it away</td>
        <td>General American English</td>
        <td>4</td>
        <td>1101</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.38</td>
        <td>1.66</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/pʊt ɪt əweɪ/</td>
        <td>[pʊɾ ɪɾ əweɪ]</td>
        <td>p-ʊ-t | ɪ-t | ə-w-eɪ</td>
        <td>eɪ,p,t,w,ə,ɪ,ʊ</td>
        <td>p,t,w</td>
        <td>ʊ,ɪ,ə,eɪ</td>
        <td>t</td>
        <td>t→ɪ,t→ə</td>
        <td>p→ʊ,ʊ→t,ɪ→t,ə→w,w→eɪ</td>
        <td></td>
        <td>linking;flapping;vowel_reduction</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → rounded_vowel → coronal → spread_vowel → coronal → neutral_vowel → rounded_glide → spread_vowel</td>
        <td>bilabial_closure,rounded_vowel,coronal,spread_vowel,neutral_vowel,rounded_glide</td>
        <td>bilabial_closure→rounded_vowel,rounded_vowel→coronal,coronal→spread_vowel,spread_vowel→coronal,coronal→neutral_vowel,neutral_vowel→rounded_glide,rounded_glide→spread_vowel</td>
        <td>p:bilabial_closure,ʊ:rounded_vowel,t:coronal,ɪ:spread_vowel,t:coronal,ə:neutral_vowel,w:rounded_glide,eɪ:spread_vowel</td>
        <td>p:bilabial_closure→ʊ:rounded_vowel,ʊ:rounded_vowel→t:coronal,t:coronal→ɪ:spread_vowel,ɪ:spread_vowel→t:coronal,t:coronal→ə:neutral_vowel,ə:neutral_vowel→w:rounded_glide,w:rounded_glide→eɪ:spread_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.162790698</td>
        <td>0.0625</td>
        <td>0.833333333</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.333333333</td>
        <td>0.029411765</td>
        <td>0.3</td>
        <td>0.064220183</td>
        <td>0.029411765</td>
        <td>0.217338447</td>
        <td>0.182110092</td>
        <td>0.191500108</td>
        <td>0.157491628</td>
        <td>0.131963835</td>
        <td>0.138768194</td>
      </tr>
      <tr>
        <td class="line-num">82</td>
        <td>E082</td>
        <td>phrase</td>
        <td>get a ticket</td>
        <td>General American English</td>
        <td>4</td>
        <td>1010</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.38</td>
        <td>1.66</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɡɛt ə tɪkɪt/</td>
        <td>[ɡɛɾ ə tɪkɪt]</td>
        <td>ɡ-ɛ-t | ə | t-ɪ-k-ɪ-t</td>
        <td>k,t,ə,ɛ,ɡ,ɪ</td>
        <td>ɡ,t,k</td>
        <td>ɛ,ə,ɪ</td>
        <td>t</td>
        <td>t→ə,ə→t</td>
        <td>ɡ→ɛ,ɛ→t,t→ɪ,ɪ→k,k→ɪ,ɪ→t</td>
        <td></td>
        <td>flapping;weak_form_reduction</td>
        <td>weak_a;ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → front_open_vowel → coronal → neutral_vowel → coronal → spread_vowel → low_visibility_velar → spread_vowel → coronal</td>
        <td>low_visibility_velar,front_open_vowel,coronal,neutral_vowel,spread_vowel</td>
        <td>low_visibility_velar→front_open_vowel,front_open_vowel→coronal,coronal→neutral_vowel,neutral_vowel→coronal,coronal→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→spread_vowel,spread_vowel→coronal</td>
        <td>ɡ:low_visibility_velar,ɛ:front_open_vowel,t:coronal,ə:neutral_vowel,t:coronal,ɪ:spread_vowel,k:low_visibility_velar,ɪ:spread_vowel,t:coronal</td>
        <td>ɡ:low_visibility_velar→ɛ:front_open_vowel,ɛ:front_open_vowel→t:coronal,t:coronal→ə:neutral_vowel,ə:neutral_vowel→t:coronal,t:coronal→ɪ:spread_vowel,ɪ:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→ɪ:spread_vowel,ɪ:spread_vowel→t:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.139534884</td>
        <td>0.0625</td>
        <td>0.833333333</td>
        <td>0.2</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.033613445</td>
        <td>0.25</td>
        <td>0.073394495</td>
        <td>0.033613445</td>
        <td>0.213029126</td>
        <td>0.161697248</td>
        <td>0.184821183</td>
        <td>0.154368932</td>
        <td>0.117171919</td>
        <td>0.133928393</td>
      </tr>
      <tr>
        <td class="line-num">83</td>
        <td>E083</td>
        <td>phrase</td>
        <td>a cup of tea</td>
        <td>General American English</td>
        <td>4</td>
        <td>0101</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.38</td>
        <td>1.66</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ə kʌp əv tiː/</td>
        <td>[ə kʌp əv tiː]</td>
        <td>ə | k-ʌ-p | ə-v | t-iː</td>
        <td>iː,k,p,t,v,ə,ʌ</td>
        <td>k,p,v,t</td>
        <td>ə,ʌ,iː</td>
        <td>p,v</td>
        <td>ə→k,p→ə,v→t</td>
        <td>k→ʌ,ʌ→p,ə→v,t→iː</td>
        <td></td>
        <td>weak_form_reduction;linking</td>
        <td>weak_a;weak_of;ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>neutral_vowel → low_visibility_velar → central_open_vowel → bilabial_closure → neutral_vowel → labiodental → coronal → spread_vowel</td>
        <td>neutral_vowel,low_visibility_velar,central_open_vowel,bilabial_closure,labiodental,coronal,spread_vowel</td>
        <td>neutral_vowel→low_visibility_velar,low_visibility_velar→central_open_vowel,central_open_vowel→bilabial_closure,bilabial_closure→neutral_vowel,neutral_vowel→labiodental,labiodental→coronal,coronal→spread_vowel</td>
        <td>ə:neutral_vowel,k:low_visibility_velar,ʌ:central_open_vowel,p:bilabial_closure,ə:neutral_vowel,v:labiodental,t:coronal,iː:spread_vowel</td>
        <td>ə:neutral_vowel→k:low_visibility_velar,k:low_visibility_velar→ʌ:central_open_vowel,ʌ:central_open_vowel→p:bilabial_closure,p:bilabial_closure→ə:neutral_vowel,ə:neutral_vowel→v:labiodental,v:labiodental→t:coronal,t:coronal→iː:spread_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.162790698</td>
        <td>0.125</td>
        <td>0.833333333</td>
        <td>0.3</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.029411765</td>
        <td>0.35</td>
        <td>0.064220183</td>
        <td>0.029411765</td>
        <td>0.238965431</td>
        <td>0.207110092</td>
        <td>0.211638997</td>
        <td>0.173163356</td>
        <td>0.150079777</td>
        <td>0.153361592</td>
      </tr>
      <tr>
        <td class="line-num">84</td>
        <td>E084</td>
        <td>phrase</td>
        <td>a glass of water</td>
        <td>General American English</td>
        <td>5</td>
        <td>01010</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.7</td>
        <td>1.98</td>
        <td>0.1</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ə ɡlæs əv wɔtɚ/</td>
        <td>[ə ɡlæs əv wɔɾɚ]</td>
        <td>ə | ɡ-l-æ-s | ə-v | w-ɔ-t-ɚ</td>
        <td>l,s,t,v,w,æ,ɔ,ə,ɚ,ɡ</td>
        <td>ɡ,l,s,v,w,t</td>
        <td>ə,æ,ɔ,ɚ</td>
        <td>s,v</td>
        <td>ə→ɡ,s→ə,v→w</td>
        <td>ɡ→l,l→æ,æ→s,ə→v,w→ɔ,ɔ→t,t→ɚ</td>
        <td>ɡl</td>
        <td>weak_form_reduction;flapping;r_coloring</td>
        <td>weak_a;weak_of;ə;ɚ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>neutral_vowel → low_visibility_velar → coronal → open_vowel → coronal → neutral_vowel → labiodental → rounded_glide → rounded_open_vowel → coronal → rhotic_vowel</td>
        <td>neutral_vowel,low_visibility_velar,coronal,open_vowel,labiodental,rounded_glide,rounded_open_vowel,rhotic_vowel</td>
        <td>neutral_vowel→low_visibility_velar,low_visibility_velar→coronal,coronal→open_vowel,open_vowel→coronal,coronal→neutral_vowel,neutral_vowel→labiodental,labiodental→rounded_glide,rounded_glide→rounded_open_vowel,rounded_open_vowel→coronal,coronal→rhotic_vowel</td>
        <td>ə:neutral_vowel,ɡ:low_visibility_velar,l:coronal,æ:open_vowel,s:coronal,ə:neutral_vowel,v:labiodental,w:rounded_glide,ɔ:rounded_open_vowel,t:coronal,ɚ:rhotic_vowel</td>
        <td>ə:neutral_vowel→ɡ:low_visibility_velar,ɡ:low_visibility_velar→l:coronal,l:coronal→æ:open_vowel,æ:open_vowel→s:coronal,s:coronal→ə:neutral_vowel,ə:neutral_vowel→v:labiodental,v:labiodental→w:rounded_glide,w:rounded_glide→ɔ:rounded_open_vowel,ɔ:rounded_open_vowel→t:coronal,t:coronal→ɚ:rhotic_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.23255814</td>
        <td>0.125</td>
        <td>0.833333333</td>
        <td>0.4</td>
        <td>0.033333333</td>
        <td>0.333333333</td>
        <td>0.042016807</td>
        <td>0.4</td>
        <td>0.091743119</td>
        <td>0.042016807</td>
        <td>0.285653564</td>
        <td>0.24587156</td>
        <td>0.253333487</td>
        <td>0.168031508</td>
        <td>0.144630329</td>
        <td>0.149019698</td>
      </tr>
      <tr>
        <td class="line-num">85</td>
        <td>E085</td>
        <td>phrase</td>
        <td>an apple a day</td>
        <td>General American English</td>
        <td>5</td>
        <td>01001</td>
        <td>has_primary_stress;has_unstressed_syllable;noninitial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.66</td>
        <td>1.94</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ən æpəl ə deɪ/</td>
        <td>[ən æpəl ə deɪ]</td>
        <td>ə-n | æ-p-ə-l | ə | d-eɪ</td>
        <td>d,eɪ,l,n,p,æ,ə</td>
        <td>n,p,l,d</td>
        <td>ə,æ,eɪ</td>
        <td>n,l</td>
        <td>n→æ,l→ə,ə→d</td>
        <td>ə→n,æ→p,p→ə,ə→l,d→eɪ</td>
        <td></td>
        <td>linking;weak_form_reduction;dark_l</td>
        <td>weak_a;ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>neutral_vowel → coronal → open_vowel → bilabial_closure → neutral_vowel → coronal → neutral_vowel → coronal → spread_vowel</td>
        <td>neutral_vowel,coronal,open_vowel,bilabial_closure,spread_vowel</td>
        <td>neutral_vowel→coronal,coronal→open_vowel,open_vowel→bilabial_closure,bilabial_closure→neutral_vowel,neutral_vowel→coronal,coronal→neutral_vowel,neutral_vowel→coronal,coronal→spread_vowel</td>
        <td>ə:neutral_vowel,n:coronal,æ:open_vowel,p:bilabial_closure,ə:neutral_vowel,l:coronal,ə:neutral_vowel,d:coronal,eɪ:spread_vowel</td>
        <td>ə:neutral_vowel→n:coronal,n:coronal→æ:open_vowel,æ:open_vowel→p:bilabial_closure,p:bilabial_closure→ə:neutral_vowel,ə:neutral_vowel→l:coronal,l:coronal→ə:neutral_vowel,ə:neutral_vowel→d:coronal,d:coronal→eɪ:spread_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.162790698</td>
        <td>0.125</td>
        <td>0.833333333</td>
        <td>0.2</td>
        <td>0</td>
        <td>0.333333333</td>
        <td>0.033613445</td>
        <td>0.25</td>
        <td>0.055045872</td>
        <td>0.033613445</td>
        <td>0.241152973</td>
        <td>0.152522936</td>
        <td>0.202673013</td>
        <td>0.145272875</td>
        <td>0.091881287</td>
        <td>0.122092176</td>
      </tr>
      <tr>
        <td class="line-num">86</td>
        <td>E086</td>
        <td>phrase</td>
        <td>black coffee please</td>
        <td>General American English</td>
        <td>4</td>
        <td>1101</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.46</td>
        <td>1.74</td>
        <td>0.1</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/blæk kɔfi pliːz/</td>
        <td>[blæk kɔfi pliːz]</td>
        <td>b-l-æ-k | k-ɔ-f-i | p-l-iː-z</td>
        <td>b,f,i,iː,k,l,p,z,æ,ɔ</td>
        <td>b,l,k,f,p,z</td>
        <td>æ,ɔ,i,iː</td>
        <td>k,z</td>
        <td>k→k,i→p</td>
        <td>b→l,l→æ,æ→k,k→ɔ,ɔ→f,f→i,p→l,l→iː,iː→z</td>
        <td>bl;pl</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>bilabial_closure → coronal → open_vowel → low_visibility_velar → low_visibility_velar → rounded_open_vowel → labiodental → spread_vowel → bilabial_closure → coronal → spread_vowel → coronal</td>
        <td>bilabial_closure,coronal,open_vowel,low_visibility_velar,rounded_open_vowel,labiodental,spread_vowel</td>
        <td>bilabial_closure→coronal,coronal→open_vowel,open_vowel→low_visibility_velar,low_visibility_velar→low_visibility_velar,low_visibility_velar→rounded_open_vowel,rounded_open_vowel→labiodental,labiodental→spread_vowel,spread_vowel→bilabial_closure,bilabial_closure→coronal,coronal→spread_vowel,spread_vowel→coronal</td>
        <td>b:bilabial_closure,l:coronal,æ:open_vowel,k:low_visibility_velar,k:low_visibility_velar,ɔ:rounded_open_vowel,f:labiodental,i:spread_vowel,p:bilabial_closure,l:coronal,iː:spread_vowel,z:coronal</td>
        <td>b:bilabial_closure→l:coronal,l:coronal→æ:open_vowel,æ:open_vowel→k:low_visibility_velar,k:low_visibility_velar→k:low_visibility_velar,k:low_visibility_velar→ɔ:rounded_open_vowel,ɔ:rounded_open_vowel→f:labiodental,f:labiodental→i:spread_vowel,i:spread_vowel→p:bilabial_closure,p:bilabial_closure→l:coronal,l:coronal→iː:spread_vowel,iː:spread_vowel→z:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.23255814</td>
        <td>0.125</td>
        <td>0.833333333</td>
        <td>0</td>
        <td>0.066666667</td>
        <td>0</td>
        <td>0.046218487</td>
        <td>0.35</td>
        <td>0.091743119</td>
        <td>0.046218487</td>
        <td>0.186253804</td>
        <td>0.22087156</td>
        <td>0.179173823</td>
        <td>0.127571099</td>
        <td>0.15128189</td>
        <td>0.122721797</td>
      </tr>
      <tr>
        <td class="line-num">87</td>
        <td>E087</td>
        <td>phrase</td>
        <td>fresh fruit salad</td>
        <td>General American English</td>
        <td>5</td>
        <td>11110</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.7</td>
        <td>1.7</td>
        <td>0.1</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/fɹɛʃ fɹuːt sæləd/</td>
        <td>[fɹɛʃ fɹuːt sæləd]</td>
        <td>f-ɹ-ɛ-ʃ | f-ɹ-uː-t | s-æ-l-ə-d</td>
        <td>d,f,l,s,t,uː,æ,ə,ɛ,ɹ,ʃ</td>
        <td>f,ɹ,ʃ,t,s,l,d</td>
        <td>ɛ,uː,æ,ə</td>
        <td>ʃ,t,d</td>
        <td>ʃ→f,t→s</td>
        <td>f→ɹ,ɹ→ɛ,ɛ→ʃ,f→ɹ,ɹ→uː,uː→t,s→æ,æ→l,l→ə,ə→d</td>
        <td>fɹ</td>
        <td>vowel_reduction;dark_l</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>labiodental → rhotic → front_open_vowel → postalveolar → labiodental → rhotic → rounded_vowel → coronal → coronal → open_vowel → coronal → neutral_vowel → coronal</td>
        <td>labiodental,rhotic,front_open_vowel,postalveolar,rounded_vowel,coronal,open_vowel,neutral_vowel</td>
        <td>labiodental→rhotic,rhotic→front_open_vowel,front_open_vowel→postalveolar,postalveolar→labiodental,labiodental→rhotic,rhotic→rounded_vowel,rounded_vowel→coronal,coronal→coronal,coronal→open_vowel,open_vowel→coronal,coronal→neutral_vowel,neutral_vowel→coronal</td>
        <td>f:labiodental,ɹ:rhotic,ɛ:front_open_vowel,ʃ:postalveolar,f:labiodental,ɹ:rhotic,uː:rounded_vowel,t:coronal,s:coronal,æ:open_vowel,l:coronal,ə:neutral_vowel,d:coronal</td>
        <td>f:labiodental→ɹ:rhotic,ɹ:rhotic→ɛ:front_open_vowel,ɛ:front_open_vowel→ʃ:postalveolar,ʃ:postalveolar→f:labiodental,f:labiodental→ɹ:rhotic,ɹ:rhotic→uː:rounded_vowel,uː:rounded_vowel→t:coronal,t:coronal→s:coronal,s:coronal→æ:open_vowel,æ:open_vowel→l:coronal,l:coronal→ə:neutral_vowel,ə:neutral_vowel→d:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.255813953</td>
        <td>0.1875</td>
        <td>0.833333333</td>
        <td>0.1</td>
        <td>0.033333333</td>
        <td>0.222222222</td>
        <td>0.046218487</td>
        <td>0.4</td>
        <td>0.100917431</td>
        <td>0.046218487</td>
        <td>0.239774476</td>
        <td>0.250458716</td>
        <td>0.222555725</td>
        <td>0.141043809</td>
        <td>0.147328656</td>
        <td>0.130915132</td>
      </tr>
      <tr>
        <td class="line-num">88</td>
        <td>E088</td>
        <td>phrase</td>
        <td>good morning</td>
        <td>General American English</td>
        <td>3</td>
        <td>110</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.1</td>
        <td>1.1</td>
        <td>0.08</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɡʊd mɔɹnɪŋ/</td>
        <td>[ɡʊd mɔɹnɪŋ]</td>
        <td>ɡ-ʊ-d | m-ɔɹ-n-ɪ-ŋ</td>
        <td>d,m,n,ŋ,ɔɹ,ɡ,ɪ,ʊ</td>
        <td>ɡ,d,m,n,ŋ</td>
        <td>ʊ,ɔɹ,ɪ</td>
        <td>d,ŋ</td>
        <td>d→m</td>
        <td>ɡ→ʊ,ʊ→d,m→ɔɹ,ɔɹ→n,n→ɪ,ɪ→ŋ</td>
        <td></td>
        <td>r_coloring</td>
        <td>ɔɹ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → rounded_vowel → coronal → bilabial_closure → rhotic_vowel → coronal → spread_vowel → low_visibility_velar</td>
        <td>low_visibility_velar,rounded_vowel,coronal,bilabial_closure,rhotic_vowel,spread_vowel</td>
        <td>low_visibility_velar→rounded_vowel,rounded_vowel→coronal,coronal→bilabial_closure,bilabial_closure→rhotic_vowel,rhotic_vowel→coronal,coronal→spread_vowel,spread_vowel→low_visibility_velar</td>
        <td>ɡ:low_visibility_velar,ʊ:rounded_vowel,d:coronal,m:bilabial_closure,ɔɹ:rhotic_vowel,n:coronal,ɪ:spread_vowel,ŋ:low_visibility_velar</td>
        <td>ɡ:low_visibility_velar→ʊ:rounded_vowel,ʊ:rounded_vowel→d:coronal,d:coronal→m:bilabial_closure,m:bilabial_closure→ɔɹ:rhotic_vowel,ɔɹ:rhotic_vowel→n:coronal,n:coronal→ɪ:spread_vowel,ɪ:spread_vowel→ŋ:low_visibility_velar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.186046512</td>
        <td>0.125</td>
        <td>0.833333333</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.029411765</td>
        <td>0.3</td>
        <td>0.064220183</td>
        <td>0.029411765</td>
        <td>0.197843246</td>
        <td>0.182110092</td>
        <td>0.177853467</td>
        <td>0.179857496</td>
        <td>0.165554629</td>
        <td>0.16168497</td>
      </tr>
      <tr>
        <td class="line-num">89</td>
        <td>E089</td>
        <td>phrase</td>
        <td>nice to meet you</td>
        <td>General American English</td>
        <td>4</td>
        <td>1011</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.38</td>
        <td>1.66</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/naɪs tə miːt juː/</td>
        <td>[naɪs tə miːt juː]</td>
        <td>n-aɪ-s | t-ə | m-iː-t | j-uː</td>
        <td>aɪ,iː,j,m,n,s,t,uː,ə</td>
        <td>n,s,t,m,j</td>
        <td>aɪ,ə,iː,uː</td>
        <td>s,t</td>
        <td>s→t,ə→m,t→j</td>
        <td>n→aɪ,aɪ→s,t→ə,m→iː,iː→t,j→uː</td>
        <td></td>
        <td>weak_form_reduction</td>
        <td>weak_to;ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → open_to_spread → coronal → coronal → neutral_vowel → bilabial_closure → spread_vowel → coronal → palatal_glide → rounded_vowel</td>
        <td>coronal,open_to_spread,neutral_vowel,bilabial_closure,spread_vowel,palatal_glide,rounded_vowel</td>
        <td>coronal→open_to_spread,open_to_spread→coronal,coronal→coronal,coronal→neutral_vowel,neutral_vowel→bilabial_closure,bilabial_closure→spread_vowel,spread_vowel→coronal,coronal→palatal_glide,palatal_glide→rounded_vowel</td>
        <td>n:coronal,aɪ:open_to_spread,s:coronal,t:coronal,ə:neutral_vowel,m:bilabial_closure,iː:spread_vowel,t:coronal,j:palatal_glide,uː:rounded_vowel</td>
        <td>n:coronal→aɪ:open_to_spread,aɪ:open_to_spread→s:coronal,s:coronal→t:coronal,t:coronal→ə:neutral_vowel,ə:neutral_vowel→m:bilabial_closure,m:bilabial_closure→iː:spread_vowel,iː:spread_vowel→t:coronal,t:coronal→j:palatal_glide,j:palatal_glide→uː:rounded_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.209302326</td>
        <td>0.125</td>
        <td>0.833333333</td>
        <td>0.2</td>
        <td>0</td>
        <td>0.111111111</td>
        <td>0.037815126</td>
        <td>0.35</td>
        <td>0.082568807</td>
        <td>0.037815126</td>
        <td>0.216651699</td>
        <td>0.216284404</td>
        <td>0.198694583</td>
        <td>0.156993985</td>
        <td>0.156727829</td>
        <td>0.143981582</td>
      </tr>
      <tr>
        <td class="line-num">90</td>
        <td>E090</td>
        <td>phrase</td>
        <td>did you call</td>
        <td>General American English</td>
        <td>3</td>
        <td>101</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.1</td>
        <td>1.38</td>
        <td>0.08</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/dɪd jə kɔl/</td>
        <td>[dɪdʒə kɔl]</td>
        <td>d-ɪ-d | j-ə | k-ɔ-l</td>
        <td>d,j,k,l,ɔ,ə,ɪ</td>
        <td>d,j,k,l</td>
        <td>ɪ,ə,ɔ</td>
        <td>d,l</td>
        <td>d→j,ə→k</td>
        <td>d→ɪ,ɪ→d,j→ə,k→ɔ,ɔ→l</td>
        <td></td>
        <td>yod_coalescence;weak_form_reduction;dark_l</td>
        <td>ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → spread_vowel → coronal → palatal_glide → neutral_vowel → low_visibility_velar → rounded_open_vowel → coronal</td>
        <td>coronal,spread_vowel,palatal_glide,neutral_vowel,low_visibility_velar,rounded_open_vowel</td>
        <td>coronal→spread_vowel,spread_vowel→coronal,coronal→palatal_glide,palatal_glide→neutral_vowel,neutral_vowel→low_visibility_velar,low_visibility_velar→rounded_open_vowel,rounded_open_vowel→coronal</td>
        <td>d:coronal,ɪ:spread_vowel,d:coronal,j:palatal_glide,ə:neutral_vowel,k:low_visibility_velar,ɔ:rounded_open_vowel,l:coronal</td>
        <td>d:coronal→ɪ:spread_vowel,ɪ:spread_vowel→d:coronal,d:coronal→j:palatal_glide,j:palatal_glide→ə:neutral_vowel,ə:neutral_vowel→k:low_visibility_velar,k:low_visibility_velar→ɔ:rounded_open_vowel,ɔ:rounded_open_vowel→l:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.162790698</td>
        <td>0.125</td>
        <td>0.833333333</td>
        <td>0.1</td>
        <td>0</td>
        <td>0.333333333</td>
        <td>0.029411765</td>
        <td>0.3</td>
        <td>0.064220183</td>
        <td>0.029411765</td>
        <td>0.226267018</td>
        <td>0.182110092</td>
        <td>0.197750108</td>
        <td>0.205697289</td>
        <td>0.165554629</td>
        <td>0.179772825</td>
      </tr>
      <tr>
        <td class="line-num">91</td>
        <td>E091</td>
        <td>phrase</td>
        <td>want to go</td>
        <td>General American English</td>
        <td>3</td>
        <td>101</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.14</td>
        <td>1.38</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/wɑnt tə ɡoʊ/</td>
        <td>[wɑnə ɡoʊ]</td>
        <td>w-ɑ-n-t | t-ə | ɡ-oʊ</td>
        <td>n,oʊ,t,w,ɑ,ə,ɡ</td>
        <td>w,n,t,ɡ</td>
        <td>ɑ,ə,oʊ</td>
        <td>t</td>
        <td>t→t,ə→ɡ</td>
        <td>w→ɑ,ɑ→n,n→t,t→ə,ɡ→oʊ</td>
        <td>nt</td>
        <td>weak_form_reduction</td>
        <td>weak_to;ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>rounded_glide → open_vowel → coronal → coronal → coronal → neutral_vowel → low_visibility_velar → rounded_vowel</td>
        <td>rounded_glide,open_vowel,coronal,neutral_vowel,low_visibility_velar,rounded_vowel</td>
        <td>rounded_glide→open_vowel,open_vowel→coronal,coronal→coronal,coronal→coronal,coronal→neutral_vowel,neutral_vowel→low_visibility_velar,low_visibility_velar→rounded_vowel</td>
        <td>w:rounded_glide,ɑ:open_vowel,n:coronal,t:coronal,t:coronal,ə:neutral_vowel,ɡ:low_visibility_velar,oʊ:rounded_vowel</td>
        <td>w:rounded_glide→ɑ:open_vowel,ɑ:open_vowel→n:coronal,n:coronal→t:coronal,t:coronal→t:coronal,t:coronal→ə:neutral_vowel,ə:neutral_vowel→ɡ:low_visibility_velar,ɡ:low_visibility_velar→oʊ:rounded_vowel</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.162790698</td>
        <td>0.0625</td>
        <td>0.833333333</td>
        <td>0.2</td>
        <td>0.033333333</td>
        <td>0.111111111</td>
        <td>0.029411765</td>
        <td>0.3</td>
        <td>0.055045872</td>
        <td>0.029411765</td>
        <td>0.204640034</td>
        <td>0.177522936</td>
        <td>0.181693788</td>
        <td>0.179508802</td>
        <td>0.155721873</td>
        <td>0.159380515</td>
      </tr>
      <tr>
        <td class="line-num">92</td>
        <td>E092</td>
        <td>phrase</td>
        <td>going to work</td>
        <td>General American English</td>
        <td>4</td>
        <td>1001</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.38</td>
        <td>1.38</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/ɡoʊɪŋ tə wɝk/</td>
        <td>[ɡoʊɪŋ tə wɝk]</td>
        <td>ɡ-oʊ-ɪ-ŋ | t-ə | w-ɝ-k</td>
        <td>k,oʊ,t,w,ŋ,ə,ɝ,ɡ,ɪ</td>
        <td>ɡ,ŋ,t,w,k</td>
        <td>oʊ,ɪ,ə,ɝ</td>
        <td>ŋ,k</td>
        <td>ŋ→t,ə→w</td>
        <td>ɡ→oʊ,oʊ→ɪ,ɪ→ŋ,t→ə,w→ɝ,ɝ→k</td>
        <td></td>
        <td>weak_form_reduction;r_coloring</td>
        <td>weak_to;ə;ɝ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → rounded_vowel → spread_vowel → low_visibility_velar → coronal → neutral_vowel → rounded_glide → rhotic_vowel → low_visibility_velar</td>
        <td>low_visibility_velar,rounded_vowel,spread_vowel,coronal,neutral_vowel,rounded_glide,rhotic_vowel</td>
        <td>low_visibility_velar→rounded_vowel,rounded_vowel→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→coronal,coronal→neutral_vowel,neutral_vowel→rounded_glide,rounded_glide→rhotic_vowel,rhotic_vowel→low_visibility_velar</td>
        <td>ɡ:low_visibility_velar,oʊ:rounded_vowel,ɪ:spread_vowel,ŋ:low_visibility_velar,t:coronal,ə:neutral_vowel,w:rounded_glide,ɝ:rhotic_vowel,k:low_visibility_velar</td>
        <td>ɡ:low_visibility_velar→oʊ:rounded_vowel,oʊ:rounded_vowel→ɪ:spread_vowel,ɪ:spread_vowel→ŋ:low_visibility_velar,ŋ:low_visibility_velar→t:coronal,t:coronal→ə:neutral_vowel,ə:neutral_vowel→w:rounded_glide,w:rounded_glide→ɝ:rhotic_vowel,ɝ:rhotic_vowel→k:low_visibility_velar</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.209302326</td>
        <td>0.125</td>
        <td>0.833333333</td>
        <td>0.3</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.033613445</td>
        <td>0.35</td>
        <td>0.073394495</td>
        <td>0.033613445</td>
        <td>0.24621019</td>
        <td>0.211697248</td>
        <td>0.218047927</td>
        <td>0.178413181</td>
        <td>0.153403803</td>
        <td>0.158005744</td>
      </tr>
      <tr>
        <td class="line-num">93</td>
        <td>E093</td>
        <td>phrase</td>
        <td>could have known</td>
        <td>General American English</td>
        <td>3</td>
        <td>101</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.1</td>
        <td>1.38</td>
        <td>0.08</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/kʊd əv noʊn/</td>
        <td>[kʊd əv noʊn]</td>
        <td>k-ʊ-d | ə-v | n-oʊ-n</td>
        <td>d,k,n,oʊ,v,ə,ʊ</td>
        <td>k,d,v,n</td>
        <td>ʊ,ə,oʊ</td>
        <td>d,v,n</td>
        <td>d→ə,v→n</td>
        <td>k→ʊ,ʊ→d,ə→v,n→oʊ,oʊ→n</td>
        <td></td>
        <td>weak_form_reduction;linking</td>
        <td>weak_have;ə</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>low_visibility_velar → rounded_vowel → coronal → neutral_vowel → labiodental → coronal → rounded_vowel → coronal</td>
        <td>low_visibility_velar,rounded_vowel,coronal,neutral_vowel,labiodental</td>
        <td>low_visibility_velar→rounded_vowel,rounded_vowel→coronal,coronal→neutral_vowel,neutral_vowel→labiodental,labiodental→coronal,coronal→rounded_vowel,rounded_vowel→coronal</td>
        <td>k:low_visibility_velar,ʊ:rounded_vowel,d:coronal,ə:neutral_vowel,v:labiodental,n:coronal,oʊ:rounded_vowel,n:coronal</td>
        <td>k:low_visibility_velar→ʊ:rounded_vowel,ʊ:rounded_vowel→d:coronal,d:coronal→ə:neutral_vowel,ə:neutral_vowel→v:labiodental,v:labiodental→n:coronal,n:coronal→oʊ:rounded_vowel,oʊ:rounded_vowel→n:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.162790698</td>
        <td>0.1875</td>
        <td>0.833333333</td>
        <td>0.2</td>
        <td>0</td>
        <td>0.222222222</td>
        <td>0.029411765</td>
        <td>0.25</td>
        <td>0.055045872</td>
        <td>0.029411765</td>
        <td>0.233608288</td>
        <td>0.152522936</td>
        <td>0.196971565</td>
        <td>0.212371171</td>
        <td>0.138657214</td>
        <td>0.179065059</td>
      </tr>
      <tr>
        <td class="line-num">94</td>
        <td>E094</td>
        <td>phrase</td>
        <td>next train home</td>
        <td>General American English</td>
        <td>3</td>
        <td>111</td>
        <td>has_primary_stress;initial_primary_stress;multiple_lexical_stresses</td>
        <td>1.18</td>
        <td>1.46</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/nɛkst tɹeɪn hoʊm/</td>
        <td>[nɛkst tɹeɪn hoʊm]</td>
        <td>n-ɛ-k-s-t | t-ɹ-eɪ-n | h-oʊ-m</td>
        <td>eɪ,h,k,m,n,oʊ,s,t,ɛ,ɹ</td>
        <td>n,k,s,t,ɹ,h,m</td>
        <td>ɛ,eɪ,oʊ</td>
        <td>t,n,m</td>
        <td>t→t,n→h</td>
        <td>n→ɛ,ɛ→k,k→s,s→t,t→ɹ,ɹ→eɪ,eɪ→n,h→oʊ,oʊ→m</td>
        <td>kst;tɹ</td>
        <td></td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → front_open_vowel → low_visibility_velar → coronal → coronal → coronal → rhotic → spread_vowel → coronal → glottal → rounded_vowel → bilabial_closure</td>
        <td>coronal,front_open_vowel,low_visibility_velar,rhotic,spread_vowel,glottal,rounded_vowel,bilabial_closure</td>
        <td>coronal→front_open_vowel,front_open_vowel→low_visibility_velar,low_visibility_velar→coronal,coronal→coronal,coronal→coronal,coronal→rhotic,rhotic→spread_vowel,spread_vowel→coronal,coronal→glottal,glottal→rounded_vowel,rounded_vowel→bilabial_closure</td>
        <td>n:coronal,ɛ:front_open_vowel,k:low_visibility_velar,s:coronal,t:coronal,t:coronal,ɹ:rhotic,eɪ:spread_vowel,n:coronal,h:glottal,oʊ:rounded_vowel,m:bilabial_closure</td>
        <td>n:coronal→ɛ:front_open_vowel,ɛ:front_open_vowel→k:low_visibility_velar,k:low_visibility_velar→s:coronal,s:coronal→t:coronal,t:coronal→t:coronal,t:coronal→ɹ:rhotic,ɹ:rhotic→eɪ:spread_vowel,eɪ:spread_vowel→n:coronal,n:coronal→h:glottal,h:glottal→oʊ:rounded_vowel,oʊ:rounded_vowel→m:bilabial_closure</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.23255814</td>
        <td>0.1875</td>
        <td>0.5</td>
        <td>0</td>
        <td>0.066666667</td>
        <td>0</td>
        <td>0.046218487</td>
        <td>0.4</td>
        <td>0.091743119</td>
        <td>0.046218487</td>
        <td>0.147563328</td>
        <td>0.24587156</td>
        <td>0.15709049</td>
        <td>0.125053668</td>
        <td>0.208365729</td>
        <td>0.133127534</td>
      </tr>
      <tr>
        <td class="line-num">95</td>
        <td>E095</td>
        <td>phrase</td>
        <td>world class service</td>
        <td>General American English</td>
        <td>4</td>
        <td>1110</td>
        <td>has_primary_stress;has_unstressed_syllable;initial_primary_stress;multiple_lexical_stresses;stress_alternation</td>
        <td>1.46</td>
        <td>1.46</td>
        <td>0.1</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/wɝld klæs sɝvɪs/</td>
        <td>[wɝld klæs sɝvɪs]</td>
        <td>w-ɝ-l-d | k-l-æ-s | s-ɝ-v-ɪ-s</td>
        <td>d,k,l,s,v,w,æ,ɝ,ɪ</td>
        <td>w,l,d,k,s,v</td>
        <td>ɝ,æ,ɪ</td>
        <td>d,s</td>
        <td>d→k,s→s</td>
        <td>w→ɝ,ɝ→l,l→d,k→l,l→æ,æ→s,s→ɝ,ɝ→v,v→ɪ,ɪ→s</td>
        <td>ld;kl</td>
        <td>r_coloring;dark_l</td>
        <td>ɝ</td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>rounded_glide → rhotic_vowel → coronal → coronal → low_visibility_velar → coronal → open_vowel → coronal → coronal → rhotic_vowel → labiodental → spread_vowel → coronal</td>
        <td>rounded_glide,rhotic_vowel,coronal,low_visibility_velar,open_vowel,labiodental,spread_vowel</td>
        <td>rounded_glide→rhotic_vowel,rhotic_vowel→coronal,coronal→coronal,coronal→low_visibility_velar,low_visibility_velar→coronal,coronal→open_vowel,open_vowel→coronal,coronal→coronal,coronal→rhotic_vowel,rhotic_vowel→labiodental,labiodental→spread_vowel,spread_vowel→coronal</td>
        <td>w:rounded_glide,ɝ:rhotic_vowel,l:coronal,d:coronal,k:low_visibility_velar,l:coronal,æ:open_vowel,s:coronal,s:coronal,ɝ:rhotic_vowel,v:labiodental,ɪ:spread_vowel,s:coronal</td>
        <td>w:rounded_glide→ɝ:rhotic_vowel,ɝ:rhotic_vowel→l:coronal,l:coronal→d:coronal,d:coronal→k:low_visibility_velar,k:low_visibility_velar→l:coronal,l:coronal→æ:open_vowel,æ:open_vowel→s:coronal,s:coronal→s:coronal,s:coronal→ɝ:rhotic_vowel,ɝ:rhotic_vowel→v:labiodental,v:labiodental→ɪ:spread_vowel,ɪ:spread_vowel→s:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.209302326</td>
        <td>0.125</td>
        <td>0.833333333</td>
        <td>0.1</td>
        <td>0.066666667</td>
        <td>0.222222222</td>
        <td>0.050420168</td>
        <td>0.35</td>
        <td>0.100917431</td>
        <td>0.050420168</td>
        <td>0.229563531</td>
        <td>0.225458716</td>
        <td>0.210828232</td>
        <td>0.157235295</td>
        <td>0.154423778</td>
        <td>0.144402898</td>
      </tr>
      <tr>
        <td class="line-num">96</td>
        <td>E096</td>
        <td>phrase</td>
        <td>six small streets</td>
        <td>General American English</td>
        <td>3</td>
        <td>111</td>
        <td>has_primary_stress;initial_primary_stress;multiple_lexical_stresses</td>
        <td>1.18</td>
        <td>1.46</td>
        <td>0.09</td>
        <td>MODELED_PROXY_NOT_RECORDED</td>
        <td>0.20 + 0.28*syllables + 0.04*cluster_types + 0.06*phrase; SD=0.04+0.02*sqrt(syllables)+0.01*phrase+0.005*cluster_types</td>
        <td>/sɪks smɔl stɹiːts/</td>
        <td>[sɪks smɔl stɹiːts]</td>
        <td>s-ɪ-k-s | s-m-ɔ-l | s-t-ɹ-iː-t-s</td>
        <td>iː,k,l,m,s,t,ɔ,ɪ,ɹ</td>
        <td>s,k,m,l,t,ɹ</td>
        <td>ɪ,ɔ,iː</td>
        <td>s,l</td>
        <td>s→s,l→s</td>
        <td>s→ɪ,ɪ→k,k→s,s→m,m→ɔ,ɔ→l,s→t,t→ɹ,ɹ→iː,iː→t,t→s</td>
        <td>sm;stɹ</td>
        <td>dark_l</td>
        <td></td>
        <td>PENDING_EXPERT_REVIEW</td>
        <td>General American target; native-speaker/phonetic validation required before benchmark release.</td>
        <td>coronal → spread_vowel → low_visibility_velar → coronal → coronal → bilabial_closure → rounded_open_vowel → coronal → coronal → coronal → rhotic → spread_vowel → coronal → coronal</td>
        <td>coronal,spread_vowel,low_visibility_velar,bilabial_closure,rounded_open_vowel,rhotic</td>
        <td>coronal→spread_vowel,spread_vowel→low_visibility_velar,low_visibility_velar→coronal,coronal→coronal,coronal→bilabial_closure,bilabial_closure→rounded_open_vowel,rounded_open_vowel→coronal,coronal→coronal,coronal→coronal,coronal→rhotic,rhotic→spread_vowel,spread_vowel→coronal,coronal→coronal</td>
        <td>s:coronal,ɪ:spread_vowel,k:low_visibility_velar,s:coronal,s:coronal,m:bilabial_closure,ɔ:rounded_open_vowel,l:coronal,s:coronal,t:coronal,ɹ:rhotic,iː:spread_vowel,t:coronal,s:coronal</td>
        <td>s:coronal→ɪ:spread_vowel,ɪ:spread_vowel→k:low_visibility_velar,k:low_visibility_velar→s:coronal,s:coronal→s:coronal,s:coronal→m:bilabial_closure,m:bilabial_closure→ɔ:rounded_open_vowel,ɔ:rounded_open_vowel→l:coronal,l:coronal→s:coronal,s:coronal→t:coronal,t:coronal→ɹ:rhotic,ɹ:rhotic→iː:spread_vowel,iː:spread_vowel→t:coronal,t:coronal→s:coronal</td>
        <td>EQUAL_WEIGHT_HEURISTIC</td>
        <td>0.209302326</td>
        <td>0.125</td>
        <td>0.5</td>
        <td>0</td>
        <td>0.066666667</td>
        <td>0.111111111</td>
        <td>0.054621849</td>
        <td>0.3</td>
        <td>0.091743119</td>
        <td>0.054621849</td>
        <td>0.152385993</td>
        <td>0.19587156</td>
        <td>0.151306692</td>
        <td>0.129140672</td>
        <td>0.165992847</td>
        <td>0.12822601</td>
      </tr>
    </tbody>
  </table>
</div>

</div>
