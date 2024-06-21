# Phyton7
date=input('Enter a date in the form mm/dd/yyyy.')
date_split=date.split('/')
months=['January','February','March','April','May','June','July','August','September','October','November','December']
months_number=11
months_name=months[months_number-1]
print(months_name,date_split[0],",",date_split[2])
