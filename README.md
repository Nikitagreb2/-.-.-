Задание 1
Данная программа предназначена для моделирования и визуализации траектории полета тела, брошенного под углом к горизонту с заданной начальной скоростью. Пользователь вводит начальную скорость и угол броска, после чего программа строит график траектории полета.
Физические формулы
Траектория полета тела описывается следующими уравнениями:
Время полета: [ t_{\text{flight}} = \frac{2 v_0 \sin(\theta)}{g} ]
где:v_0— начальная скорость ,\theta  — угол броска, g  — ускорение свободного падения.
Горизонтальное смещение: [ x(t) = v_0 \cos(\theta) \cdot t ]
Вертикальное смещение: [ y(t) = v_0 \sin(\theta) \cdot t - \frac{1}{2} g t^2 ]
Параметры
Начальная скорость ( v_0 ) (м/с) — скорость, с которой тело брошено.
Угол ( \theta ) (градусы) — угол, под которым тело брошено относительно горизонта.
График
Программа строит график зависимости высоты от дальности, где:
По оси X откладывается дальность (в метрах).
По оси Y откладывается высота (в метрах).
График отображает траекторию полета тела, показывая, как высота изменяется в зависимости от расстояния, пройденного телом.
Задание 2
Данная программа предназначена для моделирования и визуализации гармонических колебаний. Мы вводит параметры колебания, такие как амплитуда, частота и фаза, после чего программа строит график смещения колеблющегося объекта во времени.
Физические формулы
Гармоническое колебание описывается уравнением:
[ x(t) = A \cdot \sin(2 \pi f t + \phi) ]
где:
x(t)  — смещение объекта в момент времени ( t ), A— амплитуда колебания (максимальное смещение), f  — частота колебания (в Герцах), \phi  — фаза колебания , t  — время.
Фаза ( \phi ) переводится из градусов в радианы с помощью формулы:
[ \phi_{\text{rad}} = \frac{\pi}{180} \cdot \phi_{\text{deg}} ]
Параметры
Амплитуда ( A ) (м) — максимальное смещение колеблющегося объекта от положения равновесия.
Частота ( f ) (Гц) — количество колебаний в секунду.
Фаза ( \phi ) (градусы) — начальная фаза колебания, определяющая смещение в начале отсчета времени.
График
Программа строит график зависимости смещения от времени, где:
По оси X откладывается время (в секундах).
По оси Y откладывается смещение (в метрах).
График отображает, как смещение колеблющегося объекта изменяется во времени, демонстрируя характерные колебания синусоидальной формы.
Задание 3
Данная программа предназначена для моделирования процесса охлаждения тела в окружающей среде с использованием закона охлаждения Ньютона. Мы вводим начальную температуру тела, температуру окружающей среды и коэффициент теплообмена, после чего программа строит график изменения температуры тела во времени.
Физические формулы
Процесс охлаждения тела описывается уравнением Ньютона о охлаждении:
[ T(t) = T_{\text{env}} + (T_0 - T_{\text{env}}) \cdot e^{-kt} ]
где: T(t) — температура тела в момент времени ( t ),T_0— начальная температура тела,
T_{\text{env}}— температура окружающей среды, k  — коэффициент теплообмена, t  — время, e — основание натурального логарифма.
Параметры
Начальная температура ( T_0 ) (°C) — температура тела в начале процесса охлаждения.
Температура окружающей среды ( T_{\text{env}} ) (°C) — температура окружающей среды, в которой происходит охлаждение.
Коэффициент теплообмена ( k ) (1/с) — коэффициент, характеризующий скорость теплообмена между телом и окружающей средой.
График
Программа строит график зависимости температуры тела от времени, где:
По оси X откладывается время (в секундах).
По оси Y откладывается температура тела (в °C).
График отображает, как температура тела изменяется со временем, приближаясь к температуре окружающей среды.
Задание 4
Эта программа моделирует интерференцию двух волн и визуализирует результаты с помощью графиков. Она позволяет пользователю вводить параметры обеих волн — амплитуды, частоты и фазы — и затем строить три графика: для каждой волны отдельно и результирующей волны после сложения.
Физические формулы
y1 = A1sin(2πf1t + φ1)
y2 = A2sin(2πf2t + φ2)
yрезультирующая = y1 + y2
Где: (y1, y2 )- смещения первой и второй волн, (A1, A2 )- амплитуды первой и второй волн, (f1, f2 )- частоты первой и второй волн, (φ1, φ2 )- фазы первой и второй волн, t – время.
Параметры
Амплитуда первой волны (A1A1) — в метрах.
Частота первой волны (f1f1) — в герцах.
Фаза первой волны (φ1φ1) — в градусах.
Амплитуда второй волны (A2A2) — в метрах.
Частота второй волны (f2f2) — в герцах.
Фаза второй волны (φ2φ2) — в градусах.
График
Программа строит три графика:
1.	График колебания первой волны y1(t)y1(t).
2.	График колебания второй волны y2(t)y2(t).
3.	График результирующего колебания yрез(t)yрез(t), полученного сложением двух волн.
Все графики отображаются на одном окне приложения, где ось X представляет время, а ось Y — смещение волн.
Задание 5
Программа моделирует поведение идеального газа на основе уравнения состояния. Пользователь может вводить температуру и количество вещества, чтобы увидеть зависимость давления от объема газа. Результаты визуализируются на графике.
Физические формулы
Уравнение состояния идеального газа: p = (nRT) / V, где:
p - давление (Па), V - объем (м³), n - количество вещества (моль), R - универсальная газовая постоянная (8.314 Дж/(моль·К)), T - абсолютная температура (К).
Параметры
Температура (К)
Количество вещества (моль)
Единицы измерения давления (Па или атм)
График
Программа строит график зависимости давления (p) от объема (V). На графике:

* Ось X - объем (V) в м³
* Ось Y - давление (p) в выбранных пользователем единицах (Па или атм)
Задание 6
Программа моделирует затухающие колебания маятника, позволяя пользователям вводить начальную амплитуду, коэффициент затухания и частоту колебаний. На основании введенных данных строится график зависимости угла отклонения маятника от времени.
Физические формулы
θ = A * exp(-β * t) * cos(ω * t)— формула для угла отклонения (θ) маятника в зависимости от времени (t).
Где:
A — начальная амплитуда колебаний (в градусах),
β — коэффициент затухания (в 1/с),
ω=2πf — угловая частота колебаний (рад/с), где f — частота колебаний (Гц),
t — время (с).
Параметры
Амплитуда A: Начальное отклонение маятника от вертикальной оси (в градусах).
Коэффициент затухания β: Определяет скорость уменьшения амплитуды колебаний со временем (в 1/с).
Частота f: Частота собственных колебаний маятника (в Гц).
График
Программа строит один график зависимости угла отклонения маятника от времени:
Ось X: Время t (секунды).
Ось Y: Угол отклонения θ(t) (градусы).
Таким образом, программа показывает поведение затухающего колебательного процесса, демонстрируя уменьшение амплитуды колебаний со временем.
