1. Kaiharodau Ilya

2. Phone number: _+375299388089_. E-mail: _frolik.goodman@mail.ru_

3. My goal is to finish [RSS](https://app.rs.school/), my strengths are <ins> creativity, the ability to work in a team, the absence of bad habits, the ability to quickly memorize the necessary information </ins>. I strive to constantly learn something new and develop in areas of interest to me.

4. Strong knowledge of programming languages: 
      * Delphi
      * C++
      * C
      * PHP
      * Swift

5. Sample code of a function of my course project 
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
6. No work experience.

7. I am a third year student of **BSUIR, FCSaN, speciality ITS**. 

8. English level : **А2**
