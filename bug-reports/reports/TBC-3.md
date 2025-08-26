DevTools Bugs (TBC-2) \[TBC-3\] 
# Failed to load resource: net::ERR_NAME_NOT_RESOLVED 
Created: 16/Jul/25 Updated: 17/Jul/25
Resolved: 17/Jul/25 Status:DoneProject:Testing
Booking.comComponents:None Affects versions:None Fix versions:None
Parent:DevTools Bugs Type: Bug Priority: Medium Reporter: ярослав
николаев Assignee: ярослав николаев Resolution: Done Votes: 0 Labels:
booking, console, debug, javascript Remaining Estimate:Not Specified
Time Spent:Not Specified Original estimate:Not Specified Environment:
Среда (Environment): \* OS: Windows 11 Version 24H2 (Build 26100.4652)
\* Browser: Chrome 138.0.7204.158 (Official Build) (64-bit) \* Mode:
Guest Mode \* User: Not logged in \* Device: Desktop, 1920x1080 Team:
Description Шаги для воспроизведения: 1. Открыть Google Chrome (можно в
Guest Mode) 2. Перейти на сайт: https://www.booking.com 3. Открыть
DevTools → вкладка Console 4. Наблюдать ошибку: Фактический результат:
Ошибка появляется в консоли при загрузке сайта. Указывает на то, что
один из ресурсов не был загружен из-за проблем с DNS. Ожидаемый
результат: Все ресурсы сайта должны загружаться корректно без ошибок.

Дополнительно: \* Ошибка может быть связана с внешним скриптом или
устаревшей ссылкой. \* Не влияет на основной функционал сайта, но
указывает на возможную недоступность стороннего ресурса. Generated at
Wed Aug 20 19:29:50 UTC 2025 by ярослав николаев using Jira
1001.0.0-SNAPSHOT#100288-rev:f2dd5282f491cef6180dfa6d0429a5f16369d3e5.
