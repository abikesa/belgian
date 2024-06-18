 
<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

<script type="text/x-mathjax-config">
MathJax.Hub.Config({
  tex2jax: {
    inlineMath: [['$', '$'], ['\\(', '\\)']],
    processEscapes: true
  }
});
</script>

Ah, the classic debate between two exceptional Belgian beers: Rochefort 8 and Duvel. Both are stalwarts in their categories, but they cater to slightly different palates and experiences. Here's my take on them:

### Rochefort 8
**Style:** Belgian Strong Dark Ale  
**ABV:** 9.2%  
**Flavor Profile:**
- **Complexity:** Rochefort 8 is rich and intricate. It boasts dark fruit flavors like plum, fig, and raisin, with underlying notes of caramel, toffee, and chocolate. There's a subtle spiciness from the yeast, with hints of clove and pepper.
- **Mouthfeel:** Smooth, slightly creamy, and full-bodied, with a well-balanced carbonation that enhances its richness.
- **Aroma:** Dark fruits, sweet malt, and a touch of spice, creating an inviting and warming scent.

**Opinion:**
Rochefort 8 is like a symphony of flavors, perfect for those who appreciate depth and complexity in their beer. It's a contemplative drink, best enjoyed slowly to savor its evolving taste. Ideal for cold evenings or paired with hearty foods like stews or aged cheeses.

### Duvel
**Style:** Belgian Strong Pale Ale  
**ABV:** 8.5%  
**Flavor Profile:**
- **Crispness:** Duvel is bright and effervescent. It features a delicate balance of fruity esters (think pear and apple) and spicy phenols from the yeast, with a touch of hop bitterness.
- **Mouthfeel:** Light to medium-bodied with a lively carbonation that gives it a refreshing and crisp finish.
- **Aroma:** Fresh, fruity, and slightly floral, with a clean malt backbone and a hint of spice.

**Opinion:**
Duvel is the epitome of a refreshing yet strong ale. Its light and bubbly nature makes it surprisingly easy to drink despite its high ABV. It's perfect for any occasion, especially on a warm day or as an aperitif. It pairs wonderfully with lighter dishes like seafood or salads.

### Verdict
- **Rochefort 8:** Best for those who love deep, rich flavors and a complex drinking experience. It's a beer to be savored and pondered.
- **Duvel:** Ideal for those who prefer a lighter, crisper, and more refreshing beer. It's versatile and approachable, making it a great choice for various settings.

Both are fantastic in their own right, but if I had to choose, I'd go with Rochefort 8 for its sheer complexity and the richness of its flavor profile. It’s a beer that tells a story with every sip. Duvel, on the other hand, is my go-to for a more casual and refreshing experience, especially in warmer weather.

> *[Letters to Abigail](https://www.masshist.org/digitaladams/archive/doc?id=L17800512jasecond)*

![](https://upload.wikimedia.org/wikipedia/commons/4/49/%22The_School_of_Athens%22_by_Raffaello_Sanzio_da_Urbino.jpg)
![](craft.png)

### Activation Function, $Q$: 1st, 3rd, 5th, [♭♭7th](https://en.wikipedia.org/wiki/Chord_notation#Chord_quality), 9th  
- Hunter-gatherer/`War`: spiritual teachings  (I)
- Peasant/`Economics`: [humanism](https://www.uuftc.org) (B)
        
### Biases, $U()$: 11th, 13th
- Farmer/`Calculus`: judeo, christian (G)
- Manufacturer/`Philosophy`: world religions (Y)
       
### Weights, $\frac{dU()}{dQ}$: ♯9,♭9,♯11,♭13 
- Electricity/`Musick`: prophetic utterances ([O](https://www.youtube.com/watch?v=1aM1KYvl4Dw))
- Railway/`Leisure`: individual experience ([R](https://www.youtube.com/watch?v=fu-3WN9TJNI))     


```python
import numpy as np
import matplotlib.pyplot as plt

# Define the total utility function U(Q)
def total_utility(Q):
    return 100 * np.log(Q + 1)  # Logarithmic utility function for illustration

# Define the marginal utility function MU(Q)
def marginal_utility(Q):
    return 100 / (Q + 1)  # Derivative of the total utility function

# Generate data
Q = np.linspace(1, 100, 500)  # Quantity range from 1 to 100
U = total_utility(Q)
MU = marginal_utility(Q)

# Plotting
plt.figure(figsize=(14, 7))

# Plot Total Utility
plt.subplot(1, 2, 1)
plt.plot(Q, U, label=r'Total Utility $U(Q) = 100 \log(Q + 1)$', color='blue')
plt.title('Total Utility')
plt.xlabel('Quantity (Q)')
plt.ylabel('Total Utility (U)')
plt.legend()
plt.grid(True)

# Plot Marginal Utility
plt.subplot(1, 2, 2)
plt.plot(Q, MU, label=r'Marginal Utility $MU(Q) = \frac{dU(Q)}{dQ} = \frac{100}{Q + 1}$', color='red')
plt.title('Marginal Utility')
plt.xlabel('Quantity (Q)')
plt.ylabel('Marginal Utility (MU)')
plt.legend()
plt.grid(True)

# Adding some calculus notation and Greek symbols
plt.figtext(0.5, 0.02, r"$MU(Q) = \frac{dU(Q)}{dQ} = \lim_{\Delta Q \to 0} \frac{U(Q + \Delta Q) - U(Q)}{\Delta Q}$", ha="center", fontsize=12)

plt.tight_layout()
plt.show()
```

Running this code will generate a visual demonstration of diminishing marginal utility with appropriate calculus notation and Greek symbols.

Here is the generated image:

![Diminishing Marginal Utility](https://abikesa.github.io/johnadams/diminishing_marginalutility.png)

> One needs challenges, a worthy adversary, the embrace of more remote overtones of the harmonic series - ***Q**ualities*

- Westmalle Dubbel, $7$ %
- Duvel, $8.5$ %
- Truth, $8.7$ %
- Westmalle Tripel, $9.5$ %
- St. Bernardus `Abt 12`, $10$ %
