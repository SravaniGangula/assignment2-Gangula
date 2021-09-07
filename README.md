# assignment2-Gangula
Assignment2-Markdown
# Gangula Sravani Reddy
##### My favourite location in the world is 'Switzerland'

Switzerland is located in **Europe**.The amazing mountains, heaps of lakes and beautiful villages make for the most beautiful scenery in Switzerland. Each city in Switzerland has its own individuality, with different landscapes and their unique city life. I like it as it is known for the **sceneric** places.

---

## Directions to University
1. Go to nearest international airport in Missouri State.
2. Fly from Missouri to Switzerland in Europe.
- Plan and pack dresses in prior.
- Carry a camp tent so that you can enjoy near the beach side.
- A foldable Umbrella
- A cozy and warm jacket

---

## Table Section

The below table demonstrates my favourite food or drinks that i recommend to try. I am a foodie and would like to explore more places and food items.

| Food/Drink | Location | Price |
| --- | --- | ---: |
| Chicken Biryani | Hyderabad(India) | 15$ |
| Spicy Chicken Burger | Mooyah(NWMSU) | 8$ |
| Irani Chai | Hyderabad(India) | 5$ |
| Chicken Mandi | Hyderabad(India) | 15$ |

---

## Pithy Quotes

> It is never too late to be what you might have been.- ***George Eliot***
>
>Life isn't about finding yourself. Life is about creating yourself. - ***George Bernard Shaw***

---

## Code Fencing

> A numerical method is a mathematical tool designed to solve numerical problems. The implementation of a numerical method with an appropriate convergence check in a programming language is called a numerical algorithm.

>Simpson's rules are several approximations for definite integrals, named after Thomas Simpson. The most basic of these rules, called Simpson's 1/3 rule, or just Simpson's rule. Link to the Source - <https://en.wikipedia.org/wiki/Simpson%27s_rule>
> Link for the Code Source - <https://cp-algorithms.com/num_methods/simpson-integration.html>
~~~ 
const int N = 1000 * 1000; // number of steps (already multiplied by 2)
double simpson_integration(double a, double b){
    double h = (b - a) / N;
    double s = f(a) + f(b); // a = x_0 and b = x_2n
    for (int i = 1; i <= N - 1; ++i) { // Refer to final Simpson's formula
        double x = a + h * i;
        s += f(x) * ((i & 1) ? 4 : 2);
    }
    s *= h / 3;
    return s;
}
~~~


[About me](https://github.com/SravaniGangula/assignment2-Gangula/blob/main/AboutMe.md)