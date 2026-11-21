# Day 03 – Cybersecurity Fundamentals

# English Version

## 1. Overview

On Day 3, I studied the fundamental concepts of cybersecurity, common cyber threats, attack techniques, security layers, network security, endpoint security, and SOC operations.

The main objective was to understand how cyberattacks happen, how organizations protect their systems, and how SOC analysts detect and investigate suspicious activities.


## 2. Theory – What I Learned

### 2.1 Threat, Vulnerability, and Risk

- **Threat:** A potential danger that can cause damage to a system or data.
- **Vulnerability:** A weakness that an attacker can exploit.
- **Risk:** The possibility of damage when a threat exploits a vulnerability.

### 2.2 Common Cybersecurity Domains

I learned about six major cybersecurity domains:

1. Network Security
2. Application Security
3. Endpoint Security
4. Cloud Security
5. Identity and Access Management (IAM)
6. Security Operations

### 2.3 CIA Triad

The CIA Triad represents three fundamental principles of information security.

- **Confidentiality:** Protecting information from unauthorized access.
- **Integrity:** Maintaining the accuracy and reliability of information.
- **Availability:** Ensuring systems and data are accessible when needed.

### 2.4 Common Cyber Threats

- **Malware:** Malicious software designed to damage systems or steal information.
- **Phishing:** Tricking users into revealing sensitive information through fake emails or websites.
- **Insider Threat:** Security risks caused by people inside an organization.
- **Advanced Persistent Threat (APT):** A sophisticated attack that maintains unauthorized access over an extended period.

### 2.5 Common Attack Types

- **Brute Force:** Repeatedly trying passwords to gain unauthorized access.
- **DDoS:** Overwhelming a target with traffic from multiple sources.
- **SQL Injection:** Exploiting insecure database queries through malicious SQL input.
- **Zero-Day Attack:** Exploiting a vulnerability before an effective security fix is available.

### 2.6 Case Study – WannaCry Ransomware

WannaCry was a worldwide ransomware attack in May 2017.

Key findings:

- Targeted vulnerable Windows systems.
- Exploited the EternalBlue vulnerability.
- Encrypted files and demanded Bitcoin.
- Commonly reported estimates indicate approximately 300,000 affected systems across 150 countries.

**Security Lesson:** Regular security updates and disabling outdated protocols are important for preventing similar attacks.

### 2.7 Case Study – Twitter/X Bitcoin Scam

In July 2020, attackers compromised several high-profile Twitter accounts.

- Fake Bitcoin giveaway messages were posted.
- Users were promised double the Bitcoin they sent.
- Victims were tricked into transferring cryptocurrency.

**Security Lesson:** Account protection, MFA, and secure administrative access are essential.

### 2.8 Cyber Kill Chain

The Cyber Kill Chain describes seven stages of a cyberattack.

1. Reconnaissance – Collecting information about the target.
2. Weaponization – Preparing malicious tools or payloads.
3. Delivery – Sending the malicious payload.
4. Exploitation – Exploiting a vulnerability or user behavior.
5. Installation – Installing malicious software.
6. Command and Control (C2) – Communicating with attacker-controlled infrastructure.
7. Actions on Objectives – Achieving the attacker's final goal.

### 2.9 Defense-in-Depth

Defense-in-Depth uses multiple security layers to protect an organization.

Main security layers:

- Perimeter Security
- Network Security
- Endpoint Security
- Application Security
- Data Security
- Human Security

**Key Concept:** If one security layer fails, other layers can still help reduce the impact of an attack.

### 2.10 Network Security Basics

Important networking concepts for SOC analysts:

- **IP Address:** Identifies a device on an IP network.
- **Port:** Identifies a communication endpoint or service.
- **Protocol:** Defines communication rules between devices.
- **Firewall:** Controls network traffic based on security rules.
- **IDS:** Detects suspicious activities and generates alerts.
- **IPS:** Detects and can block malicious traffic.
- **Network Segmentation:** Divides a network into smaller sections to improve security.

**Common Network Ports:**

- 20/21 – FTP
- 22 – SSH
- 23 – Telnet
- 25 – SMTP
- 53 – DNS
- 80 – HTTP
- 443 – HTTPS
- 3389 – RDP

### 2.11 Endpoint Security Basics

Endpoint security protects computers, laptops, and servers.

Important concepts:

- **Antivirus:** Detects and removes malware.
- **EDR:** Monitors endpoint activities and supports threat detection and response.
- **System Hardening:** Reduces system weaknesses through secure configuration.
- **Patching:** Fixes known vulnerabilities through software updates.

