# Installation

This SISD library can be intatalled using the following command: <br>
*install_github("abh2k/sisd")*<br> <br>
This library can be imported using: <br>
*library(SISD)*<br><br>

Parameters of the SISD function:
<ul>
<li>N : The total population number</li>
<li>gamma : The recovery rate</li>
<li>T_Current : Denotes the day when the training phase ends. After this day, the prediction phase starts.</li>
<li>T_Start : Denotes the minimum length of the training phase (in days).</li>
<li>T_Validation : Length of Validation Period</li>
<li>T_Limit : Denotes the upper limit of the number of additional days that can be added to the minimum training phase to optimally choose the training phase.</li>
<li>T_Pred : Denotes the length of the prediction phase (in days).</li> 
<li>data : The dataframe containing the observed data in the format specified below.</li>
<li>mu (Optional) : If mu is given the the death rate is fixed. If this is None, then an optimal mu is choosen using the data-driven algorithm</li> 
</ul>
