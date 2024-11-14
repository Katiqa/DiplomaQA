<h1>Дипломный проект "QA Engineer"</h1>
<h2>Запуск автотестов</h2>
<details><summary>Предусловия</summary>
    <ul>
        <li>Установлена Android Studio</li>
        <li>Установлена последняя стабильная версия Android SDK</li>
        <li>Android эмулятор с API 29, с русским языком системы</li>
        <li>Установлен Allure</li>
    </ul>
</details>

<ol>
    <<li>Открыть репозиторий в Android Studio.</li>
    <li>Установить JAVA, используемую в проекте, на JAVA_HOME.</li>
    <li>Собрать проект.</li>
    <li>Запустить эмулятор Android или устройство с API 29.</li>
    <li>Выполнить тесты командой "./gradlew connectedAndroidTest" в терминале Android Studio.</li>
    <li>После завершения автотестов, сохранить папку "allure-results" по пути "Device Explorer/sdcard/googletests/test_outputfiles/allure-results".</li>
    <li>В папке на уровень выше allure-results выполнить команду "allure serve", чтобы получить визуализацию результатов тестов в формате index.html.</li>
</ol>
