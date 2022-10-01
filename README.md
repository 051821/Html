# python program to calculate bill
u=int(input("unit:"))
if(u<=100):
    bill=u*1.5;
elif(u<=200):
    bill=((100*1.5)+(u-100)*2.5);
elif(u<=300):
    bill=((100*1.5)+(100*2.5)+(u-200)*4);
elif(u<=350):
    bill=((100*1.5)+(100*2.5)+(100*4)+(u-300)*5);
elif(u>350):
    bill = ((100 * 1.5) + (100 * 2.5) + (100 * 4)+(50*15)+(u-350)*15);
print("electricity bill is",bill)


