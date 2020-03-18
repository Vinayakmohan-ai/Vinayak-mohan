class Techlearnersmentors:
   'Common base class for all employees'
   mCount = 0
   tlCount = 0

   def addStacks(name, interest, expertise ):
      addStacks.name = name
      addStacks.interest = interest
      addStacks.expertise = expertise
      Techlearnersmentors.tlmCount += 1
      
   def setMentorOrLearner(m):
       if m==mentor:
           print ("Mentor : ",addStacks.name)
           Techlearnersmentors.mCount += 1
       else:
           print ("Techlearner : ",addStacks.name)
           Techlearnersmentors.tlCount += 1
           
   def setAvailableTime(time):
       setAvailableTime.time=time
print ("Avalable time: ",setAvailableTime.time )

  def getMentor(n):
       #finds available mentors
      for value in getMentor:
        if n == value:
            return True
    return False
print(is_group_member([9, 12, 15, 18], 21))
print(is_group_member([8, 10, 12], 14))
 
