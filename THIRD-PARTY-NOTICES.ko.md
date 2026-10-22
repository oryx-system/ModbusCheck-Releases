# Modbus Check 타사 구성요소 고지

이 문서는 Modbus Check 자체의 사용조건과 타사 구성요소의 라이선스를 구분하기 위한 고지입니다. 타사 구성요소에는 각각의 원본 라이선스가 적용되며, 그 라이선스가 부여하는 권리를 Modbus Check 자체 사용조건으로 축소하지 않습니다.

현재 운영 패키지 32개가 모두 원본 라이선스 파일을 포함하는지 확인했습니다. 원본 라이선스·고지 파일 39개의 내용을 배포 manifest의 SHA256과 대조한 검토 복사본을 `notices/`에 원래 경로대로 보관했습니다. 파일명·저작권·허가·면책 문구를 변경하지 않았습니다.

주요 구성요소는 다음과 같습니다.

| 구성요소 | 기준 버전 | 라이선스 및 고지 |
|---|---|---|
| Chart.js | 4.5.1 | MIT |
| Tabulator | 6.6.1 | MIT |
| modbus-serial | 8.0.25 | ISC |
| serialport / bindings-cpp | 13.0.0 | MIT |
| rotating-file-stream | 3.2.10 | MIT |
| fflate | 0.8.3 | MIT |
| i18next | 26.4.7 | MIT |
| SheetJS Community Edition | 0.20.3 | Apache-2.0 |
| Lucide 정적 아이콘 | 기존 고정 자산 | ISC 및 Feather 유래 아이콘의 MIT 고지 |
| Node.js | 24.22.1 기준 | Node와 포함 구성요소의 전체 `runtime/LICENSE` |

모든 운영 패키지와 해당 고지 경로는 `THIRD_PARTY_NOTICES-INVENTORY.md`와 `package-license-audit.json`을 참고하세요. 원본 SheetJS 패키지에는 별도 NOTICE 파일이 없으며, 전체 LICENSE와 원본 저작권 고지를 유지합니다. 생성 브라우저 번들에 남아 있는 저작권 고지도 제거하지 않습니다.

Windows 설치 파일은 기존 Inno Setup으로 생성합니다. Inno Setup의 원본 저작권과 웹 주소를 제거하지 않았으며, 공식 라이선스는 <https://jrsoftware.org/files/is/license.txt>에서 확인할 수 있습니다. Windows의 기존 .NET Framework와 사용자 PC의 Chrome/Edge는 앱 패키지에 재배포하지 않습니다.

이 파일과 원본 고지 사본을 패키지에 포함합니다. 공식 Node 수정 런타임으로 교체할 때에는 그 버전의 LICENSE와 포함 구성요소 고지를 다시 복사·확인하고, 실제 최종 패키지의 버전·파일 목록으로 이 문서를 갱신합니다. 이 고지는 해당 구성요소에 대한 권리를 제한하지 않습니다.
