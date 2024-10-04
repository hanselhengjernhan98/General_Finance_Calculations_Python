# Critique of Mean Variance Analysis + Correlation and Covariance + Levered vs Unlevered Returns with Python

Check out 3 showcases of my mini finance projects!

__Showcase 1 (Critique of Mean Variance Analysis)__ <br><br>

__Objectives__ <br><br>
1. Mean Variance Analysis on a basket of shares to find the stock with 5-year historical best performance
   - Found out that MSFT is on the efficient Frontier - as could be seen in the plot, with relatively okay risk when measured using std, let's see if it's truly reflective of the risk involved 
3. To do that, I first go to find out if MSFT shares are normally distributed
4. Find out mu, sigma, z stat and p value of MSFT

<img width="906" alt="image" src="https://github.com/user-attachments/assets/4b6d99d7-328e-403d-b50d-e2d602dce8a9">


__Lessons Learnt After this Showcase:__ <br></br>
- Assuming that MSFT Returns (generally) follow a Normal Distribution, there is 0% probability that we get that extreme outcomes in a sample.

- MSFT Returns DON´T follow a Normal Distribution as they exhibit "Fat Tails". Extreme Events/Outcomes are not reflected in the Mean-Variance Analysis. The Standard Deviation of Returns underestimates true Risk.

__Showcase 2 (Correlation and Covariance)__ <br><br>


Do instruments/assets __move together__ (and to what extent)? <br>

Three cases:
- unrelated (__no__ relationship/correlation)
- moving together (__positive__ relationship/correlation)
- moving in opposite directions (__negative__ relationship/correlation)

__Objectives__ <br><br>
-  Find out correlation and covariance of a basket of stocks


__Lessons Learnt after this Showcase:__ <br><br>

- Similar assets are (highly) positive correlated. Different assets exhibit low/no/negative correlation.
- In portfolio management it´s beneficial to have assets with low/no/negative correlation (portfolio diversification effect).

<img width="912" alt="image" src="https://github.com/user-attachments/assets/ed93d475-741a-4778-8aa0-e2a58d363120">


__Showcase 3 (levered vs unlevered returns)__

__Objectives:__

1. Calculate levered returns for Bitcoin (leverage = 4). 

2. Visualize and compare with unlevered Investment.

<img width="580" alt="image" src="https://github.com/user-attachments/assets/165c50c6-aa6f-45d6-a542-a84016489fac">

Levered returns amplify gains and losses! Win big, but lose big when the wrong call is made.
