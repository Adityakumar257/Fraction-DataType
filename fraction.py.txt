class Fraction:


  def__init__(self,n,d):
    self.num = n
    self.den = d


  def__str__(self):
    return "{}/{}".format(self.num,self.den)


  def__add__(self,other):
    


   temp_num=self.num * other.den + other.num * self.den
   temp_den=self.den * other.den


   return"{}/{}".format(tem_num,temp_den)



  def__sub__(self,other):
    


   temp_num=self.num * other.den - other.num * self.den
   temp_den=self.den * other.den


   return"{}/{}".format(tem_num,temp_den)


   def__mul__(self,other):
    


   temp_num=self.num * self.num * other.num 
   temp_den=self.den * self.den * other.den


   return"{}/{}".format(tem_num,temp_den)


  def__truediv__(self,other):
    


   temp_num=self.num * self.num * other.num
   temp_den=self.den * self.den * other.num


   return"{}/{}".format(tem_num,temp_den)




