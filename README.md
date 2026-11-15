
# Calculator — Collatz

<p align="center">

[![C++](https://img.shields.io/badge/C%2B%2B-20-00599C.svg?logo=cplusplus)](https://isocpp.org/)
[![Algorithm](https://img.shields.io/badge/Algorithm-Collatz-blueviolet.svg)](https://en.wikipedia.org/wiki/Collatz_conjecture)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.html)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](https://github.com/rkdgus127/Calculator)

</p>
---

프로그램의 규모가 커지고 연산량이 증가할수록 실행 시간과 시스템 자원 사용량도 증가합니다.

Collatz는 이러한 연산 부담을 측정하기 위해 제작되었습니다.

### Features

- **Performance Benchmark**
- **Progress Logging**
- **Overflow Detection**
- **Maximum Steps**

```text
[COLLATZ] Checked: 100000 | Verified: 100000 | Overflow: 0 | Max Steps: 350
[COLLATZ] Checked: 300000 | Verified: 100000 | Overflow: 0 | Max Steps: 442
[COLLATZ] Checked: 400000 | Verified: 100000 | Overflow: 0 | Max Steps: 440
```

### Log Format

| Field | Description |
|:---|:---|
| `Checked` | 누적 검사 수 |
| `Verified` | 해당 구간에서 검증된 수 |
| `Overflow` | 정수 오버플로 발생 횟수 |
| `Max Steps` | 검사 과정에서 기록된 최대 반복 횟수 |

## License

This project is licensed under the **GNU General Public License v3.0**.

You may use, modify, and redistribute this software under the terms of GPL-3.0.

See [LICENSE](LICENSE) for more information.

---

<p align="center">
  <sub>Calculate. Measure. Challenge.</sub>
</p>
