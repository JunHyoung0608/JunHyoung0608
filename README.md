![header](https://capsule-render.vercel.app/api?type=waving&color=8a2be2&height=200&section=header&text=Welcome%20to%20Junbro's%20GitHub&fontSize=45&animation=fadeIn&fontAlignY=40)

<div align="center">

**안녕하세요! 탄탄한 논리와 최적화로 문제를 해결하는 시스템 반도체 엔지니어 이준형입니다.**
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

| 프로젝트명 | 분야 (Category) | 주요 기술 및 내용 | 핵심 성과 / 트러블슈팅 |
| :--- | :--- | :--- | :--- |
| **[저전력 CNN 가속기 기반 제스처 사진기](https://github.com/junbro0608/CNN-Gesture-Camera)** | SoC / AI Accelerator | • Zynq-7000 기반 경량 CNN 가속기(Verilog) 설계 및 Jetson 연동<br>• 비대칭형 Cache, 타일 재사용, 곱셈기 제거(Shift & Add) 최적화<br>• MediaPipe & LSTM 기반 손 제스처 추론 파이프라인 구축 | • 메모리 접근 50% 감소 및 저전력 상시 감지 구현<br>• Critical Path 데이터 경로 튜닝으로 Timing Closure (WNS +0.12ns, TNS 0ns) 달성<br>• 추론/영상 렌더링 멀티프로세싱 분리로 실시간 FPS 확보 |
| **[AXI 주변장치 설계 및 UVM 검증](https://github.com/junbro0608/AXI-Based-Soc-Design-and-UVM-Verification)** | SoC / Verification | • MicroBlaze 기반 AXI4 Lite SPI/I2C Master 설계<br>• HW-HAL-Driver-Application SW 계층 구조 구축<br>• UVM 검증 환경(Driver, Monitor, Scoreboard) 구축 | • AXI 핸드셰이크 및 데이터 송수신 무결성 검증 (Error 0)<br>• 1-tick 'Done' 신호 폴링 누락 문제를 하드웨어 'Done Flag Logic' 추가로 해결 |
| **[RISC-V MCU 기반 게임기](https://github.com/junbro0608/MCU_Up_Down_Game)** | SoC / MCU | • RISC-V (RV32I) 아키텍처 기반 MCU 시스템 구조 설계<br>• APB 버스 통합 및 R-type 최적화 데이터패스/컨트롤러 구현 | • 하드웨어 프로세서 설계를 통한 실시간 Up/Down 게임 로직 구동 |
| **[FPGA 기반 비전 연주 시스템](https://github.com/junbro0608/VGA_CAM_Project)** | FPGA / Vision | • 6대 카메라 및 다중 FPGA(Basys3) 간 SPI/I2C 연동<br>• YCoCg 2:1 압축 및 핑퐁(Double Buffering) 메모리 제어 | • 모자이크 2X3 영상 합성 및 12-bit 음계 검출 시스템 구현 |
| **[멀티 페리퍼럴 통합 제어기](https://github.com/junbro0608/Peripheral-Multiple-Control-System)** | FPGA / Hardware | • Basys3(Artix-7) 활용 디지털 시계, 스톱워치, 센서 통합 제어<br>• `AsciiSender` FSM, 동기식 원형 `TX_FIFO`, `TX_ARBITER` 설계 | • 물리 버튼 및 UART 인터페이스를 통한 페이로드 전송 및 우선순위 제어 |
| **[AI 운전자 졸음 감지 시스템](https://github.com/junbro0608/Monitor-drowsy-driving)** | On-Device AI | • Jetson Orin Nano 기반 로컬 LLM(Ollama) 및 STT/TTS 연동<br>• YOLO Pose 머리 기울기 계산 및 눈 상태(EAR) 분석 로직 구현 | • 비전, 오디오, LLM 파이프라인 멀티프로세스 통합으로 실시간 졸음 감지 및 음성 경고 제공 |
| **[시각장애인용 점자 인식 및 음성 출력](https://github.com/junbro0608/Braille-reading-and-voice-output-programs-for-the-visually-impaired)** | Computer Vision | • YOLOv5 활용 시각장애인용 실시간 점자 인식 알고리즘 구현<br>• 인식된 텍스트를 오디오로 변환하는 TTS 음성 출력 시스템 적용 | • 딥러닝 기반 객체 인식을 실생활 보조기기 프로그램으로 확장 |

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
  </a>
</div>

---

## 📫 Contact

<div align="center">
  <a href="mailto:junhyung0608@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</div>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=8a2be2&height=100&section=footer)
