class Student:
    def __init__ (self, student_id,marks,age):
            self.__student_id=student_id
            self.__age=age
            self.__marks=marks
            self.__course_id=None
            self.__fees=None
            
    def set__student_id(self, student_id):
            self.__student_id = student_id

    def get__student_id(self):
        return self.__student_id
    
    def set__age(self, age):
            self.__age = age

    def get__age(self):
        return self.__age   
    
    def set__marks(self, marks):
            self.__marks =marks

    def get__marks(self):
        return self.__marks
        
    def set__marks(self, course_id):
            self.__course_id =course_id
        
    def get__course_id(self):
        return self.__course_id
        
    def set__fees(self, fees):
        if(course_id==1001):
            self.__fees =25575.0
        else:
            self.__fees =15500.0

    def get__fees(self):
        return self.__fees
        
    def validate_marks(self):
             if(self.__marks>=0 and self.__marks<=100):
                 print("True")
             else:
                 print("False")
    def validate_age(self):
            if(self.__age>20):
                 print("True")
            else:
                 print("False")
    def check_qualification(self):
            if(self.__age>20 and self.__marks>=65):
                 return True
            else:
                 return False
        
    def choose_course(self,course_id):
        if(self.check_qualification()):
            self.course_id=self.get__fees()
            if(self.__marks>80):
                self.__fees=self.__fees-(self.fees*25/100)
                return True
        return False
            
        
    
s1=Student(1,70,21)
s1.set__student_id(1004)
s1.set__age(21)
s1.set__marks(65)
if(s1.check_qualification()):
    print("Student has qualified")
    if(s1.choose_course(1002)):
        print("Course allocated")
    else:
        print("Invalid course id")
else:
    print("Student has not qualified")
