Let: Ground Coffee
     Coffee Filter
     Water
     Coffee Maker[]
            [0]Coffee Pot
            [1]Filter Basket
     Coffee Mug
     Creamer
     Sweetener
     Spoon

Functions: Prepare() {
                Empty1() = Empty Older Filter
                Empty2() = Empty Old Coffee from Coffee Pot
                Rinse1() = Rinse Pot
                Rinse2() = Rinse filter basket
}
           Fill1()  = Fill Coffee Pot with water to desired level
           Pour()   = Pour water from Coffee pot into Coffee Maker
           Start()  = Press Start Button
           Fill2()  = Fill Mug with Coffee, Cream, Sweetener
           Stir()   = Stir contents of mug with spoon 
           Drink()  = sip from mug
           
STEPS:

1. Check to see if coffee maker is empty && clean.
    IF not, run Prepare().
    ELSE move to step 2.
2. RUN Fill1().
2. RUN Pour(). 
3. Place Coffee Filter inside Filter Basket. 
3. Scoop ground coffee into filter; amount of ground coffee = one TBSP for ever cup of water.
4. RUN Start().
5. Fill2().eventListener(gurgle, steam hiss).
6. RUN Stir().
7. RUN Drink().

