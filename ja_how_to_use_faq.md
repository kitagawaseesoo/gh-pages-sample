---
layout: ja/how_to_use/custom
title: ABCI利用を希望する法人等（約款） - ご利用申込み方法 - ご利用方法 | ABCI
permalink: /ja/how_to_use/custom.html
---

<h2 class="h2">クラウドサービス</h2>

<h3 class="h3">資源タイプ</h3>
<div class="lead_text">＊ABCIでは、ユーザのリソース要求に応じて5つの資源タイプからマッチするものを選択できます。</div>


<table class="table">
<tr>
<th>タイプ名</th>
<th>CPUコア数<br />割当量 / 総量</th>
<th>GPU数<br />割当量 / 総量</th>
<th>メモリ（GB）<br />割当量 / 総量</th>
<th>ローカルストレージ（TB）<br />割当量 / 総量</th>

</tr>

<tr align="center">
	<th>F（ノード専有)</th>
	<td>40 / 40</td>
	<td>4 / 4</td>
	<td>360 / 384</td>
	<td>1.4 / 1.6</td>
</tr>

<tr align="center">
	<th>G.large</th>
	<td>20 / 40</td>
	<td>4 / 4</td>
	<td>240 / 384</td>
	<td>0.7 / 1.6</td>
</tr>

<tr align="center">
	<th>G.small</th>
	<td>5 / 40</td>
	<td>1 / 4</td>
	<td>60 / 384</td>
	<td>0.175 / 1.6</td>
</tr>

<tr align="center">
	<th>C.large</th>
	<td>20 / 40</td>
	<td>0 / 4</td>
	<td>120 / 384</td>
	<td>0.7 / 1.6</td>
</tr>

<tr align="center">
	<th>C.small</th>
	<td>5 / 40</td>
	<td>0 / 4</td>
	<td>30 / 384</td>
	<td>0.175 / 1.6</td>
</tr>

</table>
<br /><br /><br />

<h3 class="h3">提供サービス</h3>
<div class="lead_text">＊ABCIでは、処理スループットの最大化を可能とするバッチ型・対話型の実行サービスに加え、自由度の高い予約サービス、IDE、各種ストレージサービスを提供します。</div>

<table class="table">
<tr>
<th>サービス名</th>
<th>説　明</th>
<th>割当ノード数<br />（最小/最大）</th>

</tr>

<tr>
	<th>Spot</th>
	<td>バッチ実行型ジョブサービス</td>
	<td align="center">1 / 512</td>
</tr>

<tr>
	<th>On-demand</th>
	<td>インタラクティブ実行型ジョブサービス</td>
	<td align="center">1 / 32</td>
</tr>

<tr>
	<th>Reserved</th>
	<td>日単位での資源予約サービス</td>
	<td align="center">1 / 32</td>
</tr>

<tr>
	<th>IDE (開発中)</th>
	<td>WebUIベースの統合開発環境</td>
	<td align="center">未定</td>
</tr>

<tr>
	<th>Group Storage</th>
	<td>グループ内で共有できるストレージサービス</td>
	<td align="center">N / A</td>
</tr>

<tr>
	<th>Secure Object Storage<br />（開発中）</th>
	<td>暗号化に対応したオブジェクトストレージサービス</td>
	<td align="center">N / A</td>
</tr>

</table>

