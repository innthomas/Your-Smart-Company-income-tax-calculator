# Your-Smart-Company-income-tax-calculator
#this calculator obtains data from user to compute tax liability

print('Your SMART company tax calculator')

try:
    company_name = input('Company name: ')
    revenue = float(input('taxable income for the year:' ))
    rate = float(input('applicable tax rate:'))
    
    def company_tax (revenue, rate=0.3):
        tax_liability=revenue*rate
        print(company_name.upper() + "'s tax liability for the year in view is N",tax_liability)
        return tax_liability
   
       #print('Your tax liability for the year in view is ',tax_liability)
    
    company_tax(revenue,rate)
    
    
except:
    print("invalid input!")
    
else:
    print('Please endeavour to pay your tax on time!')
    
