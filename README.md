The sortedcitation package provides 3 commands to sort the bibliography at the end of the article.

`\scite{biblabel}`: similar to `\cite{biblabel}`. But \scite only supports single biblabel, for I don't know how to scan a string. 

`\sbibitem{biblabel}{the ref content}`: It is DIFFERENT from `\bibitem{biblabel} the ref content`. For one need to use the ref content as the second option.

`\begin{sbibliography}...\end{sbibliography}` has NO option, comparing to `\begin{thebibliography}{30}...\end{thebibliography}`. 
