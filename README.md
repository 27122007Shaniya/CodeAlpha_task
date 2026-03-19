database=[]
def add_data(new_record):
    if new_record in database:
         print("Duplicate Data Not Added")
    else:
         database.append(new_record)
         print("Unique Data Added Successfully")
while True:
    data=input("Enter data (or 'exit'):")
    if data=="exit":
         break
    add_data(data)
print("Final Database:",database)
    