### 2.12 Email and Web Security

- **Phishing Detection:** Identifying suspicious emails and messages.
- **URL Filtering:** Blocking malicious or unauthorized websites.
- **Sandboxing:** Analyzing suspicious files in an isolated environment.

### 2.13 SIEM – Security Information and Event Management

SIEM is a centralized security platform used to collect and analyze logs from multiple sources.

Main functions:

- Log Collection
- Log Analysis
- Event Correlation
- Alert Generation
- Security Monitoring

Examples of SIEM tools:

- Splunk
- Microsoft Sentinel
- IBM QRadar

### 2.14 Common Log Sources

SOC analysts use different logs to investigate security incidents.

- **Windows Logs:** Login attempts, user activities, and process creation.
- **Firewall Logs:** Blocked traffic, suspicious connections, and port scans.
- **DNS Logs:** Domain queries and suspicious DNS activities.
- **VPN Logs:** Remote access attempts, timestamps, and source IP addresses.

### 2.15 Incident Detection and Triage

Basic SOC L1 workflow:

1. Alert Triggered
2. Alert Validation
3. Evidence Collection
4. Severity Assessment
5. Escalation
6. Documentation

The L1 analyst validates alerts, collects evidence, evaluates severity, and escalates incidents when necessary.

### 2.16 Common SOC Use Cases

**Brute Force Detection**

Repeated failed login attempts may indicate password guessing.

**Phishing Alert**

A user reports a suspicious email that requires investigation.

**Geo-Login Alert**

An unusual login location may indicate possible account compromise.

### 2.17 Cybersecurity Best Practices

- Use strong and unique passwords.
- Enable Multi-Factor Authentication (MFA).
- Keep software updated.
- Avoid sensitive activities on untrusted public Wi-Fi.
- Use antivirus and firewall protection.
- Participate in security awareness training.

---

## 3. Tools and Technologies

During this learning section, I studied several cybersecurity tools and technologies.

### 3.1 SIEM Tools

**Purpose:** Collecting, analyzing, and correlating security logs.

Examples:

- Splunk
- Microsoft Sentinel
- IBM QRadar

### 3.2 Antivirus and EDR

**Purpose:** Protecting endpoint devices and detecting suspicious activities.

Examples:

- Microsoft Defender
- CrowdStrike Falcon
- SentinelOne

### 3.3 Network Security Tools

**Purpose:** Monitoring network traffic and detecting suspicious connections.

Examples:

- Firewall
- IDS/IPS
- Wireshark

### 3.4 VirusTotal

**Purpose:** Checking suspicious URLs, files, domains, and IP addresses using multiple security engines and threat intelligence sources.

Website: https://www.virustotal.com/

### 3.5 WHOIS Lookup

**Purpose:** Checking domain registration information and identifying domain-related details.

### 3.6 IP Reputation Tools

**Purpose:** Checking whether an IP address has been reported for suspicious or malicious activities.

Example:

- AbuseIPDB: https://www.abuseipdb.com/

### 3.7 Password Strength Checker

**Purpose:** Understanding password strength and identifying weak password patterns.

Example:

- Kaspersky Password Check: https://password.kaspersky.com/

**Important:** Never enter a real password into an online password checker. Use only a dummy password.

---

## 4. Practical Lab / Assignment

### Assignment No. 1

The course introduced three practical tasks to develop basic security investigation skills.

### Task 1 – Malicious URL Analysis

**Objective:** Analyze a suspicious or instructor-provided URL using VirusTotal.

Activities:

1. Open VirusTotal.
2. Select the URL analysis option.
3. Submit a safe, authorized test URL.
4. Review security vendor detection results.
5. Check the URL reputation.
6. Record the findings.

**Expected Learning:**

- Understanding URL reputation.
- Identifying suspicious websites.
- Understanding security vendor detection results.

### Task 2 – WHOIS Lookup and IP Reputation Check

**Objective:** Investigate domain and IP address information.

Activities:

1. Perform a WHOIS lookup for an authorized test domain.
2. Review domain registration information.
3. Identify relevant IP address information.
4. Check IP reputation using an appropriate threat intelligence service.
5. Record suspicious findings.

**Expected Learning:**

- Understanding domain registration information.
- Identifying IP ownership and network information.
- Checking IP reputation.
- Understanding basic threat intelligence.

### Task 3 – Password Strength Analysis

**Objective:** Understand password strength and password security.

Activities:

1. Open the Kaspersky Password Check website.
2. Enter a dummy test password.
3. Review the password strength result.
4. Understand why weak passwords are dangerous.

**Expected Learning:**

