void main() {
/*
   // 1st Done
   
   List names = ["Ahsan Ali", "Najaf Ali", "Raza Ali"];
   
   print("All Names: $names");
   
   
   // 2nd Done
   
   List days = ["Monday", "Tuesday", "wednesday","Thursday","Friday","Saturday", "Sunday"];
     
   print("${days.last}");
   
   
   // 3rd Done
   
   List student = ["Ahsan Ali","Computer Science", 08,"A",95.3];
   
   print("Student Data: $student");
   print("Name: ${student[0]}");
   print("Dept: ${student[1]}");
   print("Roll no: ${student[2]}");
   print("Grade: ${student[3]}");
   print("Percentage: ${student[4]}");
   

   // 4th Done
   
   
   List numbers = [10,20,30,40,50,60];
   int smallest = numbers.reduce ((a, b) => a < b ? a : b);
   int greatest = numbers.reduce ((a, b) => a > b ? a : b);
   
   print("$numbers");
   print("Smallest number: $smallest");
   print("Greatest number: $greatest");
 
 
  // 5th Done 
   
  List numbers = [3, 7, 24, 15, 18];
  int maximumValue = numbers.reduce ((a, b) => a > b ? a : b);  
   
  print("Maximum Value is: $maximumValue"); 
    
   // 6 Done
   
   List bookShop = ["Pen","Bag","Eraser","Books"];
   
   print("$bookShop");
   print(bookShop.reversed);
 
   
    */
   // 6th Assigment
   
   List items = ["Apple", "Banana"];
   print("1 fruits: $items");
   
   items.add("Grapes");
   print("2 Add: $items");
   
   items.addAll(["Watermelon","Cherry"]);
   print("3 Added All: $items");
   
   items.insert(1, "mango");
   print("4 Insert: $items");
   
   items.insertAll(2, ["Orange", "Stawberry"]);
   print("5 InsertAll: $items");
   
   items.remove("Banana");
   print("6 Remove: $items");
   
   items.removeAt(0);
   print("7 RemoveAt: $items");
   
   items.removeLast();
   print("8 Removelast: $items");
   
   items.removeRange(1,3);
   print("9 RemoveRange: $items");
   
   items.length-1;
   print("10 length: ${items.length}");

   print("11 First: ${items.first}");
   print("12 last: ${items.last}");
   print("13 Reversed: ${items.reversed}");
   
   items.sort();
   print("14 Sort: $items"); 
     
   print("15 Empty or Not: ${items.isEmpty}"); 
   
 }
