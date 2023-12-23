# bloc4 Analyse de données non structurées

AT&T Inc. is an American multinational telecommunications holding company headquartered at Whitacre Tower in Downtown Dallas, Texas. It is the world's largest telecommunications company by revenue and the third largest provider of mobile telephone services in the U.S. As of 2022, AT&T was ranked 13th on the Fortune 500 rankings of the largest United States corporations, with revenues of $168.8 billion.

One of the main pain point that AT&T users are facing is constant exposure to SPAM messages, and the Company is looking for an automated way of detecting spams to protect their users.

Our goal is to build a spam detector, that can automatically flag spams as they come based solely on the sms' content.

This project is made up of different parts :
- get and analyse the data
- transform and preprocess the data so as to be ready for use for training our models
- create models, train it and asses performance
- conclusion

For this exercice, we choose three models :
- a logistic regression (base model)
- a LSTM model
- a BERT model using transfert learning

only the two first models are dowloaded due the important size of the bert model (widely more than 25 Mo)
