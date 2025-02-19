# Pen4o’s Odyssey – Week 5

След като Пенчо активира механизма в залата със статуите, той стига до **таен кладенец**, който обещава да даде достъп до скрито съкровище. Глас от дълбините на кладенеца прошепва:

*“Трябва да налееш точния обем вода. Не по-малко, не повече. Само тогава ще получиш това, което търсиш!”*

Пенчо трябва да налее вода в кладенеца, но ако добави твърде много или въведе невалидна стойност, кладенецът ще се затвори завинаги.

Напишете функция, която приема едно число - точното количество вода, което се очаква да има в кладенеца. За да налее тази вода, Пенчо ще използва серия от канчета с различен капацитет.

На следващите редове ще четете капацитета на всяко канче, докато:

- Общото количество вода достигне **точно** зададеното количество

ИЛИ

- Пенчо въведе отрицателно число, което ще накара кладенеца да се затвори незабавно

ИЛИ

- Пенчо препълни кладенеца с вода, което ще накара кладенеца да се затвори незабавно

Отпечатайте на конзолата дали опитът на Пенчо е бил успешен, или не.

### Вход

- Точното количество вода, което трябва да има в кладенеца (target volume)
- На следващите редове - поредица от числа, представляващи капацитета на всяко канче, което използва.

* Пенчо пълни всяко канче догоре, т.е. обема на водата в канчето е равна на капацитета на канчето.

### Изход

- Ако Пенчо достигне точно зададеното количество, отпечатайте:
    - “Success! The well reveals its precious treasure!”
- Ако Пенчо въведе отрицателно число, отпечатайте:
    - “Failure! The well has been sealed.”
- Ако Пенчо налее повече от необходимото количество, отпечатайте:
    - “Overflow! The well rejects your offering.”
    

### Примери

| **Вход** | **Изход** |
| --- | --- |
| 50, [30, 20] | Success! The well reveals its precious treasure! |
| 100, [10, 30, -10] | Failure! The well has been sealed. |
| 50, [30, 40] | Overflow! The well rejects your offering. |
