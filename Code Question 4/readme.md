# 🏆 Code Question 4

+ Qual è il metodo migliore per clonare l’oggetto chef, e perché?
- Lo spread operator, perché ci permette di creare una shallow copy con tutti i dati che ci interessano senza intaccare il funzionamento di "makeBurger"

+ Qual è il metodo migliore per clonare l’oggetto restaurant, e perché?
- structuredClone(), perché ci permette di effettuare una deepcopy con tutti i dati che ci interessano, senza intaccare il funzionamento di Date()