- Understanding password strength.
- Recognizing weak password patterns.
- Learning the importance of strong and unique passwords.

**Security Precautions:**

- Never submit real passwords.
- Do not upload confidential files or private company URLs to public analysis platforms without authorization.
- Use only authorized test data.

## 6. Conclusion

Day 3 helped me understand the fundamental concepts of cybersecurity and how different security technologies work together to protect an organization.

I also learned how SOC analysts use SIEM, security logs, network monitoring, and threat intelligence to identify and investigate suspicious activities.

These concepts provide an important foundation for my future Blue Team and SOC Analyst L1 learning journey.

**Next Learning Focus:** Network Fundamentals and Network Security in greater detail.

---

# 日本語版

## 1. 学習概要（Overview）

Day 3では、サイバーセキュリティの基本概念、主なサイバー脅威、攻撃手法、多層防御、ネットワークセキュリティ、エンドポイントセキュリティ、SOCの業務について学習しました。

今回の学習の目的は、サイバー攻撃の仕組み、組織のシステムを保護する方法、SOCアナリストが不審な活動を検知・調査する方法を理解することです。

---

## 2. 理論・学習内容（Theory）

### 2.1 脅威・脆弱性・リスク

- **Threat（脅威）：** システムやデータに被害を与える可能性がある危険。
- **Vulnerability（脆弱性）：** 攻撃者に悪用される可能性がある弱点。
- **Risk（リスク）：** 脅威が脆弱性を悪用した場合に発生する可能性のある被害。

### 2.2 主なサイバーセキュリティ分野

主な6つの分野について学習しました。

1. ネットワークセキュリティ
2. アプリケーションセキュリティ
3. エンドポイントセキュリティ
4. クラウドセキュリティ
5. ID・アクセス管理（IAM）
6. セキュリティオペレーション

### 2.3 CIAトライアド

CIAトライアドは、情報セキュリティの基本となる3つの原則です。

- **Confidentiality（機密性）：** 許可されていない人から情報を守ること。
- **Integrity（完全性）：** 情報の正確性と信頼性を維持すること。
- **Availability（可用性）：** 必要なときにシステムやデータを利用できること。

### 2.4 主なサイバー脅威

- **Malware（マルウェア）：** システムへの被害や情報の盗難を目的とする悪意のあるソフトウェア。
- **Phishing（フィッシング）：** 偽のメールやWebサイトでユーザーをだまして情報を盗む攻撃。
- **Insider Threat（内部脅威）：** 組織内部の人によって発生するセキュリティリスク。
- **APT（高度持続的脅威）：** 長期間にわたって不正アクセスを維持する高度な攻撃。

### 2.5 主な攻撃の種類

- **Brute Force（ブルートフォース攻撃）：** パスワードを何度も試して不正アクセスを行う攻撃。
- **DDoS（分散型サービス妨害攻撃）：** 複数の送信元から大量の通信を送り、サービスを停止させる攻撃。
- **SQL Injection（SQLインジェクション）：** 悪意のあるSQL文でデータベースを不正に操作する攻撃。
- **Zero-Day Attack（ゼロデイ攻撃）：** 有効な修正や対策が提供される前に脆弱性を悪用する攻撃。

### 2.6 事例研究 – WannaCryランサムウェア

WannaCryは、2017年5月に世界中で発生したランサムウェア攻撃です。

主な内容：

- 脆弱性のあるWindowsシステムを標的にした。
- EternalBlueの脆弱性を悪用した。
- ファイルを暗号化し、ビットコインを要求した。
- 約30万台のシステム、約150か国に被害が発生したと報告されている。

**セキュリティ上の教訓：** 定期的なセキュリティ更新と古いプロトコルの無効化が重要です。

### 2.7 事例研究 – Twitter/Xのビットコイン詐欺

2020年7月、攻撃者が複数の著名なTwitterアカウントに不正アクセスしました。

- 偽のビットコインプレゼント企画を投稿した。
- 送ったビットコインを2倍にして返すと約束した。
- 被害者から暗号資産をだまし取った。

**セキュリティ上の教訓：** アカウント保護、MFA、安全な管理者アクセスが重要です。

### 2.8 サイバーキルチェーン

サイバーキルチェーンは、サイバー攻撃の流れを7つの段階で説明するモデルです。

1. Reconnaissance（偵察）：標的の情報を収集する。
2. Weaponization（武器化）：攻撃用のツールやファイルを準備する。
3. Delivery（配送）：悪意のあるファイルを送る。
4. Exploitation（脆弱性の悪用）：脆弱性やユーザーの行動を悪用する。
5. Installation（インストール）：マルウェアなどをインストールする。
6. Command and Control（C2）：攻撃者のサーバーと通信する。
7. Actions on Objectives（目的の実行）：攻撃者の最終目的を実行する。

