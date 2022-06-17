Комментарии в JavaScript //
console.log('текст'); // вывод текста в консоль

Константы
const pi=3.14; //создание константы 
const surface=4*pi*3390*390; - помещение константы в константу


Математические операции:
    Возведение в степень 
2**4; //16 
Math.pow(2,4); //16
% - остаток от деления


Общее:
Если результат вычисления не число - NaN

Определение функции
    (name)=> {
        return SOMETHING;
    }

Пример определения функции и фиксация ее в константеж
    ПРИМЕР1 (одно входное)
    const surfaceAreaCalculator=(radius)=> {
        return 4*3.14*radius*radius;
    }
    const surfaceOfMars=surfaceAreaCalculator(3390);
    
    ПРИМЕР2 (с двумя входными)
    const percentageCalculator=(number,total) => {
        return number*100/total;
    }

    ПРИМЕР3 
    // const <name> = (<argument>) => {
    //   return <expressions>;
    // };
    const identity = (value) => {
    return value;
    };

    ПРИМЕР4 (подходит если у функции 1 аргумент)
    // const <name> = (<argument>) => <expressions>;
    const identity = value => value;

    ПРИМЕР5 
    // Такую функцию можно использовать до её определения (в этом же файле).
    function identity(value) {
    return value;
    }
