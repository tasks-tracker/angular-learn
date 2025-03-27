🔹 1. Основы Angular
1. Настройка среды и первое приложение
Установка Node.js, npm/yarn

Angular CLI (ng new, ng serve, ng generate)

Структура проекта (src/, angular.json)

2. Компоненты и шаблоны
Создание компонентов (@Component)

Шаблоны (HTML + Angular-синтаксис)

Data Binding

Интерполяция ({{ value }})

Property binding ([property]="value")

Event binding ((event)="handler()")

Two-way binding ([(ngModel)])

3. Директивы
Встроенные директивы:

*ngIf, *ngFor (с trackBy)

ngClass, ngStyle

Создание кастомных директив

4. Pipes (Преобразование данных)
Встроенные (date, currency, json)

Кастомные pipes (@Pipe)

5. Модули (@NgModule)
declarations, imports, exports, providers

Фичи-модули (FeatureModule)

🔹 2. Работа с данными
1. Сервисы и Dependency Injection (DI)
Создание сервисов (@Injectable)

Иерархия инжекторов (providedIn: 'root' vs модульные провайдеры)

2. HTTP-запросы (HttpClient)
GET, POST, PUT, DELETE

Обработка ошибок (catchError)

Интерсепторы (HttpInterceptor)

3. Формы
Template-driven формы (ngModel, NgForm)

Reactive формы (FormControl, FormGroup, FormArray)

Валидация (встроенная и кастомная)

🔹 3. Роутинг и навигация
RouterModule, Routes

routerLink, router-outlet

Параметры маршрутов (/products/:id)

Lazy Loading (ленивая загрузка модулей)

Guards (CanActivate, CanDeactivate)

Resolvers (предзагрузка данных)

🔹 4. Управление состоянием (State Management)
1. RxJS и Observables
Observable, Subject, BehaviorSubject

Операторы (map, filter, switchMap, debounceTime)

Отписка от подписок (async pipe, takeUntil)

2. Глобальное состояние
Сервисы с BehaviorSubject

NgRx (если проект большой):

Actions, Reducers, Effects, Selectors

🔹 5. Оптимизация и продвинутые темы
1. Производительность
ChangeDetectionStrategy.OnPush

trackBy в *ngFor

Ленивая загрузка модулей и компонентов

2. SSR и PWA
Angular Universal (Server-Side Rendering)

Service Workers (Progressive Web Apps)

3. Тестирование
Unit-тесты (Jasmine, Karma)

E2E-тесты (Cypress, Protractor)

4. Интеграции
UI-библиотеки (Angular Material, PrimeNG)

Графики (Chart.js, D3.js)

Аутентификация (JWT, OAuth)
