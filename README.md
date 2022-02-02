# Pandas-Review

ecom[ecom['Lot']=='90 WT']['Purchase Price']

ecom[(ecom['CC Provider']=='American Express') & (ecom['Purchase Price']>95)]

ecom[ecom['CC Exp Date'].apply(lambda exp: exp[3:]== '25')]

ecom['Email'].apply(lambda email: email.split('@')[1]).value_counts()
