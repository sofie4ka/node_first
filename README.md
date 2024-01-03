# node_first

Website with a deployed project:
https://node-first-woad.vercel.app/
Answers on questions:
### dev Deps vs Deps
Залежно від оточення, команди для встановлення можуть відрізнятись. Деякі команди встановлюють і devDep, і звичайні залежності, а інші — лише звичайні. DevDep призначені для режиму розробки.

### Чому у нас окремі інструменти для форматування/лінтування?
Лінтування пов'язане з конкретною мовою програмування, тоді як форматування може застосовуватись до різних форматів. Є інструменти, що форматують багато типів файлів, наприклад, Prettier форматує як Markdown, так і JSON.

### Різниця між VPS/FaaS?
VPS — це віртуальні сервери, які працюють постійно, в той час як FaaS активуються лише при виклику. Це робить FaaS економічнішими, оскільки вони не активні без потреби. Проте для фонових завдань, постійної роботи певних процесів або зберігання даних в пам'яті необхідні VPS.

### Навіщо потрібні peerDeps?
peerDeps дозволяють розробникам бібліотек вказувати, які додаткові залежності потрібні для їхніх пакетів. Це корисно, наприклад, для зазначення сумісної версії іншої бібліотеки, необхідної для працездатності.

### npm i vs npm ci
Краще використовувати npm ci, оскільки це гарантує стабільну установку залежностей з package-lock.json. Це дозволяє уникнути випадкових проблем зі зламаними залежностями. Використання ci гарантує точність встановлених версій залежностей, усуваючи можливість несподіваних змін, які можуть виникнути при використанні npm i.
