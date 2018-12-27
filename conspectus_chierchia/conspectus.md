---
title: Конспект 'Logic in grammar' Г. Кьеркиа
author: Алексей Кошевой
date: 31 декабря 2018
...

# Базовая теория NPI

## Контексты, лицензирующие NPI

В литературе выделяются следующие контексты:

(@) Отрицание

    (a) I didn't ever eat that fish

    (a') \*I ever ate that dish

(@) Нижесходящие (DE) квантификаторы:

    (b) Few people had ever heard about linguistics

    (b’) \*Many people had ever heard about linguistics

(@) Левый аргумент оператора *каждый*:


    (c) Every person who ever met John liked him

    (c’) \*Every person who liked John ever met him

(@) Антецедент условного предложения:

    (d) If you ever meet John, you will like him

    (d’) \*If you like John, you will ever meet him

(@) Компаративные конструкции:

    (e) He was taller than we ever imagined

    (e’) \*He was so tall than we ever imagined

(@) Вопросы:

    (f) Did you ever go to Italy?

(@) *До*-предложения:

    (g) John died before we could ever confront him with his misdoings

    (g') \*John died after we could ever confront him with his misdoings

(@) *Too*:

    (h) John thinks he is too smart to ever be caught

    (h') \*John thinks he is smart enough to be ever caught

(@) *Only*:

    (i) Only John has ever undertaken my defense

    (i') \*Even John has ever undertaken my defense

(@) Предикаты "сожаления":

    (j) I am sorry I ever met you

    (j’) \*I am glad I ever met you

Список выше считается исчерпывающим для идентификации принадлежности элемента к классу NPI.

## Веридикативность и невередикативность (Giannakidou)

В отличие от более-менее стандартного подхода, где считается, что NPI лицензируются ТОЛЬКО в контекстах нижесходящего следования, Анастасия Гйанакиду предлагает другой критерий, а именно веридикативность;

(@) (a) Оператор f невередикативен, титтк, для любого p, f(p) не влечёт p.
    (b) Оператор f антиверидикативен, титтк, для любого p, f(p) влечёт $\neg p$.

Делаются следующие предположения о лицензировании:

(@) (a) An “Affective Polarity Item” (API) is licensed in S iff S is non-veridical.
    (b) A negative polarity item (NPI) is licensed in S iff S is anti- veridical.


# Теория импликатур

Кьеркия предложил теорию (на самом деле еще в ранних работах), которая описывает
те проблемные случаи, которая (нео-)грайсианская прагматика описать не может --
например, вложенные импликатуры (если мы считаем, что импликатуры порождаются после
семантической деривации, то тогда вложенные импликатуры невозможны -- потому что непонятно,
когда они успевают породится).

## Исчерпывание альтернатив

Одна из главных идей Кьеркия в том, что скалярные импликатуры порождаются с помощью скрытого грамматического оператора
исчерпывания альтернатив O, который работает следующим образом:

(@) $Alt = \{x, y, z\}$

    $O_{Alt}(x) = x \land \neg y \land \neg z$

Т.е. с помощью оператора O (скрытого only), выбирается одна альтернатива из множества. Рассмотрим конкретный пример:

(@) Joe or Bill will show up

    ALT = {$B_s(\text{show up}(j) \vee \text{show up}(b))$, $B_s(\text{show up}(j) \land \text{show up}(b))$}

    $B_s(O_{ALT}(\text{show up}(j) \vee \text{show up}(b))) = B_s(\text{show up}(j) \vee \text{show up}(b)) \land \neg B_s(\text{show up}(j) \land \text{show up}(b))$

В данном случае говорящий породил импликатуру с инклюзивным or. Также он предлагает и другие скрытые операторы, например (D-оператор, соотвествующий
английскому *each*) для предложений типа *John and Mary hit a pole*, для того, чтобы пораждать импликатуры типа -- "они оба ударились в один столб" / "каждый из них ударился о столбы (различные)"

## Релевантность

# Подход Кьеркиа к NPI

## *Even* и *only*
