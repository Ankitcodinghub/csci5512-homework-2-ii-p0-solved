# csci5512-homework-2-ii-p0-solved
**TO GET THIS SOLUTION VISIT:** [CSCI5512 Homework 2 II P0 Solved](https://www.ankitcodinghub.com/product/csci-5512-artificial-intelligence-ii-p0-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124494&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI5512 Homework 2 II P0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Homework 2

1. (50 points) [Programming Assignment] Consider the Hidden Markov Model in Figure 1.

Figure 1: Hidden Markov Model

Assume each of the hidden variables Xi,i = 0,1,2,3,… and the evidence variables Ei,i = 1,2,3,… to be boolean, and can take two values T and F. Let P(X0 = T) = P(X0 = F) =

0.5. Let the transition matrix P(Xt+1|Xt) and sensor matrix P(Et|Xt) be given by

,

where, in the T matrix,

T11 = P(Xt+1 = T|Xt = T) , T12 = P(Xt+1 = F|Xt = T) ,

T21 = P(Xt+1 = T|Xt = F) ,

and in the E matrix, T22 = P(Xt+1 = F|Xt = F) ,

E11 = P(Et = T|Xt = T) , E12 = P(Et = F|Xt = T) ,

E21 = P(Et = T|Xt = F) , E22 = P(Et = F|Xt = F) .

Consider two sequences of evidence e1:10 over 10 time steps:

Evidence sequence 1: e1:10 = ⟨F,F,F,T,T,T,T,F,F,F⟩

Evidence sequence 2: e1:10 = ⟨F,T,F,T,F,T,F,T,F,T⟩

For each of the above two sequences of evidence:

(a) (25 points) Write a program to compute the smoothed estimates of Xt,t = 1,…,10 given evidence e1:10.

(b) (25 points) Write a program to find the most likely sequence of states X1:10 given evidence e1:10.

In addition to the smoothed estimates and sequence of states, you have to submit code for SmoothHMM implementing computation of smoothed estimate and MaxSeq implementing computation of the most likely sequence. The code for both algorithms should take two input arguments:

(i) n, the length of the evidence (n = 10 for the two examples above)

(ii) The evidence sequence containing a ‘1’ for T and ‘0’ for F. Thus, for the first example e1:10 = ⟨F,F,F,T,T,T,T,F,F,F⟩, implying the input should be 0 0 0 1 1 1 1 0 0 0.

The output for SmoothHMM should be an list of length n with smoothed estimates of P(Xt = T),t = 1,…,n. The output should be clearly displayed on screen after running the program.

The output for MaxSeq should be a binary list of length n containing the most likely sequence of states with 1 corresponding to T and 0 corresponding to F. The output should be clearly displayed on screen after running the program.

Sample input for Python 3.6 for (a) and (b) when n = 10 and e1:10 = ⟨F,F,F,T,T,T,T,F,F,F⟩

$python SmoothHMM.py 10 0 0 0 1 1 1 1 0 0 0

$python MaxSeq.py 10 0 0 0 1 1 1 1 0 0 0Assignment Project Exam Help

2. (50 points) [Programming Assignment] Consider the umbrella network shown in Figure 2.

or F (false). Let Ri be the random variable corresponding to the hidden state (rain) at step i. Assume the prior probability of rain . Consider the following three evidence sequences:

(ii) u1:10 = (F,F,F,F,F,F,F,T,T,T)

(iii) u1:10 = (F,T,F,T,F,T,F,T,F,T)

Figure 2: The Umbrella Network

For each of the three choices of u1:10, your code should output the filtering probability P(R10|u1:10). We want to approximate this probability using two separate sample methods as follows:

(a) (20 points) Estimate P(R10|u1:10) using likelihood weighting with 100 and 1000 samples. You have to submit code for lwUmbrella which takes 3 arguments: an integer numSamples, denoting the number of samples (set to 100 and 1000), an integer numSteps, denoting the number of steps (set to 10), and evidence, denoting the evidence u1:numSteps (T = 1,F = 0) of length numSteps. Run the likelihood weighting 10 times, and find the average of the estimate P(RnumSteps|u1:numSteps) and the variance of the estimate.

Sample input for Python 3.6 for when numSamples = 100, numSteps = 10, and u1:10 = (T,T,T,T,T,F,F,F,F,F)

$python lwUmbrella.py 100 10 1 1 1 1 1 0 0 0 0 0

(b) (25 points) Estimate P(R10|u1:10) using particle filtering with 100 and 1000 particles. You have to submit code for pfUmbrella, which takes 3 arguments: an integer numSamples, denoting the number of particles (set to 100 and 1000), an integer numSteps, denoting the number of steps (set to 10), and evidence, denoting the evidence u1:numSteps (T = 1,F = 0) of length numSteps. The output should be the estimate P(RnumSteps|u1:numSteps) and the variance of the estimate.

Sample input for Python 3.6 for when numSamples = 100, numSteps = 10, and u1:10 = (T,T,T,T,T,F,F,F,F,F)

$python pfUmbrella.py 100 10 1 1 1 1 1 0 0 0 0 0

(c) (5Assignment Project Exam Helppoints) Comment on the relative performance of the two methods on the three evidence

sequences and two sample sizes. In particular, how close are the estimates to the true probabilities and what are the variance of the estimates.

Your code must be runnable on a CSE lab machine (e.g., csel-kh1260-01.cselabs.umn.edu). One option is to SSH into a machine. Learn about SSH, and other options, at these links: https:// cse.umn.edu/cseit/self-help-guides/secure-shell-ssh and https://cse.umn.edu/cseit/ self-help-guides.

Instructions

Follow the rules strictly. If we cannot run your code, you will not get any credit.

• Things to submit

2. Python code for Problem 1 (a) and (b) (must include the required SmoothHMM.py and MaxSeq.py files).

3. Python code for Problem 2 (a) and (b) (must include the required lwUmbrella.py and pfUmbrella.py files).

4. README.txt: README file that contains your name, student ID, email, assumptions you are making, other students you discussed the homework with, and other necessary details.

5. Any other files which are necessary for your code (such as package dependencies like a requirements.txt or yml file).

Homework Policy. (1) You are encouraged to collaborate with your classmates on homework problems, but each person must write up the final solutions individually. You need to list in the README.txt which problems were a collaborative effort and with whom. (2) Regarding online resources, you should not:

• Google around for solutions to homework problems,

• Ask for help on online,

• Look up things/post on sites like Quora, StackExchange, etc.Assignment Project Exam Help
