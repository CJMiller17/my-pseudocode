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

Functions: Empty1() = Empty Older Filter
           Empty2() = Empty Old Coffee
           Rinse1() = Rinse Pot
           Rinse2() = Rinse filter basket
           Fill1()  = Fill Water to desired level
           Start()  = Press Start Button
           .EventListener(gurgle, steam hiss)
           Fill2()  = Fill Mug with Coffee, Cream, Sweetener
           Stir()   = Stir contents of mug with spoon 
           Drink()  = sip from mug
STEPS:

1. Check to see if coffee maker is empty && clean.
    IF not, run Empty1(), Empty2(), Rinse1(), and Rinse2().
    ELSE move to step 2.
2. RUN Fill1(). Place Coffee Filter inside Filter Basket. Scoop ground coffee into filter; amount of ground coffee = one TBSP for ever cup of water.
3. RUN Start().
4. Fill2().eventListener(gurgle, steam hiss) // RUN Fill2() when you pot gurgling and hissing from steam.
5. RUN Stir().
6. RUN Drink().

