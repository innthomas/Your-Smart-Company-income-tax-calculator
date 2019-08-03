# Your-Smart-Company-income-tax-calculator
#this calculator obtains data from user to compute tax liability

while True:
    try:
        print('COMPANY INCOME TAX CALCULATOR')
        company_name = input('Company name: ')
        revenue = int(input('revenue for the year:' ))
        rate = float(input('applicable tax rate:'))
    
        def company_tax (revenue, rate=0.3):
            tax_liability=revenue*rate
            print(company_name + "'s tax liability for the year in view is N",tax_liability)
            return tax_liability
   
           #print('Your tax liability for the year in view is ',tax_liability)
    
        company_tax(revenue,rate)
    
    
    except:
        print("invalid input!")
    
    else:
        print('Next?')
        
    
