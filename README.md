As a data analyst at a medical institute, I've been assigned to assist in the development of a mobile app intended to guide lottery addicts through exercises that will let them better estimate their chances of winning.We'll work collaboratively with engineers & here we're going to build a logic for the app aimed at helping lottery addicts realistically understand their chances of winning using probabilities. Hopefully, the app will help the addicts realize that buying too many tickets will do little to improve their chances of winning thus stopping them from buying the tickets in an unhealthy manner. <br />
We'll apply concepts including:   
 - calculating theoretical and empirical probabilities <br />
 - use of probability rules to calculate different probabilities <br />
 - use of combinations and permutations to count the sizes of sample spaces <br />

    
We'll build functions that can answer users questions like:<br />
- What is the probability of winning the big prize with a single ticket?<br />
- What is the probability of winning the big prize if we play 40 different tickets (or any other number)?<br />
- What is the probability of having at least five (or four, or three, or two) winning numbers on a single ticket?<br />

We managed to write four functions to help us meet our objectives that were as follows:<br />

     i)one_ticket_probability() — calculates the probability of winning the big prize with a single ticket
    ii)check_historical_occurrence() — checks whether a certain combination has occurred in the Canada lottery data set
    iii)multi_ticket_prob() — calculates the probability for any number of tickets between 1 and 13,983,816
    iv)prob_less6() — calculates the probability of having three, four or five winning numbers

Possible features for a second version of the app include: <br />
- Improve the probability_less6() function to show the probabilities for having two winning numbers as well.<br />
- Making the outputs even easier to understand by adding fun analogies (for example, we can find probabilities for strange events and compare with the chances of winning in lottery; for instance, we can output something along the lines “You are 100 times more likely to be the victim of a shark attack than winning the lottery”).<br />
- Combine the one_ticket_probability() and check_historical_occurrence() to output information on probability and historical occurrence at the same time.<br />
