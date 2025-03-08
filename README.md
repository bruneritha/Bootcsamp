importjava.util.*
class exponentbase{
public static voidmain(string[]args){
int base,exponent;
system.out.print("enter the number:")
scanner obj = new scanner(system.in)
system.out.print("enter the base:")
base=obj.nextInt();
system.out.print("enter the exponent:")
exponent=obj.nextInt();
int result=1
for(i=1;i<=exponent;i++){
result=result*base}
system.out.print("the result:"+result)
return result}}


