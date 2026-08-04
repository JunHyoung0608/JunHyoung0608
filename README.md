![header](https://capsule-render.vercel.app/api?type=waving&color=8a2be2&height=200&section=header&text=Welcome%20to%20Junbro's%20GitHub&fontSize=45&animation=fadeIn&fontAlignY=40)

<div align="center">

**시스템 반도체 엔지니어 | 하드웨어 설계 및 UVM 검증**
*RISC-V 아키텍처, FPGA 플로우, 그리고 최신 검증 방법론을 끊임없이 탐구합니다.*

</div>

---

## 🛠️ Technical Skills

### 💡 Hardware Design & Verification
<img src="https://img.shields.io/badge/Verilog_HDL-6A0DAD?style=for-the-badge&logo=cpu&logoColor=white" /> <img src="https://img.shields.io/badge/SystemVerilog-6A0DAD?style=for-the-badge&logo=intel&logoColor=white" /> <img src="https://img.shields.io/badge/UVM-1E90FF?style=for-the-badge&logo=codeforces&logoColor=white" />

### 💻 Software Development
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" /> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />

---

## ⚙️ Engineering Tools & Platforms

| Category | Tools & Platforms | Description |
| :--- | :--- | :--- |
| **Verification** | `UVM`, `VCS`, `Verdi` | UVM Testbench 아키텍처 구성, SVA, FSDB 디버깅 및 커버리지 분석 |
| **Simulation** | `ModelSim`, `Vivado Simulator` | RTL 시뮬레이션 및 기능 검증 |
| **FPGA Flow** | `Vivado`, `Quartus` | 합성(Synthesis), 타이밍 클로저 및 비트스트림 생성 |
| **Hardware** | `Basys3 (Artix-7)`, `Jetson Orin Nano` | 타겟 보드 포팅 및 하드웨어 디버깅 |

---

## 🚀 Featured Projects

### 🔍 System-on-Chip (SoC) 및 검증
* **SoC AXI Peripheral (SPI & I2C) 설계 및 UVM 검증**[cite: 5]
  * MicroBlaze용 AXI4 Lite 기반 SPI/I2C Master 하드웨어 모듈을 설계하고, HW-HAL-Driver-Application으로 이어지는 소프트웨어 계층 구조 구축.[cite: 5]
  * UVM 통합 검증 환경(Driver, Monitor, Scoreboard)을 구성하여 AXI 핸드셰이크 과정과 데이터 송수신(Error 0)의 무결성 검증.[cite: 5]
  * **Troubleshooting:** 1-tick 동안만 유지되는 'Done' 신호로 인해 SW 폴링이 불가능했던 문제를 하드웨어 내부에 'Done Flag Logic' 레지스터를 추가하는 방식으로 해결하여 안정적인 SW-HW 동기화 구현.[cite: 5]
* **RISC-V (RV32I) MCU 시스템 설계**
  * APB 버스 통합 및 핵심 코어 프로세서 아키텍처 설계
  * R-type 명령어 체계에 최적화된 데이터패스(Datapath) 및 컨트롤러 구현
* **UVM 기반 통합 검증 환경 구축**
  * APB RAM 및 UART 컨트롤러를 위한 검증 환경(Driver, Monitor, Scoreboard) 구축

### 📟 FPGA 및 하드웨어 설계
* **FPGA 기반 On-Device 통합 제어 시스템**[cite: 3]
  * Basys3(Artix-7)를 활용하여 디지털 시계, 스톱워치 및 센서(HCSR04, DHT11)를 물리 버튼과 UART로 제어하는 하드웨어 시스템 설계.[cite: 3]
  * 페이로드를 ASCII로 변환해 전송하는 `AsciiSender` FSM, 동기식 원형 `TX_FIFO`, 그리고 송신 우선순위를 제어하는 `TX_ARBITER` 설계 및 검증.[cite: 3]
* **하드웨어 기반 레트로 게임 (Basys3)**
  * Verilog를 활용한 크롬 공룡 게임(좌측으로 이동하는 장애물 렌더링) 및 테트리스 로직 설계
  * VGA 및 UART 디스플레이 커스텀 드라이버 구현

### 🤖 On-Device AI 및 컴퓨터 비전
* **AI 운전자 모니터링 시스템 (KCCI On-Device AI)**[cite: 4]
  * Jetson Orin Nano 기반으로 로컬 LLM(Ollama)과 STT/TTS를 연동해 상황 맞춤형 음성 경고를 제공하는 졸음 감지 시스템 개발.[cite: 4]
  * YOLO Pose를 활용한 머리 기울기 계산 로직을 구현하고, 비전, 오디오, LLM 파이프라인을 백그라운드/포그라운드 프로세스로 완벽하게 통합.[cite: 4]
* **2024 캡스톤 디자인: AI 점자 시스템**
  * YOLOv5를 활용한 시각장애인용 점자 인식 및 음성 출력 프로그램 설계

---

## 🏆 Honors & Awards

> **금상 (Gold Prize)** · 제 15 회 대한전기학회 산업전기응용부문회 대학생 작품 경진대회 (2024)  
> **우수상 (Excellence Award)** · CISC Career Day (2024)

---

## 📊 GitHub Statistics

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=junbro0608&theme=dracula&hide_border=true" alt="GitHub Streak" height="150" />
  <br><br>
  <a href="https://github.com/vn7n24fzkq/github-profile-summary-cards">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=junbro0608&theme=dracula" alt="Top Langs" />
  </a>
</div>

---

## 📫 Contact

<div align="center">
  <a href="mailto:[Your Email Here]"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="[Your LinkedIn Link Here]"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</div>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=8a2be2&height=100&section=footer)
