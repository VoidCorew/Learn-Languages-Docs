# Двойные союзы (Doppelte Konnektoren)

---

## 1. Что это такое?

**Двойные союзы (Doppelte Konnektoren)** — это пары союзов, которые соединяют два элемента (слова, части предложения) и выражают определённые логические отношения: добавление, выбор, противопоставление и т. д.

!!! warning Внимание

    Это надо не так использовать

---

## 2. Часто используемые двойные союзы

| Союзы                     | Значение                         | Пример                                          |
|---------------------------|----------------------------------|-------------------------------------------------|
| **nicht nur … sondern auch …** | не только … но и …            | Er spricht **nicht nur** Deutsch, **sondern auch** Englisch. |
| **entweder … oder …**     | либо … либо …                   | **Entweder** du kommst mit, **oder** du bleibst zu Hause. |
| **sowohl … als auch …**   | как … так и …                   | Sie mag **sowohl** Pizza **als auch** Pasta.   |
| **weder … noch …**        | ни … ни …                       | Ich habe **weder** Zeit **noch** Geld.         |
| **je … desto …**          | чем … тем …                     | **Je** mehr du übst, **desto** besser wirst du. |

!!! quote Цитирования

    Какие-то цитирования если надо


И если нужно диаграммы

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```

Или такие

``` mermaid
sequenceDiagram
  autonumber
  Alice->>John: Hello John, how are you?
  loop Healthcheck
      John->>John: Fight against hypochondria
  end
  Note right of John: Rational thoughts!
  John-->>Alice: Great!
  John->>Bob: How about you?
  Bob-->>John: Jolly good!
```

Или такие

``` mermaid
stateDiagram-v2
  state fork_state <<fork>>
    [*] --> fork_state
    fork_state --> State2
    fork_state --> State3

    state join_state <<join>>
    State2 --> join_state
    State3 --> join_state
    join_state --> State4
    State4 --> [*]
```

Или такие

``` mermaid
classDiagram
  Person <|-- Student
  Person <|-- Professor
  Person : +String name
  Person : +String phoneNumber
  Person : +String emailAddress
  Person: +purchaseParkingPass()
  Address "1" <-- "0..1" Person:lives at
  class Student{
    +int studentNumber
    +int averageMark
    +isEligibleToEnrol()
    +getSeminarsTaken()
  }
  class Professor{
    +int salary
  }
  class Address{
    +String street
    +String city
    +String state
    +int postalCode
    +String country
    -validate()
    +outputAsLabel()  
  }
```

Или такое

- Nulla et rhoncus turpis. Mauris ultricies elementum leo. Duis efficitur
  accumsan nibh eu mattis. Vivamus tempus velit eros, porttitor placerat nibh
  lacinia sed. Aenean in finibus diam.

    * Duis mollis est eget nibh volutpat, fermentum aliquet dui mollis.
    * Nam vulputate tincidunt fringilla.
    * Nullam dignissim ultrices urna non auctor.

Или вообще такое

- [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
- [ ] Vestibulum convallis sit amet nisi a tincidunt
    * [x] In hac habitasse platea dictumst
    * [x] In scelerisque nibh non dolor mollis congue sed et metus
    * [ ] Praesent sed risus massa
- [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque

---

## 3. Слово-порядок

- При использовании двойных союзов порядок слов остаётся прямым:  
  подлежащее → глагол → остальное.

Пример:  
- **Nicht nur** Maria, **sondern auch** Paul lernt Deutsch.

!!! failure
    
    Какие-то регулярные ошибки

---

## 4. Примеры предложений

### nicht nur … sondern auch …
- Sie ist **nicht nur** freundlich, **sondern auch** fleißig.  
(Она не только дружелюбная, но и трудолюбивая.)

### entweder … oder …
- Wir gehen **entweder** ins Kino **oder** ins Theater.

### sowohl … als auch …
- Ich esse **sowohl** Gemüse **als auch** Fleisch.

### weder … noch …
- Er hat **weder** Hunger **noch** Durst.  
(Он не голоден и не хочет пить.)

### je … desto …
- **Je** früher wir gehen, **desto** besser.

!!! note Как лучше сделать

    Как лучше что-то сделать

---

## 5. Тренировочные задания

### Задание 1: Заполни пропуски подходящими двойными союзами

1. Ich mag \_\_\_ Pizza \_\_\_ Pasta.  
2. \_\_\_ sie ist müde, \_\_\_ sie arbeitet weiter.  
3. \_\_\_ du willst lernen, \_\_\_ du musst anfangen.  
4. Wir gehen \_\_\_ ins Schwimmbad \_\_\_ in den Park.  
5. Er hat \_\_\_ Lust \_\_\_ Zeit.

??? example "Ответы"

    Ответы к каждому заданию

---

### Задание 2: Переведи на немецкий

1. Я говорю не только по-немецки, но и по-английски.  
2. Либо ты идёшь со мной, либо остаёшься дома.  
3. Он ни голоден, ни хочет пить.  
4. Чем больше ты читаешь, тем лучше ты понимаешь.  
5. Мы приглашаем как учителей, так и учеников.

---

### Задание 3: Найди и исправь ошибку

1. Sie ist sowohl freundlich sondern auch hilfsbereit.  
2. Ich habe nicht Zeit noch Lust.  
3. Entweder du kommst oder bleibst du zu Hause.  
4. Je schneller du läufst, desto du bist müde.  
5. Ich liebe weder Kaffee als auch Tee.

---

## 6. Советы

- **nicht nur … sondern auch …** — одна из самых популярных конструкций.  
- **weder … noch …** требует отрицания сразу двух элементов.  
- **je … desto …** часто встречается в письменной и формальной речи.  
- При этом глагол **остается на втором месте** в главных предложениях.

---

