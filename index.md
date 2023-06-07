# Überprüfen ob man mit der Malware infiziert ist

## Möglichkeit 1 (Windows):

1. öffnen der Website https://prismlauncher.org/news/cf-compromised-alert/
2. ![grafik](https://github.com/itsmetin/newsreport/assets/130148056/eea7be07-31b3-47b6-aecd-eea98fecf24e) Programm für Windows herunterladen
3. Windows + R drücken, sodass sich ein Programm namens "Ausführen" öffnet
4. Das hier eingeben: ``` powershell -executionpolicy bypass -file "%UserProfile%\Downloads\check_cf.ps1"```
5. Enter drücken, Powershell öffnet sich und man erfährt ob man infiziert ist.

Beispiel:

![grafik](https://github.com/itsmetin/newsreport/assets/130148056/02aff1dc-c01c-4df5-a32b-fa44deca3f0f)