### 2.9 多層防御（Defense-in-Depth）

多層防御とは、複数のセキュリティ対策を組み合わせて組織を保護する方法です。

主な防御層：

- 境界セキュリティ
- ネットワークセキュリティ
- エンドポイントセキュリティ
- アプリケーションセキュリティ
- データセキュリティ
- 人的セキュリティ

**重要な考え方：** 1つの防御層が突破されても、ほかの防御層によって被害を減らすことができます。

### 2.10 ネットワークセキュリティの基礎

SOCアナリストに必要なネットワークの基本概念です。

- **IP Address（IPアドレス）：** IPネットワーク上の機器を識別するアドレス。
- **Port（ポート）：** 通信先やサービスを識別する番号。
- **Protocol（プロトコル）：** 機器同士が通信するためのルール。
- **Firewall（ファイアウォール）：** セキュリティルールに基づいて通信を制御する。
- **IDS（侵入検知システム）：** 不審な活動を検知してアラートを出す。
- **IPS（侵入防止システム）：** 不審な通信を検知し、遮断することができる。
- **Network Segmentation（ネットワーク分割）：** ネットワークを小さく分割して安全性を高める。

**主なネットワークポート**

- 20/21 – FTP
- 22 – SSH
- 23 – Telnet
- 25 – SMTP
- 53 – DNS
- 80 – HTTP
- 443 – HTTPS
- 3389 – RDP

### 2.11 エンドポイントセキュリティの基礎

エンドポイントセキュリティは、パソコン、ノートPC、サーバーなどを保護する仕組みです。

主な概念：

- **Antivirus（アンチウイルス）：** マルウェアを検知・削除する。
- **EDR：** 端末の活動を監視し、脅威の検知と対応を支援する。
- **System Hardening（システムの強化）：** 安全な設定によってシステムの弱点を減らす。
- **Patching（パッチ適用）：** ソフトウェアの更新によって既知の脆弱性を修正する。

### 2.12 メールとWebのセキュリティ

- **Phishing Detection（フィッシング検知）：** 不審なメールやメッセージを見つける。
- **URL Filtering（URLフィルタリング）：** 悪意のあるWebサイトへのアクセスをブロックする。
- **Sandboxing（サンドボックス）：** 隔離された環境で不審なファイルを分析する。

### 2.13 SIEM – セキュリティ情報イベント管理

SIEMは、複数の情報源からログを収集・分析する集中管理型のセキュリティプラットフォームです。

主な機能：

- ログ収集
- ログ分析
- イベント相関分析
- アラート生成
- セキュリティ監視

主なSIEMツール：

- Splunk
- Microsoft Sentinel
- IBM QRadar

### 2.14 主なログの種類

SOCアナリストは、セキュリティインシデントの調査にさまざまなログを使用します。

- **Windows Logs：** ログイン試行、ユーザー活動、プロセス作成。
- **Firewall Logs：** ブロックされた通信、不審な接続、ポートスキャン。
- **DNS Logs：** ドメインへの問い合わせ、不審なDNS通信。
- **VPN Logs：** リモートアクセス、接続時刻、送信元IPアドレス。

### 2.15 インシデント検知とトリアージ

SOC L1の基本的なワークフローです。

1. アラート発生
2. アラートの確認
3. 証拠の収集
4. 深刻度の評価
5. エスカレーション
6. 調査内容の記録

L1アナリストはアラートを確認し、証拠を収集して深刻度を評価します。必要に応じて上位チームへ引き継ぎます。

### 2.16 SOCの主な検知事例

**Brute Force Detection（ブルートフォース攻撃の検知）**

短時間に何度もログインに失敗した場合、パスワードを推測する攻撃の可能性があります。

**Phishing Alert（フィッシングアラート）**

ユーザーから不審なメールの報告があり、調査が必要になります。

**Geo-Login Alert（位置情報に基づく異常ログイン）**

通常とは異なる場所からのログインは、アカウント侵害の可能性があります。

### 2.17 サイバーセキュリティのベストプラクティス

- 強力で異なるパスワードを使用する。
- 多要素認証（MFA）を有効にする。
- ソフトウェアを最新の状態に保つ。
- 信頼できない公共Wi-Fiで重要な操作をしない。
- アンチウイルスとファイアウォールを利用する。
- セキュリティ教育に参加する。

---

## 3. ツールと技術（Tools and Technologies）

