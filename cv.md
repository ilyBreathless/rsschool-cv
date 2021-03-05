1. Кайгородов Илья

2. Телефон: _+375299388089_. E-mail: _frolik.goodman@mail.ru_

3. Моя цель успешно закончить [школу RSS](https://app.rs.school/), моими сильными сторонами являются <ins> креативность, умение работать в команде, отсутствие вредных привычек, способность быстро запоминать нужную информацию </ins>. Стремлюсь постоянно узнавать что-то новое и развиваться в интересных мне сферах.

4. Навыки:
     Уверенное знание языков программмирования: 
      * Delphi
      * C++
      * C
      * PHP
      * Swift

5. Пример кода функции моего курсового проекта 
 ```c++
void DrawXLeft(HDC hdc, int iX, int iY)
{
     HPEN hPenOld;
     HPEN hLinePen;
     HWND hWnd;
     COLORREF qLineColor;
     qLineColor = RGB(255, 0, 0);
     const int kiPenWidth = 10;
     hLinePen = CreatePen(PS_SOLID, kiPenWidth, qLineColor);
     hPenOld = (HPEN)SelectObject(hdc, hLinePen);
     // Get bounds
     const int kiLowX = iX * gkiSqrSz + 2 * kiPenWidth;
     const int kiHighX = (iX + 1) * gkiSqrSz - 2 * kiPenWidth;
     const int kiLowY = iY * gkiSqrSz + 2 * kiPenWidth;
     const int kiHighY = (iY + 1) * gkiSqrSz - 2 * kiPenWidth;
     BITMAP krestikObject;
     GetObject(krestik, sizeof(BITMAP), &krestikObject);
     HDC memDC = CreateCompatibleDC(hdc);
     SelectObject(memDC, krestik);
     alpha = 0;
     if (alpha >= 255) forward = false;
     if (alpha <= 0) forward = true;
     if (forward)
     alpha += 40; else
     alpha -= 20;
     // if (alpha = 255) forward = false;
     blf.SourceConstantAlpha = alpha;
     AlphaBlend(hdc, kiLowX - 15, kiLowY - 15, krestikObject.bmWidth,
     krestikObject.bmHeight, memDC, 0, 0, krestikObject.bmWidth,
     krestikObject.bmHeight, blf);
     DeleteDC(memDC);
     Sleep(100);
}            
```
6. Опыт работы отсутствует.

7. Являюсь студентом 3-го курса **БГУИР, ФКСиС, специальности ПОИТ**. 

8. Уровень английского языка : **А2**
