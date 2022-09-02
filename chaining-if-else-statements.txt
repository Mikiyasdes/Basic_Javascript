function testSize(num) {

if(num<5)
{
    return "Tiny"
}
 else if(num<10)
 {
   return "Small" 
 } 
  else if(num<15)
  {
    return "Medium" 
  }
   else if(num<20)
   {
     return "Large"
   }
    else
    {
      return "Huge"
    }

  return "Change Me";

}

testSize(7);