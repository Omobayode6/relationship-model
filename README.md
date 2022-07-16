# please note that all the first ids which is the primary id are underlined.

Hotel(Hotel_Id, Hotel_name, #Type_Id)
Type(Type_Id, Type_Name)
Room(Room_Id, Floor, #Hotel_id, #Category_Id)
Categoty(Category_Id, Category_Name, Price, Beds_numbers)
Employee(Employee_Id, Employee_name, Employee_Speciality, #Hotel_Id)
