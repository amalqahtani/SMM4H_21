<h1> # SMM4H_21 </h1>

<h2> Task 5 : Classification of tweets self-reporting potential cases of COVID-19 </h2> 

<p> This new binary classification task involves automatically distinguishing tweets that self-report potential cases of COVID-19 (annotated as “1”) from those that do not (annotated as “0”). “Potential case” tweets include those indicating that the user or a member of the user’s household was denied testing for, symptomatic of, directly exposed to presumptive or confirmed cases of COVID-19, or has had experiences that pose a higher risk of exposure to COVID-19. “Other” tweets are related to COVID-19 and may discuss topics such as testing, symptoms, traveling, or social distancing, but do not indicate that the user or a member of the user’s household may be infected. </p>

<ul>
<li> Training data: 7,181 tweets </li>
<li> Test data: 10,000 tweets </li>
</ul>

<h2> Task 6 : Classification of COVID19 tweets containing symptoms </h2>

Identifying personal mentions of COVID19 symptoms requires distinguishing personal mentions from other mentions such as symptoms reported by others and references to news articles or other sources. The classification medical symptoms from COVID-19 Twitter posts presents two key issues: First, there is plenty of discourse around news and scientific articles that describe medical symptoms. While this discourse is not related to any user in particular, it enhances the difficulty of identifying valuable user-reported information. Second, many users describe symptoms that other people experience, instead of their own, as they are usually caregivers or relatives of people presenting the symptoms. This makes the task of separating what the user is self-reporting particularly tricky, as the discourse is not only around personal experiences. 

<p> This task is considered a three-way classification task where the target classes are: </p>
<ul> <b>
  <li>  self-reports  </li>
  <li>  non-personal reports  </li>
  <li>  literature/news mentions </li>
  </b> </ul>

<ul>
  <li> Training data: 9,567 tweets  </li>
  <li>  Test data: 6,500 tweets  </li>
</ul>
