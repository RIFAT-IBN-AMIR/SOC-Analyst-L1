# Day 02 – IP and File Investigation by Tools

**Learning Path:** SOC Analyst Level 1  
**Date:** November 13, 2026  

# 🇬🇧 English Documentation

## 1. Learning Objectives

The main objectives of Day 2 were:

- Learn how to investigate suspicious IP addresses.
- Understand how to use VirusTotal and AbuseIPDB.
- Identify important information related to IP addresses.
- Compare investigation results from different threat intelligence platforms.
- Understand the basics of file investigation.
- Learn how SOC analysts use investigation results to make security decisions.

## 2. IP Address Investigation Using VirusTotal

**Tool:** [VirusTotal](https://www.virustotal.com/)

**Sample IP Address:** `185.234.219.246`

I used VirusTotal to investigate the sample IP address and explored the following sections.

### Detection Overview

- Shows detection results from different security vendors.
- Helps identify whether an IP address has been flagged as suspicious or malicious.

### Basic Information

I explored the basic information associated with the IP address:

- ASN (Autonomous System Number)
- Country and geographical location
- ISP (Internet Service Provider)

### Reputation

- Provides reputation-related information about an IP address.
- Helps understand whether the IP address has been reported as suspicious.

### Relations

- Shows related domains, files, and other connected indicators.
- Helps analysts understand possible connections between different threat indicators.

### Timeline

- Provides historical information and activity related to the IP address.
- Helps understand changes and previous activities.

## 3. IP Address Investigation Using AbuseIPDB

**Tool:** [AbuseIPDB](https://www.abuseipdb.com/)

**Sample IP Address:** `185.234.219.246`

I also investigated the same IP address using AbuseIPDB.

Through this investigation, I learned how AbuseIPDB provides information about IP addresses reported for suspicious or abusive activities.

The investigation helped me understand:

- IP address abuse reports.
- Reported suspicious activities.
- Abuse-related reputation information.
- How threat intelligence platforms provide investigation data.

## 4. Comparison of VirusTotal and AbuseIPDB

After investigating the same IP address on both platforms, I compared their results.

**Observation:**

The investigation results from VirusTotal and AbuseIPDB were consistent with each other.

This comparison helped me understand the importance of using multiple threat intelligence sources during an IP investigation.

However, matching results from two platforms do not automatically prove that an IP address is completely safe or malicious. Additional investigation and supporting evidence are important.

## 5. Understanding SOC Investigation Decisions

A SOC analyst should not make security decisions based on a single detection result.

Important investigation practices:

- Review detection results from multiple security vendors.
- Check IP reputation and abuse reports.
- Investigate related domains and indicators.
- Compare information from different threat intelligence platforms.
- Evaluate available evidence before making a decision.

If suspicious activity is supported by sufficient evidence, the analyst may escalate the case to an L2 analyst.

If no suspicious activity is identified, the analyst should document the findings and continue monitoring when necessary.

**Important:** An IP address with no detections or abuse reports is not automatically safe.

## 6. Introduction to File Investigation Using VirusTotal

**Reference:** [EICAR Official Website](https://www.eicar.org/download-anti-malware-testfile/)

I learned the basic process of investigating files using VirusTotal.

The course introduced the EICAR test file, which is a harmless file designed to test antivirus detection capabilities.

### Investigation Process

1. Visit the EICAR official website.
2. Download the EICAR test file.
3. Open VirusTotal.
4. Select the File section.
5. Upload the test file for analysis.
6. Review the detection results.

**Note:** The EICAR test file is not real malware. It is designed to test antivirus and security products. Independent completion of this practical exercise is still pending.

## 7. Key Learning Outcomes

After completing the Day 2 learning activities, I gained an understanding of:

- IP address investigation using VirusTotal.
- IP address investigation using AbuseIPDB.
- Detection Overview and IP reputation.
- ASN, geographical location, and ISP information.
- Relations and Timeline sections.
- Comparing investigation results from multiple platforms.
- Basic file investigation procedures.
- Evidence-based investigation and escalation procedures.

## 8. Knowledge Gaps and Further Practice

I need additional practice in the following areas:

- Understanding IP reputation and abuse confidence scores in detail.
- Investigating related domains and indicators.
- Understanding why different security platforms may produce different results.
- Performing EICAR file investigation independently.
- Improving my ability to analyze investigation evidence.

## 9. Next Steps

- Practice more IP investigations using different sample IP addresses.
- Explore AbuseIPDB reports and reputation information in more detail.
- Complete the EICAR file investigation independently.
- Continue learning Network Fundamentals.

/////

# 日本語版

## 1. 学習目標

Day 2では、以下の内容を学習しました。

- 不審なIPアドレスの調査方法を学ぶ。
- VirusTotalとAbuseIPDBの使い方を理解する。
- IPアドレスに関する重要な情報を確認する。
- 複数の脅威インテリジェンスツールの調査結果を比較する。
- ファイル調査の基本を学ぶ。
- 調査結果をもとにSOCアナリストが判断する方法を理解する。

## 2. VirusTotalを使用したIPアドレスの調査

**使用ツール：** [VirusTotal](https://www.virustotal.com/)

**調査対象のIPアドレス：** `185.234.219.246`

VirusTotalを使用してIPアドレスを調査し、以下の項目を確認しました。

### Detection Overview（検出概要）

- 複数のセキュリティベンダーによる検出結果を確認する。
- 不審または悪意のあるIPアドレスとして検出されているかを確認する。

### Basic Information（基本情報）

IPアドレスに関する以下の情報を確認しました。

- ASN（自律システム番号）
- 国や地域
- ISP（インターネットサービスプロバイダー）

### Reputation（評価・評判）

- IPアドレスの評価に関する情報を確認する。
- 不審なIPアドレスとして報告されているかを確認する。

### Relations（関連情報）

- 関連するドメインやファイルなどを確認する。
- 脅威に関連する情報を調査する。

### Timeline（タイムライン）

- IPアドレスに関連する過去の情報や活動履歴を確認する。
- 過去の活動や変化を理解する。

## 3. AbuseIPDBを使用したIPアドレスの調査

**使用ツール：** [AbuseIPDB](https://www.abuseipdb.com/)

**調査対象のIPアドレス：** `185.234.219.246`

VirusTotalだけでなく、AbuseIPDBを使用して同じIPアドレスも調査しました。

AbuseIPDBを通して、不審な活動や不正利用が報告されたIPアドレスに関する情報を確認する方法を学びました。

今回の調査では、以下の内容について理解を深めました。

- IPアドレスの不正利用に関する報告
- 報告された不審な活動
- 不正利用に関する評価情報
- 脅威インテリジェンスツールによる調査情報の提供方法

## 4. VirusTotalとAbuseIPDBの調査結果の比較

同じIPアドレスを両方のツールで調査し、結果を比較しました。

**調査結果：**

VirusTotalとAbuseIPDBの調査結果は一致していました。

この比較を通して、IPアドレスを調査するときに複数の脅威インテリジェンスツールを使用することの重要性を理解しました。

ただし、2つのツールの結果が一致していても、そのIPアドレスが完全に安全、または悪意のあるものであると断定することはできません。追加調査と証拠の確認が重要です。

## 5. SOCアナリストの調査と判断

SOCアナリストは、一つの検出結果だけでセキュリティ上の判断をしてはいけません。

重要な調査方法：

- 複数のセキュリティベンダーの検出結果を確認する。
- IPアドレスの評価や不正利用に関する報告を確認する。
- 関連するドメインや情報を調査する。
- 複数の脅威インテリジェンスツールの情報を比較する。
- 十分な証拠をもとに判断する。

不審な活動が確認され、十分な証拠がある場合は、L2アナリストにエスカレーションすることがあります。

不審な活動が確認されない場合も、調査結果を記録し、必要に応じて監視を続けます。

**重要：** 検出結果や不正利用の報告がなくても、そのIPアドレスが必ず安全であるとは限りません。

## 6. VirusTotalを使用したファイル調査の基礎

**参考サイト：** [EICAR公式サイト](https://www.eicar.org/download-anti-malware-testfile/)

VirusTotalを使用したファイル調査の基本的な手順を学びました。

EICARテストファイルは、ウイルス対策ソフトの検出機能をテストするために作られた無害なファイルです。

### 調査手順

1. EICARの公式サイトにアクセスする。
2. EICARテストファイルをダウンロードする。
3. VirusTotalを開く。
4. Fileセクションを選択する。
5. テストファイルをアップロードする。
6. 検出結果を確認する。

**注意：** EICARテストファイルは本物のマルウェアではありません。ウイルス対策ソフトやセキュリティ製品のテストに使用されます。実際に自分で行う実習は今後の課題です。

## 7. 学習成果

Day 2の学習を通して、以下の内容を理解しました。

- VirusTotalを使用したIPアドレスの調査方法
- AbuseIPDBを使用したIPアドレスの調査方法
- Detection OverviewとIP Reputation
- ASN、地域情報、ISPの確認方法
- RelationsとTimelineの役割
- 複数のツールによる調査結果の比較
- ファイル調査の基本的な手順
- 証拠に基づいた調査とエスカレーションの重要性

## 8. 今後の課題

今後、以下の内容をさらに練習する必要があります。

- IPアドレスの評価やAbuse Confidence Scoreについて詳しく理解する。
- 関連するドメインや情報を調査する。
- セキュリティツールによって調査結果が異なる理由を理解する。
- EICARファイルを使用した調査を自分で実践する。
- 調査結果から証拠を分析する能力を高める。

## 9. 次回の学習内容

- 異なるサンプルIPアドレスを使用して調査を練習する。
- AbuseIPDBの報告情報や評価について詳しく学ぶ。
- EICARファイルを使用した調査を自分で実践する。
- ネットワークの基礎学習を続ける。
