# 🎯 Code Question 6 (Bonus)

+ Qual è il metodo migliore per clonare l’oggetto chef, e perché?
- Annidare più spread operator (vedi main.js), in quanto l'oggetto "chef" contiene altri oggetti annidati, che però non possiamo clonare con structuredClone() perché contengono delle funzioni. 