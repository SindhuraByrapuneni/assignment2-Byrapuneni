# assignment2-Byrapuneni
A repository is a place where project files are stored for safe keeping
# Sindhura Byrapuneni
#### Kerela
**Kerela is rich in Nature**. it is surrounding with forest, beaches and beautiful places. It  has a different cluture and traditions, Their construction of bulidings is different and ancient.

*****
### New York
1. I will book a TapRide to Kansas Airport.
2. I will book a ticket from Kansas to New York.
3. In New York my friend will come and pick up.

### Items List
* clothes
* creams
* camera
* shoes

![Added an image to About me](Photo/Photo.jpg)

----------------
### Food Menu

The below table represents the varieties of Biriyani.

|Biriyani Type       |Location      |Cost   |
|-------------       |--------      |----   |
|Chicken Biriyani    |Omaha         |$7     |
|Mutton Biriyani     |Omaha         |$9     |
|Prawns Biriyani     |Kansas        |$8     |
|Fish Biriyani       |Kansas        |$7     |


----------------
### Pithy Quotes

> "All good things take time."
>>"Time flies like an arrow; fruit flies like a banana."


--------------
### Code Fencing

An algorithm is a series of instructions telling a computer how to transform a set of facts about the world into useful information.

Source Code:- <https://cp-algorithms.com/><br>


bool probablyPrimeFermat(int n, int iter=5) {
    if (n < 4)
        return n == 2 || n == 3;

    for (int i = 0; i < iter; i++) {
        int a = 2 + rand() % (n - 3);
        if (binpower(a, n - 1, n) != 1)
            return false;
    }
    return true;
}

Source Code:- <https://cp-algorithms.com/algebra/primality_tests.html#toc-tgt-1><br>
