Window registry & batch files for PC performance 

# Registry
## Keyboard
- HKEY_CURRENT_USER\Control Panel\Accessibility\Keyboard Response
- HKEY_CURRENT_USER\Control Panel\Keyboard

## Memory
- HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\Ndu
- NDU 기능으로 인한 메모리 누수 방지

# Batch
## 수신 창 자동 조정 수준 변경
- TCP 통신 시 데이터 수신 속도 증가
- default: normal
- other options: highlyrestricted, restricted, experimental, normal, disable
- https://docs.microsoft.com/ko-kr/troubleshoot/windows-server/networking/tcpip-performance-known-issues

## 최고의 성능
- 설정-전원 및 절전-추가 전원 설정 or 제어판\하드웨어 및 소리\전원 옵션
![image](https://user-images.githubusercontent.com/20695889/178247341-ebcaeea2-a606-472b-84e7-ec5f25eb10e4.png)
