# Cybersecurity Journey

Практический лог моего пути в кибербезопасность: разведка, эксплуатация и разбор уязвимостей на учебных площадках (VulnHub, TryHackMe, Metasploitable2 и др.)

## Обо мне
Изучаю кибербезопасность с фокусом на Blue Team / SOC. Базовые навыки: Linux, сети, Python. Веду этот репозиторий, чтобы фиксировать методологию, а не только результат — включая ошибки и то, как их исправлял.

## Стек инструментов
`Nmap` · `Metasploit Framework` · `John the Ripper` · `Hydra` · `Wireshark` · `Snort` · `Kali Linux` · `VirtualBox`

## Пройденные машины / комнаты

| Проект | Платформа | Статус | Техники |
|---|---|---|---|
| [Metasploitable2](./metasploitable2/README.md) | Локально (VirtualBox) | ✅ Root получен | Service exploitation, backdoors, password cracking |
| TryHackMe — Neighbour | TryHackMe | 🔄 В процессе | IDOR |

## Roadmap
- [x] Настройка лаборатории (Kali + VirtualBox + изолированная сеть)
- [x] Базовая разведка через Nmap
- [x] Эксплуатация известных бэкдоров (vsftpd, Samba, UnrealIRCd)
- [x] Взлом хешей паролей (John the Ripper)
- [ ] Веб-уязвимости (DVWA, OWASP Top 10)
- [ ] Blue Team: настройка Snort/Wazuh, детект собственных атак
- [ ] TryHackMe SOC Level 1 path

## Дисклеймер
Все атаки проводились исключительно на специально подготовленных учебных машинах в изолированной локальной сети или на платформах, явно предназначенных для этого (VulnHub, TryHackMe). Никакие реальные системы третьих лиц не атаковались.