今回の学習では、いくつかのサイバーセキュリティツールと技術について学びました。

### 3.1 SIEMツール

**目的：** セキュリティログの収集、分析、相関分析。

例：

- Splunk
- Microsoft Sentinel
- IBM QRadar

### 3.2 アンチウイルスとEDR

**目的：** エンドポイント端末を保護し、不審な活動を検知する。

例：

- Microsoft Defender
- CrowdStrike Falcon
- SentinelOne

### 3.3 ネットワークセキュリティツール

**目的：** ネットワーク通信を監視し、不審な接続を検知する。

例：

- Firewall
- IDS/IPS
- Wireshark

### 3.4 VirusTotal

**目的：** 複数のセキュリティエンジンと脅威情報を利用して、不審なURL、ファイル、ドメイン、IPアドレスを確認する。

Website: https://www.virustotal.com/

### 3.5 WHOIS Lookup

**目的：** ドメインの登録情報や関連情報を確認する。

### 3.6 IP Reputation Tools

**目的：** IPアドレスが不審な活動や悪意のある活動に関係していると報告されているか確認する。

例：

- AbuseIPDB: https://www.abuseipdb.com/

### 3.7 Password Strength Checker

**目的：** パスワードの強度を確認し、弱いパスワードの特徴を理解する。

例：

- Kaspersky Password Check: https://password.kaspersky.com/

**重要：** 実際に使用しているパスワードをオンラインの確認ツールに入力してはいけません。必ずテスト用のダミーパスワードを使用します。

---

## 4. 実践演習・課題（Practical Lab / Assignment）

### Assignment No. 1

今回の講座では、基本的なセキュリティ調査スキルを身につけるため、3つの実践課題が紹介されました。

### Task 1 – Malicious URL Analysis（悪意のあるURLの分析）

**目的：** VirusTotalを使用して、不審なURLまたは講師から指定されたURLを分析する。

実施内容：

1. VirusTotalを開く。
2. URL分析の機能を選択する。
3. 安全で、分析が許可されたテストURLを入力する。
4. セキュリティベンダーの検知結果を確認する。
5. URLのレピュテーションを確認する。
6. 調査結果を記録する。

**学習目標：**

- URLのレピュテーションを理解する。
- 不審なWebサイトを特定する。
- セキュリティベンダーの検知結果を理解する。

### Task 2 – WHOIS Lookup and IP Reputation Check（WHOIS検索とIPレピュテーションの確認）

**目的：** ドメインとIPアドレスの情報を調査する。

実施内容：

1. 許可されたテスト用ドメインのWHOIS検索を行う。
2. ドメインの登録情報を確認する。
3. 関連するIPアドレス情報を調べる。
4. 適切な脅威情報サービスを使ってIPレピュテーションを確認する。
5. 不審な情報があれば記録する。

**学習目標：**

- ドメイン登録情報を理解する。
- IPアドレスの所有者とネットワーク情報を確認する。
- IPレピュテーションを確認する。
- 基本的な脅威インテリジェンスを理解する。

### Task 3 – Password Strength Analysis（パスワード強度の分析）

**目的：** パスワードの強度と安全性を理解する。

実施内容：

1. Kaspersky Password CheckのWebサイトを開く。
2. テスト用のダミーパスワードを入力する。
3. パスワードの強度を確認する。
4. 弱いパスワードが危険な理由を理解する。

**学習目標：**

- パスワードの強度を理解する。
- 弱いパスワードの特徴を知る。
- 強力で安全なパスワードの重要性を学ぶ。

**セキュリティ上の注意：**

- 実際に使用しているパスワードを入力しない。
- 許可なく、機密ファイルや会社の非公開URLを公開分析プラットフォームにアップロードしない。
- 必ず許可されたテストデータを使用する。


## 6. まとめ（Conclusion）

Day 3では、サイバーセキュリティの基本概念と、組織を保護するためにさまざまなセキュリティ技術がどのように連携するかを学びました。

また、SOCアナリストがSIEM、セキュリティログ、ネットワーク監視、脅威インテリジェンスなどを利用して、不審な活動を検知・調査する方法について理解しました。

今回学んだ内容は、今後Blue TeamやSOC Analyst L1の知識と実践スキルを身につけるための重要な基礎になります。

**Next Learning Focus:** Network Fundamentals and Network Security in greater detail.

**次回の学習目標：** ネットワークの基礎とネットワークセキュリティについて、さらに詳しく学習する。

এটাই এক ফাইলের সম্পূর্ণ Day 3 documentation। GitHub-এ `Day-03-Cybersecurity-Fundamentals.md` নামে রাখবে।
