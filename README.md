# 🔐 Project Name

> 한 줄 프로젝트 설명
> Example: SSH Brute Force 공격 탐지 및 자동 차단 시스템

---

## 📌 Overview

이 프로젝트는 **어떤 보안 문제를 해결하기 위해 만든 프로젝트인지** 설명합니다.

예시
이 프로젝트는 Linux 서버에서 발생하는 **SSH Brute Force 공격을 탐지하고 자동으로 차단하는 시스템**을 구현하는 것을 목표로 합니다.
로그 분석을 통해 공격 패턴을 탐지하고 자동으로 방화벽 정책을 적용합니다.

---

## 🛠 Tech Stack

| Category      | Technology    |
| ------------- | ------------- |
| OS            | Ubuntu 22.04  |
| Language      | Python / Bash |
| Security Tool | Fail2ban      |
| Log           | auth.log      |
| Firewall      | iptables      |

---

## 🏗 Architecture

```
Attacker
   │
   ▼
SSH Server
   │
   ▼
Log Monitoring Script
   │
   ▼
Attack Detection
   │
   ▼
Firewall (iptables) Block
```

---

## ⚙️ Features

* SSH 로그인 실패 로그 분석
* Brute Force 공격 패턴 탐지
* 공격 IP 자동 차단
* 공격 로그 기록 및 분석

---

## 🚀 How to Run

```bash
git clone https://github.com/yourname/project-name.git

cd project-name

bash install.sh
```

또는

```bash
python3 main.py
```

---

## 📊 Result

테스트 환경에서 공격 시뮬레이션 결과

| Attack Attempt | Detection | Block   |
| -------------- | --------- | ------- |
| 50 Attempts    | Detected  | Blocked |

---

## 📷 Demo

```
/images/demo.png
```

---

## 📚 What I Learned

* Linux 보안 로그 분석
* Brute Force 공격 패턴 이해
* 자동화된 보안 대응 시스템 구현
* iptables 기반 네트워크 차단 정책

---

## 🔗 Related Skills

* Linux Security
* Network Security
* Log Analysis
* Security Automation
