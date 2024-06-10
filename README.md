# Coding-Set-4
Alg Workbench 1

product = 1

while product < 100:
  num = float(input('Enter a number: '))
  product = number * 10
  print('Product: ', product)

 if product >= 100:
    print('Product is now greater than or equal to 100. Exiting loop.')
    break
Enter a number: 5
Product:  50.0
Enter a number: 1
Product:  10.0
Enter a number: 100
Product:  1000.0
Product is now greater than or equal to 100. Exiting loop.

Alg Workbench 3

for number in range(0, 1001, 10):
  print(number, end=',')
0,10,20,30,40,50,60,70,80,90,100,110,120,130,140,150,160,170,180,190,200,210,220,230,240,250,260,270,280,290,300,310,320,330,340,350,360,370,380,390,400,410,420,430,440,450,460,470,480,490,500,510,520,530,540,550,560,570,580,590,600,610,620,630,640,650,660,670,680,690,700,710,720,730,740,750,760,770,780,790,800,810,820,830,840,850,860,870,880,890,900,910,920,930,940,950,960,970,980,990,1000

Programming Exercise #1

total_bugs = 0

for day in range(1,  6):
    bugs_collected = int(input('Enter the number of bugs collected on day {day}: '))
    total_bugs += bugs_collected

print('Total bugs collected in five days:', total_bugs)

Enter the number of bugs collected on day {day}: 6
Enter the number of bugs collected on day {day}: 6
Enter the number of bugs collected on day {day}: 5
Enter the number of bugs collected on day {day}: 4
Enter the number of bugs collected on day {day}: 6
Total bugs collected in five days: 27

Exercise #4
speed = float(input('Enter the speed of the vehicle(in miles per hour): '))
hours = int(input("Enter the number of hours that the vehicle has traveled: "))
Enter the speed of the vehicle(in miles per hour): 40
Enter the number of hours that the vehicle has traveled: 3

print('\nHour\tDistance Traveled')
Hour	Distance Traveled

for hour in range (1, hours + 1): 
    distance = speed * hour
    print(f'{hour}\t{distance} miles')
1	40.0 miles
2	80.0 miles
3	120.0 miles

Exercise 13 

rows = 6

for i in range(rows, 0, -1) 
  for j in range(0, i)
        print('*', end='')
    print()
    
