# Finding the area and perimeter of geometric shapes
## Description
Functions used to calculate the area and perimeter of geometric shapes(rectangle and triangle)

## Math formulas
### Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²

### Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a

## Functions

### circle.py
- area(r)

Description: calculates area of a circle with giving radius=r.

Example:

    from geometric_lib import circle
    
    r = 1.0
    print(area(r))
    
    '3.141592653589793'

- perimeter(r)

Description: calculates perimeter of a circle with giving radius=r.

Example:

    from geometric_lib import circle
    
    r = 1.0
    print(perimeter(r))
    
    '6.283185307179586'

### square.py

- area(r)

Description: calculates area of a circle with given side=a.

Example:

    from geometric_lib import circle
    
    a = 1.0
    
    print(area(a))
    
    '1.0'

- perimeter(r)

Description: calculates perimeter of a circle with given side=a.

Example:

    from geometric_lib import circle
    
    a = 1.0
    
    print(perimeter(a))
    
    '4.0'


## Commits History
- commit f4837dffa04fa7b7e6229d3dd96f6cd1638d9b9d (HEAD -> main, origin/documentation_333805)
Author: dvgurevich <dvgurevich@mail.ru>
Date:   Fri Dec 22 22:57:13 2023 +0300

    docs: added documentation for circle functions

- commit f9b57072b86d4f131fbbf490d147ed75df9977c4
Author: dvgurevich <dvgurevich@mail.ru>
Date:   Fri Dec 22 22:57:04 2023 +0300

    docs: added documentation for square functions
