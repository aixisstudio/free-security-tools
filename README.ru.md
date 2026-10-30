# Free Security Tools

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | **Русский**

Бесплатные open-source инструменты безопасности для всех

##Пароли и секреты

| Инструмент | Описание
|---|---|
| [KeePassXC] (https://github.com/keepassxreboot/keepassxc) | Оффлайн менеджер паролей — стандарт сообщества |
| [Bitwarden] (https://github.com/bitwarden) | Менеджер паролей полного стека, который вы можете самостоятельно разместить |
[Vaultwarden] (https://github.com/dani-garcia/vaultwarden) | Легкий Rust Bitwarden-совместимый сервер
| [pass] (https://www.passwordstore.org/) | Менеджер паролей Unix — gpg + git |
| [age] (https://github.com/FiloSottile/age) | Современное, простое шифрование файлов
[GnuPG] (https://gnupg.org/) Классический пакет OpenPGP

Оригинальное название: Two-Factor Auth

| Инструмент | Описание
|---|---|
| [Aegis] (https://github.com/beemdevelopment/Aegis) | Приложение Android 2FA с открытым исходным кодом
[Ente Auth] (https://github.com/ente-io/ente) | Сквозной зашифрованный аутентификатор |
[2FAS] (https://github.com/twofas) Бесплатный аутентификатор для iOS / Android

Оригинальное название: Endpoint & Malware Defense

| Инструмент | Описание
|---|---|
| [ClamAV](https://github.com/Cisco-Talos/clamav) | Антивирусный движок с открытым исходным кодом |
[YARA] (https://github.com/VirusTotal/yara) | Соответствие шаблонам для идентификации вредоносных программ |
[Lynis] (https://github.com/CISOfy/lynis) | Аудитор закалки системы
[OpenSCAP] (https://github.com/OpenSCAP/openscap) | Сканер соответствия требованиям безопасности
[Chkrootkit] (https://github.com/Magentah/chkrootkit) | Обнаружение локальных руткитов

###Сетевая безопасность

| Инструмент | Описание
|---|---|
| [Snitch] (https://github.com/aixisstudio/Snitch) | Брандмауэр приложений — смотрите и блокируйте каждое соединение на процесс, правила Sigma, 8 языков пользовательского интерфейса |
[Wireshark] (https://gitlab.com/wireshark/wireshark) | Анализатор протоколов
| [Nmap] (https://github.com/nmap/nmap) | Открытие сети и сканирование портов
[Zeek] (https://github.com/zeek/zeek) | Монитор сетевой безопасности
[CrowdSec] (https://github.com/crowdsecurity/crowdsec) | IPS, управляемый сообществом
[Pi-hole] (https://github.com/pi-hole/pi-hole) | Блокировка сетевого трекера

##   Оценка уязвимости

| Инструмент | Описание
|---|---|
[OpenVAS / GVM] (https://github.com/greenbone/openvas-scanner) | Полный сканер уязвимостей
| [Nuclei] (https://github.com/projectdiscovery/nuclei) | Быстрый шаблонный сканер |
[Nikto] (https://github.com/sullo/nikto) | Сканер веб-сервера
| [ZAP] (https://github.com/zaproxy/zaproxy) | Прокси-сервер безопасности веб-приложения OWASP
| [sqlmap] (https://github.com/sqlmapproject/sqlmap) | Автоматизация SQL-инъекций
| [grype] (https://github.com/anchore/grype) | Сканер контейнеров и файловых систем
| [trivy] (https://github.com/aquasecurity/trivy) | Все-в-одном сканере (изображения, IaC, repos) |

##Крипто и анонимность

| Инструмент | Описание
|---|---|
[VeraCrypt] (https://veracrypt.fr) | Шифрование диска (преемник TrueCrypt)
[Tor Browser] (https://www.torproject.org/) | Анонимный просмотр
https://tails.net/ - Amnesic Incognito Live OS
[Сигнал] [https://github.com/signalapp] [Частный мессенджер]
[Криптоматор] (https://github.com/cryptomator/cryptomator) | Облачное шифрование на стороне клиента

## песочница и анализ

| Инструмент | Описание
|---|---|
[Любой.] Run community [https://any.run/] | Интерактивная песочница вредоносных программ
| [CAPEv2](https://github.com/kevoreilly/CAPEv2) | Самоходная песочница вредоносных программ |
| [pestudio](https://www.winitor.com/) | Статический анализ вредоносных программ для файлов PE |
[Гидра] (https://github.com/NationalSecurityAgency/ghidra) | Обратно-инженерный комплекс АНБ |

###Тренировки

| Платформа | Описание
|---|---|
[HackTheBox] (https://www.hackthebox.com/) | Хакерские лаборатории и проблемы
[TryHackMe] (https://tryhackme.com/) | Учебные комнаты по безопасности
[OWASP Juice Shop] (https://github.com/juice-shop/juice-shop) | Умышленно уязвимое веб-приложение
[DVWA] (https://github.com/digininja/DVWA) | Damn Vulnerable Web App
[picoCTF] (https://picoctf.org/) | CTF для начинающих

Инструменты безопасности Dev Security Tools

| Инструмент | Описание
|---|---|
[Гит-секреты] (https://github.com/awslabs/git-secrets) | Остановка ваших учетных данных
[truffleHog] (https://github.com/trufflesecurity/trufflehog) | Найти просочившиеся ключи в истории git
| [Gitleaks] (https://github.com/gitleaks/gitleaks) | Быстро секретный сканер для репо |
[Semgrep] (https://github.com/semgrep/semgrep) | Шаблоны безопасности на уровне кода
[Bearer] (https://github.com/bearer/bearer) | Безопасность данных
[OWASP Dependency-Check] (https://owasp.org/www-project-dependency-check/) | Сканер уязвимой зависимости
[Syft] [https://github.com/anchore/syft] [поколение SBOM]
[Чекков] (https://github.com/bridgecrewio/checkov) | Сканирование безопасности IaC

###Угроза разведки
| Инструмент | Описание
|---|---|
[MISP] (https://github.com/MISP/MISP) | Платформа обмена информацией об угрозах
[OpenCTI] (https://github.com/OpenCTI-Platform/opencti) | Управление киберугрозами
[Yeti] (https://github.com/yeti-platform/yeti) | Управление МОК |
[AbuseIPDB] (https://www.abuseipdb.com/) | База данных о злоупотреблении IP сообщества

## - Дом и малый офис
| Инструмент | Описание
|---|---|
[Home Assistant + Frigate] (https://frigate.video/) | NVR с обнаружением объектов ИИ
| [Nextcloud] (https://github.com/nextcloud/server) | Файлы с самостоятельным размещением, заменяющие Dropbox |
[Иммих] (https://github.com/immich-app/immich) | Самостоятельно размещенные фотографии Google
[Vaultwarden] (https://github.com/dani-garcia/vaultwarden) | Самостоятельный Bitwarden |

---
## Участие

Pull request'ы приветствуются — открой PR, он будет проверен и принят. Ведёт [aixisstudio](https://github.com/aixisstudio), автор [Snitch](https://github.com/aixisstudio/Snitch) — open-source application firewall.

## Лицензия: MIT
