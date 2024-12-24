**Команда для терминала(command line) для определения activityName и package ,**
**необходимо навестись на конкретный экран, а затем ввести команду:**  
  
-для mac/linux  
adb shell dumpsys window | grep -E 'mCurrentFocus'  
-для windows  
adb shell dumpsys window | find "mCurrentFocus"

**Команда для установки приложения в телефон посредством adb**
**через командную строку (command line)**

adb install C://... путь к файлу apk
